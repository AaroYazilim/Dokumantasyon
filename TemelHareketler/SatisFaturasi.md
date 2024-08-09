---
SayfaID: SatisFaturasi
SayfaTipi: Fatura
---

# Satış Faturası

**Erişim Linki :** [erp.aaro.com.tr/FaturaSatisFaturasi](https://erp.aaro.com.tr/FaturaSatisFaturasi)

### Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "satış faturası" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Musteri/Satici -> Hareket Oluştur -> Satış Faturası şeklinde ulaşım sağlayabilirsiniz. 
- Sol menüden Satış & Pazarlama -> Listeler -> Satış Faturası Listesi -> Yeni Hareket Ekle üzerinden ulaşım sağlayabilirsiniz. 

## Tanım 

Satış faturası, bir satıcı tarafından müşteriye mal veya hizmet satışı sonrasında düzenlenen ve satışı belgelendiren ticari bir belgedir.
Satış faturası, yasal bir belge olduğundan dolayı doğru ve eksiksiz düzenlenmesi önemlidir. Faturanın bir kopyası satıcıda kalırken, asıl nüshası müşteriye verilir. 
Bu, her iki taraf için de muhasebe kayıtlarının düzgün tutulması ve olası anlaşmazlıkların önlenmesi açısından kritiktir.

## Genel

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir. 

**Belge No:** Belge numarasını ifade eder. Otomatik sıradaki numara gelir. İstenirse seri kullanılabilir.

**Müşteri:** İşlemin yapıldığını cari kartını ifade eder. 

**Döviz:** Bu banka hesabının çalıştığı döviz cinsini belirtir.Türk lirası haricinde başka bir döviz seçildiğinde sadece o döviz cinsinden hareket işlenmesine izin verir. 
Banka hesabının bakiyesi seçilen döviz cinsinden takip edilir.

**Depo:** Bu işlemin kullandığı depoyu belirtir.

**Vade** İşlemin yapıldığı vadeyi belirtir. Cari ile ilgili işlem yapıldığında otomatik buradaki vade gelecektir.
	Ay sonu seçeneği belirtilen günden sonraki ay sonuna alır. 0 ise ayın sonuna alır. Vade ile ilgili detaylı [Vade](../TemelOzellikler/Vade.md)

**Açıklama** İşleme ait açıklamayı belirtir. Açıklama kullanım detayları için linke tıklayınız.[Açıklama](../TemelOzellikler/Aciklama.md)

**KDV Dahil** Kalemlerde birim fiyat ve tutarın 'KDV Dahil' olduğunu belirtir. KDV dahil kullanım detayları için linke tıklayınız.[KDV Dahil](../TemelOzellikler/KDVdahil.md)

## Detay

**Beklenen Tahsilatlar ve Ödemeler** Bir işletmenin, belirli bir zaman dilimi içinde müşterilerinden almayı beklediği ödemelerdir. 
	Bu, genellikle satışlardan kaynaklanan alacakları ve diğer gelir kalemlerini içerir. Beklenen Tahsilatlar ve Ödemeler kullanım detayları için linke tıklayınız. [Beklenen Tahsilatlar ve Ödemeler](../TemelOzellikler/BeklenenTahOd.md)

**Cari Detay:**

**Alt Tip:** Alt hareket tipini belirtir.

**Sözleşme:** Bu hareketin hangi sözleşmeye ait olduğunu gösterir. Sözleşme kullanım detayları için linke tıklayınız.[Sözleşme](../TemelOzellikler/Sozlesme.md)

**Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir. Proje kullanım detayları için linke tıklayınız.[Proje](../TemelOzellikler/Proje.md)

**Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir. Plasiyer kullanım detayları için linke tıklayınız.[Plasiyer](../TemelOzellikler/Plasiyer.md)

**Cari Adres:** Girilen carinin birden çok adresi varsa ve farklı adrese gönderilecekse seçilmelidir. Carinin adresini belirtir. Kalemlerde değiştirilebilir.

**Ref. İthalat İhracat:** Bu hareket bir ithalat ya da ihracata ait olduğunu belirtir. Kalemlerde değiştirilebilir.

### Açıklamalar

- **Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](/TemelOzellikler/Aciklama.md "Açıklama")	

### Etiketler

- **Etiketler:** Bu kartı gruplamak ve ileride gruplu rapor alabilmek için kullanılır. [Etiketler](/TemelOzellikler/Etiketler.md "Etiketler")

## Doldurmamız gereken bilgileri doldurduktan sonra kaydet butonuna basarak bir sonraki kalem ekleme aşamamıza geçebiliriz.

- Açılan ekranda kalem(kart) ekleme alanımız açılacaktır. 
- Satış faturamızda satış yapacağımız işlem stok, gelir gider, demirbaş olabilir. En başta ki kutucuktan seçim yapılabilir, sistem otomatik stok olarak getirir.
- Kart Adı: Stok, demirbaş ya da gelir gider satışını gerçekleştireceğimiz kartı belirtir.
- Miktar: Satış yapacağımız stoğun miktarını belirtir, bu alanın doldurdurulması gerekmektedir.
- Brüt Fiyat: Bir ürün veya hizmetin vergiler ve ek ücretler dahil toplam satış fiyatını belirtir. 
	Buraya tıklayarak yeni fiyat eklenebilir, son 3 ay için alış ve satış ortalama fiyatlarını gösterir.
- İskonto: Satışını yaptığımız işlemlerin iskonto oranını belirtir. Uyguladığımız iskonto var ise buraya oranı girebiliriz.
- Net Fiyat: Bir ürün veya hizmetin vergiler ve ek ücretler hariç, sadece temel maliyetini ifade eden fiyatı belirtir. 
	Buraya tıklayarak yeni fiyat eklenebilir, son 3 ay için alış ve satış ortalama fiyatlarını gösterir.
- Tutar: Bir mal veya hizmetin toplam mali değerini ifade eden miktarı belirtir. 
- KDV oran: KDV oranını ifade eder.
- Depo: Bu kalemin kullandığı depoyu belirtir.
- Açıklama: Kaleme ait açıklamayı belirtir.
- Proje: Bu kalemin hangi projeye ait olduğunu belirtir.
- Sözleşme: Bu kalemin hangi sözleşmeye ait olduğunu gösterir.
- Proje: Bu kalemin hangi projeye ait olduğunu belirtir.

- Satış faturasında 1 kalem belirtilecekse kaydet diyerek bir sonraki aşamaya geçebiliriz.
- Başka kalemlerde mevcut ise yukarıda aşamaları tekrar ederek yeni kalemleri ekleyebilirsiniz.

- Sağ üst köşede faturaya ait toplam fiyat kısımlarını içerir;
	- Toplam: Satış faturasının KDV hariç toplam tutarını içerir.
	- İskonto Sonrası: Satış faturasının KDV dahil fiyatından uygulanan iskonto tutarını ifade eder.
	- KDV: Satış faturasının KDV oranının karşılık geldiği tutarı ifade eder.
	- Genel Toplam: Satış faturasının tüm kalemlerin KDV dahil tutarının toplamını belirtir.

### Kalem Ekleme Ek Özellikler

- Yeni Stok Kalemi Ekle: Stok kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Gelirgider Kalemi Ekle: Gelir gider kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- Yeni Demirbaş Kalemi Ekle: Demirbaş kalemi eklemek için burayı seçerek ekleme sağlayabilirsiniz.
- İrsalİyeden Kalem Ekle: İrsaliyeden eklemek istediğimiz kalemleri seçerek faturamıza aktarım yapabiliriz.
- Siparişten Kalem Ekle: Siparişten eklemek istediğimiz kalemeleri seçerek faturamıza aktarım yapabiliriz.

## Notlar 

İşleme ait özel notlar belirtebiliriz. 
Önemli bir detay var ise bu detayları burada belirtebiliriz.
Notlar kullanım detayları için linke tıklayınız. [Notlar](../TemelOzellikler/Notlar.md)

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpeg, png, pdf vb. formatlarda bu belgeleri buraya yükleyebiliriz.
Buraya işlem gerçekleşirken ki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- Daha önce yüklediklerimden seç -> belgeyi seçelim -> İlişkilendir şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- Yüklenecek belge veya resimleri seçin -> belgeyi ya da belgeleri seçelim -> Yükle şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

## Kaydetme ve Silme

- Doldurulması gereken alanlar girildikten sonra sağ alt köşede bulunan Kaydet butonuna tıklayarak Müşteri/Satıcı kartı açma işlemimizi tamamlayabilirsiniz.
- Kayıtlı bir kartı silmek için sol altta bulunan sil butonuna tıklayarak silebilirsiniz.

## Yazdır

- Sayfanın sağ üstünde bulunan yazıcı sembolü ile sayfaya tanımlanan özel çıktı formatları ile farklı çıktılar alınabilir. 
- Kartta bulunan bilgilerin kullanıcının isteğine bağlı olarak özel tasarım ile yazdırılmasını sağlar.
- Birden çok çıktı tasarım yapılabilir ve değiştirilebilir.
- Kullanıcıya özel ekstre, dövizli ekstre gibi farklı tasarımlar yapılabilir.
- Çıktı tasarımlarının herbirine ayrı ayrı yetkiler verilerek sadece istenilen kullanıcının bilirli çıktılara ulaşması sağlanabilir.
- Çıktılar program üzerinden e-mail olarak gönderilebilir. 

## Ek İşlemler

 Sayfanın sağ üstünde bulunan alt altta üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- Yevmiye Fiş: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Faturayı kopyalamak için kullanılır.
- Tüm Kalemlerde Değiştir: Buradan depo, proje, sözleşme, vergi muafiyeti, vergileri yenile, iskonto oranı, ref. ithalat ihracat, plasiyer, Ref teslim tarihi bilgilerini tüm kalemlerde değiştirebiliriz.
- Döviz Türü Değiştir: Döviz türü değişikliği yapabiliriz.
- Depo Terminaline Aktar: 
- Görev Oluştur: Satış Faturası için görev oluşturup, kişi atayabiliriz, açıklama, tarih bitiş, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemimizi gerçekleştirebiliriz.
- Görev Bağla: Açılan listede ki görevlerden görevi bağlayacağımız, birleştireceğimiz görevi seçelim, kaydet diyerek görevi bağlayabiliriz.
- Nakit Tahsilat: Fatura için nakit tahsilata hızlı erişimdir. Buradan kasamızı, nakit tahsilat tutarını girerek, eklemek istediğimiz bilgileri ekleyerek, faturaya ait nakit tahsilat tanımlayabiliriz.
- Kredi Pos Tahsilat: Sipariş için pos tahsilata hızlı erişimdir. Buradan pos tahsilat işlemlerini gösterebiliriz, çekim yaptığım pos tahsilatın bankasını seçelim, tutarını girelim, taksit adedini girelim, eklemek istediğimiz bilgileri ekleyerek, siparişe ait pos tahlisat tanımlayabiliriz. 
- Banka Tahsilat: Fatura için Havale/EFT Alma hareketine hızlı erişimdir. Buradan banka hesabımıza gelen Havale/EFT Alma işlemimizi, gelen banka hesabımızı seçerek gerekli bilgileri ekleyerek faturaya ait havale/EFT ödemimizi girebiliriz.
- İrsaliyelerini Gör: Faturasını oluşturduğumuz satışımızın irsaliyesini görmek için hızlı erişim sağlar.
- Siparişlerini Gör: Faturasını oluşturduğumuz satışımızın siparişini görmek için hızlı erişim sağlar.
- Sipariş Detayları: Sipariş detyalarına hızlı erişim sağlayabiliriz.
- Alış - Satış Analiz: Faturasını oluşturduğumuz ürünlerin alış fiyatalarını, satış yaptığımız fiyatları görerek kar-zarar analizi yapabiliriz.


# e-Fatura / e-Arşiv Gönderme

- Oluşturduğumuz satış fatura bilgilerimizi kontrol edelim.
- KDV Dahil Mi: Faturaya girilen tutarın KDV dahil mi hariç mi olduğunu ifade eder. KDV dahil fiyat girildiğinde bu seçenek işaretlenmelidir.
- e-Fatura / e-Arşiv Fatura Gönder seçeneğine tıklandığında fatura oluşturma ekranına yönlendirme sağlanır.
- e-Fatura / e-Arşiv Fatura Önizle fatura önizlemesini görüntüleyerek kontrolleri sağlayabilirsiniz.
- e-Fatura / e-Arşiv Fatura Gönder seçeneğine tıklayarak fatura oluşturma işlemeni tamamlayabilirsiniz.