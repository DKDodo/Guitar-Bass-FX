# Guitar & Bass FX

![Guitar & Bass FX](brand/full-logo.png)

Elektro, akustik, klasik gitar ve bas için geliştirilen telefon, tablet ve bilgisayar uygulaması.

Bu depo kullanım bilgileri ve **herkese açık kurulum sürümleri** içindir. Kaynak kod ayrı, gizli depoda tutulur.

## Windows

[Son Windows sürümü](https://github.com/DKDodo/Guitar-Bass-FX/releases/latest)

ZIP'i bir klasöre çıkarıp `BasSahnePC.exe` ile aç. Java ayrıca kurulmaz. Masaüstü kısayolu ve uygulamanın görünen adı **Guitar & Bass FX**'tir. Teknik çalıştırılabilir dosya adı önceki sürümlerle uyumluluk için korunur.

**Güncellemeler** düğmesi yeni Windows sürümlerini kontrol eder, indirir ve dosyaları doğruladıktan sonra geçişi başlatır. Açılıştaki otomatik denetim kapatılabilir. Kaydedilmemiş pedalboard için kayıt seçimi sunulur; önceki uygulama ve kayıt dosyaları korunur.

## Mevcut önizleme

- Dört enstrüman profili ve altı yuvalı yerel pedalboard düzenleme. Android 0.17 Vintage Analog altı metal görünümlü kartı, ayrı aç/kapat ve kısa demo düğmelerini birlikte gösterir; yalnız seçilen pedalın ayarları ayrı panelde açılır. Düğmeyle parametre düzenleme, sabit Dinle/Bitti ve Düzen menüsü ekranı sadeleştirir.
- 11 pedal modeli: EQ, kompresör, overdrive, chorus, delay, oda reverb, Gate, Fuzz, Auto-wah ve Synth VA/FM.
- Altı yuvadan bağımsız 7 özgün amfi karakteri ve 4 algoritmik kabin; parametre, bypass ve zincirdeki yer seçimi.
- Tek pedal veya bütün düzen için 2,7 saniyelik üretilmiş ses örneği. Gate demosu bypass ile kıyaslamak için örnek gürültü içerir.
- Windows 0.6 / Android 0.17 arasında elle ortak v2 dosya aktarımı; eski v1/v2 dosyaları açılır. Yeni Gate/Fuzz/Auto-wah modelleri için bu yeni sürümler gerekir; önceki Windows 0.5/Android 0.10 bu modelleri tanımaz.
- Android 0.17 Canlı çal · USB: kayıtlı altı yuvadaki EQ, kompresör ve gate sırası, ayarları ve bypass canlıya bağlıdır. Enstrüman profili kayıttan gelir. Diğer aktif pedallar ve amfi/kabin bu adımda başlangıcı bloklar; düzenleyicide bypass yapılması gerekir. Gerçek USB ses/uyumluluk/gecikme kabulü bekler.
- Manuel başlatılan kromatik akort: nota, Hz, sent, pes/tiz göstergesi.
- Windows için GitHub güncellemeleri.
- Android telefon ve tablet ekranlarına uyarlanan arayüz.

Bu bir geliştirme önizlemesidir. Pedalboard efekt/amfi/kabin motoru kısa örnek sesi işler; Android 0.17 kayıtlı EQ/kompresör/gate pedalboardunu canlı USB yoluna bağlar. Diğer pedallar ve amfi/kabin canlı değildir. Cihaz/oturum giriş-çıkış düzeyleri ortak ton dosyasına yazılmaz. Amfiler ticari modellerin birebir kopyası değildir; kabinler ölçülmüş IR kaydı kullanmaz. Gerçek enstrümanla karşılaştırmalı dinleme, ses kartı ölçüm doğruluğu ve sahne kabulü bekler. Canlı zincir, gerçekçi piyano/saksafon/klarnet dönüşümü, üyelik ve otomatik eşitleme sonraki adımlardır.

[Kompresör ve gate rehberi](Guitar-Bass-FX-0.16-Dinamik-Pedallar-Rehberi.txt) · [Telefon pedalboard rehberi](Guitar-Bass-FX-0.13-Pedalboard-Rehberi.txt) · [Yeni pedal paketi kullanım rehberi](Guitar-Bass-FX-0.11-Pedal-Paketi-Rehberi.txt) · [Amfi ve kabin rehberi](Guitar-Bass-FX-0.10-Amfi-Pedal-Rehberi.txt)

## İsim geçişi

Proje adı **Guitar & Bass FX** olarak seçildi. Önceki BasSahne 0.3 Windows kurulumları, mevcut güncelleme adresinden uyumlu 0.4 geçiş paketini alabilir. Sonraki sürümler yeni yayın deposundan gelir. Uygulama kimlikleri, dosya biçimi ve kayıt klasörleri bu geçişte korunur.

## Gizlilik

Sürüm denetimi ve indirme GitHub'a bağlanır; ses veya pedalboard içeriği gönderilmez. Uygulamada GitHub hesabı/parolası gerekmez. Normal internet bağlantısı bilgileri GitHub hizmetlerine ulaşır. SHA-256 ve boyut kontrolü dosya bütünlüğünü doğrular; bağımsız Windows kod imzası değildir.

Android, Windows güncelleme kanalı üzerinden kurulmaz. Google Play yayını henüz yapılmadı.

## Android 0.17 Vintage Analog

Kullanıcının seçtiği sıcak analog tema Android pedalboardunda uygulandı. Ayrı güç/demo düğmeleri, seçili pedal ayar şeridi, doğrudan Canlı çal ve sabit Tonlar/Akort gezinmesi bulunur. Ortak renkler tonlar, akort ve USB ekranlarında da kullanılır. Kayıt ve ses motoru sözleşmeleri korunur. Windows 0.6 sürümü sürer.

Kullanım: [Vintage Analog rehberi](Guitar-Bass-FX-0.17-Vintage-Analog-Rehberi.txt). Gerçek ses/gecikme/sahne/tablet ve kullanıcının uygulanan tema incelemesi henüz kabul edilmedi.
