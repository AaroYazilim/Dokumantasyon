
## Depo - Stok Soruları

**Soru:** 
Sayım farkını nasıl silebilirim?

**Cevap:**

**Stok modülü -> Stok Haraketleri Listesi -> Stok Hareketleri** adımlarını izleyerek işlem sayfasına ulaşabilirsiniz.  
Stok sayım farkımıza gelelim, büyütece basarak ya da çift tıklayarak detayına girelim.
Kalem işaretine tıklayalım, sol alt köşedeki sil butonundan silelim.

**Soru:** Elimde tek bir ürün farkı var bunu nasıl işlerim?

**Cevap:**  

**Stok Modülü -> Hareket Oluştur -> Devir -> İlgili Depo -> Yeni Stok Kalemi Ekle -> Stok Seçimi** adımlarını izleyip miktar girişini gerçekleştirebilirsiniz.
Ardından *Kaydet*e tıklayıp işlemi tamamlayın.

**Soru:** Kesilen faturada stok kodu nasıl görüntülenir?

**Cevap:** 

*Ayarlar -> Modül sayfası -> Parametre Listesi -> Yeni Parametre Ekle* işlemlerini takip edin.    
Sonrasında "eDonusum_KalemdeStokKoduBilgisiGonderilsin (E-Fatura)" parametresini "Evet" olarak ayarlayarak, gönderilen faturalarda stok kodunun görüntülenmesini sağlayabilirsiniz.

**Soru:** Yanlış açılan stok ve cari kayıtlarının düzeltilmesi ve hareketlerinin taşınması nasıl yapılır?

**Cevap:** 
Yanlış açılan stok kartına hareket eklenmişse, ilgili hareketin bulunduğu yere gidip kartı değiştirmeniz gerekir.
Örneğin, bir satış faturasında yanlış stok kalemini düzeltmek için:   
Faturanın yevmiye fişinden muhasebeleştirme onayı ve kilidini kaldırın.
Faturanın içeriğine gidip, yanlış kalemleri doğru kalemlerle değiştirin.
Yanlış kalemin hareketi kalmadığında, ilgili stok kartını listeden çıkarabilirsiniz.

**Soru:** Fiyat listesi düzenleme şablonları ve bu şablonların tekrar yüklenmesi nasıl yapılır?

**Cevap:** *Rapor -> Stok -> Fiyat -> Fiyat Listesi Aktarım/Düzeltme Şablonu* kısmından mevcut fiyat listelerini indirip düzenleyin.  
*Ayarlar -> Modül Sayfası -> Dışarıdan Aktarma -> Stok -> Fiyat Listesi Aktarma* yolunu izleyerek tekrar yükleyin.

**Soru:** Stok sayımı nasıl yapılır ?

**Cevap:** 
Stoklarımızın sayımlarını yaptıktan sonra birden çok kalem var ise excel doldurarak aktarmak bizler için kolaylık sağlayacaktır.
Öncelikle stok sayım girişi kaydı oluşturmamız gerekmektedir; 
Stok -> Stok Sayım Listesi -> Yeni Stok Sayım Girişi Ekle -> Sayım yapılan depomuzu seçelim -> Gerekli alanları doldurduktan sonra "Kaydet" diyerek stok sayım girişi kaydımızı tamamlayabiliriz.
Açılan ekranda ürünleri tek tek girerek veya "Sayılmayan stoklardan ekle" seçeneğini kullanarak toplu bir seçim yapabiliriz. 
Ctrl ve Shift tuşlarını kullanarak açılan listeden birden fazla ürün seçip sayım girişi detaylarımızı ekleyebiliriz.
Stoklarımızın sayımlarını girdikten sonra "Stoğa İşle" diyerek sayımlarımızı stoklarımıza işleme işlemimizi tamamlabiliriz. 
Bir diğer yöntem ise; Stok sayım girişi kaydı yaptıktan sonra stokları tek tek seçmek yerine excel dosyası indirip üzerinde doldurulma yapılarak sisteme toplu bir şekilde eklenebilir.
Ayarlar -> Dışarıdan Aktarmalar -> Stok Sayım Aktarma -> Excel Şablonu İndir -> şablonumuzu indirdikten sonra excel şablonunu doldurmamız gerekmektedir.
Excel şablonunda stok kodu kısmına sistemimizde kayıtlı olan stok kodlarını girmeliyiz, 
Mamül Miktar sayımdan sonra elimizde mevcut olan stok adetimizi girmemiz gerekmektedir,
SeriLot Kodu buraya seri veya lot takibini sağladığımız stokların seri - lot numaralarını girmemiz gerekmektedir.
Açıklama buraya sayım girişi için stoklara özel açıklamayı ifade eder.
Excelimizi doldurduktan sonra sistemimize sayım girişimizi yapabiliriz;
Stok Sayım Dışarıdan Aktarma ekranına gelerek, Dosya Seç -> Dosyamızı seçelim -> Sayım Giriş Listesi -> Açtığımız sayım girişi listemizi seçelim -> Şablonu Yükle diyelim.
Sayım girişimizi sisteme excel ile toplu aktarım sağlamış olduk, sayım girişimizi stoklarımıza işleyelim;
Stok -> Stok Sayım Listesi -> Sayım girişimize girelim -> Stoğa İşle diyerek stoklarımıza işleyerek sayım girişimizi tamamlayalım.

**Soru:** Elimde tek bir ürün farkı var bunu nasıl işleyeceğim ?

**Cevap:** Ters kayıt girerek işleyeceğiz, *Stok -> Hareket Oluştur -> Devir -> Depomuzu seçelim -> 
Yeni Stok Kalemi Ekle -> Borç-Alacak seçelim -> Stok kartını seçelim ->* İlgili alanları doldurarak işlemimizi kaydedelim.

## Üretim Soruları 

**Soru:** Üretimde harcanan ürün depodan nasıl düşecek?

**Cevap:** Reçeteler işlem yapıldıkça hammadde, yarı mamül ve mamüller üretilip üretim hareketi girildikçe sistemden otomatik olarak düşmektedir.

## Satış&Pazarlama Soruları

**Soru:** Siparişin açık kaleminin ne kadar olduğunu ve ne kadarının sevkedildiğini nasıl görebilirim ?

**Cevap:** Siparişin açık kalemlerinin ne kadarının sevkedildi görmek için; 

Satış&Pazarlama modülünden -> Alınan Sipariş Listesi -> Siparişimizi seçelim -> Kısayollar -> Sevkiyat Detayları şeklinde ulaşım sağlayabiliriz.

Tüm siparişlerin sevkiyat detaylarını görmek için sevkiyat detaylarındayken kalem işaretinde düzenle diyerek filtreleme yaparak istediğiniz aralıktaki 
siparişlerinizin sevkiyat detaylarına erişim sağlayabilirsiniz.

Bir diğer yöntem ise Rapor -> Sipariş/Teklif -> Hareket -> Sipariş Sevkiyat Detayları (Arama kısmına sevkiyat yazarak da erişim sağlayabilirsiniz) -> 
Tarih aralığını seçelim -> Cari seçelim -> Sadece Açık Siparişler seçili olmalı -> Raporla -> Yazdır/İndir şeklindedi listelemektir.

**Soru:** Cari siparişlerin sevkiyatlarını nasıl görüntüleyebilirim, liste yapmak istiyorum.

**Cevap:** Alınan sipariş hareketlerini -> Cariyi seçelim -> Tarih aralığını seçelim -> Üç işlem butonundan Listeyi Excele Aktar diyerek listeyi excel formatında indirebilirsiniz. 

*Excele indir gelmiyor ise yetkiniz olmayabilir kontrol edelim.*  

**Soru:** Verilen teklifi siparişleştir dediğimde geçerlilik tarihi geçmiştir diye uyarı veriyor ne yapmam gerekiyor ?

**Cevap:** 
Verilen teklifimizi açalım, detay kısmında geçerlilik tarihi yer almaktadır tarihi güncel tarihle değiştirdiğimizde siparişleştirme yapabiliriz.

## Çek Senet Soruları

**Soru:** Müşteriye çeki nasıl ciro edebilirim?

**Cevap:** Çek/Senet modülünden -> Hareket Olustur -> Çek Ciro Edildi/Verildi şeklinde ulaşım sağlayabilirsiniz.
Buradan çeki ciro edeceğimiz cariyi seçelim, döviz türünü seçelim *Kaydet* diyelim.
Çek Senet Ekle mavi butonun yanında ki oktan ciro ekle seçeneğini seçelim, Ciro edilecek çeki seçelim *Kaydet* seçeneğine basalım.

**Soru:** Çek /senet takibi nasıl yapılır? (alındı, tahsile verme, tahsil etme, iade, detaylandırılacak)

**Cevap:** Öncelikle çek senet işlemlerinde bir çekin kaydının girilmesi gerekir. 
- Bu çek alındı kaydıdır. Alınan çek farklı bir firmaya ciro edilebilir borcumuzu kapatabilmek için. 
- Ayrıca çek/senet işlemlerinde adım adım ilerlemek gerekir. 
- Çekin banka hesabımıza geçmesi için öncelikle alınan çekin bankaya tahsile verilmesi gerekir tahsile verildikten sonra bankadan tahsil edilip hesabımıza geçer. 
	Mesela bir çek aldık direk bankadan tahsil et dersek karşımıza gelmez, çekin tahsile verilmesi gerekir.
- Çek/Senet Hareketleri Listesinden çek/senet hareketlerini görüntüleyebilirsiniz.

## Müşteri/Satıcı Soruları 

**Soru:** Carinin açık siparişlerinin sevkiyat listesini nasıl görüntüleyebilirim nasıl indirebilirim?

**Cevap:** Siparişlerin sevkiyatlarını görüntülemek için; 
Satış&Pazarlama -> Listeler -> Alınan Sipariş Hareketleri -> Cariyi seçelim -> Tarihi seçelim -> Listeyi Excele Aktar diyerek listeyi excele aktarımını gerçekleştirebiliriz.

Bir diğer yöntem ise;
Rapor -> Sipariş/Teklif -> Hareket -> Sipariş Sevkiyat Detayları -> Alınan Sipariş -> Cariyi seçelim -> Sadece Açık Siparişler seçeneğini seçelim -> Raporla şeklinde erişim sağlamaktır.

## Banka Soruları

**Soru:** Banka eksi girişi yapmıyor, nasıl girilebilir?

**Cevap:** Borcu Alacak yaparak sorunu çözebiliriz.

**Soru:** Bankadan nasıl virman yapabilirim?

**Cevap:** Banka Hesapları Arası Transfer yapmamız gerekiyor;
Banka -> Hareket Oluştur -> Banka Hesapları Arası Transfer -> Banka Alacak: Gönderici bankayı seçelim -> Tutarı girelim -> Şirket-Şube seçelim -> Banka Borç: Alıcı bankayı seçelim. 
Kaydet diyerek işlemimizi tamamlayabiliriz.
Banka hesapları arası transfer detayları için lütfen linke tıklayınız. [Banka Hesapları Arası Transfer](../TemelHareketler/BankaHesaplariArasiTransfer.md)
*Kaydet* şeklinde işlemimizi tamamlayabiliriz.

**Soru:** Kasadan veya Bankadan Gelir ve Gider hareketleri (Cari Kaydı Açmadan) nasıl işlenir?

**Cevap:** Kasadan ve bankadan gelir/gider hareketi seçeneği ile cari kaydı yapılmadan işlem yapılabilir.  
Örneğin; Bim marketinden alınan ürünü banka kartı ile ödeme yapılarak alındığını düşünelim bankadan gider hareketi seçilerek ilgili 
banka hesabı seçilip kayıt işleminden sonra gider kartı (Temizlik Giderleri, Mutfak Giderleri, Yemek Giderleri vb.) 
eklenip tutar girilir, açıklama kısmında detay belirtilir bu da raporlama da kolaylık sağlar.

**Soru:** Personel maaşlarını bankadan nasıl gösterebilirim?

**Cevap:** Bankalar içerisinde maaş ödeme hesabına para aktarıp personel maaş ödemesi çıkabilirsiniz.
    
	 Banka -> Hareket -> Yeni Banka Hesap Kartı -> 

	**Soru:** Personel maaşlarını bankadan nasıl gösterebilirim?
	
	?? **Cevap:** Bankalar içerisinde maaş ödeme hesabına para aktarıp personel maaş ödemesi çıkabilirsiniz.
	?? Banka -> Hareket -> Yeni Banka Hesap Kartı -> 
	
	**Soru:** Kredi kartını nasıl takip ediyoruz ödemelerini nasıl yapacağız?
	
	??? **Cevap:** Ödeme zamanı geldiğinde kredi carisine diğer bankadan transfer yapıyoruz.

**Soru:** Kredi kartını nasıl takip ediyoruz,ödemelerini nasıl yapacağız?

**Cevap:** Ödeme zamanı geldiğinde kredi carisine diğer bankadan transfer yapıyoruz.

**Soru:** Bankadan çekilen kredi nasıl takip edilir?

**Cevap:** Cari kartı açılır (banka hesap adı ve kredi sözleşme numarasıyla beraber).       

Müşteri/Satıcı -> Müşteri/Satıcı Kartı Listesi -> Yeni Müşteri/Satıcı Kartı Ekle -> Kredi kartı detaylarını girerek cari açabilirsiniz.
Bu cari kartının muhasebe hesap tanımları banka kredi hesaplarına atanır (muavin mizanda ilgili hesaplarda çıkması için). 

Açılan cari kartımıza kredi tutarımız kadar borç girilir.   Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Kaydettiğimiz kredi kartı carimizi seçelim -> Krediyi ne için aldığımızın detaylarını girebiliriz (Gelir gider demirbaş alımı, ihtiyaç giderleri vb.) -> Tutarı girelim.  
Her ay ödeme yapılarak güncel bakiye kontrol edilir. 

Bankadan ödeme yaptık diyelim; Banka -> Havale/EFT Gönderme -> Hangi bankadan ödeme yaptığımızı seçelim -> Kredi carimizi seçelim -> Cari Bankayı seçelim -> Ödeme yaptığımız tutarı girelim -> *Kaydet* diyerek işlemimizi tamamlayabiliriz.

Nakit(Kasa'dan) ödeme yaptık diyelim; Kasa -> Hareket Oluştur -> Nakit ödeme -> Ödeme yapılan kasamızı seçelim -> Kredi kartı carimizi seçelim -> *Kaydet* diyerek işlemimizi tamamlayalım.

Müşteri/Satıcı -> Müşteri/Satıcı Hareketleri Listesi -> Carimizi seçerek filtreleme yapalım buradan kalan borçumuzu yaptığımız ödemelerimizi takip edebiliriz.

**Soru:** Bankadan devir işlemini nasıl yapacağız ?

**Cevap:** Arama çubuğuna "devir" yazarak erişim sağlayabilirsiniz ya da Banka -> Hareket Oluştur -> Devir -> Gelir gider deposunu çalıştıracağız ->
Yeni Banka kalemi ekle -> Alacak-Borçlu seçelim -> Bankayı seçelim -> Tutar girelim -> Açıklama eklenebilir -> Kaydet diyerek işlemimizi tamamlayalım.
Yevmiye fişini açalım; üç işlem butonu -> Yevmiye Fiş kontrollerimizi sağlayalım -> Tutarlarımızı karşılatıralım kontrol ederek işlemimizi sonlandıralım.
Cevap: Banka -> Hareket Oluştur -> Devir -> Gelir gider deposunu çalıştıracağız -> Yeni Banka kalemi ekle -> Alacak-Borçlu seçelim -> Bankayı seçelim -> Tutar girelim -> Açıklama eklenebilir -> *Kaydet* diyerek işlemimizi tamamlayalım.

Yevmiye fişini açalım; üç işlem butonu -> Yevmiye Fiş kontrollerimizi sağlayalım -> Tutarlarımızı karşılaştıralım, kontrol ederek işlemimizi sonlandıralım.

## İhracat Soruları

**Soru:** Mikro ihracatta KDV nasıl sıfırlanır?

**Cevap:** Mikro ihracat, küçük ölçekli ihracat işlemlerini ifade eder ve genellikle e-ticaret yoluyla yapılan ihracatlar için kullanılır. 
Mikro ihracat, belirli bir parasal limitin altında kalan ve daha basit gümrük prosedürleri gerektiren ihracat işlemleridir. 
Türkiye'de mikro ihracat işlemleri, Elektronik Ticaret Gümrük Beyannamesi (ETGB) ile gerçekleştirilir ve gümrük müşavirine ihtiyaç duyulmadan hızlı bir şekilde yapılabilir.
KDV sıfırlama yapmıyoruz, muafiyet girmemiz gerekiyor. Vergi muafiyetlerini girmemiz gerekmektedir.
Vergi muafiyetini nasıl yapılır;
Faturamızı oluşturduktan sonra kalemlerimizin yanında ki büyüteçe tıklayalım -> Vergiler - Muafiyet Ekle -> KDV Muafiyet -> İhracat muafiyet kodunu seçelim.
Muafiyet tanımlamamız tamamlanmıştır, kontrol edelim.
e-Arşiv, e-Faturayı gönder diyelim, Fatura Tipi ISTISNA olması gerekmektedir.

	**Soru:** İhracat Faturasını nasıl kesebilirim ? Nelere dikkat etmemiz gerekmektedir?
	
	**Cevap:** İhracat faturalarında yasal gerekliliklere uymak önem arz etmektedir. 
	Yurtdışı satışlarında vergi uygulanmamaktadır vergi muafiyeti girilmesi gerekmektedir. Muafiyet ihracat faturalarında mutlaka eklenmelidir.
	İhracat işleminin hangi koşullarda yapıldığını gösteren teslim şartları (Incoterms) net bir şekilde belirtilmelidir.
	Ödeme yöntemleri ve şartları da fatura üzerinde yer almalıdır.
	Eğer fatura dövizle kesiliyorsa, döviz cinsi ve kur bilgileri de eklenmelidir.
	İhraç edilen malın detaylı ve doğru bir şekilde tanımlanması, cins, miktar, birim fiyat gibi bilgilerin açıkça belirtilmesi gerekir.
	Satıcı ve alıcının tam unvanı, adresi, vergi kimlik numarası gibi bilgileri eksiksiz bir şekilde yazılmalıdır.
	
	Aaro'da ihracat faturamızı oluşturalım;
	
	Satış&Pazarlama -> Hareket Oluştur -> Satış Faturası -> Carimizi seçelim -> Kaydet diyelim -> Kalemlerimizi ekleyelim -> Kalem detaylarına girelim;
	Üç işlem butonuna tıklayalım -> Tüm Kalemlerde Değiştir -> Vergi Muafiyeti / Vergileri Yenile iki seçeneği seçelim -> Kaydet diyelim.
	Fatura Tipi İstisna olmalıdır. e-Arşiv - e-Fatura Önizle yaparak kontrollerimizi sağladıktan sonra gönderme işlemimizi gerçekleştirebiliriz.
	İhracat faturalarında beyanname bilgileri de belirtilmelidir.
	
	İthalat-İhracat faturalarında e-Fatura mükellefi yazısı çıkmazsa faturada bir hata var demektir, faturanızı kontrol ediniz.
	e-Faturayı ithalat veya ihracat için gönderdiğimizde senaryo ve fatura tipi İstisna olarak seçili olmalıdır.
	İthalat ve ihracat faturalarında ödeme şekli/tipi seçmek zorunludur.


## İhraç Faturaları Soruları

**Soru:** GTIP kodu nedir, nasıl tanımlarım ? 

**Cevap:** GTIP (Gümrük Tarife İstatistik Pozisyonu) Kodu, Türkiye'de malların ithalat ve ihracat işlemlerinde kullanılan, 
ürünlerin gümrük tarife cetvelinde sınıflandırılmasını sağlayan bir koddur. 
Bu kod, bir ürünün ticaretine ilişkin vergi oranlarını, ithalat veya ihracat kısıtlamalarını ve diğer gümrük mevzuatlarını belirler.

Ürünün GTIP kodu belirlenirken, öncelikle ürünün ne olduğu, hangi malzeme ya da ham madde içerdiği ve nasıl bir işlevi olduğu doğru bir şekilde tanımlanmalıdır. 

Ürünün GTIP kodunu belirlemek için Gümrük ve Ticaret Bakanlığı'nın yayınladığı gümrük tarife cetvelleri kullanılabilir. Bu cetvellerde yer alan sınıflandırmalara göre ürünün kodu bulunur.

Bu kod sayesinde, ürünün gümrükte hangi tarife dilimine girdiği ve ne kadar vergi uygulanacağı belirlenir.

GTIP kodunun doğru bir şekilde belirlenmesi ve kullanılması, ticaretin sorunsuz yürümesi ve olası gümrük sorunlarının önlenmesi açısından oldukça önemlidir.

GTIP tanımlamasını yapalım;
Stok -> Stok Kartı Listesi -> Yeni Stok Kartı Ekle -> Gerekli alanları dolduralım -> 
Gelişmiş kısmında GTIP alana stok kartına ait GTIP kodumuzu girmemiz gerekmektedir -> *Kaydet* diyerek GTIP kodu tanımlı stok kartımızı tanımlayalım.

**Soru:** İhraç kayıtlı fatura kesiyorum fakat KDV sıfırladığım halde ihraç kayıtlı fatura olmuyor ne yapmalıyım ?

**Cevap:** İhraç kayıtlı fatura keserken KDV oranının sıfır olmasının nedeni vergi muafiyet durumunun olmasıdır.
Bu durumda KDV oranımızı eski haline getirerek yani; kalem stoğu için ihraç kayıtlı fatura oluşturacağız KDV oranı:%20 bunu yazalım.
Stok kartında vergi KDV sıfırlayarak değil vergi muafiyetini belirteceğiz.
Daha sonrasında; üç işlem butonu -> Tüm kalemlerde değiştir -> Vergi Muafiyeti seçeneğimizi aktif ederek - 11/1-a Mal İhracatı (301) ->
Vergileri Yenile seçeneğini de aktif edelim -> Kaydet diyelim -> Gerekli bilgiler tamamlandıktan sonra faturanın kontrollerini sağlayalım.
Fatura kalemlerinin tutarını, toplam tutarını kontrol edelim, fatura tipi: İhraç Kayıtlı olmadına dikkat edelim, kontrollerimizi sağladıktan sonra faturamızı gönderebiliriz. 

**Soru:** İhraç kayıtlı e-arşiv fatura nasıl kesilir?

**Cevap:** Normal satış faturası kaydı girilir burada dikkat edilmesi gereken hususlar; stok kartında GTIP kodu belirtilmelidir, 
KDV istisnası KDV de belirtilmelidir.(KDV girilerek sıfırlanmamalıdır)
Fatura tamamlandıktan sonra e-Arşiv fatura gönder seçeneğinden sonra karşımıza çıkan ekranda ihraç kayıtlı seçeneği seçmemiz gerekmektedir.

## Fatura Soruları 

**Soru:** Birden fazla irsaliye tek faturada nasıl birleştirilir?

**Cevap:** Birleştireceğimiz irsaliyelerden birini açalım, üç işlem sekmesinden Faturalaştır diyelim, bilgileri kontrol ettikten sonra kaydet diyelim.
Sağ üstte İrsaliyeden Kalem Ekle seçeneğine tıklayalım, irsaliyelerimizi seçelim kaydet butonu basarak irsaleyimizi fatura dönüştürebiliriz.
Bir diğer yöntem ise satış faturası açalım, yeni stok kalemi ekle kısmındaki oka tıklayalım irsaliyeden kalem ekle diyerek irsaliyelerimizi seçebiliriz.

**Soru:** Faturada kalemlerin KDV'sini nasıl değiştirebilirim?

**Cevap:** Kalemin yanında ki büyüteçe tıklayalım -> Vergiler -> KDV Oranını girelim -> *Kaydet* -> 
Üç işlem butonundan Tüm Kalemlerde Değiştir seçelim -> Vergileri Yenile -> *Kaydet* diyerek KDV Oranı değişikliği gerçekleştirebiliriz.

**Soru:** E-fatura Entegratörü üzerinden kesilen fatura programda nasıl eşleştirilir?

**Cevap:** Foribadan kesilen faturanın eşleştirilmesi için Aaro'dan da aynı şekilde satış faturası hareketi oluşturulur ancak gönderilmez.Kaydedildikten sonra tekrardan düzenlenir ve 
üst kısımda yer alan e-fatura/e-arşiv bilgileri kısmından UUID kısmına faturadaki ETTN numarası, Ref Belge no kısmına fatura numarası yazılır. 
Kesilen faturanın tipine göre efaturaTipID, efaturaProfilID,efaturaDurumID seçeneklerinden uygun olanları seçilerek eşleştirme kayıt işlemi ile tamamlanır.

**Soru:** e-Fatura geçiş işlemleri nasıl yapılır?

**Cevap:** İlk olarak firmanın mali mühür alması gerekir.   
Mali mühür yoksa tÜBİTAK kamusm sayfasından alabilir(Link:https://mportal.kamusm.gov.tr/).
Mali mührü aldıktan sonra entegratör firmanın evrakları iletilir. 

Ayrıca sözleşmenin dışında firma bilgi formunda istenilen bilgiler doldurulacak ve bu formda istenilen evraklar temin edilecek. (İmza sirküsü, vergi levhası, oda kayıt belgesi, yetkili kimlik fotokopisi)
Entegratör firma ya evraklar,sözleşme ve istenilen kontör miktarı ile birlikte iletilir.(e-fatura/e-arşiv/e-irsaliye geçişleri bilgisi verilir)

**Soru:** Muafiyetli fatura nasıl kesilir ? Faturalara nasıl muafiyet eklenir ?

**Cevap:** Satış Faturası hareketi normal olarak girilir.  
Bu harekette girilen her kart açılarak (Satış faturası alanında her kalemin yanında bulunan büyüteçten erişim sağlayabilirsiniz) 
KDV'nin altında yer alan muafiyet ekleme seçeneği ile açılan bölümden ilgili muafiyet nedeni seçilir ve kaydedilir. 
Eğer birden fazla kart ekli ise her kart için aynı şekilde muafiyet eklenir. 
Eğer tüm kalemlerin muafiyetleri aynıysa, örneğin hepsi 17/1 Kültür ve Eğitim Amacı Taşıyan İşlemler (201) kapsamındaysa, bu muafiyetten muafiyet eklenecek ise;
Üç işlem butonu -> Tüm Kalemde Değiştir -> Vergi Muafiyeti seçelim: 17/1 Kültür ve Eğitim Amacı Taşıyan İşlemler  (201) muafiyet kodumuzu seçelim -> Vergileri Yenile seçelim -> 
Kaydet diyerek tüm kalemlere aynı muafiyet kodunu tanımlama işlemimizi tamamlayabiliriz.

**Soru:** Bir faturayı iptal ettik Aaro'dan ve foriba'dan tekrar fatura kesmek istediğimizde foribada numara gözüktüğü için tekrar kesemiyoruz ne yapmamız lazım ?

**Cevap:** Fatura iptali foribadan yapılıp Aaro'dan silindiği taktirde Aaro işlemi tanıyamaz, Aaro'dan silindiğinde sistem bunu bilirdi ve o kodu tekrar verirdi.
Şimdi aynı kodu manuel değişiklik yaparak kullanmamız gerekmektedir. 

**Soru:** Tevkifatlı fatura nasıl kesilir?

**Cevap:** Fatura hareketi sistemimizde olduğu gibi oluşturulur.  Harekete eklenen kartlar için o kartların içeriğine gidilerek vergi oranı kısmında tevkifatlı vergi oranı açılır.
(Stok kaleminin yanında ki kalem işaretine tıklayalım -> Vergiler -> Muafiyet Ekle -> KDV Muafiyet muafiyeti seçiniz.)  
Açılan vergi tanımında tevkifat tipi belirtilerek kaydedilir. Hareketin içeğindeki kart görüntülenerek tevkifat oranı değiştirilebilir.

**Soru:** Muhtelif cari özelliği nedir?

**Cevap:** Muhtelif cari özelliğimiz ile tek bir cari altında birden fazla carimizi takip edebiliriz. 

Mesela; N11 sitesinde firmamızın ürünlerini satıyoruz herhangi bir kişi ürünümüzü satın aldı ve bu döngü sürekli halde devam ediyor. 
Bir ürünü birden fazla kişi bir kereliğine alabilir ve biz bu kişileri müşterimiz olarak açmak istemeyiz. 
Çünkü; ödemelerini biz asıl anlaşmalı firmamız olan N11'den almaktayız. 
O yüzden N11 firmasını  muhtelif cari olarak açabiliriz. Cari kartı içeriğinde yer alan muhtelif cari özelliğimizi aktif ederek.
(Müşteri/Satıcı kartının içine girelim Muhtelif Cari özelliğini aktif edelim.) 

**Soru:** Benim bir müşterim var tek seferlik alışveriş yaptı cari açmak istemiyorum cari açmadan nasıl fatura kesebilirim ?

**Cevap:** Muhtelif cari özelliğimizi kullanarak tek seferlik müşterilerimizin fatura işlemlerinde kullanabiliriz.
Muhtelif cari açalım öncellikle; Müşteri&Satıcı -> Müşteri&Satıcı Kartı Listesi -> Yeni Müşteri/Satıcı Kartı Ekle -> 
örneğin adına Muhtelif Cari diyerek genel ortak bir ad ile açabiliriz -> Gelişmiş -> Muhtelif Cari seçeneğimizi aktif etmemiz gerekmektedir.

Satış faturamızı oluşturalım; Müşteri&Satıcı -> Hareket Oluştur -> Satış Faturası -> Cari olarak açtığımız Muhtelif Cariyi seçelim -> 
Carimizi seçtikten sonra muhtelif carimizin bilgilerini dolduracağımız alan gelecektir bilgileri dolduralım -> satış yaptığımız stok, gelir gider ya da demirbaşı girelim ->
*Kaydet* diyerek e-Fatura/e-Arşiv faturamızın ön izlemesini yaparak kontrollerimizi sağlayalım.

**Soru:** e-Arşiv faturamı iptal etmek istiyorum nasıl yapabilirim ?

**Cevap:** e-Arşiv faturalarında kesildikten 7 gün içerisinde iptal işleminin yapılması gerekmektedir.
İptal etmek istediğiniz faturanın düzenlenmiş ve karşı tarafa iletilmiş olması gerekir. 
İptal işlemi için belirli bir süre sınırı bulunmaktadır 7 gün içerisinde yapılması gerekmektedir.

**Soru:** Demirbaş kiralık araç tanımlama işlemini nasıl yapabilirim ?

**Cevap:** Gelir gider -> Alış Faturası -> Cariyi seçelim -> Gelir gider -> kalemimizi dolduralım kart adını, miktar ve fiyatını girelim -> 
Depo olarak GelirGider Depo (GG) seçelim -> Demirbaşımızı seçelim. 
Kaydettikten sonra yevmiye fişimizi açalım gelir giderimize göre yevmiye fişlerimizi güncelleyelim.

**Soru:** Fatura adresimizi değiştirmemiz gerekiyor Aaro'da nasıl değiştireceğiz ?

**Cevap:** Ayarlar -> Şirket Listesi -> Adres bilgilerinden değişiklik yapabilirsiniz.

**Soru:** Makine tamirini nasıl gösterebilirim. Stok açmamız gerekli mi ?

**Cevap:** Makine tamirinizin faturası kesilecek mi, banka, kasa çıkışımı yapılacak ya da cari gösterilecek mi bu gibi detaylar önemlidir.
Fatura kesilen tamirimizi;
Gelir gider -> Hareket Oluştur -> Alış Faturası -> Carimizi seçelim -> Kaydet -> Kalemimizi dolduralım Gelir gider seçelim -> 
Kart Adı örn; Makine Tamiri -> Fiyat bilgisini girelim -> Demirbaş seçelim -> Doldurulması gereken bilgileri doldurduktan sonra işlemimizi tamamlayabiliriz.

**Soru:** Siparişimi irsaliyeleştirmeden nasıl fatura oluşturabilirim ?

**Cevap:** Siparişini oluşturmuş olduğumuz bir siparişi irsaliyesini kesmeden direk faturalaştırmak istiyorsak; 
Alınan Siparişlerden siparişimizi açalım -> Faturalalaştır diyerek siparişimizi faturalandırabiliriz.

**Sipariş ya da teklifi olmayan bir siparişimiz için fatura oluşturmak istiyorsak;**
Satış&Pazarlama -> Hareket Oluştur -> Satış Faturası -> Carimizi seçelim -> Kaydet diyelim -> Kalemlerimi dolduralım -> Kaydet diyerek faturalandırma işlemimizi gerçekleştirebiliriz.


**Soru:** Serbest Meslek Makbuzu (SMM) makbuzları, avukat makbuzları nasıl işlenir ?

**Cevap:** Vergi tanımı yapmamız gerekmektedir. Gelir gider olarak tanımlayacağımız için gelir gider kartı açmamız gerekmektedir;
Gelir Gider Modülü -> Yeni Gelir Gider Kartı Ekle -> Gelir gider adı girelim Örn; Avukat Gideri -> 
Vergi Oranları; bu kısımda yeni bir vergi oranı tanımlayacağız Örn; KDVSTOPAJ20 detaylı ekle diyelim;
Stok Vergi Kodu KDVSTOPAJ20 aynısını yazabiliriz -> Stok Vergi Adı Stopaj diyebiliriz -> 
Alış KDV Oranı KDV oranını girelim -> Satış KDV Oranı KDV oranını girelim ->
Alış Vergi 1 Gelir Vergisi Stopajı 0003 (Gelir Vergisi Stopajı) seçebiliriz -> Alış Vergi Oranı 1 vergi oranını girelim -> 
Satış Vergi 1 Gelir Vergisi Stopajı 0003 (Gelir Vergisi Stopajı) seçebiliriz -> Satış Vergi Oranı 1 vergi oranını girelim -> Kaydet diyerek stopajımızı tanımlayabiliriz.
Gelir/Gider Kartı (Yeni) ekranımızdan Vergi oranları kısmını tanımladığımız stopajı seçelim. Tanımlayacağımız bilgileri doldurduktan sonra kaydedebiliriz.

Avukat gideri kartımızı açtık, alış faturamızı girebiliriz;
Müşteri&Satıcı -> Hareket Oluştur -> Alış Faturası -> Avukata açtığımız cariyi seçelim -> *Kaydet* -> Kalemimizi dolduralım;
GelirGider seçelim -> Avukat gideri olarak açtığımız kartı seçelim -> Miktar 1 seçelim -> 
Tutarı girelim -> Depomuzu GelirGider Depomuzu seçelim -> Ekleyeceğimiz detaylar ekleyip tutarı kontrol edip *Kaydet* diyelim.

**Soru:** Tek bir hareket için KDV oranı nasıl değiştirilir?

**Cevap:** Herhangi bir kartımızın sadece bir hareket için vergi oranını ilgili harekette kartımızı ekledikten sonra görüntüleyerek
KDV bölümünde yer alan rakamı ihtiyacımız olan vergi oranını yazıp kaydederek vergi oranını sadece bu hareket için değiştirmiş oluruz.
Kalemin yanında ki büyüteçe tıklayalım -> Vergiler -> KDV oranını girelim -> Kaydet şeklinde KDV oranını değişikliği gerçekleşir.

**Soru:** KDV'den muaf fatura neden ve hangi durumlarda kesilir?

**Cevap:** KDV'den muaf fatura, genellikle belirli şartlar altında veya belirli türdeki işlemler için kesilen bir faturadır.   

İşte KDV'den muaf fatura kesilme nedenleri ve durumları:  
Özel Kanunlar: Bazı özel sektörler veya faaliyetler KDV'den muaf olabilir.   
Örneğin, sağlık, eğitim ve sosyal hizmetler gibi belirli sektörlerdeki işlemler KDV'den muaf olabilir.  
Yurt Dışına Yapılan Satışlar da KDV uygulanmaz. Türkiye'den yurt dışına yapılan mal ve hizmet satışları KDV'den muaf tutulur. İhracatçı firmalar, KDV'yi müşteriden tahsil etmezler.  
Yatırım Teşvikleri: Bazı yatırım teşvikleri ve devlet destekleri kapsamında KDV muafiyeti sağlanabilir.  
Özel Sektör Destekleri: Kamu sektörüne yapılan belirli hizmetler veya mal alımları da KDV'den muaf olabilir.   
Diplomatik ve Konsolosluk Satışları: Diplomatik misyonlar ve konsolosluklar için yapılan satışlar KDV'den muaf olabilir.

**KDV'den muaf fatura kesilmesi gerektiğinde, ilgili mevzuat ve düzenlemelere dikkat edilmelidir.** 

**Muafiyet durumunu ve uygulama şekillerini netleştirmek için mali müşavir veya vergi uzmanına danışmak en doğrusu olacaktır.**

**Soru:** Fatura tipleri ve bu tiplerin özellikleri nelerdir ? Hangi tipteki faturalar iptal edilebilir? Hangi tip faturalarda iade faturası kesmek gerekir? 

**Cevap:** e-Faturalar Temel ve ticari fatura olarak iki tip e-Fatura türü vardır.  
Ticari faturaların onaylanma süresi 7 gündür, 7 gün içerisinde onaylanmaz ya da reddedilmezse otomatik onaylanır.   
Ticari faturalarda 7 gün içerisinde onay ya da ret yapılabilir.  
Temel faturalar kesildiğinde fatura kesilmiş olur, onay ya da ret seçeneği yoktur; 7 gün sonrasında iade faturası kesilebilir. 7 gün içerisinde faturayı oluşturan taraf iptal edilebilir.  

Bize fatura kesecek işletme;
e-fatura bizde e-fatura isek bize e-fatura olarak keser ve sistemimize düşer. Bu faturayı onaylamamız ya da reddetmemiz gerekmektedir.  
Karşı taraf e-Arşiv biz e-Fatura isek bize e-Arşiv olarak keser.  
Karşı taraf e-Fatura biz e-Arşiv isek bize e-Arşiv olarak keser.

e-Arşiv faturaları bizim sistemimize düşmez, e-Arşiv kesen firma faturayı iletmek durumundadır.   
Fatura bize ulaştığında bilgilerimizi kontrol ederek alış faturamızı girmemiz gerekmektedir.   
Adımıza düzenlenen e-Arşiv faturaları gelir vergi dairesi başkanlığı GIB üzerinden bilgilerimizle giriş yaparak adımıza düzenlenen faturaları seçerek teyit edebiliriz.  
E-Arşiv Portalı giriş -> İnteraktif Vergi Dairesi -> Adıma düzenlenen belgeler -> Tarih seçerek adımıza düzenlenen faturaları görebiliriz.
	(Görüntüleme tarihleri max 7 gün aralığında seçilebilir, haftalık bakılabilir.)

**Soru:** İade faturası nasıl kesilir?

**Cevap:** Satış iade faturası kesmek için;
	Satış&Pazarlama -> Satış İade Faturası -> Cari Seçelim -> Kalem ekleyelim - Ürünlerin gönderilmesi için satış iade irsaliyesi oluşturmuş isek irsaliyeden kalem ekle diyerek irsaliyemizi seçerek irsaliye kalemlerimizin faturamıza aktarabiliriz.

Bir diğer alternatif yol ise; 
		Satış&Pazarlama -> Satış İade İrsaliyesi Listesi -> İrsaliyemizi seçelim -> Üç işlem butonundan Faturalaştır diyerek Satış İade Faturamızı oluşturabiliriz. 
		Ürünlerin İade nedenlerini açıklama kısmında belirtilmelidir.

İrsaliyemiz yok ise kalem ekleyebiliriz, bu kalem stok, gelir gider ya da demirbaş olabilir.
	*Kaydet* diyerek faturamızı kaydedebiliriz, e-Fatura/e-Arşiv Fatura Gönder diyelim -> Fatura Tipini **İade** olarak seçmemiz gerekmektedir.
	e-Faturamızın önizlemesini yaparak tekrardan kontrollerimizi sağlayarak e-Fatura/e-Arşiv gönderme işlemimizi tamamlayabiliriz.

NOT: Kalem açıklamalarına iade nedenlerini belirtiğimiz faturalarda Kalem Açıklamalarını Gönder seçeneğini seçerek iade nedeninin görünmesini sağlayabiliriz.

Satın alma iade faturası kesmek için;
	Satın Alma -> Alış İade Faturası -> Cari Seçelim -> Kalem Ekleyelim - Ürünleri göndermek için alış iade irsaliyesi oluşturmuş isek irsaliyeden kalem ekle diyerek irsaliyemizi seçerek irsaliye kalemlerimizin faturamıza aktarabiliriz. 

Bir diğer alternatif yol ise; 
		Satın Alma -> Alış İade İrsaliyesi Listesi -> İrsaliyemizi seçelim -> Üç işlem butonundan Faturalaştır diyerek Alış İade Faturamızı oluşturabiliriz. 
		Ürünlerin İade nedenlerini açıklama kısmında belirtilmelidir.

İrsaliyemiz yok ise kalem ekleyebiliriz, bu kalem stok, gelir gider ya da demirbaş olabilir.
	*Kaydet* diyerek faturamızı kaydedebiliriz, e-Fatura/e-Arşiv Fatura Gönder diyelim -> Fatura Tipini **İade** olarak seçmemiz gerekmektedir.  
	e-Faturamızın önizlemesini yaparak tekrardan kontrollerimizi sağlayarak e-Fatura/e-Arşiv gönderme işlemimizi tamamlayabiliriz.
	NOT: Kalem açıklamalarına iade nedenlerini belirtiğimiz faturalarda Kalem Açıklamalarını Gönder seçeneğini seçerek iade nedeninin görünmesini sağlayabiliriz.
		
**Soru:** Kesilen faturada stok kodu nasıl görüntülenir ? 

**Cevap:** Aaro'da kesilen faturamızı açalım stok kalemimizin yanında ki büyütece tıklayalım burada stok kodumuzu görüntüleyebilir, linke tıklayarak stok kartımıza erişebiliriz.

**Soru:** Karşı taraf fatura kesemiyor e-posta da hata veriyor ne yapmamız gerekiyor ?

**Cevap:** Karşı taraf sovosla görüşmeli sovos'a geçtiklerinin tanımını yapmaları gerekiyor.

**Soru:** Alış-satış faturalarımı son 3 aylık şekilde görüntüleyerek vergi detaylı raporlamak istiyorum, nereden bakabilirim ? 

**Cevap:** Rapor kısmında arama butonuna fatura yazarak ya da Rapor -> Fatura/İrsaliye -> Hareket şeklinde; üç farklı vergi detaylı rapora ulaşım sağlayabiliriz.

Fatura-İrsaliye Listesi Vergi Detaylı; Bu rapordan faturaların vergi numaralarını, KDV Matrah, KDV tutarları, tevkifat ve oranları, tutar detayları görüntülenir.  

Fatura-İrsaliye Listesi Vergi Detaylı Pivot; Bu pivot tablosunun veya analizinin vergi ile ilgili bilgileri detaylı bir şekilde içermesi anlamına gelir.
 	 	 	
Fatura-İrsaliye Satırları Listesi Vergi Detaylı; Bu raporda fatura ve irsaliyelerin satır bazlı vergi detayları görüntülenmektedir.

Raporlarda istediğimiz özelliklere göre filtreleme yapabiliriz. 
Hareket türüne, giriş veya çıkışa, belirli tarih aralıklarına ve tutarlara göre filtreler uygulayarak istediğimiz detaylara kolayca ulaşabiliriz.

**Soru:** Kur farkı faturası karşı taraftan kesildi. Bu kur farkı faturasını nasıl işleyeceğiz ?

**Cevap:** Kur farkı faturaları, genellikle Türkiye'de döviz ile yapılan alışverişlerde ödeme zaman dilimindeki farklılıklardan kaynaklanır. 
Bu durum sonucunda karşılıklı olarak kur farkı faturası kesilmektedir. 
Karşı taraf bize fatura kestiğinde;
Satın Alma -> Alış Faturası -> Fatura tarihini girelim -> Carimizi seçelim -> Döviz türünü seçelim -> Kaydet ->
Fatura ekranım açıldıktan sonra tekrar kaydet diyelim -> Üç İşlem Butonunu seçelim -> Kur Farkı Faturası olarak işlensin -> Düzenleme -> Kaleme gelelim ->
GelirGider -> Kart Adı: Kur Farkı Gideri -> Tutar: Kur Farkı Faturasının tutarını girelim (Bu kısımda döviz ve türk lirası alanı mevcut ₺ karşılığına tutar giriniz) -> Kaydet
diyerek kur farkı faturası kesme işlemimizi tamamlayalım.
Kur farkı faturaları genellikle türk lirası bazında yapılmaktadır.

**Soru:** Karşı taraf fatura kesemiyor, e-postada hata veriyor ne yapmamız gerekiyor ?

**Cevap:** Karşı taraf Sovos'la görüşmelidir. Sovos'a geçtiklerinin tanımını yapmaları gerekmektedir.

## Diğer

**Soru:** Geçiçi Anahtar Nasıl Oluşturulur ?

**Cevap:** Ayarlar -> Modül Sayfası -> Destek -> Geçici Erişim Anahtarı
Geçici erişim anahtarınızdan 12 saat erişim izni verilmektedir.
Erişim anahtarı sayesinde yapılması gereken işlemler için sizin adınıza destek verebilmemiz için kullanım sağlanmaktadır.

## Yetki Soruları

**Soru:** Herhangi bir çıktı tasarımında rapor yetkisi nasıl açılır?

**Cevap:** Bu işlemi herhangi bir çıktı tasarımından gerçekleştirebiliriz,
Çıktımıza gelelim; Ayarlar -> Çıktı Listesi -> çıktımızın kategorisinden tasarımızı açalım, açılan ekranda rapor yetkileri kısmında Yeni Rapor Yetkileri Ekle,
kullanıcıyı ya da kullanıcı grubu seçelim okuma yetkisini açalım.

**Soru:** Belirli bir tarihten önce yapılan bir işlemde değişiklik yapma yetkiniz yoktur uyarısı nasıl çözülür? 

**Cevap:** Ayarlar -> Modül sayfası -> Kullanıcı listesi bölümünden ilgili kullanıcı açılarak Cari ve Muhasebe alanında Bugünden Önce(gün), 
bugünden sonra(gün) bölümlerinde karşılarındaki rakam değerleri değiştirilerek kaydet seçeneği ile işlem tamamlanır. 
(sistemi yenile veya çıkış yapıp giriş yaparak tekrar dene)

**Soru:** Kdv den muaf fatura kesmek istiyorum yetkisiz işlem diyor, yetki nasıl açılır?

**Cevap:** Ayarlar -> Modül sayfası -> Yetki alt listesi bölümünden Yeni Yetki Alt Ekle diyerek çıkan ekranda AltProgramID kısmına "Genel – DekontFatura_KDVdenMuafYapabilir" 
yetkisi seçilerek okuma,ekleme,silme, düzenleme aktif edilerek kaydedilir.

**Soru:** KDV oranı değiştirme yetkisi nasıl açılır?

**Cevap:** Ayarlar modül sayfası yetki alt listesi bölümünden Yeni Yetk Alt Ekle diyerek çıkan ekranda AltProgramID kısmına "DekontFatura_KDVOranDegistirebilir " 
yetkisi seçilerek okuma,ekleme,silme, düzenleme aktif edilerek kaydedilir.

**Soru:** Cari kartı açarken vergi numarasını 11111111111 girmek istiyorum sistem izin vermiyor nasıl düzeltebiliriz ?

**Cevap:** Mükerrer cari yetkilerini açmamız gerekmektedir. Mükerrer kendini tekrarlayan TC, vergi numarasını anlamına gelmektedir.
Ayarlar -> Yetki Alt Listesi -> Yeni Yetki Alt Ekle -> Kullanıcıyı seçelim -> Genel - Cari_MukerrerVergiNoKaydedebilir -> 
Okuma - Ekleme - Silme - Düzeltme seçeneklerinden kullanıcı için uygun olan seçenekleri seçelim. -> *Kaydet* diyelim yetkimiz aktif oldu.
Aaro'dan çıkış yapıp tekrar giriş yapalım. 

**Soru:** Kullanıcı kayıt yapma tarih aralığı yetkilendirmesi nasıl yapılır ?

**Cevap:** Ayarlar -> Modül sayfası -> Kullanıcı listesi bölümünden ilgili kullanıcı açılarak Cari ve Muhasebe alanında Bugünden Önce(gün), 
bugünden sonra(gün) bölümlerinde karşılarındaki rakam değerleri değiştirilerek kaydet seçeneği ile işlem tamamlanır. 
(sistemi yenile veya çıkış yapıp giriş yaparak tekrar dene)

## Personel Soruları

**Soru:** Personel çıkışını nasıl yapacağım?

**Cevap:** Personelin mesaileri var ise öncelik olarak personelin çıkış işlemini yapmalıyız.  
Personel -> Personel Kartı Listesi -> Personeli seçelim -> Kısayollar -> Giriş Çıkış kayıtları -> Yeni Personel Giriş/Çıkış Kaydı Ekle -> Çıkış Tarihini girelim ->
Çıkış Nedeni SSK - Çıkış Nedeni - Açıklama bilgilerini dolduralım, *Kaydet* diyelim.

## Karma Transfer Hareketi

**Soru:** Karma transfer hareketi mantığı nedir?

**Cevap :** Mesela bir firma eksik ödeme yaptı 0,60 TL gibi bakiyesi açık görünüyor firmadan tekrar ödeme istemek yerine karma transfer hareketi ile bakiye kapanabilir.
Karma Transfer Hareketini açalım Ahmet isimli cari firmamıza borçlu carimizi alacak olarak (GelirGider, Stok vb.) 
seçip ilgili diğer hesabı ise borç olarak seçiyoruz ve karma transfer hareketi tamamlanmış oluyor.

## Devir

**Soru:** Belli bir tarihten önceki işlemlerin devir olarak görünüyor, firmaların geçmiş hareketlerini nasıl görüntüleyebiliriz ?

**Cevap:** Sistemde otomatik  olarak hareketler listesinde belirli bir tarihten öncesini devir olarak toplam tutarını getirir.   
Firmalarımız bu olayda hareketlerini göremiyor. Hareketlerin detayını görebilmesi için filtreleme bölümünde yer alan başlangıç tarihi kısıtını 
istedikleri bir tarihi girerek hareketlere ulaşabilirler.

## Rapor Soruları  

**Soru:** Sipariş ve iş emirleri üzerinden malzeme ihtiyaç ve stok durum raporu(MRP) nasıl alınır?

**Cevap:** Rapor -> Stok -> Toplam -> MalzemeMevcudu (DepoMinMaxMiktar Kontrolü) -> İlgili sipariş ve ya iş emri seçerek raporlayabiliriz.

**Soru:** Cari bakiye raporunu nasıl alabilirim ?

**Cevap:** Rapor -> Müşteri/Satıcı -> Bakiye -> Müşteri-Satıcı Bakiye buradan erişim sağlayabiliriz detaylı bakiye raporları için cari bazlı min, max tutarlar için seçenekleri seçerek erişim sağlayabiliriz.

**Soru:** Stok satış raporunu nasıl alabilirim ?

**Cevap:** Stok adına göre detaylı rapor almak istiyorsak;
Rapor -> Stok -> Toplam -> Stok Hareketleri Miktar Toplamları (StokAdına göre Gruplu) -> Tarih, depo, tutar filtrelemeleri ile rapor alabiliriz. 

**Soru:** Üretim operasyona göre planlama raporunu nasıl alabilirim ?

**Cevap:** Rapor -> Üretim -> Planlama -> Operasyon Bazında Planlama (Makine,Mamül) şeklinde raporlarına erişim sağlayabiliriz. 

**Soru:** Depoya göre malzeme mevcudu raporlarını nasıl alabilirim ?

**Cevap:** Rapor -> Stok -> Toplam -> Malzeme Mevcudu -> Depo kısmında rapor almak istediğimiz depoyu seçelim -> Raporla diyerek, raporumuza ulaşım sağlayabiliriz.

**Soru:** Bir cari ile ekstre karşılaştırmak istiyorum, ekstresine nasıl ulaşabilirim ?

**Cevap:** Rapor -> Müşteri/Satıcı -> Müşteri-Satıcı Ekstre -> Tarih Aralığı seçelim -> Carimizi seçelim -> Raporla diyerek, raporumuza ulaşım sağlayabiliriz.
Bir diğer yöntem ise;
Müşteri/Satıcı -> Müşteri/Satıcı Kartlar Listesi -> Carimizi açalım -> Kısayollar -> Ekstre Dökümü şeklinde ulaşım sağlayabiliriz. 

**Soru:** Banka hesap kartımın ekstresini detaylı olarak almak istiyorum nasıl alabilirim ?

**Cevap:** Rapor -> Banka -> Hareket -> Banka Ekstre Detaylı -> Tarih aralığı seçebiliriz -> BankaHesabını seçelim -> Raporla diyerek, raporumuza ulaşım sağlayabiliriz.

**Soru:** Kasa hareketlerimi detaylı görmek istiyorum nasıl bakabilirim ?

**Cevap:** Rapor -> Kasa -> Hareket -> Kasa Detaylı Ekstre -> Tarih Aralığımızı seçelim -> Kasamızı seçelim -> Raporla diyerek raporumuza ulaşım sağlayabiliriz.

**Soru:** Stok depo miktar listesi detaylı görmek ve excele aktarmak istiyorum nereden alabilirim ?

**Cevap:** Rapor -> Stok -> Toplam -> Malzeme Mevcudu (StokAdı, DepoDetaylı,Fiyatlı) şeklinde ulaşabilir ve excele aktarabilirsiniz. 

## POS Tahsilat Soruları 

**Soru:** PayTR, iyzico, MokaPos vs. gibi aracı bir entegratör firmayla çalışıyoruz. Yapılan tahsilatları ve faturaları sisteme nasıl işlemeliyiz? 
Komisyon faturalarını, ve kalan fatura tutarını nasıl takip ederiz?  Kalan alacağımızı nasıl takip ederiz?

**Cevap:** İki yöntem ile takip edebiliriz;

**1. Yöntem:** Aracı firma ile olan borç alacak takibini basit bir şekilde takip etmek için kullanılabilir.

Aracı Sanal Pos hesabı tek hesap üzerinden takip edilir. Gelen faturaları, EFT/Havale ödemelerini tek caride tutarız.  
Örneğin, bize müşterimiz sanal pos aracılığıyla 200 tl ödeme gerçekleştirdi, entegratör firma bu işlem için bize 5 tl komisyon kesti ve faturalandırdı.
Kalan 195 tl'yi EFT/Havale olarak banka hesabımıza gönderdi.

1. İlk olarak Aracı Sanal Pos hesabımıza cari açalım. Örneğin adı "Pos Entegratör" olsun.
	Müşteri/Satıcı -> Modül Sayfası -> Hareket -> Yeni Müşteri/Satıcı Kartı Ekle buradan gerekli bilgileri doldurarak cari açma işlemimizi yapalım.

2. Bize sanal pos aracılığı ile ödeme yapan carimizin ödemesini Müsteri / Satıcı hesapları arası transfer ile girelim.;
	Müşteri/Satıcı -> Hareket Oluştur -> Müsteri / Satıcı hesapları arası transfer -> 
		1. Alacaklı seçelim -> Bize ödeme yapan carimizi seçelim -> Tutarı örneğin 200 tl girelim.
		2. Borçlu seçelim -> Bu karıtını açtığımız entegratör firması olacak. Örneğin "Pos Entegratör". 
		Bu şekilde pos çeken müşterimiz bizden 200 ₺ alacaklandı ve entegratör firma 200 ₺ borçlandı.
		
3. Entegratör firmasi bize Komisyon faturası kestiğinde Alış faturası olarak girelim;
	Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Carimizi açtığımız entegratör carisi seçelim -> GelirGider seçelim -> Pos Komisyon olarak tanımlayabiliriz -> Miktar 1 -> Tutar 5 ₺ -> *Kaydet* diyerek tamamlayalım.
	Bu şekilde entegratör firmanın bize olan borcu 5 ₺ azalarak 195 ₺ oldu.

4. Entegratör firmadan bize ödeme geldiğinde, EFT/Havale alma girişini yapalım;
	Banka -> Hareket Oluştur -> Havale/EFT Alma -> Hangi bankamıza geldiğini seçelim -> Cari -> Açtığımız entegratör carisini seçelim -> Tutar 195 ₺ -> *Kaydet* diyerek işlemi tamamlayalım.
	Bu şekilde entegratör firmanın bize bir borcu kalmamış oldu. 
	Hesabımızda 195 ₺ oldu.
	5 ₺ komisyon giderimiz oldu.
	POS Ödeme yapan müşterimizin 200 ₺ alacağı oldu.

Bu şekilde carimiz ile beklenen ödeme, yapılan ödeme toplam tutarlarını kalem kalem takip edebiliriz.  
Fakat bu yöntemde kesilecek faturaların takibini yapamayız. Faturaların ve havale eft alacağımızın ayrı ayrı takibini yapabilmek için ikinci yöntemi tercih edebilirsiniz.

**2. Yöntem:** Aracı firma ile olan borç alacak takibini komisyon faturaları ve havale eft alacağı şeklinde detaylı takip edilmek isteniyorsa kullanılabilir. 

Aracı Sanal Pos hesabı iki hesap üzerinden takip edilir. Gelen faturaları bir cari hesapta tutulur. EFT/Havale ödemeleri ve alacaklar başka bir cari hesapta tutulur.
Örneğin, bize müşterimiz sanal pos aracılığıyla 200 ₺ ödeme gerçekleştirdi, entegratör firma bu işlem için bize 5 ₺ komisyon kesti ve faturalandırdı.
Kalan 195 ₺'yi EFT/Havale olarak banka hesabımıza gönderdi.

1. İlk olarak Aracı Sanal Pos hesabımıza iki cari hesap açalım. Örneğin birinin adı "Pos Entegratör Komisyon" olsun. Diğeri cari hesabın adı "Pos Entegratör Havale" olsun.
	Müşteri/Satıcı -> Modül Sayfası -> Hareket -> Yeni Müşteri/Satıcı Kartı Ekle buradan gerekli bilgileri doldurarak cari açma işlemimizi yapalım.

2. Bize sanal pos aracılığı ile ödeme yapan carimizin ödemesini Karma Transfer Hareketi ile girelim.;
	Müşteri/Satıcı -> Hareket Oluştur -> Diğerleri -> Karma Transfer Hareketi -> İşlem Tarihini girelim. 
		1. Kaleme -> Cari seçelim -> Alacak seçelim -> Bize ödeme yapan carimizi seçelim -> 200 ₺ girelim. 
		2. Kaleme -> Cari seçelim -> Borç seçelim -> "Pos Entegratör Havale" hesabımını seçelim -> 195 ₺ hesabımıza yatacak ödeme tutarını girelim.
		3. Kaleme -> Cari seçelim -> Borç seçelim -> "Pos Entegratör Komisyon" hesabını seçelim -> 5 ₺ işlem için bizden kesilecek olan komisyon tutarını girelim.
		Bu şekilde pos çeken müşterimiz bizden 200 ₺ alacaklandı ve entegratör firma 200 ₺ borçlandı.
		İlk senaryodan farklı olarak burada komisyon ödeme tutarlarımızı ve Havale alacağımızı ayrı ayrı takip edebiliyoruz.
		
3. Entegratör firması bize Komisyon faturası kestiğinde Alış faturası olarak girelim;
	Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Carimizi açtığımız "Pos Entegratör Komisyon" carisi seçelim -> GelirGider seçelim -> Pos Komisyon olarak tanımlayabiliriz -> Miktar 1 -> Tutar 5 ₺ -> *Kaydet* diyerek tamamlayalım.
	Bu şekilde entegratör firmanın bize olan borcu 5 ₺ azalarak toplamda 195 ₺ oldu. "Pos Entegratör Komisyon" carisinde borç kalmadı fakat "Pos Entegratör Havale" hesabında 195 ₺ borcu kaldı.

4. Entegratör firmadan bize ödeme geldiğinde, EFT/Havale alma girişini yapalım;
	Banka -> Hareket Oluştur -> Havale/EFT Alma -> Hangi bankamıza geldiğini seçelim -> Cari -> Açtığımız "Pos Entegratör Havale" carisini seçelim -> Tutar 195 ₺ -> *Kaydet* diyerek işlemi tamamlayalım.
	Bu şekilde entegratör firmanın bize bir borcu kalmamış oldu. 
	Hesabımızda 195 ₺ oldu.
	5 ₺ komisyon giderimiz oldu.
	POS Ödeme yapan müşterimizin 200 ₺ alacağı oldu.

Bu şekilde carimiz ile beklenen ödeme, yapılan ödeme, tahakkuk eden komisyon ve faturalandırılmış komisyon toplam tutarlarını kalem kalem takip edebiliriz.

Aracı firma ödemeleri ay sonunda ya da belirli tarihlerde yapmaktadır.   
Bu aralıkta ise bizim devam eden işlem akışlarımız olmaktadır. Bir önceki ayın ödemelerini yaptı, bu ay girdiğimiz tahsilatların ödemelerini gerçekleşmedi şeklinde senaryolar olabilir.
Kalan hesabımız ne kadar, ne kadar daha ödeme almam gerekiyor aynı zamanda kestiği komisyon bedellerini, ne kadar komisyon kesecek takip edebilmemiz için iki ayrı cari hesabı açmamız gerekmektedir.

## Dışarıdan Aktarma Soruları

**Soru:** Dışarıdan aktarma yapmak istiyorum 1000 adetten fazla yüklenemez uyarısı veriyor ne yapmam gerekiyor?

**Cevap:** Dışarıdan toplu aktarım yapmak istediğinizde sistem 995 adet olacak şekilde aktarılmaktadır. Kendimiz excel dosyası hazırlayacak isek ilk 5 satır boş bırakılmadır.   
Aaro'nun hazır şablonlarında ilk 5 satır yüklemeye hazır şekilde ayarlanmıştır. Verilerimizi doldurup aktarımı gerçekleştirebiliriz.

**Soru:** Grid sütunlarını nasıl ayarlayabilirim ve grid sütunlarımı excele nasıl aktarabilirim ?

**Cevap:** Üç işlem butonundan Grid Sütunları Ayarla seçelim sürekle bırak mantığıyla istediğimiz grid sütunalarını ayarlayalım.
Üç işlem butonunu seçelim Listeyi Excele Aktar diyerek ayarladığım grid sütunları ayarladığımız şekilde excel listesine erişim sağlayabiliriz.
Not: Listeyi excele aktar seçeneği gelmiyorsa indirme yetkiniz kapalıdır.
 
**Soru:** Stok kartı açmak için excel ile stok kartları dosyası hazırlayıp toplu yükleme yapabilir miyiz ?

**Cevap:** Evet, toplu yükleme yapabiliriz. Ayarlar -> Modül Sayfası -> Dışarıdan Aktarma -> Stok ve Benzeri Kartlar -> Stok Aktarmaları -> Stok Kartı Aktarma -> Excel Şablonu İndir -> 
Excel dosyamızı hazırlayalım zorunlu alanlar Stok Adı - Stok Kodu - KDV - Birim -> Sistemde Var Olan Stok Kayıtlarını Güncelle bu seçeneği kaldıralım -> 
Dosya seç -> Dosyamızı seçelim -> Şablonu Yükle stok kartı toplu yükleme işlemimiz gerçekleşti.

**Soru:** Excele aktarılan kayıt sınırını nasıl düzeltebilirim ?

**Cevap:** Ayarlar -> Parametre Listesi -> Yeni Parametre Ekle -> Parametre: DisariExcelAktarMaxSatirSayisi (Genel) -> Değer: rakam değerleri değiştirilerek kaydet seçeneği ile işlem tamamlanır.


## Gelir Gider Soruları 

**Soru:** Gelir Gider kalemleriyle aylık rapor almak istiyorum nasıl alabilirim ?

**Cevap:** Rapor -> Gelir Gider -> Toplam -> Gelir Gider Hareketleri Toplamları şeklinde ulaşım sağladıktan sonra tarih filtremesi yaparak bir aylık kalem detaylı rapor alabilirsiniz.


## Çıktı Tasarım Soruları 

**Soru:** Çıktı tasarımı nasıl yapılır ?

**Cevap:** Ayarlar -> Çıktı Listesi -> Çıktı Tasarımı yapacağımız tipi seçelim Örn; Verilen Teklif -> Sistemde var olan tasarımlarımızı buradan görüntüleyebiliriz -> 
Düzenlemek istediğimiz tasarımı seçelim -> Düzenle -> Üç İşlem Butonu -> Çıktı Dosyasını İndir (Var olan dosyanın üzerinde çalışma yaptığımızda o dosyanın üzerine
kaydeder yeni bir çalışma yapacağımız da çıktı dosyanı indirip tekrar yükleyerek üzerinde çalışmamız daha uygun olur.)
Dosyamızı indirdikten sonra; 

Yeni Çıktı Ekle -> Kod girelim -> Şirket-Şube seçelim -> Ön Tanımlı Çıktı Verilen Teklif olarak seçelim -> Tasarımımıza yeni bir isim verelim -> 
*Kaydet* dediğimizde çıktı tasarımımızın bilgileri gelecek -> Yeni Rapor Yetkileri Ekle (Tasarımıza müdahale de bulunacak ya da düzenleme yapacak kişilere yetki açabiliriz.)  
Tasarla diyerek tasarım düzenleme alanımız açılacak -> Buradan istediğimiz tasarımı yapabiliriz.
***


## Demirbaş Soruları 

**Soru:** Demirbaş kiralık araç nasıl tanımlarım ?

**Cevap:** Gelir Gider -> Hareket Oluştur -> Alış Faturası -> Gelir Gider Hizmet depomuzu seçelim -> Taşıt Giderleri -> Hangi Demirbaş ekle -> 
Gerekli alanları doldurduktan sonra *Kaydet* diyelim. 
Yevmiye Fişini açarak gelir giderimize uygun olacak şekilde değişikliklerimizi yapalım.