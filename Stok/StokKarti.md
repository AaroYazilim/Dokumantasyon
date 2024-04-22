
## Stok Kartý

### Ulaþým

- Sol sekmede Aaro kullanýcý bilgilerinin hemen altýnda yer alan arama motorundan "Stok kartý" olarak aratarak ulaþým saðlayabilirsiniz.
- Sol menüden Stok -> Stok Modülü -> Yeni Stok Kartý þeklinde ulaþým saðlayabilirsiniz. 
- Sol menüden Stok -> Kartlar -> Stok Kartý Listesi üzerinden ulaþým saðlayarak yeni kart ekleyebilir yada mevcutlarý düzenleyebilirsiniz.

### Taným

Stok, bir iþletmenin sahip olduðu satýþ veya üretim için kullanýlmak üzere depoladýðý tüm fiziksel varlýklarý ifade eder. 
Bu varlýklar, malzemeler, hammadde, yarý mamul veya tamamlanmýþ ürünler olabilir. 
Stok kartlarýnýzý tanýmlayarak, bu varlýklarýn miktarýný, deðerini ve döngüsünü izleyebilir ve optimize edebilirsiniz. 
Stok seviyelerini belirlemek, stok hareketlerini iþlemek ve envanterin doðru bir þekilde yönetilmesi için stok kartlarý tanýmlanmalýdýr.
Aþaðýdaki bilgiler doldurularak stok kartýnýzý tanýmlayabilirsiniz.

### Genel

**Stok Adý:** Bu stok kartýnýn kendine özel adýdýr.

**Stok Kodu:** Kartýn kendine özel kodudur. Detaylý taným için linke týklayýnýz. [Kart Kodu](/TemelOzellikler/KartKodu.md "Stok Kodu")

**Birim 1:** Stok kartýnýn hangi birim cinsinden takip edileceðini belirtir. Girilecek ürünün ölçü ya da sayým birimi yani adet m3 kg litre desi koli plaka gibi özellikler eklenebilir.

**Kodlar:** Kartlarý hiyerarþik olarak gruplamak için kullanýlýr. Detaylý taným için linke týklayýnýz. [Kodlar](/TemelOzellikler/Kodlar.md "Kodlar")

**Etiketler:** Gruplamak için kullanýlýr. Detaylý taným için linke týklayýnýz. [Etiketler](/TemelOzellikler/Etiketler.md "Etiketler")


### Fiyat

**Alýþ Fiyat:** Bu stok kartýna ait ürün veya hizmetin satýn alýnýrken ödenen fiyatýný ifade eder.

**Döviz Adý:** Bu stok kartýna ait alýþ fiyatýnýn çalýþtýðý döviz cinsini belirtir. Bilgi amaçlýdýr.

**Satýþ Fiyat:** Bu karta ait ürün veya hizmetin müþterilere satýldýðý fiyatý ifade eder.

**Döviz Adý:** Bu stok kartýn aiat alýþ fiyatýnýn çalýþtýðý döviz cinsini belirtir. Bilgi amaçlýdýr.


### Barkod

**Barkod1:** Bu stok kartýna ait barkod numarasýný belirtir. 

**Barkod2:** Bu stok kartýna ait ikinci barkod numarasýný belirtir. Birden fazla barkodu olan stoklar için kullaným saðlayabilirsiniz.


### Ölçü Birimleri

**Birim 2:** Bu stok kartý için ikinci ölçü birimidir.Kolay hesap yapmak ve raporlarda farklý cins rapor alabilmek için kullanýlýr.

**Birim 3:** Bu stok kartý için üçüncü ölçü birimidir.Kolay hesap yapmak ve raporlarda farklý cins rapor alabilmek için kullanýlýr.

**Çevrimiçi Birim2:** Birim-1 cinsinden bu stoðun kaç Birim-2 cinsinden olduðunu belirtir.Örneðin; Birim-1:Adet ve Birim-2:Deste ise bu deger = 0,1(1/10) olur.

**Çevrimiçi Birim3:** Birim-1 cinsinden bu stoðun kaç Birim-3 cinsinden olduðunu belirtir.Örneðin; Birim-1:Adet ve Birim-3:Düzine ise bu deger = 0,083(1/12) olur.

**Üretim Birim:** Üretimle ilgili raporlarda seçilen birim cinsinden rapor almanýzý kolaylaþtýrýr.

**Rapor Birim:** Raporlarda seçilen birim cinsinden rapor almanýzý kolaylaþtýrýr.

**Kalýnlýk:** Stoðun kalýnlýk ölçüsünü belirtir.

**En:** Stoðun en ölçüsünü belirtir.

**Boy:** Stoðun boy ölçüsünü belirtir.

**Yoðunluk:** Stoðun yoðunluk ölçüsünü belirtir.

**Aðýrlýk:** Stoðun aðýrlýk ölçüsünü belirtir.


### Vergi Oranlarý

**Vergi Oranlarý:** Bu stok kartý ait iþlemlerde kullanýlacak devletin belirlemiþ olduðu KDV oranýný(vergi oranýný) belirtir. **Girilmesi Zorunludur.**

### Muhasebe Tanýmlarý

Muhasebeleþme tanýmlarýný ayarlayarak bu kart için hareket iþlendiðinde otomatikman belirli muhasebe hesaplarýna gerekli kayýtlarýn oluþmasýný saðlayabilirsiniz.
[Muhasebeleþme Tanýmlarý](/TemelOzellikler/MuhasebelesmeTanimlari.md "Muhasebeleþme Tanýmlarý")



### Bayi Tanýmlarý

**Bayide Göster:** Tüm stoklarýnýz bayilerinize gösterilmez.Bayi sisteminiz aktif ise göstermek istediðiniz bir stok ise iþartelemeniz gerekmektedir.

**Bayi Maks. Miktar:** Bayileriniz, belirleyeceðiniz sayýnýn üzerindeki stok miktarýný göremez. Örneðin;Deponuzda 100 birim ABC stoðu var.
Bu alana 50 girilirse, bayileriniz bu stoðun miktarýný 50+ þeklinde görecektir.0 girerseniz asdece'Stokta Var' ya da 'Stokta Yok' þeklinde görürler.

**Stok Yönetimi**

**Takip Yöntemi:** Stok miktar takibi yapýlýrken Seri veya Lot takibi yapýlýp yapýlmadýðýný belirler. **Girilmesi Zorunludur.**

**TY Kod Ön Eki:** Otomatik baþlatýlan Seri ve Lot numaralarýnda No'nun istenilen seri ile baþlasýný saðlar. **Girilmesi Zorunludur.**

**TY Üretim Bire Bir iliþki:** Üretim hareketlerinde bu stok üretilirken her bir Seri ve Lot için hangi hammaddelerin bire bir kontrolünün yapýlmasý için kullanýlýr. **Girilmesi Zorunludur.**

**Raf Takibi:** Raf takibi yapýlýp yapýlmayacaðýný belirler. *Girilmesi Zorunludur.**

**Paket Takibi:** Paket takibi yapýlýp yapýlmayacaðýný belirler. *Girilmesi Zorunludur.**


### Geliþmiþ

**Þirket-Þube:**  Kartýn ait olduðu þirket ve þubeyi belirtir. Þirket-Þube kullaným detaylarý için linke týklayýnýz. [Þirket-Þube](/TemelOzellikler/SirketSubeKart.md "Þirket-Þube")

**Durum:** Kartýn kullanabilirliðini belirtir. Pasif kartlar iþlemde kullanýlamaz.

**GTIP:** Ýhracat tipindeki e-faturalarda, stoða ait GTIP deðerinin doldurulmasý zorunludur.

**Harici Depo Miktar:** Depo dýþýnda kalan miktarý belirtir.

**Hizmet Mi:** Bu seçenek hizmet takibi olarak seçilirse miktar takibi yapýlmaz, depoda gözükmez, eski bakiye kontrolü yapýlmaz.

**Stok Kýsa Kodu:** Raporlama için gereklidir. 

**Stok Kýsa Adý:** Raporlama için gereklidir. 

**Kargo ücreti:** Kargo ücreti 

**StandartMý:** Stok kartýnýn standart stok olarak deðerlendirilmesini saðlar. Filtreleyerek bulmamýzý kolaylaþtýrýr. 


### Açýklamalar

Bu kýsma stok ile ilgili açýklama eklenebilir.


Doldurulmasý gereken alanlar girildikten sonra sað alt köþede bulunan Kaydet butonuna basarak Stok kartý açma iþlemimizi tamamlayabilirsiniz.
