---
SayfaID: Stok
SayfaTipi: Kart
---

## Stok Kartı

**Erişim Linki :** [erp.aaro.com.tr/Stok/Kalem](https://erp.aaro.com.tr/Stok/Kalem)

### Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altındaki arama motorundan "Stok kartı" olarak aratarak ulaşım sağlayabilirsiniz.
- Sol menüden *Stok -> Stok Modülü -> Yeni Stok Kartı* şeklinde ulaşım sağlayabilirsiniz. 
- *Sol menüden Stok -> Kartlar -> Stok Kartı Listesi* üzerinden ulaşım sağlayarak yeni kart ekleyebilir ya da mevcutları düzenleyebilirsiniz.

### Tanım

Stok, bir işletmenin satış veya üretim amacıyla depoladığı tüm fiziksel varlıkları ifade eder. Bu varlıklar malzemeler, ham madde, yarı mamul veya tamamlanmış ürünler olabilir. Stok kartlarınızı tanımlayarak, bu varlıkların miktarını, değerini ve döngüsünü izleyebilir ve optimize edebilirsiniz. Stok seviyelerini belirlemek, stok hareketlerini işlemek ve envanterin doğru bir şekilde yönetilmesi için stok kartları oluşturulmalıdır. 

Stok kartınızı tanımlamak için aşağıdaki bilgileri doldurabilirsiniz.

### Genel

**Stok Adı:** Bu stok kartının kendine özel adıdır.

**Stok Kodu:** Kartın kendine özel kodudur. Detaylı tanım için linke tıklayınız. [Kart Kodu](../TemelOzellikler/KartKodu.md)

**Birim 1:** Stok kartının hangi birim cinsinden takip edileceğini belirtir. Girilecek ürünün ölçü ya da sayım birimi yani adet, m3, kg, litre, desi, koli, plaka gibi özellikler eklenebilir.

**Kodlar:** Kartları hiyerarşik olarak gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Kodlar](../TemelOzellikler/Kodlar.md)

**Etiketler:** Gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Etiketler](../TemelOzellikler/Etiketler.md)


### Fiyat

**Alış Fiyat:** Bu stok kartına ait ürün veya hizmetin satın alınırken ödenen fiyatını ifade eder.

**Döviz Adı:** Bu stok kartına ait alış fiyatının çalıştığı döviz cinsini belirtir. Bilgi amaçlıdır.

**Satış Fiyat:** Bu karta ait ürün veya hizmetin müşterilere satıldığı fiyatı ifade eder.

**Döviz Adı:** Bu stok kartın alış fiyatının çalıştığı döviz cinsini belirtir. Bilgi amaçlıdır.


### Barkod

**Barkod1:** Bu stok kartına ait barkod numarasını belirtir. 

**Barkod2:** Bu stok kartına ait ikinci barkod numarasını belirtir. Birden fazla barkodu olan stoklar için kullanım sağlayabilirsiniz.


### Ölçü Birimleri

**Birim 2:** Bu stok kartı için ikinci ölçü birimidir.Kolay hesap yapmak ve raporlarda farklı cins rapor alabilmek için kullanılır.

**Birim 3:** Bu stok kartı için üçüncü ölçü birimidir.Kolay hesap yapmak ve raporlarda farklı cins rapor alabilmek için kullanılır.

**Çevrimiçi Birim2:** Birim-1 cinsinden bu stoğun kaç Birim-2 cinsinden olduğunu belirtir.Örneğin; Birim-1:Adet ve Birim-2:Deste ise bu değer = 0,1(1/10) olur.

**Çevrimiçi Birim3:** Birim-1 cinsinden bu stoğun kaç Birim-3 cinsinden olduğunu belirtir.Örneğin; Birim-1:Adet ve Birim-3:Düzine ise bu değer = 0,083(1/12) olur.

**Üretim Birim:** Üretimle ilgili raporlarda seçilen birim cinsinden rapor almanızı kolaylaştırır.

**Rapor Birim:** Raporlarda seçilen birim cinsinden rapor almanızı kolaylaştırır.

**Kalınlık:** Stoğun kalınlık ölçüsünü belirtir.

**En:** Stoğun en ölçüsünü belirtir.

**Boy:** Stoğun boy ölçüsünü belirtir.

**Yoğunluk:** Stoğun yoğunluk ölçüsünü belirtir.

**Ağırlık:** Stoğun ağırlık ölçüsünü belirtir.


### Vergi Oranları
 Bu stok kartı ait işlemlerde kullanılacak devletin belirlemiş olduğu KDV oranını(vergi oranını) belirtir. **Girilmesi Zorunludur.**

### Muhasebe Tanımları

Muhasebeleşme tanımlarını ayarlayarak, bu kart için hareket işlendiğinde otomatik olarak belirli muhasebe hesaplarına gerekli kayıtların oluşturulmasını sağlayabilirsiniz.
[Muhasebeleşme Tanımları](../TemelOzellikler/MuhasebelesmeTanimlari.md)



### Bayi Tanımları

**Bayide Göster:** Stoklarınızın tamamı bayilerinize gösterilmez. Bayi sisteminiz aktifse, göstermek istediğiniz stoku işaretlemeniz gerekmektedir.

**Bayi Maks. Miktar:** Bayileriniz, belirlediğiniz sayının üzerindeki stok miktarını göremezler. Örneğin, deponuzda 100 birim ABC stoğu varsa ve bu alana 50 girerseniz, bayileriniz bu stoğun miktarını "50+" şeklinde görecektir. Eğer 0 girerseniz, bayiler sadece "Stokta Var" veya "Stokta Yok" şeklinde görebilirler.

**Stok Yönetimi**

**Takip Yöntemi:** Stok miktar takibi yapılırken seri veya lot takibi yapılıp yapılmadığını gösterir. **Girilmesi Zorunludur.**

**TY Kod Ön Eki:** Otomatik başlatılan seri ve lot numaralarında numaranın istenilen seri ile başlamasını sağlar. **Girilmesi Zorunludur.**

**TY Üretim Birebir ilişki:** Üretim hareketlerinde bu stok üretilirken her bir seri ve lot için hangi ham maddelerin bire bir kontrol edileceğini belirler. **Girilmesi Zorunludur.**

**Raf Takibi:** Raf takibi yapılıp yapılmayacağını belirler. *Girilmesi Zorunludur.**

**Paket Takibi:** Paket takibi yapılıp yapılmayacağını belirler. *Girilmesi Zorunludur.**


### Gelişmiş

**Şirket-Şube:**  Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Durum:** Kartın kullanılabilirliğini belirtir. Pasif kartlar işlemde kullanılamaz.

**GTIP:** İhracat tipindeki e-faturalarda, stoğa ait GTIP değerinin doldurulması zorunludur.

**Harici Depo Miktar:** Depo dışında kalan miktarı belirtir.

**Hizmet Mi:** Bu seçenek hizmet takibi olarak seçilirse miktar takibi yapılmaz, depoda gözükmez, eski bakiye kontrolü yapılmaz.

**Stok Kısa Kodu:** Raporlama için gereklidir. 

**Stok Kısa Adı:** Raporlama için gereklidir. 

**Kargo ücreti:** Kargo ücreti 

**StandartMı:** Stok kartının standart stok olarak değerlendirilmesini sağlar. Filtreleyerek bulmayı kolaylaştırır. 


### Açıklamalar

Bu kısma stok ile ilgili açıklama eklenebilir. Açıklama detaylarına linkten erişim sağlayabilirsiniz. [Açıklamalar](../TemelOzellikleri/Aciklama.md)


## Kaydetme ve Silme

- Doldurulması gereken alanlar girildikten sonra sağ alt köşede bulunan *Kaydet* butonuna tıklayarak Müşteri/Satıcı kartı açma işleminizi tamamlayabilirsiniz.
- Kayıtlı bir kartı silmek için sol altta bulunan sil butonuna tıklayabilirsiniz.

## Kısayollar

Stokta bulunan kısayollar sekmesi ile stokla ait ilgili raporlara ve öncelikli sayfalara kolayca ulaşabilirsiniz.

- Liste
	- Hareketleri
	- Alınan Sipariş Hareketleri
	- Depo Miktarları

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından, hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

## Yazdır

- Sayfanın sağ üstünde bulunan yazıcı sembolü ile sayfaya tanımlanan özel çıktı formatları ile farklı çıktılar alınabilir. 
- Kartta bulunan bilgilerin kullanıcının isteğine bağlı olarak özel tasarım ile yazdırılmasını sağlar.
- Birden çok çıktı tasarım yapılabilir ve değiştirilebilir.
- Kullanıcıya özel ekstre, dövizli ekstre gibi farklı tasarımlar yapılabilir.
- Çıktı tasarımlarının her birine ayrı ayrı yetkiler verilerek sadece istenilen kullanıcının belirli çıktılara ulaşması sağlanabilir.
- Çıktılar program üzerinden e-mail olarak gönderilebilir. 


## Ek İşlemler

 Sayfanın sağ üstünde bulunan alt alta üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- [Ana Sayfaya Kısayol Olarak Ekle](../TemelOzellikler/KisaYollaraEkleme.md)
- Görev Oluştur 
- Görev Bağla

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlarda bu belgeleri buraya yükleyebiliriz.
Buraya işlem esnasındaki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- *Daha önce yüklediklerimden seç -> belgeyi seç -> İlişkilendir* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- *Yüklenecek belge veya resimleri seç -> belgeyi ya da belgeleri seç-> Yükle* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)


## Notlar

İşleme ait özel notlar belirtebiliriz. 
Önemli bir detay var ise bu detayları burada belirtebiliriz.
Notlar kullanım detayları için linke tıklayınız. [Notlar](../TemelOzellikler/Notlar.md)

