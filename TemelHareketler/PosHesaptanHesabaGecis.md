---
SayfaID: PosHesaptanHesabaGeçiş
SayfaTipi: Banka
---

# Satış Faturası

**Erişim Linki :** [erp.aaro.com.tr/KrediPosBankadanTahsilat](https://erp.aaro.com.tr/KrediPosBankadanTahsilat)

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "pos hesap" şeklinde aratarak ulaşım sağlayabilirsiniz.
- Sol menüden *Banka -> Hareket Oluştur -> Diğer İşlemler -> POS Hesaptan Hesaba Geçiş* şeklinde ulaşım sağlayabilirsiniz. 

## Tanım 

POS (Point of Sale) hesaptan hesaba geçiş işlemi, POS cihazları aracılığıyla yapılan satışlardan elde edilen tutarın, 
geçici olarak POS hesabında tutulduktan sonra işletmenin ana banka hesabına aktarılmasını ifade eder. 
Bu işlem, POS cihazları ile yapılan işlemlerin düzgün bir şekilde muhasebeleştirilmesini ve finansal tabloların doğru bir şekilde güncellenmesini sağlar.

POS cihazı üzerinden gerçekleştirilen satış işlemleri, müşterilerin kredi kartı veya banka kartı ile ödeme yapmaları sonucunda POS hesabına yansır. 
Bu tutar, genellikle bankanın geçici bir POS hesabında toplanır.

Belirli bir süre sonunda (genellikle günlük, haftalık veya banka anlaşmalarına göre), POS hesabında biriken tutar, işletmenin ana banka hesabına transfer edilir. 
Bu işlem, bankanın belirlediği süre sonunda otomatik olarak gerçekleşir veya işletme tarafından manuel olarak da yapılabilir.

POS hesabından ana hesaba yapılan bu geçiş, muhasebe kayıtlarına "POS hesabından ana hesaba transfer" olarak kaydedilir. 
Bu işlem, POS hesabındaki tutarın azaltılması (borç) ve ana hesaba eklenmesi (alacak) şeklinde muhasebe kayıtlarına yansıtılır.

Bu işlem, POS hesabındaki hareketlerin doğru bir şekilde takip edilmesini ve tüm satışların zamanında ana hesaba aktarılmasını sağlar. 
Ayrıca, bankalardan gelen hesap ekstreleri ile POS geçiş işlemlerinin uyumlu olup olmadığını kontrol etmek önemlidir.

Örnek:

Bir işletme, POS cihazı ile 1.000 TL'lik satış yapar ve bu tutar POS hesabına aktarılır. 
Gün sonunda bu 1.000 TL, POS hesabından işletmenin ana banka hesabına transfer edilir. Bu işlem, muhasebe kayıtlarında şu şekilde görünür:

POS Hesabı: 1.000 TL borç (azaltma)  
Ana Banka Hesabı: 1.000 TL alacak (artış)  
Bu şekilde, POS hesaptan hesaba geçiş işlemi, işletmenizin POS cihazı üzerinden yapılan satışların düzgün bir şekilde ana hesaba aktarılmasını ve finansal kayıtlarınızın doğru ve güncel tutulmasını sağlar.

## Genel

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir. 

**Belge No:** Belge numarasını ifade eder. Otomatik olarak sıradaki numara gelir. İstenilirse seri kullanılabilir.

**Banka Hesap:** İşlemin yapılacağı banka hesabı ifade eder. 

**Döviz:** Banka hesabının çalıştığı döviz cinsini belirtir. Türk lirası dışında bir döviz seçildiğinde, yalnızca o döviz cinsinden işlem yapılmasına izin verir. Banka hesabının bakiyesi, seçilen döviz cinsine göre takip edilir.

**Kur:** Belirtilen dövizin, işlem yapılan para birimi karşısındaki değerini ifade eder. 
Kur, dövizin güncel piyasa değerini yansıtır ve bu oran üzerinden işlemler gerçekleştirilir.

**Açıklama:** İşleme ait açıklamayı belirtir. [Açıklama](../TemelOzellikler/Aciklama.md)

## Detay 

**Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir. Proje kullanım detayları için linke tıklayınız.[Proje](../TemelOzellikler/Proje.md)

**Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir. Plasiyer kullanım detayları için linke tıklayınız.[Plasiyer](../TemelOzellikler/Plasiyer.md)

**Alt Tip:** Alt hareket tipini belirtir.

### Açıklamalar

- **Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](/TemelOzellikler/Aciklama.md "Açıklama")	

### Etiketler

- **Etiketler:** Bu kartı gruplamak ve sonrasında gruplu rapor alabilmek için kullanılır. [Etiketler](/TemelOzellikler/Etiketler.md "Etiketler")

## Doldurmamız gereken bilgileri doldurduktan sonra *Kaydet* butonuna basarak bir sonraki kalem ekleme aşamamıza geçebiliriz.

## Notlar 

İşleme ait özel notlar ekleyebiliriz. Önemli bir detay varsa, bu ayrıntıları burada belirtebiliriz. Notların kullanım detayları için lütfen bağlantıya tıklayınız.[Notlar](../TemelOzellikler/Notlar.md)

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlardaki belgeleri buraya yükleyebiliriz.
Buraya işlem esnasındaki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- *Daha önce yüklediklerimden seç -> belgeyi seç -> İlişkilendir* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- *Yüklenecek belge veya resimleri seç -> Belgeyi ya da belgeleri seç -> Yükle* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 


## Ek İşlemler

 Sayfanın sağ üst köşesinde bulunan, alt alta üç çizgi şeklindeki düğme ile ek işlemlere erişebilirsiniz.








- Yevmiye Fiş: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Faturayı kopyalamak için kullanılır.
- Tüm Kalemlerde Değiştir: Buradan depo, proje, sözleşme, vergi muafiyeti, vergilerin yenilenmesi, iskonto oranı, referans ithalat/ihracat, plasiyer ve referans teslim tarihi gibi bilgileri tüm kalemler için toplu olarak değiştirebilirsiniz.
- Döviz Türü Değiştir: Döviz türü değişikliği yapabiliriz.
- Görev Oluştur: Satış Faturası için görev oluşturup, kişi atayabiliriz. Açıklama, tarih bitiş, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemimizi gerçekleştirebiliriz.
- Görev Bağla: Açılan listedeki görevlerden bağlayacağımız, birleştireceğimiz görevi seçip, *Kaydet* diyerek görevi bağlayabiliriz.
- Grid Sütunları Ayarla: Burada kartın detaylarının görünümünde değişiklikler yapabilirsiniz. 
