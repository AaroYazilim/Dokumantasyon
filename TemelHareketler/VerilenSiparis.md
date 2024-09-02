---
SayfaID: VerilenSiparis
SayfaTipi: Siparis
---

# Verilen Teklif

**Erişim Linki :** [erp.aaro.com.tr/FaturaVerilenSiparis](erp.aaro.com.tr/FaturaVerilenSiparis)

## Ulaşım 

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan 'sipariş' şeklinde aratarak ulaşım sağlayabilirsiniz.
- Sol sekmede yer alan modüller kısmından Musteri/Satici -> Hareket Oluştur -> Satış ve Pazarlama -> Verilen Sipariş şeklinde ulaşım sağlayabilirsiniz.
- Sol sekmede yer alan modüller kısmından Satış&Pazarlama -> Hareket Oluştur -> Verilen Sipariş şeklinde ulaşım sağlayabilirsiniz.

## Tanım

Verilen sipariş, bir işletmenin ihtiyaç duyduğu mal veya hizmetleri tedarik etmek amacıyla satıcılara yaptığı resmi satın alma talebini ifade eder. 
Bu işlem, satın alma sürecinde kullanılan temel bir adımdır ve genellikle siparişin detaylarını, miktarını, fiyatını ve teslimat koşullarını içerir.
Verilen siparişte siparişin kim tarafından onaylandığı ve sipariş numarası gibi izleme bilgileri de bulunur.

### Genel 

**Şirket-Şube:** Bu kartın ait olduğu şirket ve şubeyi belirtir. [Şirket-Şube](../TemelOzellikler/SirketSubeHareket.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir. **Girilmesi Zorunludur.**

**Belge No:** Belge numarasını ifade eder. Otomatik olarak sıradaki numara gelir. İstenilirse seri kullanılabilir.

**Satıcı:** Satın alma yapıldığı cari kartını ifade eder. **Girilmesi Zorunludur.**

**Döviz:** Bu işlemin çalıştığı döviz cinsini belirtir.

**Depo:** Bu işlemin kullanıldığı depoyu belirtir.

**Vade:** İşlemin yapıldığı vadeyi belirtir.

**Açıklama:** İşleme ait açıklamayı belirtir.

**KDV Dahil:** Kalemlerde birim fiyat ve tutarın 'KDV Dahil' olduğunu belirtir.

### Detay

- **Beklenen Tahsilat ve Ödemeler:** Bir işletmenin, belirli bir zaman dilimi içinde müşterilerinden almayı beklediği ödemelerdir. 
	Bu, genellikle satışlardan kaynaklanan alacakları ve diğer gelir kalemlerini içerir. Beklenen Tahsilatlar ve Ödemeler kullanım detayları için linke tıklayınız. [Beklenen Tahsilatlar ve Ödemeler](../TemelOzellikler/BeklenenTahOd.md)

- **Alt Tip:** Alt hareket tipini belirtir.

- **Sözleşme:** Bu hareketin hangi sözleşmeye ait olduğunu gösterir.

- **Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir.

- **Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir.

- **Cari Adres:** Carinin adresini belirtir. Farklı adrese gönderilecekse seçilmelidir. Kalemlerde değiştirilebilir.

- **Ref. İthalat İhracat:** Bu hareket bir ithalat yada ihracat ise seçilmelidir. Hangi ithalata veya ihracata ait olduğunu belirtir. Kalemlerde Değiştirilebilir.

- **Teslim Tarihi:** Verilen siparişin teslim edildiği tarihi belirtir.

### Açıklamalar

- **Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](../TemelOzellikler/Aciklama.md)

### Etiketler

- **Etiketler:** Bu kartı gruplamak ve sonrasında gruplu rapor alabilmek için kullanılır. [Etiketler](../TemelOzellikler/Etiketler.md)

## Doldurmamız gereken bilgileri doldurduktan sonra *Kaydet* butonuna basarak bir sonraki kalem ekleme aşamamıza geçebiliriz.

- Açılan ekranda kalem(kart) ekleme alanımız açılacaktır. 
- Verilen siparişimiz stok, gelir gider, demirbaş olabilir. En başta ki kutucuktan seçim yapılabilir, sistem otomatik stok olarak getirir.
- Kart Adı: Stok, demirbaş ya da gelir gider satışını gerçekleştireceğimiz kartı belirtir.
- Miktar: Teklifte belirtilmesi istenilen stoğun miktarını belirtir, bu alanın doldurdurulması gerekmektedir.
- Brüt Fiyat: Bir ürün veya hizmetin vergiler ve ek ücretler dahil toplam satış fiyatını belirtir. 
	Buraya tıklayarak yeni fiyat eklenebilir, son 3 ay için alış ve satış ortalama fiyatlarını gösterir.
- İskonto: Teklifimizde girdiğimiz kalem için iskonto oranını belirtir. Uyguladığımız iskonto var ise buraya oranı girebiliriz.
- Net Fiyat: Bir ürün veya hizmetin vergiler ve ek ücretler hariç, sadece temel maliyetini ifade eden fiyatı belirtir. 
	Buraya tıklayarak yeni fiyat eklenebilir, son 3 ay için alış ve satış ortalama fiyatlarını gösterir.
- Tutar: Bir mal veya hizmetin toplam mali değerini ifade eden miktarı belirtir. 
- KDV oran: KDV oranını ifade eder.
- Depo: Bu kalemin kullandığı depoyu belirtir.
- Açıklama: Kaleme ait açıklamayı belirtir.
- Proje: Bu kalemin hangi projeye ait olduğunu belirtir.
- Sözleşme: Bu kalemin hangi sözleşmeye ait olduğunu gösterir.

- Siparişte bir kalem belirtilecekse *Kaydet* diyerek bir sonraki aşamaya geçebiliriz.
- Başka kalemlerde mevcut ise yukarıda ki aşamaları tekrar ederek yeni kalemleri ekleyebilirsiniz.

- Sağ üst köşede faturaya ait toplam fiyat kısımları bulunur;
	- Toplam: Siparişin KDV hariç toplam tutarını içerir.
	- İskonto Sonrası: Siparişin KDV dahil fiyatından uygulanan iskonto tutarını ifade eder.
	- KDV: Siparişin KDV oranının karşılık geldiği tutarı ifade eder.
	- Genel Toplam: Siparişin tüm kalemlerin KDV dahil tutarının toplamını belirtir.

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlardaki belgeleri buraya yükleyebiliriz.
Buraya işlem esnasındaki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- *Daha önce yüklediklerimden seç -> belgeyi seç -> İlişkilendir* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- *Yüklenecek belge veya resimleri seç -> Belgeyi ya da belgeleri seç -> Yükle* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

## Notlar 

İşleme ait özel notlar ekleyebiliriz. Önemli bir detay varsa, bu ayrıntıları burada belirtebiliriz. Notların kullanım detayları için lütfen bağlantıya tıklayınız.[Notlar](../TemelOzellikler/Notlar.md)

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

## Kalem Ekleme

- Yeni Stok Kalemi Ekle: Vereceğimiz siparişin stok kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Gelirgider Kalemi Ekle: Vereceğimiz siparişin gelir gider kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Demirbaş Kalemi Ekle: Vereceğimiz siparişin demirbaş kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Tekliften Kalem Ekle: Siparişimizde, verdiğimiz tekliflerden kalem eklemek için kullanılır.
- Talepten Kalem Ekle: Siparişimizde, satın alma talebinde bulunan taleplerden kalem eklemek için kullanılır.


## Kaydetme ve Silme

- Doldurulması gereken alanlar girildikten sonra sağ alt köşede bulunan *Kaydet* butonuna tıklayarak Verilen sipariş işleminizi tamamlayabilirsiniz.
- Kayıtlı bir kartı silmek için sol altta bulunan sil butonuna tıklayabilirsiniz.

## Yazdır

- Sayfanın sağ üstünde bulunan yazıcı sembolü ile sayfaya tanımlanan özel çıktı formatları ile farklı çıktılar alınabilir. 
- Kartta bulunan bilgilerin kullanıcının isteğine bağlı olarak özel tasarım ile yazdırılmasını sağlar.
- Birden çok çıktı tasarım yapılabilir ve değiştirilebilir.
- Kullanıcıya özel teklif formu gibi farklı tasarımlar yapılabilir.
- Çıktı tasarımlarının her birine ayrı ayrı yetkiler verilerek sadece istenilen kullanıcının belirli çıktılara ulaşması sağlanabilir.
- Çıktılar program üzerinden e-mail olarak gönderilebilir. 

## Düzenleme 

Verilen siparişimize ekleme yapmak ya da herhangi bir düzeltme yapmak için kalem işaretini seçerek açılan ekranda düzenlemeleri yapabiliriz.

## Ek İşlemler

 Sayfanın sağ üstünde bulunan alt alta üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- Yevmiye Fiş: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Verilen siparişi kopyalamak için kullanılır.
- Tüm Kalemlerde Değiştir: Buradan depo, proje, sözleşme, vergi muafiyeti, vergilerin yenilenmesi, iskonto oranı, referans ithalat/ihracat, plasiyer ve referans teslim tarihi gibi bilgileri tüm kalemler için toplu olarak değiştirebilirsiniz.
- Döviz Türü Değiştir: Döviz türü değişikliği yapabiliriz.
- Görev Oluştur: Sipariş için görev oluşturup, kişi atayabiliriz. Açıklama, tarih bitiş, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemimizi gerçekleştirebiliriz.
- Görev Bağla: Açılan listedeki görevlerden bağlayacağımız, birleştireceğimiz görevi seçip, *Kaydet* diyerek görevi bağlayabiliriz.
- Kapat: Siparişimizi açmak ya da kapatmak için kullanılır.
- Paylaş: Alınan siparişin hangi şirket veya şubelerde gözükeceğini buradan seçebiliriz.
- İrsaliyeleştir: Siparişimiz tamamalandıktan sonra buradan irsaliyeleştir yaparak, siparişimizi irsaliyeleştirebiliriz.
- Faturalaştır: Siparişimiz tamamalandıktan sonra buradan faturalaştır yaparak, siparişimizi faturalaştırabiliriz.
- Grid Sütunları Ayarla: Burada kartın detaylarının görünümünde değişiklikler yapabilirsiniz.
