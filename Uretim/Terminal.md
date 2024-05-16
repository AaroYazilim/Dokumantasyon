
# Canlý Üretim Terminali 

Canlý üretim terminaliyle üretim anýndaki süreçlerini detaylý olarak izleyebilirsiniz.
Operatörler, iþçiler ve yöneticiler, üretim süreçlerini terminal üzerinden takip edebilir ve gerekirse müdahale edebilirler.
Üretime baþlandýðý an sistem üzerinden baþladýklarýný iþaretlemeli, mola verdiklerinde mola nedeni ile birlikte mola detaylarýný girmeli ve iþlem bittiðinde bitirmelidir.
Personel bitiri seçtiðinde iþlemi canlý takipte göremeyiz, iþlem yapýlma aþamasýnda canlý görüntülenmektedir.
Üretim bittiði andan itibaren canlý üretimden takip edemeyiz.
Biten iþlemler için; Üretim -> Listeler -> Üretim Hareketleri Listesinden görüntüleyebiliriz.

Ýlk iþlem olarak bir terminal kullanýcýsý eklememiz gerekmektedir.

- [Terminal Kullanýcý Ekleme](/Uretim/TerminalKullaniciEkleme.md "Terminal Kullanýcý Ekleme"), kullanýcýmýzý tanýmlayarak terminal sistemine eriþimimiz baþlayacaktýr.
- Üretim terminaline kullanýcýmýzý tanýmladýktan sonra terminal sistemine giriþ yapabiliriz.
- https://erp.aaro.com.tr/ adresini açýnýz, üretim terminali kullancýnýzý ve þifrenizi giriniz. (Aaro hesabý yazan yerde ki mail ile giriþ yapabilirsiniz. ayse@aaro.com.tr)
	Aaro açýk olan tarayýcýmýzdan bu sayfaya eriþim saðlayamayýz. Terminal ve kullanýcý sayfasýný ayný anda kullanmak istiyorsak farklý bir tarayýcýdan giriþ yapmamýz gerekmektedir.
- Terminal sistemini aktif kullanabilmemiz için [Operasyon Makine Eþleþtirme](/Uretim/OperasyonMakineEslestirme.md "Operasyon Makine Eþleþtirme") gerekmektedir. 
	Reçeteleri eþleþtirip iþlem yapabilmemiz için eþleþtirme yapmamýz gerekmektedir.
	Makinenin iþlemleri eþleþtirip tanýmladýktan sonra,
- Terminal sisteminin çalýþmasý için, terminal ile makine eþleþtirmemiþse makineyi kullanýcý ile eþleþtirme yapmamýz gerekmektedir. 
- Terminal ile makineyi eþleþtirdiðimizde, terminal sistemimizde makine ve yapýlacak operasyon aktif olacaktýr. 
- Terminal sisteminde hangi makineyi kullanacaksak aaro logosunun altýnda bulunan makinelerden seçim yapabiliriz ya da kullanýcý bilgilerimizden makine seçemimizi gerçekleþtirebiliriz.
- Makine terminal sisteminde aktif olduktan sonra canlý üretim terminal kýsmýmýza geçebiliriz.
- Terminali açýnýz, iþlem yapacaðýnýz makineyi seçiniz.

- Terminal sistemine giriþ yaptýðýmýzda bizi karþýlayan ekranda;

	**Devam Eden Ýþ Emri**
		Burada yarým kalan, devam etmemiz gereken iþlerimizi görüntülenir.
		Devam etmek istediðimiz iþi seçerek canlý üretim terminalimize baþlayabiliriz.

	**Üretim Planý**
		Burada otomatik planlanan ya da yapmýþ olduðumuz planlamalar görüntülenir.
		Ýþleme baþlayacaðýmýz operasyonu seçerek iþleme baþlayabiliriz.
		Baþlangýç Tarihi, Bitiþi Tarihi, Aktiflik, Sipariþ Hareket, Stok, Ýþ emri seçeneklerinden filtrelemeler yaparak istediðimiz verilere kolayca ulaþabiliriz.

	**Üretim Hareketleri**
		Burada yapmýþ olduðumuz operasyonlarý görüntülenir.
		Ýstediðimiz aralýklarý seçerek filtreleme yapabiliriz.
		Personel, Sipariþ hareket, Stok, Ýþ emri, Operasyon, Makine, Reçete, Son Operasyon Mu. seçeneklerinden filtrelemeler yaparak istediðimiz verilere kolayca ulaþabiliriz.

- Üretim yapýlacak iþ emrini seçtikten sonra üretim hareketi sayfamýz açýlacaktýr. Açýlan ekranda;
	**Hazýrlýk Baþlat** Makinenin ýsýnmasýný beklediðimiz zaman diliminde ya da üretim hazýrlýk aþamlarýna baþladýðýmýzda burayý aktif etmemiz gerekmektedir.
	**Üretim Baþlat** Hazýrlýk aþamamýz bittikten sonra üretimi baþlat aþamasýna geçebiliriz.
		**Durakla** Makine arýza verdiðinde ya da duraklamamýz gereken bir durum olduðunda duraklaya basarak durma eylemimizi aktif bir þekilde iþlemiþ olmaktayýz.
			Bu butona bastýðýmýzda neden ekraný karþýlamaktadýr. Durma nedemizi buraya girmemiz gerekmektedir makine arýzalandý gibi detaylarý belirtmemiz gerekmektedir.
		**Mola Ver**
			Bu butonu seçtiðimizde üretim süresi sayma durar. 
			Mola verdiðimiz zaman burayý iþaretlememiz gerekmektedir. Kaç dk sürdüðünü sistem otomatik hesaplar.
			Devam et dediðimizde süre, üretim süresininden devam eder. 
		**Bitir**
			Bu butona bastýðýmýzda üretim hareket ekraný açýlacaktýr; 
			Bu ekran üzerinde, üretim hareketlerinde sisteme kaydedilenden farklý bir iþlem gerçekleþtiðinde müdahale edebilirsiniz. 
			Örneðin makine saatte 10 adet ürün olacak þekilde tanýmlý fakat biz yavaþ üretimden kaynaklý saatte 8 adet ürün çýkardýk buradan verileri güncelleyebiliriz.
			Makine saatte 10 adet ürün olacak þekilde tanýmlýyken makine saatte 11 adet üretim yaptý ayný þekilde mamül miktarýný deðiþtirebiliriz.
			Bir baþka senaryoda ise, hammadde kullanýmý tanýmlandýðý miktarýn üzerine çýkmýþ ya da daha az kullanýlmýþ olabilir. Bu durumda, hammadde miktarýný güncelleyebilirsiniz. 
			Operasyon sýrasýnda çalýþan personel bilgilerini de operasyon ekranýndan ekleyebilirsiniz.O operasyonda çalýþan personelleri, personel listesinden eklemesini yapabiliriz.
			Üretim süreçlerindeki saatlerin yanlýþ kaydedilmiþ veya eksik olduðunu fark ederseniz, bu bilgileri güncelleyebilirsiniz.
			Üretimde bir duraklama olmuþsa, duraklama nedenini bu ekrandan girebilirsiniz. 
			Ek olarak, operasyona ait açýklamalarý üretim açýklama kýsmýna ekleyebilirsiniz. 
			Bu sayede üretim süreçlerinin daha doðru ve verimli bir þekilde yönetilmesi saðlanýr.

			Geliþmiþ -> Atlandý: Terminal ekranýnda atlamak, üretim sürecinde belirli bir adýma geçiþi ifade eder. 
			Örneðin, bir üretim iþçisi veya yönetici, ürünlerin üretim aþamalarýný takip ederken, terminal ekranýnda belirli bir aþamadan diðerine geçiþi için kullaným saðlar.
			Üretim aþamasýnýn atlandýðýný veya tamamlandýðýný göstermek için kullanýlýr.

Verileri kontrol ettikten sonra kaydet butonuna basarak üretim operasyonu kaydet iþlemini tamamlayabilirsiniz.
