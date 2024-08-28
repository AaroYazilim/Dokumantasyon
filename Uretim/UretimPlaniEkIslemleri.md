---
SayfaID: UrIsEmriPlan
SayfaTipi: PlanDetay
---

## Yeni Üretim Girişi

İş emrine ait yeni üretim hareketi girişinde düzenleme yapabilir, hareket düzenleme yapabiliriz.

### Genel

**Tarih:** İşlem tarihini girelim.

**Makine Adı:** İşlemde kullanılan makineyi seçelim.

**Detay:**

### Mamüller

**Mamül Adı:** Mamül adına tıkladığımızda mamülün stok kartı açılacaktır. 
	Stok detaylarını görüntüleyebiliriz birim1, stok kodu, kategori, alış, satış fiyatları, barkod ve ölçü birimlerinde değişiklik yapabiliriz.

**Miktar:** Mamülümüzün olması gereken miktarını girelim. 

**Birim:** Miktar birim cinsi, kg, adet, metrekare vb. burada yazar.

**Seri/Lot:** Seri lotla takip ettiğimiz ürün ise detaylarını burada görüntüleyebiliriz.

### Ham maddeler

**Ham madde Adı:** Ham madde adına tıkladığımızda ham maddenin stok kartı açılacaktır. 
	Stok detaylarını görüntüleyebiliriz birim1, stok kodu, kategori, alış, satış fiyatları, barkod ve ölçü birimlerinde değişiklik yapabiliriz.

**Miktar:** Hammaddemizin olması gereken miktarını girelim. 

**Birim:** Miktar birim cinsi, kg, adet, metrekare vb. burada yazar.

**Reçete Miktar:** Reçete için gerekli olan miktarı burada görüntüleyebiliriz.

**Seri/Lot:** Seri lotla takip ettiğimiz ürün ise detaylarını burada görüntüleyebiliriz.

### Çalışan Personel Listesi

Üretimde çalışan personelleri seçelim. Personelin kaydı yok ise detaylı ekle diyerek ekleme yapabiliriz.

### Üretim Süreçleri

**Başlangıç** Operasyona başlama saatini giriniz.

**Bitiş** Operasyonun bitiş tarihini giriniz.

**Hazırlık Süre** Operasyona hazırlık süresi, makine ne kadar sürede ısındı gibi operasyona başlamadan önce geçen süredir.

**Üretim Süre** Operasyonun üretim süresi, ne kadar sürede yapıldığıdır.

**Duraklama Süre** Makine bozulduğunda ya da makine arızaları gibi duraklamalar olduğunda ne kadar süre arıza verdi ise o süreyi gireceğimiz alandır.

**Mola Süre** Personel ne kadar süre mola verdi ise o süreyi gireceğimiz alandır. 


### Duraklama Nedeni

**Neden** Operasyonun neden duraklamaya uğradığının detayını girdiğimiz alandır. Makine bozuldu, arızalandı gibi nedenleri belirttiğimiz yerdir. 
Kayıtlı nedenleri listeden seçebilirsiniz, yeni bir neden eklemek için detaylı ekle yaparak hızlıca ekleme yapabilirsiniz.

### Üretim Açıklama

Operasyona ait detayları ve özel açıklamalar burada belirtilmelidir.

### Gelişmiş

**Atlandı:** Üretim hareketi ekranında atlamak, üretim sürecinde belirli bir adıma geçişi ifade eder. 
	Örneğin, bir üretim işçisi veya yönetici, ürünlerin üretim aşamalarını takip ederken, belirli bir aşamadan diğerine geçişi için kullanım sağlar.
	Üretim aşamasının atlandığını veya tamamlandığını göstermek için kullanılır.

**İş Emri No:** İş emri numarasına tıklayarak iş emrine erişim sağlayabilirsiniz.

## Üretilen 

Burada İş emrinin ne kadarı gerçekleştirilen miktar görünür. Tıklayarak hareketlerine erişim sağlayabiliriz.

## Parçala

İş emrimizden kalan kısımlar yetişmedi ya da iş yoğunluğu değişti gibi detaylar olduğunda parçala kısmını kullanarak iş emrini bölebilirsiniz.

## İş Emri Operasyon Çıktısı (Y.I)

Operasyonların iş emri çıktıları buradan alınarak ilgili kişilere iletilebilir. Bu sayede, her adımın takibi kolayca yapılabilir ve işlemlerin doğru kişilere ulaşması sağlanır.

İş emri operasyon çıktıları sisteme tanımlayalım;

İlk olarak iş emri operasyon alanımızdan çıktı tasarım ID numaramızı öğrenmemiz gerekmektedir.
Üretim -> Listeler -> Üretim Planı -> Herhangi bir operasyonun üzerine tıklayalım -> Y.I. -> En üst arama çubuğunda ki linkte IsEmriPlanID= ... Burada yazan 5 haneli numara bizim tasarım ID'mizdir.

ID'mizi öğrendikten bir sonra ki işlemimiz parametrelerden iş emri operasyon çıktısına tasarım ID tanımlamamız gerekmektedir.
Ayarlar -> Parametre Listesi -> Yeni Parametre Ekle -> Parametre: Uretim_IsEmriPlanCiktisi (Üretim Planı) -> Değer=TasarımID -> Kaydet diyerek eşleştirmemizi tamamlayalım.

Tasarımlarımızda düzenleme yapmak istediğimizde;
Ayarlar -> Çıktı Listesi -> İş Emri -> İlgili tasarımı seçelim -> Tasarla diyerek düzenleme yapabiliriz.

Bir günün tüm operasyon çıktılarının tamamını almak istersek;

Tarihe tıklayalım -> Y.I. tıkladığımızda o güne ait bütün operasyonların iş emri çıktılarına erişim sağlarız.

## İstifleme Barkod Çıktısı Stok (Y.Br)

Siparişle üretimi birbirine bağlayan istifleme barkodudur.
İş emrinde istifleme barkodu, üretim sürecinde kullanılan malzemelerin veya tamamlanmış ürünlerin izlenebilirliğini ve doğru şekilde istiflenmesini sağlamak amacıyla kullanılan bir barkod sistemidir. 
Bu barkodlar, malzeme veya ürünlerin depolanması, taşınması ve takibi süreçlerinde büyük kolaylık sağlar.

İstifleme Barkod çıktıları sisteme tanımlayalım;

İlk olarak iş emri operasyon alanımızdan çıktı tasarım ID numaramızı öğrenmemiz gerekmektedir.
Üretim -> Listeler -> Üretim Planı -> Herhangi bir operasyonun üzerine tıklayalım -> Y.Br. -> En üst arama çubuğunda ki linkte IsEmriPlanID= ... Burada yazan 5 haneli numara bizim tasarım ID'mizdir.

ID'mizi öğrendikten bir sonra ki işlemimiz parametrelerden iş emri operasyon çıktısına tasarım ID tanımlamamız gerekmektedir.
Ayarlar -> Parametre Listesi -> Yeni Parametre Ekle -> Parametre: Uretim_IsEmriPlanCiktisi (Üretim Planı) -> Değer=TasarımID -> Kaydet diyerek eşleştirmemizi tamamlayalım.

Tasarımlarımızda düzenleme yapmak istediğimizde;
Ayarlar -> Çıktı Listesi -> İş Emri -> İlgili tasarımı seçelim -> Tasarla diyerek düzenleme yapabiliriz.

Bir günün tüm operasyon çıktılarının tamamını almak istersek;

Tarihe tıklayalım -> Y.Br. tıkladığımızda o güne ait bütün operasyonların iş emri çıktılarına erişim sağlarız.

## İş Emri

Üretim planındayken kolayca iş emrine erişim sağlar. 
İş emrinde sipariş detaylarını, operasyon işlemlerini, iş emrine ait belge ve görselleri, kayıt bilgilerini görüntüleyebiliriz.

## Makine Değiştir

Alternatif makineler gösterilir, buradan değişim yapacağımız makineyi seçebiliriz.

## Sipariş Açıklamaları

Sipariş detaylarını burada görüntüleyebilir linklerinden kolayca erişim sağlayabiliriz.