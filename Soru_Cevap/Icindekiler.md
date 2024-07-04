
## Depo - Stok Soruları

Soru: Sayım farkını nasıl silebilirim ?

Cevap: Stok modülünden -> Stok Haraketleri Listesi -> stok haraketlerimiz burada gözükmektedir.
Stok sayım farkımıza gelelim, büyütece basarak ya da çift tıklayarak detayına girelim.
Kalem işaretine tıklayalım, saol alt köşede sil butonundan silebilirsiniz.

Soru: Elimde tek bir ürün farkı var bunu nasıl işlerim ?

Cevap: Stok Modülüne gelelim -> Hareket Oluştur -> Devir -> depomuzu seçelim -> Yeni Stok Kalemi Ekle -> stoğu seçelim miktarı girelim.
Kaydet diyerek işlemimizi tamamlayabiliriz.

Soru: Kesilen fatura da stok kodu nasıl görüntülenir?

Cevap: Ayarlar -> Modül sayfası -> Parametre Listesi -> Yeni Parametre ekle diyerek "eDonusum_KalemdeStokKoduBilgisiGonderilsin (E-Fatura)" 
parametresi evet yapılarak gönderilen faturalarda stok kodunun görüntülenmesi sağlanır.

*** Soru: Yanlış açılan stok ve cari kayıtlarının düzeltilmesi, hareketlerin taşınması nasıl yapılır?
*** 
*** Cevap: Yanlış açılan herhangi bir stok kartı ile ilgili hareket yapılmışsa o harekete gidip ilgili kartı değiştirmek gerekir. 
*** Örneğin bir satış faturasında yanlış açılan stok kalemi nasıl düzeltilir ilk başta faturanın yevmiye fişinden 
*** muhasebeleştirmesi(onayını ve kilidini kaldır) iptal edilerek o harekette değişiklik yapılması sağlanır.

***Soru: Fiyat listesi düzenleme şablonları ve bu şablonların tekrar yüklenmesi nasıl yapılır?
***
***Cevap: Rapor -> Stok -> Fiyat -> Fiyat Listesi Aktarım/Düzeltme Şablonu -> sistemde yer alan fiyat listelerinin indirilip düzenleyelim,
***Ayarlar -> Modül Sayfası -> Dışarıdan Aktarma -> Stok -> Fiyat Listesi Aktarma şeklinde tekrardan yükleyebiliriz.



## Üretim Soruları 

Soru: Üretimde harcanan ürün depodan nasıl düşecek ?

Cevap: Reçeteler işlem yapıldıkça hammadde, yarı mamül ve mamüller üretilip üretim hareketi girildikçe sistemden otomatik olarak düşmektedir.



## Satış&Pazarlama Soruları

Soru: Siparişin açık kalemi ne kadar ve ne kadar sevkedildiğini nasıl görebilirim ?

Cevap: Siparişin açık kalemlerini ne kadar sevketildi görmek için;
Satış&Pazarlama modülünden -> Alınan Sipariş Listesi -> Siparişimizi seçelim -> Kısayollar -> Sevkiyat Detayları şeklinde ulaşım sağlayabiliriz.
Tüm siparişlerin sevkiyat detaylarını görmek için sevkiyat detaylarındayken kalem işaretinde düzenle diyerek filtreleme yaparak istediğiniz aralıkta ki siparişlerinizin sevkiyat detaylarına erişim sağlayabilirsiniz.

Soru: Cari siparişlerin sevkiyatlarını nasıl görüntüleyebilirim, liste yapmak istiyorum.

Cevap: Alınan sipariş hareketlerini -> Cariyi seçelim -> Tarih aralığını seçelim -> Üç işlem butonundan Listeyi Excele Aktar diyerek listeyi excel formatında indirebilirsiniz.
Excele indir gelmiyor ise yetkiniz olmayabilir kontrol edelim.
Bir diğer yöntem ise Rapor -> Sipariş/Teklif -> Hareket -> Sipariş Sevkiyat Detayları (Arama kısmına sevkiyat yazarakta erişim sağlayabilirsiniz) -> 
Tarih aralığını seçelim -> Cari seçelim -> Sadece Açık Siparişler seçili olmalı -> Raporla -> Yazdır/İndir şeklinde erişim sağlayabiliriz.


## Çek Senet Soruları

Soru: Müşteriye çeki nasıl ciro edebilirim ?

Cevap: Çek/Senet modülünden -> Hareket Olustur -> Çek Ciro Edildi/Verildi şeklinde ulaşım sağlayabilirsiniz.
Buradan çeki ciro edeceğimiz cariyi seçelim, döviz türünü seçelim kaydet diyelim.
Çek Senet Ekle mavi butonun yanında ki oktan ciro ekle seçeneğini seçelim, Ciro edilecek çeki seçelim kaydet seçeneğine basalım.

Soru: Çek /senet takibi nasıl yapılır? (alındı, tahsile verme, tahsil etme, iade, detaylandırılacak)

Cevap: Öncelikle çek senet işlemlerinde bir çekin kaydının girilmesi gerekir. 
- Bu çek alındı kaydıdır. Alınan çek farklı bir firmaya ciro edilebilir borcumuzu kapatabilmek için. 
- Ayrıca çek/senet işlemlerinde adım adım ilerlemek gerekir. 
- Çekin banka hesabımıza geçmesi için öncelikle alınan çekin bankaya tahsile verilmesi gerekir tahsile verildikten sonra bankadan tahsil edilip hesabımıza geçer. 
	Mesela bir çek aldık direk bankadan tahsil et dersek karşımıza gelmez, çekin tahsile verilmesi gerekir .
- Çek/Senet Hareketleri Listesinden çek/senet hareketlerini görüntüleyebilirsiniz.

## Müşteri/Satıcı Soruları 

Soru: Carini açık siparişlerinin sevkiyat listesini nasıl görüntüleyebilirim nasıl indirebilirim ?

Cevap: Siparişlerin sevkiyatlarını görüntülemek için; Satış&Pazarlama -> Listeler -> Alınan Sipariş Hareketleri -> Cariyi seçelim -> Tarihi seçelim -> Listeyi Excele Aktar diyerek listeyi excele aktarımını gerçekeleştirebiliriz.

Bir diğer yöntem ise;
Rapor -> Sipariş/Teklif -> Hareket -> Sipariş Sevkiyat Detayları -> Alınan Sipariş -> Cariyi seçelim -> Sadece Açık Siparişler seçeneğini seçelim -> Raporla diyerek erişim sağlayabiliriz.

## Banka Soruları

Soru: Banka eksi girişi yapmıyor nasıl girilebilir ?

Cevap: Borcu Alacak yapıyoruz bu şekilde sistem izin veriyor.

Soru: Bankadan nasıl virman yapabilirim ?

Cevap: Bankalar Arası Transfer yapmamız gerekiyor;
Banka -> Hareket Oluştur -> Banka Hesapları Arası Transfer -> Banka Alacak: Gönderici bankayı seçelim -> Tutarı girelim -> Şirket-Şube seçelim -> Banka Borç: Alıcı bankayı seçelim. 
Kaydet diyerek işlemimizi tamamlayabiliriz.

Soru: Kasadan veya Bankadan Gelir ve Gider hareketleri (Cari Kaydı Açmadan) nasıl işlenir?

Cevap: Kasadan ve bankadan gelir/gider hareketi seçeneği ile cari kaydı yapılmadan işlem yapılabilir.
Örneğin; Bim marketinden alınan ürünü banka kartı ile ödeme yapılarak alındığını düşünelim bankadan gider hareketi seçilerek ilgili 
banka hesabı seçilip kayıt işleminden sonra gider kartı (Temizlik Giderleri, Mutfak Giderleri, Yemek Giderleri vb.) 
eklenip tutar girilir gerekirse açıklama da eklenerek raporlardan alınabilir.


Soru: Personel maaşlarını bankadan nasıl gösterebilirim ?

?? Cevap: Bankalar içerisinde maaş ödeme hesabına para aktarıp personel maaş ödemesi çıkabilirsiniz.
?? Banka -> Hareket -> Yeni Banka Hesap Kartı -> 

Soru: Kredi kartını nasıl takip ediyoruz ödemelerini nasıl yapacağız ?

??? Cevap: Ödeme zamanı geldiğinde kredi carisine diğer bankadan transfer yapıyoruz.

Soru: Bankadan çekilen kredi nasıl takip edilir?

Cevap: Cari kartı açılır (banka hesap adı ve kredi sözleşme numarasıyla beraber). Müşteri/Satıcı -> Müşteri/Satıcı Kartı Listesi -> Yeni Müşteri/Satıcı Kartı Ekle -> Kredi kartı detaylarınızı girerek cari açabilirsiniz.
Bu cari kartının muhasebe hesap tanımları banka kredi hesaplarına atanır (muavin mizanda ilgili hesaplarda çıkması için). 
Açılan cari kartımıza kredi tutarımız kadar borç girilir. Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Kaydettiğimiz kredi kartı carimizi seçelim -> Krediyi ne için aldığımızın detaylarını girebiliriz (Gelir gider demirbaş alımı, ihtiyaç giderleri vb.) -> Tutarı girelim.
Her ay ödeme yapılarak güncel bakiye kontrol edilir. 
Bankadan ödeme yaptık diyelim; Banka -> Havale/EFT Gönderme -> Hangi bankadan ödeme yaptığımızı seçelim -> Kredi carimizi seçelim -> Cari Bankayı seçelim -> Ödeme yaptığımız tutarı girelim -> Kaydet diyerek işlemimizi tamamlayabiliriz.
Nakit(Kasa'dan) ödeme yaptık diyelim; Kasa -> Hareket Oluştur -> Nakit ödeme -> Ödeme yapılan kasamızı seçelim -> Kredi kartı carimizi seçelim -> Kaydet diyerek işlemimizi tamamlayalım.
Müşteri/Satıcı -> Müşteri/Satıcı Hareketleri Listesi -> Carimizi seçerek filtreleme yapalım buradan kalan borçumuzu yaptığımız ödemelerimizi takip edebiliriz.



## İhracat Soruları

Soru: Mikro ihracatta KDV nasıl sıfırlanır ?

Cevap: KDV sıfırlama yapmıyoruz, muafiyet girmemiz gerekiyor. Vergi muafiyetlerinde 301 seçmemiz gerekmektedir.
Vergi muafiyetini nasıl yapılır;
Faturamızı oluşturduktan sonra kalemlerimizin yanında ki büyüteçe tıklayalım -> Vergiler - Muafiyet Ekle -> KDV Muafiyet -> 11/1-a Mal İhracatı  (301) seçelim.
Muafiyet tanımlamamız tamamlanmıştır, kontrol edelim.
e-Arşiv, e-Faturayı gönder diyelim, Fatura Tipi ISTISNA olması gerekmektedir.

## İhraç Faturaları Soruları


Soru: İhraç kayıtlı e-arşiv fatura nasıl kesilir?

Cevap: Normal satış faturası kaydı girilir fatura tamamlandıktan sorna e-Arşiv fatura gönder seçeneğinden sonra karşımıza çıkan ekranda ihraç kayıtlı seçeneği seçmemiz gerekmektedir.

## Fatura Soruları 

Soru: Birden fazla irsaliye tek fatura nasıl birleştirilir ?

Cevap: Bir irsaliyemizi açalım, üç işlem sekmesinden Faturalaştır diyelim, bilgileri kontrol ettikten sonra kaydet diyelim.
Sağ üstte İrsaliyeden Kalem Ekle seçeneğine tıklayalım, irsaliyelerimizi seçelim kaydet butonu basarak irsaleyimizi fatura dönüştürebiliriz.
Bir diğer yöntem ise satış faturası açalım, yeni stok kalemi ekle kısmındaki oka tıklayalım irsaliyeden kalem ekle diyerek irsaliyelerimizi seçebiliriz.

Soru: Faturada kalemlerin KDV'sini nasıl değiştirebilirim ?

Cevap: Kalemin yanında ki büyüteçe tıklayalım -> Vergiler -> KDV oranını girelim -> Kaydet -> 
Üç işlem butonundan Tüm Kalemlerde Değiştir seçelim -> Vergileri Yenile -> Kaydet diyerek KDV oranı değişikliği gerçekleştirebiliriz.

Soru: E-fatura Entegratörü üzerinden kesilen fatura program da nasıl eşleştirilir?

Cevap: Foribadan kesilen faturanın eşleştirilmesi için Aaro'dan aynı şekilde satış faturası hareketi oluşturulur ama gönderilmez kaydedildikten sonra tekrardan düzenlenir ve 
üst kısımda yer alan efatura/earşiv bilgileri kısmından UUID kısmına faturadaki ETTN numarası, Ref Belge no kısmına fatura numarası yazılır. 
Kesilen faturanın tipine göre efaturaTipID, efaturaProfilID,efaturaDurumID seçeneklerinden uygun olanları seçilerek eşleştirme kayıt işlemi ile tamamlanır.

Soru: e-Fatura geçiş işlemleri nasıl yapılır?

Cevap: İlk olarak firmanın mali mühür alması gerekir. 
Mali mührü yoksa tübitak kamusm sayfasından alabilir(Link:https://mportal.kamusm.gov.tr/) 
Mali mührü aldıktan sonra entegratör firmanın evrakları iletilir.
Ayrıca sözleşmenin dışında firma bilgi formunda istenilen bilgiler doldurulacak ve bu formda istenilen evraklar temin edilecek. (İmza sirküsü, vergi levhası, oda kayıt belgesi, yetkili kimlik fotokopisi)
Entegratör firma ya evraklar,sözleşme ve istenilen kontör miktarı ile birlikte iletilir.(efatura/earşiv/eirsaliye geçişleri bilgisi verilir)

Soru: Muafiyetli fatura nasıl kesilir ?

Cevap: Satış Faturası hareketi normal olarak girilir. 
Bu harekette girilen her kart açılarak (Satış faturası alanında her kalemin yanında bulunan büyüteçten erişim sağlayabilirsiniz). 
KDV'nin altında yer alan muafiyet ekleme seçeneği ile açılan bölümden ilgili muafiyet nedeni seçilir ve kaydedilir. 
Eğer birden fazla kart ekli ise her kart için aynı şekilde muafiyet eklenir.

Soru: Tevkifatlı fatura nasıl kesilir ?

Cevap: Fatura hareketi sistemimizde olduğu gibi oluşturulur. Harekete eklenen kartlar için o kartların içeriğine gidilerek vergi oranı kısmında tevkifatlı vergi oranı açılır.
(Stok kaleminin yanında ki kalem işaretine tıklayalım -> Vergiler -> Muafiyet Ekle -> KDV Muafiyet muafiyeti seçiniz.)
Açılan vergi tanımında tevkifat tipi belirtilerek kaydedilir. Hareketin içeğindeki kart görüntülenerek tevkifat oranı değiştirilebilir.

Soru: Muhtelif cari özelliği nedir ?

Cevap: Muhtelif cari özelliğimiz ile tek bir cari altında birden fazla carimizi takip edebiliriz. 
Mesela; N11 sitesinde firmamızın ürünlerini satıyoruz herhangi bir kişi ürünümüzü satın aldı ve bu döngü sürekli halde devam ediyor. 
Bir ürünü birden fazla kişi bir kereliğine alabilir ve biz bu kişileri müşterimiz olarak açmak istemeyiz. Çünkü; ödeme kısımlarını da biz asıl firmamız olan N11'den almaktayız. 
O yüzden N11 firmasını  muhtelif cari olarak açabiliriz. Cari kartı içeriğinde yer alan muhtelif cari özelliğimizi aktif ederek.
(Müşteri/Satıcı kartının içine girelim Muhtelif Cari özelliğini aktif edelim.) 

Soru: Tek bir hareket için kdv oranı nasıl değiştirilir?

Cevap: Herhangi bir kartımızın sadece bir hareket için vergi oranını ilgili harekette kartımızı ekledikten sonra görüntüleyerek
KDV bölümünde yer alan rakamı ihtiyacımız olan vergi oranını yazıp kaydederek vergi oranını sadece bu hareket için değiştirmiş oluruz.
Kalemin yanında ki büyüteçe tıklayalım -> Vergiler -> KDV oranını girelim -> Kaydet şeklinde KDV oranını değişikliği gerçekleşir.

## Diğer

Soru: Geçiçi Anahtar Nasıl Oluşturulur ?

Cevap: Ayarlar -> Modül Sayfası -> Destek -> Geçici Erişim Anahtarı
Geçici erişim anahtarınızdan 12 saat erişim izni verilmektedir.
Erişim anahtarı sayesinde yapılması gereken işlemler için sizin adına destek verebilmemiz adına kullanım sağlanmaktadır.

## Yetki Soruları

Soru: Herhangi bir çıktı tasarımında rapor yetkisi nasıl açılır ?

Cevap: Bu işlemi herhangi bir çıktı tasarımından gerçekleştirebiliriz,
Çıktımıza gelelim; Ayarlar -> Çıktı Listesi -> çıktımızın kategorisinden tasarımızı açalım, açılan ekranda rapor yetkileri kısmında Yeni Rapor Yetkileri Ekle,
kullanıcıyı ya da kullanıcı grubu seçelim okuma yetkisini açalım.

Soru: Belirli bir tarihten önce  yapılan bir işlemde değişiklik yapma yetkiniz yoktur uyarısı nasıl çözülür?

Cevap: Ayarlar -> Modül sayfası -> Kullanıcı listesi bölümünden ilgili kullanıcı açılarak Cari ve Muhasebe alanında Bugünden Önce(gün), 
bugünden sonra(gün) bölümlerinde karşılarındaki rakam değerleri değiştirilerek kaydet seçeneği ile işlem tamamlanır. 
(sistemi yenile veya çıkış yapıp giriş yaparak tekrar dene)

Soru: Kdv den muaf fatura yetkisi nasıl açılır ?

Cevap: Ayarlar -> Modül sayfası -> Yetki alt listesi bölümünden Yeni Yetk Alt Ekle diyerek çıkan ekranda AltProgramID kısmına "Genel – DekontFatura_KDVdenMuafYapabilir" 
yetkisi seçilerek okuma,ekleme,silme, düzenleme aktif edilerek kaydedilir.

Soru: KDV oranı değiştirme yetkisi nasıl açılır ?

Cevap:Ayarlar modül sayfası yetki alt listesi bölümünden Yeni Yetk Alt Ekle diyerek çıkan ekranda AltProgramID kısmına "DekontFatura_KDVOranDegistirebilir " 
yetkisi seçilerek okuma,ekleme,silme, düzenleme aktif edilerek kaydedilir.

## Personel Soruları

Soru: Personel çıkışını nasıl yapacağım ?

Cevap: Personelin mesaileri var ise öncelik olarak personelin çıkış işlemini yapmalıyız.
Personel -> Personel Kartı Listesi -> Personeli seçelim -> Kısayollar -> Giriş Çıkış kayıtları -> Yeni Personel Giriş/Çıkış Kaydı Ekle -> Çıkış Tarihini girelim ->
Çıkış Nedeni SSK - Çıkış Nedeni - Açıklama bilgilerini dolduralım, kaydet diyelim.

## Karma Transfer Hareketi

Soru: Karma transfer hareketi mantığı nedir ?

Cevap : Mesela bir firma eksik ödeme yaptı 0,60 TL gibi bakiyesi açık görünüyor firmadan tekrar ödeme istemek yerine karma transfer hareketi ile bakiye kapanabilir.
Karma Transfer Hareketini açalım Ahmet isimli cari firmamıza borçlu carimizi alacak olarak (GelirGider, Stok vb.) 
seçip ilgili diğer hesabı ise borç olarak seçiyoruz ve karma transfer hareketi tamamlanmış oluyor.

## Devir

Soru: Belli bir tarihten önceki işlemlerin devir olarak görünmesi

Cevap: Sistemde otomatik  olarak hareketler listesinde belirli bir tarihten öncesini devir olarak toplam tutarını getirir. 
Firmalarımız bu olayda hareketlerini göremiyor. Hareketlerin detayını görebilmesi için filtreleme bölümünde yer alan başlangıç tarihi kısıtını 
istedikleri bir tarihi girerek hareketlere ulaşabilirler.

## MRP Raporu 

Soru: Sipariş ve iş emirleri üzerinden malzeme ihtiyaç ve stok durum raporu(MRP) nasıl alınır?

Cevap: Rapor -> Stok -> Toplam -> MalzemeMevcudu (DepoMinMaxMiktar Kontrolü) -> İlgili sipariş ve ya iş emri seçerek raporlayabiliriz.

## POS Tahsilat Soruları 

Soru: PayTR, iyzico, MokaPos vs. gibi aracı bir entegratör firmayla çalışıyoruz. Yapılan tahsilatları ve faturaları sisteme nasıl işlemeliyiz? Komisyon faturalarını, ve kalan fatura tutarını nasıl takip ederiz?  Kalan alacağımızı nasıl takip ederiz?

Cevap: İki yöntem ile takip edebiliriz;

1. Yöntem: Aracı firma ile olan borç alacak takibini basit bir şekilde takip etmek için kullanılabilir.

Aracı Sanal Pos hesabı tek hesap üzerinden takip edilir. Gelen faturaları, EFT/Havale ödemelerini tek caride tutarız.
Örneğin, bize müşterimiz sanal pos aracılığıyla 200 tl ödeme gerçekleştirdi, entegratör firma bu işlem için bize 5 tl komisyon kesti ve faturalandırdı.
Kalan 195 tl'yi EFT/Havale olarak banka hesabımıza gönderdi.

	1. İlk olarak Aracı Sanal Pos hesabımıza cari açalım. Örneğin adı "Pos Entegratör" olsun.
	Müşteri/Satıcı -> Modül Sayfası -> Hareket -> Yeni Müşteri/Satıcı Kartı Ekle buradan gerekli bilgileri doldurarak cari açma işlemimizi yapalım.

	2. Bize sanal pos aracılığı ile ödeme yapan carimizin ödemesini Müsteri / Satıcı hesapları arası transfer ile girelim.;
	Müşteri/Satıcı -> Hareket Oluştur -> Müsteri / Satıcı hesapları arası transfer -> 
		1. Alacaklı seçelim -> Bize ödeme yapan carimizi seçelim -> Tutarı örneğin 200 tl girelim.
		2. Borçlu seçelim -> Bu karıtını açtığımız entegratör firması olacak. Örneğin "Pos Entegratör". 
		Bu şekilde pos çeken müşterimiz bizden 200tl alacaklandı ve entegratör firma 200tl borçlandı.
		
	3. Entegratör firmasi bize Komisyon faturası kestiğinde Alış faturası olarak girelim;
	Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Carimizi açtığımız entegratör carisi seçelim -> GelirGider seçelim -> Pos Komisyon olarak tanımlayabiliriz -> Miktar 1 -> Tutar 5 tl -> Kaydet diyerek tamamlayalım.
	Bu şekilde entegratör firmanın bize olan borcu 5tl azalarak 195tl oldu.

	4. Entegratör firmadan bize ödeme geldiğinde, EFT/Havale alma girişini yapalım;
	Banka -> Hareket Oluştur -> Havale/EFT Alma -> Hangi bankamıza geldiğini seçelim -> Cari -> Açtığımız entegratör carisini seçelim -> Tutar 195 tl -> Kaydet diyerek işlemi tamamlayalım.
	Bu şekilde entegratör firmanın bize bir borcu kalmamış oldu. 
	Hesabımızda 195tl oldu.
	5Tl komisyon giderimiz oldu.
	POS Ödeme yapan müşterimizin 200tl alacağı oldu.

Bu şekilde carimiz ile beklenen ödeme, yapılan ödeme toplam tutarlarını kalem kalem takip edebiliriz.
Fakat bu yöntemde kesilecek faturaların takibini yapamayız. Faturaların ve havale eft alacağımızın ayrı ayrı takibini yapabilmek için ikinci yöntemi tercih edebilirsiniz.

2. Yöntem: Aracı firma ile olan borç alacak takibini komisyon faturaları ve havale eft alacağı şeklinde detaylı takip edilmek isteniyorsa kullanılabilir. 

Aracı Sanal Pos hesabı iki hesap üzerinden takip edilir. Gelen faturaları bir cari hesapta tutulur. EFT/Havale ödemeleri ve alacaklar başka bir cari hesapta tutulur.
Örneğin, bize müşterimiz sanal pos aracılığıyla 200 tl ödeme gerçekleştirdi, entegratör firma bu işlem için bize 5 tl komisyon kesti ve faturalandırdı.
Kalan 195 tl'yi EFT/Havale olarak banka hesabımıza gönderdi.

	1. İlk olarak Aracı Sanal Pos hesabımıza iki cari hesap açalım. Örneğin birinin adı "Pos Entegratör Komisyon" olsun. Diğeri cari hesabın adı "Pos Entegratör Havale" olsun.
	Müşteri/Satıcı -> Modül Sayfası -> Hareket -> Yeni Müşteri/Satıcı Kartı Ekle buradan gerekli bilgileri doldurarak cari açma işlemimizi yapalım.

	2. Bize sanal pos aracılığı ile ödeme yapan carimizin ödemesini Karma Transfer Hareketi ile girelim.;
	Müşteri/Satıcı -> Hareket Oluştur -> Diğerleri -> Karma Transfer Hareketi -> İşlem Tarihini girelim 
		1. Kaleme -> Cari seçelim -> Alacak seçelim -> Bize ödeme yapan carimizi seçelim -> 200tl girelim 
		2. Kaleme -> Cari seçelim -> Borç seçelim -> "Pos Entegratör Havale" hesabımını seçelim -> 195 tl hesabımıza yatacak ödeme tutarını girelim.
		3. Kaleme -> Cari seçelim -> Borç seçelim -> "Pos Entegratör Komisyon" hesabını seçelim -> 5 tl işlem için bizden kesilecek olan komisyon tutarını girelim.
		Bu şekilde pos çeken müşterimiz bizden 200tl alacaklandı ve entegratör firma 200tl borçlandı.
		İlk senaryodan farklı olarak burada komisyon ödeme tutarlarımızı ve Havale alacağımızı ayrı ayrı takip edebiliyoruz.
		
	3. Entegratör firmasi bize Komisyon faturası kestiğinde Alış faturası olarak girelim;
	Müşteri/Satıcı -> Hareket Oluştur -> Alış Faturası -> Carimizi açtığımız "Pos Entegratör Komisyon" carisi seçelim -> GelirGider seçelim -> Pos Komisyon olarak tanımlayabiliriz -> Miktar 1 -> Tutar 5 tl -> Kaydet diyerek tamamlayalım.
	Bu şekilde entegratör firmanın bize olan borcu 5tl azalarak toplamda 195tl oldu. "Pos Entegratör Komisyon" carisinde borç kalmadı fakat "Pos Entegratör Havale" hesabında 195tl borcu kaldı.

	4. Entegratör firmadan bize ödeme geldiğinde, EFT/Havale alma girişini yapalım;
	Banka -> Hareket Oluştur -> Havale/EFT Alma -> Hangi bankamıza geldiğini seçelim -> Cari -> Açtığımız "Pos Entegratör Havale" carisini seçelim -> Tutar 195 tl -> Kaydet diyerek işlemi tamamlayalım.
	Bu şekilde entegratör firmanın bize bir borcu kalmamış oldu. 
	Hesabımızda 195tl oldu.
	5Tl komisyon giderimiz oldu.
	POS Ödeme yapan müşterimizin 200tl alacağı oldu.

Bu şekilde carimiz ile beklenen ödeme, yapılan ödeme, tahakkuk eden komisyon ve faturalandırılmış komisyon toplam tutarlarını kalem kalem takip edebiliriz.

Aracı firma bize ödemeleri ay sonunda ya da belirli tarihlerde bize ödeme yapmaktadır. 
Bu aralıkta ise bizim devam eden işlem akışlarımız olmaktadır. Bir önceki ayın ödemelerini yaptı. Bu ay girdiğimiz tahsilatların ödemelerini gerçekleşmedi şeklinde senaryolar olabilir.
Kalan hesabımız ne kadar, ne kadar daha ödeme almam gerekiyor aynı zamanda kestiği komisyon bedellerini, ne kadar komisyon kesecek takip edebilmemiz için iki ayrı cari hesabı açmamız gerekmektedir.

## Dışarıdan Aktarma Soruları

Soru: Dışarıdan aktarma yapmak istiyorum 1000 adetten fazla yüklenemez uyarısı veriyor ne yapmam gerekiyor ?

Cevap: Dışarıdan toplu aktarım yapmak istediğinizde sistem 995 adet olacak şekilde aktarılmaktadır. 
2500 adet verimiz var ise bunu 995 olarak dosyalara bölmemiz gerekmektedir. Bu şekilde aktarımı gerçekleştirebiliriz.


