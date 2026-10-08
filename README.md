# Guitar & Bass FX

![Guitar & Bass FX](brand/full-logo.png)

Elektro, akustik, klasik gitar ve bas için geliştirilen telefon, tablet ve bilgisayar uygulaması.

Bu depo kullanım bilgileri ve **herkese açık kurulum sürümleri** içindir. Kaynak kod ayrı, gizli depoda tutulur.

## Windows

[Son Windows sürümü](https://github.com/DKDodo/Guitar-Bass-FX/releases/latest)

ZIP'i bir klasöre çıkarıp `BasSahnePC.exe` ile aç. Java ayrıca kurulmaz. Masaüstü kısayolu ve uygulamanın görünen adı **Guitar & Bass FX**'tir. Teknik çalıştırılabilir dosya adı önceki sürümlerle uyumluluk için korunur.

**Güncellemeler** düğmesi yeni Windows sürümlerini kontrol eder, indirir ve dosyaları doğruladıktan sonra geçişi başlatır. Açılıştaki otomatik denetim kapatılabilir. Kaydedilmemiş pedalboard için kayıt seçimi sunulur; önceki uygulama ve kayıt dosyaları korunur.

## Mevcut önizleme

- Dört enstrüman profili ve altı yuvalı yerel pedalboard düzenleme.
- 8 pedal modeli: EQ, kompresör, overdrive, chorus, delay, oda reverb ve Synth VA/FM.
- Altı yuvadan bağımsız 7 özgün amfi karakteri ve 4 algoritmik kabin; parametre, bypass ve zincirdeki yer seçimi.
- Tek pedal veya bütün düzen için 2,7 saniyelik üretilmiş ses örneği.
- Windows 0.5 / Android 0.10 arasında elle ortak v2 dosya aktarımı; eski v1 dosyaları açılır. Yeni v2 dosyası eski Windows 0.4 ile açılmaz.
- Manuel başlatılan kromatik akort: nota, Hz, sent, pes/tiz göstergesi.
- Windows için GitHub güncellemeleri.
- Android telefon ve tablet ekranlarına uyarlanan arayüz.

Bu bir geliştirme önizlemesidir. Efekt/amfi/kabin motoru kısa örnek sesi işler; yeni DSP canlı USB yoluna henüz bağlanmadı. Amfiler ticari modellerin birebir kopyası değildir; kabinler ölçülmüş IR kaydı kullanmaz. Gerçek enstrümanla karşılaştırmalı dinleme, ses kartı ölçüm doğruluğu ve sahne kabulü bekler. Canlı zincir, gerçekçi piyano/saksafon/klarnet dönüşümü, üyelik ve otomatik eşitleme sonraki adımlardır.

[Amfi ve pedalboard kullanım rehberi](Guitar-Bass-FX-0.10-Amfi-Pedal-Rehberi.txt)

## İsim geçişi

Proje adı **Guitar & Bass FX** olarak seçildi. Önceki BasSahne 0.3 Windows kurulumları, mevcut güncelleme adresinden uyumlu 0.4 geçiş paketini alabilir. Sonraki sürümler yeni yayın deposundan gelir. Uygulama kimlikleri, dosya biçimi ve kayıt klasörleri bu geçişte korunur.

## Gizlilik

Sürüm denetimi ve indirme GitHub'a bağlanır; ses veya pedalboard içeriği gönderilmez. Uygulamada GitHub hesabı/parolası gerekmez. Normal internet bağlantısı bilgileri GitHub hizmetlerine ulaşır. SHA-256 ve boyut kontrolü dosya bütünlüğünü doğrular; bağımsız Windows kod imzası değildir.

Android, Windows güncelleme kanalı üzerinden kurulmaz. Google Play yayını henüz yapılmadı.
