
# Üretim Hareketi 

Üretim süreçlerinde gerçekleşen her aşama bir üretim harekettir. Bunlar karıştırma, başlama, durma gibi eylemlerde birer harekettir.
Üretim aşamasında iki çeşit yöntem mevcuttur birincisi, manuel giriş yapmak diğeri ise canlı üretim hareketidir.
Canlı üretim hareketinde işlem operasyon yapılırken terminal sisteminde yapılan her hareketin anında işlenmesidir.
Operasyona başlandığında başla seçeneğini ile başlamak, arıza olduğunda duraklama işlem bittiğinde bitire basarak süreleri sistemin otomatik hesaplamasını ve canlı takip yapabilmektir.
Manuel giriş ise işlem bittikten sonra verilerin sisteme manuel olarak girilmesidir.
Çalışan personellerin isimleri, ne kadar mola verildi, neden işlem durdu ne kadar sürede operasyon bitti bunların manuel olarak girilmesidir.

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "üretim hareketi" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Hareketler -> Hızlı Üretim Hareketi Girişi Sadece İşçilik şeklinde ulaşım sağlayabilirsiniz.
	Sadece İşçilik girişinde sadece operasyon ile ilgili detaylar girilir.

### Genel 

**Tarih:** İşleme ait tarihi giriniz.
**İş Emri No:** Verilen iş emrinin kendine ait bir numarası olmaktadır. 
**Operasyon:** Yapılacak operasyon işlemini seçiniz. Eğer yok ise detaylı ekle yaparak hızlıca operasyon tanımlayabilirsiniz.
**Makine:** Operasyonda kullanılacak makineyi seçiniz yok ise detaylı ekle yaparak hızlıca makine girişini sağlayabilirsiniz.
**Detay:** Detayı listeden seçebilirsiniz ya da detaylı ekle yaparak hızlıca ekleyebilirsiniz.
**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)
**Açıklama** Reçeteye ait detay açıklaması eklemesi yapabilirsiniz. Açıklamalar hakkında detaylı bilgiler için tıklayınız. [Açıklama](../TemelOzellikler/Aciklama.md)
**İşçilik / Saat:** Üretim sürecinde çalışan işçilerin çalışma maliyetleridir. Detaylı bilgi için tıklayınız. [İşçilik Maliyeti](../Uretim/İscilikMaliyeti.md)
**Çalışma Mal. / Saat:** Makine masraflarının hesapları ve işçilik hesaplarının toplamıdır. Detaylı bilgi için tıklayınız. [Çalışma Mal. / Saat](../Uretim/BirimMaliyeti.md)
**Döviz:** Bu işlemin çalıştığı döviz cinsini belirtir.Türk lirası haricinde başka bir döviz seçildiğinde sadece o döviz cinsinden hareket işlenmesine izin verir. 
Banka hesabının bakiyesi seçilen döviz cinsinden takip edilir.

### Çalışan Personel Listesi 

Bu operasyonda çalışan personelleri listeden seçebilirsiniz. Personel yok ise detaylı ekle yaparak hızlıca personelin kaydını oluşturabilirsiniz.

### Üretim Süreçleri

**Başlangıç** Operasyona başlama saatini giriniz.
**Bitiş** Operasyonun bitiş tarihini giriniz.
**Hazırlık Süre** Operasyona hazırlık süresi, makine ne kadar sürede ısındı gibi operasyona başlamadan önceki geçen süredir.
**Üretim Süre** Operasyonun üretim süresi, ne kadar sürede yapıldığıdır.
**Duraklama Süre** Makine bozulduğunda ya da makine arızaları gibi duraklama olduğunda ne kadar süre arıza verdi ise o süreyi gireceğimiz alan.
**Mola Süre** Personel ne kadar süre mola verdi ise o süreyi gireceğimiz alan. 

### Duraklama Nedeni

**Neden** Operasyon neden duraklamaya uğradığının detayını girdiğimiz alandır. Makine bozuldu, arızlandı gibi nedenleri belirttiğimiz yerdir. 
Kayıtlı nedenleri listeden seçebilirsiniz, yeni bir neden eklemek için detaylı ekle yaparak hızlıca ekleme yapabilirsiniz.

### Üretim Açıklama

Operasyona ait detayları ve özel açıklamalar burada belirtilmelidir.


Bütün alanları doldurduktan sonra kaydet butonuna basarak opersayon işlemimizi başarıyla tamamlamış bulunmaktayız.


# Hızlı Üretim Girişi

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "üretim hareketi" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Hareketler -> Hızlı Üretim Hareketi Girişi şeklinde ulaşım sağlayabilirsiniz.

İşlemler dışında hammadde ya da mamul eklemesi yapıldığında buradan hareket girişi yapılmalıdır. 
Burada işlemler aynı fakat buradan hammadde ve mamul girişi ekleyebilirsiniz.

### Mamüller

**Mamül Adı** Mamülün adını giriniz.
**Miktar** Kullanılan miktar, kaç adet kullanıldığını giriniz.
**Depo** Hangi depodan temin edildiğini çıkış yapılacak olan depoyu seçiniz.

### Hammmaddeler 

**Hammadde Adı** Hammaddenin adını giriniz.
**Miktar** Kullanılan miktar, kaç adet kullanıldığını giriniz.
**Birim Fiyat** Kullanılan hammaddenin birim fiyatını ifade eder.
**Depo** Hangi depodan temin edildiğini çıkış yapılacak olan depoyu seçiniz.
