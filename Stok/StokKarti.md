
## Stok Kartı

### Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "Stok kartı" olarak aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Stok -> Stok Modülü -> Yeni Stok Kartı şeklinde ulaşım sağlayabilirsiniz. 
- Sol menüden Stok -> Kartlar -> Stok Kartı Listesi üzerinden ulaşım sağlayarak yeni kart ekleyebilir yada mevcutları düzenleyebilirsiniz.

### Tanım

Stok, bir işletmenin sahip olduğu satış veya üretim için kullanılmak üzere depoladığı tüm fiziksel varlıkları ifade eder. 
Bu varlıklar, malzemeler, hammadde, yarı mamul veya tamamlanmış ürünler olabilir. 
Stok kartlarınızı tanımlayarak, bu varlıkların miktarını, değerini ve döngüsünü izleyebilir ve optimize edebilirsiniz. 
Stok seviyelerini belirlemek, stok hareketlerini işlemek ve envanterin doğru bir şekilde yönetilmesi için stok kartları tanımlanmalıdır.
Aşağıdaki bilgiler doldurularak stok kartınızı tanımlayabilirsiniz.

### Genel

**Stok Adı:** Bu stok kartının kendine özel adıdır.

**Stok Kodu:** Kartın kendine özel kodudur. Detaylı tanım için linke tıklayınız. [Kart Kodu](../TemelOzellikler/KartKodu.md)

**Birim 1:** Stok kartının hangi birim cinsinden takip edileceğini belirtir. Girilecek ürünün ölçü ya da sayım birimi yani adet m3 kg litre desi koli plaka gibi özellikler eklenebilir.

**Kodlar:** Kartları hiyerarşik olarak gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Kodlar](../TemelOzellikler/Kodlar.md)

**Etiketler:** Gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Etiketler](../TemelOzellikler/Etiketler.md)


### Fiyat

**Alış Fiyat:** Bu stok kartına ait ürün veya hizmetin satın alınırken ödenen fiyatını ifade eder.

**Döviz Adı:** Bu stok kartına ait alış fiyatının çalıştığı döviz cinsini belirtir. Bilgi amaçlıdır.

**Satış Fiyat:** Bu karta ait ürün veya hizmetin müşterilere satıldığı fiyatı ifade eder.

**Döviz Adı:** Bu stok kartın aiat alış fiyatının çalıştığı döviz cinsini belirtir. Bilgi amaçlıdır.


### Barkod

**Barkod1:** Bu stok kartına ait barkod numarasını belirtir. 

**Barkod2:** Bu stok kartına ait ikinci barkod numarasını belirtir. Birden fazla barkodu olan stoklar için kullanım sağlayabilirsiniz.


### Ölçü Birimleri

**Birim 2:** Bu stok kartı için ikinci ölçü birimidir.Kolay hesap yapmak ve raporlarda farklı cins rapor alabilmek için kullanılır.

**Birim 3:** Bu stok kartı için üçüncü ölçü birimidir.Kolay hesap yapmak ve raporlarda farklı cins rapor alabilmek için kullanılır.

**Çevrimiçi Birim2:** Birim-1 cinsinden bu stoğun kaç Birim-2 cinsinden olduğunu belirtir.Örneğin; Birim-1:Adet ve Birim-2:Deste ise bu deger = 0,1(1/10) olur.

**Çevrimiçi Birim3:** Birim-1 cinsinden bu stoğun kaç Birim-3 cinsinden olduğunu belirtir.Örneğin; Birim-1:Adet ve Birim-3:Düzine ise bu deger = 0,083(1/12) olur.

**Üretim Birim:** Üretimle ilgili raporlarda seçilen birim cinsinden rapor almanızı kolaylaştırır.

**Rapor Birim:** Raporlarda seçilen birim cinsinden rapor almanızı kolaylaştırır.

**Kalınlık:** Stoğun kalınlık ölçüsünü belirtir.

**En:** Stoğun en ölçüsünü belirtir.

**Boy:** Stoğun boy ölçüsünü belirtir.

**Yoğunluk:** Stoğun yoğunluk ölçüsünü belirtir.

**Ağırlık:** Stoğun ağırlık ölçüsünü belirtir.


### Vergi Oranları

**Vergi Oranları:** Bu stok kartı ait işlemlerde kullanılacak devletin belirlemiş olduğu KDV oranını(vergi oranını) belirtir. **Girilmesi Zorunludur.**

### Muhasebe Tanımları

Muhasebeleşme tanımlarını ayarlayarak bu kart için hareket işlendiğinde otomatikman belirli muhasebe hesaplarına gerekli kayıtların oluşmasını sağlayabilirsiniz.
[Muhasebeleşme Tanımları](../TemelOzellikler/MuhasebelesmeTanimlari.md)



### Bayi Tanımları

**Bayide Göster:** Tüm stoklarınız bayilerinize gösterilmez.Bayi sisteminiz aktif ise göstermek istediğiniz bir stok ise işartelemeniz gerekmektedir.

**Bayi Maks. Miktar:** Bayileriniz, belirleyeceğiniz sayının üzerindeki stok miktarını göremez. Örneğin;Deponuzda 100 birim ABC stoğu var.
Bu alana 50 girilirse, bayileriniz bu stoğun miktarını 50+ şeklinde görecektir.0 girerseniz asdece'Stokta Var' ya da 'Stokta Yok' şeklinde görürler.

**Stok Yönetimi**

**Takip Yöntemi:** Stok miktar takibi yapılırken Seri veya Lot takibi yapılıp yapılmadığını belirler. **Girilmesi Zorunludur.**

**TY Kod Ön Eki:** Otomatik başlatılan Seri ve Lot numaralarında No'nun istenilen seri ile başlasını sağlar. **Girilmesi Zorunludur.**

**TY Üretim Bire Bir ilişki:** Üretim hareketlerinde bu stok üretilirken her bir Seri ve Lot için hangi hammaddelerin bire bir kontrolünün yapılması için kullanılır. **Girilmesi Zorunludur.**

**Raf Takibi:** Raf takibi yapılıp yapılmayacağını belirler. *Girilmesi Zorunludur.**

**Paket Takibi:** Paket takibi yapılıp yapılmayacağını belirler. *Girilmesi Zorunludur.**


### Gelişmiş

**Şirket-Şube:**  Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Durum:** Kartın kullanabilirliğini belirtir. Pasif kartlar işlemde kullanılamaz.

**GTIP:** İhracat tipindeki e-faturalarda, stoğa ait GTIP değerinin doldurulması zorunludur.

**Harici Depo Miktar:** Depo dışında kalan miktarı belirtir.

**Hizmet Mi:** Bu seçenek hizmet takibi olarak seçilirse miktar takibi yapılmaz, depoda gözükmez, eski bakiye kontrolü yapılmaz.

**Stok Kısa Kodu:** Raporlama için gereklidir. 

**Stok Kısa Adı:** Raporlama için gereklidir. 

**Kargo ücreti:** Kargo ücreti 

**StandartMı:** Stok kartının standart stok olarak değerlendirilmesini sağlar. Filtreleyerek bulmamızı kolaylaştırır. 


### Açıklamalar

Bu kısma stok ile ilgili açıklama eklenebilir.


Doldurulması gereken alanlar girildikten sonra sağ alt köşede bulunan Kaydet butonuna basarak Stok kartı açma işlemimizi tamamlayabilirsiniz.
