# YakınKilit Android Demo
Bu dal, Android 8+ için Bluetooth / Wi-Fi üzerinden çevrimdışı ve şifreli mesaj ve dosya aktarım prototipinin APK derleme denemesidir. Kullanıcıların QR/kod üzerinden kimlik doğrulaması gereklidir. Bağımsız güvenlik denetimi henüz yapılmadı.
## APK
GitHub Actions > **YakınKilit Android APK** > son başarılı çalışma > Artifacts > **YakinKilit-Demo-APK** dosyasını indirin. İçindeki `app-debug.apk` iki Android telefona kurulabilir.
## Kod
Kaynak `source/part-*.b64` dosyalarında Base64 olarak parçalanmış xz arşividir. Workflow önce SHA-256 doğrulaması yapar, ardından kaynakları çıkarıp Gradle ile derler.
Kaynak SHA-256: `aaca2324fdcce4d25d5f66f8ae00833ba71dd1977c20c837403fbfc1b73e313c`.
Bu **ilk prototip** olup saha/güvenlik denetimi yapılmadan hassas haberleşme için kullanılmamalıdır.
