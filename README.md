# Guitar & Bass FX

![Guitar & Bass FX](brand/full-logo.png)

Elektro, akustik, klasik gitar ve bas için geliştirilen telefon, tablet ve bilgisayar uygulaması.

Bu depo kullanım bilgileri ve **herkese açık kurulum sürümleri** içindir. Kaynak kod ayrı, gizli depoda tutulur.

## Windows

[Son Windows sürümü](https://github.com/DKDodo/Guitar-Bass-FX/releases/latest)

ZIP'i bir klasöre çıkarıp `BasSahnePC.exe` ile aç. Java ayrıca kurulmaz. Masaüstü kısayolu ve uygulamanın görünen adı **Guitar & Bass FX**'tir. Teknik çalıştırılabilir dosya adı önceki sürümlerle uyumluluk için korunur.

**Güncellemeler** düğmesi yeni Windows sürümlerini kontrol eder, indirir ve dosyaları doğruladıktan sonra geçişi başlatır. Açılıştaki otomatik denetim kapatılabilir. Kaydedilmemiş pedalboard için kayıt seçimi sunulur; önceki uygulama ve kayıt dosyaları korunur.

## Mevcut önizleme

- Android 0.21 Pedal Rafı: altı pedal kartı, aç/kapat ve ayrı ayar paneli; sabit Pedallar/Tonlar/Akort/Menü sekmeleri.
- Pedal, amfi, kabin ve synth ayarlarında global terimler: Bass, Mid, Treble, Threshold, Attack, Release, Blend ve diğerleri. Her ayarın yanındaki küçük `?` kısa Türkçe açıklama açar; yardım okumak ayarları değiştirmez.
- Üretilmiş “sesi test et” düğmeleri Android ve Windows'tan kaldırıldı.
- Dört enstrüman profili; 12 özgün pedal algoritması, 7 amfi karakteri ve 4 algoritmik kabin ayarı. Ticari pedal klonu veya ölçülmüş kabin IR'si henüz yok.
- Yeni 10 bant EQ: MXR M108S frekansları, ±12 dB, 0,1 dB adım, ayrı giriş/çıkış seviyeleri ve Düzleştir. Özgün dijital filtredir; MXR devre klonu değildir.
- Android canlı USB motoru 3/10 bant EQ, kompresör ve gate destekler. Diğer açık efektler ve amfi/kabin başlangıcı engeller; bypass gerekir. Gerçek USB ses/gecikme/sahne kabulü bekler.
- Windows 0.9 yerel pedalboard düzenleyicisi, `?` parametre yardımı, akort ve GitHub güncellemeleri. Windows pedalboard canlı ses girişi henüz yok.
- Önceki v1/v2 düzenleri korunur; telefon ve bilgisayar arasında elle ortak dosya aktarımı yapılır. Üyelik ve otomatik eşitleme henüz yok.

[Parametre yardımı rehberi](Guitar-Bass-FX-Parametre-Yardimi-Rehberi.txt) · [10 bant EQ rehberi](Guitar-Bass-FX-10-Bant-EQ-Rehberi.txt) · [Onaylanan ses yol haritası v3](Guitar-Bass-FX-Roadmap-v3.txt) · [Gerçek ses kabul tutanağı](Guitar-Bass-FX-Ses-Kabul-Tutanagi-v1.txt)

Ses kalitesi ve uyumluluk gerçek enstrüman/cihaz ölçümleriyle kabul edilecek. Bağımsız IR pilotu 10.259 sayısal kontrolden ve Android arm64 derlemesinden geçti; NAM motorunun bilgisayarda yükleme/işleme hazırlığı doğrulandı. Gerçek kabin/amfi dinlemesi, telefonda entegrasyon ve canlı performans kabulü bekler. Bu hazırlık yeni uygulama sürümü veya canlı IR/NAM desteği değildir; Android 0.21 ve Windows 0.9 korunur. GR tarzı çalgı dönüşümü ayrı sonraki iş paketidir.

## İsim geçişi

Proje adı **Guitar & Bass FX** olarak seçildi. Önceki BasSahne 0.3 Windows kurulumları, mevcut güncelleme adresinden uyumlu 0.4 geçiş paketini alabilir. Sonraki sürümler yeni yayın deposundan gelir. Uygulama kimlikleri, dosya biçimi ve kayıt klasörleri bu geçişte korunur.

## Gizlilik

Sürüm denetimi ve indirme GitHub'a bağlanır; ses veya pedalboard içeriği gönderilmez. Uygulamada GitHub hesabı/parolası gerekmez. Normal internet bağlantısı bilgileri GitHub hizmetlerine ulaşır. SHA-256 ve boyut kontrolü dosya bütünlüğünü doğrular; bağımsız Windows kod imzası değildir.

Android, Windows güncelleme kanalı üzerinden kurulmaz. Google Play yayını henüz yapılmadı.

## Android 0.19 doğrulaması

Redmi'de 479 pedalboard/menü + 310 kayıtlı canlı plan/JNI + 41 EQ/JNI kontrolü geçti. Giriş sesi açılmadı; kullanıcı düzeni ve tercihleri korundu. Gerçek telefon görüntüleri incelendi. Donanım/sahne/tablet kabulü bekler.

## Android 0.20 / Windows 0.8 doğrulaması

Redmi'de 665 pedalboard/menü +448 kayıtlı canlı plan/JNI +41 üç bant EQ/JNI kontrolü geçti; ses girişi açılmadı, kullanıcı düzeni ve tercihleri korundu. 10 bant EQ frekans tepkisi ve Java/native referans farkı, Windows dar paneli ve yerel kayıtları doğrulandı. Gerçek enstrüman/USB/gecikme/sahne/tablet kabulü bekler. [Doğrulama tutanağı](Guitar-Bass-FX-0.20-dogrulama.txt).

## Android 0.21 / Windows 0.9 yardım doğrulaması

Global ayar adları ve Türkçe `?` pencereleri eklendi. Yardım kontrolleri Redmi ve Windows'ta ayar/kayıtları değiştirmeden doğrulandı; ses girişi açılmadı. [Doğrulama tutanağı](Guitar-Bass-FX-0.21-dogrulama.txt).
