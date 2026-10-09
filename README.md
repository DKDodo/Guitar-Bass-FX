# Guitar & Bass FX

![Guitar & Bass FX](brand/full-logo.png)

Elektro, akustik, klasik gitar ve bas için geliştirilen telefon, tablet ve bilgisayar uygulaması.

Bu depo kullanım bilgileri ve **herkese açık kurulum sürümleri** içindir. Kaynak kod ayrı, gizli depoda tutulur.

## Windows

[Son Windows sürümü](https://github.com/DKDodo/Guitar-Bass-FX/releases/latest)

ZIP'i bir klasöre çıkarıp `BasSahnePC.exe` ile aç. Java ayrıca kurulmaz. Masaüstü kısayolu ve uygulamanın görünen adı **Guitar & Bass FX**'tir. Teknik çalıştırılabilir dosya adı önceki sürümlerle uyumluluk için korunur.

**Güncellemeler** düğmesi yeni Windows sürümlerini kontrol eder, indirir ve dosyaları doğruladıktan sonra geçişi başlatır. Açılıştaki otomatik denetim kapatılabilir. Kaydedilmemiş pedalboard için kayıt seçimi sunulur; önceki uygulama ve kayıt dosyaları korunur.

## Mevcut önizleme

- Android 0.19 demosuz Pedal Rafı: altı pedal kartı, aç/kapat ve ayrı ayar paneli; sabit Pedallar/Tonlar/Akort/Menü sekmeleri.
- Üretilmiş “sesi test et” düğmeleri Android ve Windows'tan kaldırıldı.
- Dört enstrüman profili; 11 özgün pedal algoritması, 7 amfi karakteri ve 4 algoritmik kabin ayarı. Ticari pedal klonu veya ölçülmüş kabin IR'si henüz yok.
- Android canlı USB motoru yalnız EQ, kompresör ve gate destekler. Diğer açık efektler ve amfi/kabin başlangıcı engeller; bypass gerekir. Gerçek USB ses/gecikme/sahne kabulü bekler.
- Windows 0.7 yerel pedalboard düzenleyicisi, akort ve GitHub güncellemeleri. Windows pedalboard canlı ses girişi henüz yok.
- Önceki v1/v2 düzenleri korunur; telefon ve bilgisayar arasında elle ortak dosya aktarımı yapılır. Üyelik ve otomatik eşitleme henüz yok.

[Demosuz sürüm rehberi](Guitar-Bass-FX-0.19-Demosuz-Surum-Rehberi.txt) · [Ses yol haritası v2](Guitar-Bass-FX-Roadmap-v2.txt)

Ses kalitesi ve uyumluluk gerçek enstrüman/cihaz ölçümleriyle kabul edilecek. Yeni açık kaynak efekt, NAM, ölçülmüş IR ve GR tarzı çalgı dönüşümü motorları araştırma/plan aşamasındadır. Demoların kaldırılması, henüz canlı desteklenmeyen modelleri çalışır hale getirmez.

## İsim geçişi

Proje adı **Guitar & Bass FX** olarak seçildi. Önceki BasSahne 0.3 Windows kurulumları, mevcut güncelleme adresinden uyumlu 0.4 geçiş paketini alabilir. Sonraki sürümler yeni yayın deposundan gelir. Uygulama kimlikleri, dosya biçimi ve kayıt klasörleri bu geçişte korunur.

## Gizlilik

Sürüm denetimi ve indirme GitHub'a bağlanır; ses veya pedalboard içeriği gönderilmez. Uygulamada GitHub hesabı/parolası gerekmez. Normal internet bağlantısı bilgileri GitHub hizmetlerine ulaşır. SHA-256 ve boyut kontrolü dosya bütünlüğünü doğrular; bağımsız Windows kod imzası değildir.

Android, Windows güncelleme kanalı üzerinden kurulmaz. Google Play yayını henüz yapılmadı.

## Android 0.19 doğrulaması

Redmi'de 479 pedalboard/menü + 310 kayıtlı canlı plan/JNI + 41 EQ/JNI kontrolü geçti. Giriş sesi açılmadı; kullanıcı düzeni ve tercihleri korundu. Gerçek telefon görüntüleri incelendi. Donanım/sahne/tablet kabulü bekler.
