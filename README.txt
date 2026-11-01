MY HOT WHEELS GARAGE — Sürüm 1.0

İçerik:
- index.html: uygulama
- manifest.webmanifest: ana ekrana ekleme bilgileri
- sw.js: çevrimdışı önbellek
- Bu sürüm araç ve fotoğrafları IndexedDB ile cihaz tarayıcısında saklar.

ÖNEMLİ KURULUM:
Bu klasörü HTTPS destekleyen bir statik web barındırma servisine yüklemen gerekir
(ör. GitHub Pages). Service Worker ve ana ekrana kurulabilir PWA davranışı için
HTTPS gereklidir. İlk kez siteyi internet varken Safari'de aç. Sonra Paylaş >
Ana Ekrana Ekle yolunu izle. Bir kez yüklendikten sonra uygulama çevrimdışı açılır.

Veriler bu cihazdaki Safari/web uygulaması depolamasında tutulur; sonsuz değildir,
iPhone'un kullanılabilir alanı ve iOS depolama politikalarıyla sınırlıdır.
Safari web sitesi verilerini silmek kayıtları silebilir. Ayarlar bölümünden düzenli
JSON yedeği oluştur. iPhone değiştirirken yedeği yeni cihaza içe aktar.

Bu bir App Store native uygulaması değildir. App Store yayını veya imzalı iOS
uygulama paketi içermez. Kayıtların cihazda kalması için aynı ana ekran uygulamasını
kullanmaya devam et ve yedeklerini sakla.
