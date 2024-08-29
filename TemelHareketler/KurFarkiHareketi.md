---
SayfaID: KurFarkiHareketi
SayfaTipi: 
---

# Kur Farkı Hareketi

**Erişim Linki :** [erp.aaro.com.tr/KurFarkiHareketi](erp.aaro.com.tr/KurFarkiHareketi)

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "kur farkı" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Müşteri/Satıcı -> Hareket Oluştur -> Diğerler -> Kur Farkı Hareketi şeklinde ulaşım sağlayabilirsiniz. 
- Sol menüden Demirbaş -> Hareket Oluştur -> Diğerler -> Kur Farkı Hareketi şeklinde ulaşım sağlayabilirsiniz. 
- Sol menüden Gelir/Gider -> Hareket Oluştur -> Diğerler -> Kur Farkı Hareketi şeklinde ulaşım sağlayabilirsiniz. 
- Sol menüden Stok -> Hareket Oluştur -> Diğerler -> Kur Farkı Hareketi şeklinde ulaşım sağlayabilirsiniz. 

## Tanım

Kur farkı, dövizli işlemler sırasında, işlem anında uygulanan döviz kuru ile işlem sonrası veya raporlama tarihindeki döviz kuru arasındaki farktır. 
Bu fark, hem alacaklı hem de borçlu hesaplarda finansal değişikliklere yol açar.
Kur farkı hesaplaması, dövizli işlemlerin kaydedilmesi ve raporlanması sırasında yapılır. 
Örneğin, bir şirket bir malı yabancı bir tedarikçiden satın alırken 1 USD = 20 TL kuru ile işlem yapar. 
Ancak, ödeme tarihi geldiğinde döviz kuru 1 USD = 21 TL olmuşsa, bu kur farkı, ödeme işlemiyle birlikte hesaplanır ve raporlanır.

- Eğer bir dövizli alacak hesabı işlem yapıldığında belirli bir döviz kuru ile kayıt edilmişse ve kur farkı nedeniyle döviz kuru değişmişse, bu fark alacaklı hesaplarda kur farkı olarak kaydedilir.
- Benzer şekilde, bir dövizli borç hesabı işlem yapıldığında belirli bir döviz kuru ile kayıt edilip kur farkı nedeniyle değiştiğinde, bu fark borçlu hesaplarda kur farkı olarak kaydedilir.

Diyelim ki bir şirket 1.000 EUR’yu 1 EUR = 25 TL kuru ile satın aldı ve işlemi 25.000 TL olarak *Kaydet*ti. 
Ancak, raporlama tarihi geldiğinde EUR/TL kuru 1 EUR = 26 TL’ye yükseldi. Bu durumda:

Şirketin 1.000 EUR alacağı 26.000 TL’ye yükseldi.
Aradaki 1.000 TL’lik fark (26.000 TL - 25.000 TL) kur farkı olarak kaydedilir.

### Genel

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Hangi şirket-şubeden malzeme gönderimi yapılacak ise o şirketi-şubeyi seçelim.
	Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir.

**Belge No:** Belge numarasını ifade eder. Otomatik olarak sıradaki numara gelir. İstenilirse seri kullanılabilir.
**Girilmesi Zorunludur.**

**Depo:** İşlemin ait olduğu depoyu ifade eder.

**Döviz:** Bu işlemin çalıştığı döviz cinsini belirtir.

**Vade:** Bu işlem için yapılması gereken süreyi ifade eder. 

### Detay

**Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir. Proje kullanım detayları için linke tıklayınız.[Proje](../TemelOzellikler/Proje.md)

**Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir. Plasiyer kullanım detayları için linke tıklayınız.[Plasiyer](../TemelOzellikler/Plasiyer.md)

**Tip:** Alt hareket tipini belirtir.

### Açıklamalar

- **Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](/TemelOzellikler/Aciklama.md "Açıklama")	

### Etiketler

- **Etiketler:** Bu kartı gruplamak ve ileride gruplu rapor alabilmek için kullanılır. [Etiketler](/TemelOzellikler/Etiketler.md "Etiketler")

## Notlar 

İşleme ait özel notlar belirtebiliriz. 
Önemli bir detay var ise bu detayları burada belirtebiliriz.
Notlar kullanım detayları için linke tıklayınız. [Notlar](../TemelOzellikler/Notlar.md)

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlarda bu belgeleri buraya yükleyebiliriz.
Buraya işlem esnasındaki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- Daha önce yüklediklerimden seç -> belgeyi seçelim -> İlişkilendir şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- Yüklenecek belge veya resimleri seçin -> belgeyi ya da belgeleri seçelim -> Yükle şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

### Kalem Ekleme 

- Yeni Stok Kalemi Ekle: Stok kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Gelirgider Kalemi Ekle: Gelir gider kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Demirbaş Kalemi Ekle: Demirbaş kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Cari Kalemi Ekle: Cari kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Kasa Kalemi Ekle: Kasa kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Banka Kalemi Ekle: Banka Hesap kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.

## Doldurmamız gereken bilgileri doldurduktan sonra *Kaydet* butonuna basarak kur farkı hareketi işlemimizi tamamlayabiliriz.

## Ek İşlemler

 Sayfanın sağ üstünde bulunan alt altta üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- Yevmiye Fiş: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Faturayı kopyalamak için kullanılır.
- Kur Güncelle:Döviz kurunda değişiklik yapmak için kullanılır.
- Tüm Kalemlerde Değiştir: Buradan depo, proje, sözleşme, vergi muafiyeti, vergileri yenile, iskonto oranı, ref. ithalat ihracat, plasiyer, Ref teslim tarihi bilgilerini tüm kalemlerde değiştirebiliriz.
- Döviz Türü Değiştir: Döviz türü değişikliği yapabiliriz.
- Görev Oluştur: Satış Faturası için görev oluşturup, kişi atayabiliriz, açıklama, tarih bitiş, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemimizi gerçekleştirebiliriz.
- Görev Bağla: Açılan listede ki görevlerden görevi bağlayacağımız, birleştireceğimiz görevi seçelim, *Kaydet* diyerek görevi bağlayabiliriz.
- Grid Sütunları Ayarla: Burada kartın detaylarının gözükmesinde değişiklikler yapabilirsiniz.