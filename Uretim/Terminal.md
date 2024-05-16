
# Canlı Üretim Terminali 

Canlı üretim terminaliyle üretim anındaki süreçlerini detaylı olarak izleyebilirsiniz.
Operatörler, işçiler ve yöneticiler, üretim süreçlerini terminal üzerinden takip edebilir ve gerekirse müdahale edebilirler.
Üretime başlandığı an sistem üzerinden başladıklarını işaretlemeli, mola verdiklerinde mola nedeni ile birlikte mola detaylarını girmeli ve işlem bittiğinde bitirmelidir.
Personel bitiri seçtiğinde işlemi canlı takipte göremeyiz, işlem yapılma aşamasında canlı görüntülenmektedir.
Üretim bittiği andan itibaren canlı üretimden takip edemeyiz.
Biten işlemler için; Üretim -> Listeler -> Üretim Hareketleri Listesinden görüntüleyebiliriz.

İlk işlem olarak bir terminal kullanıcısı eklememiz gerekmektedir.

- [Terminal Kullanıcı Ekleme](/Uretim/TerminalKullaniciEkleme.md "Terminal Kullanıcı Ekleme"), kullanıcımızı tanımlayarak terminal sistemine erişimimiz başlayacaktır.
- Üretim terminaline kullanıcımızı tanımladıktan sonra terminal sistemine giriş yapabiliriz.
- https://erp.aaro.com.tr/ adresini açınız, üretim terminali kullancınızı ve şifrenizi giriniz. (Aaro hesabı yazan yerde ki mail ile giriş yapabilirsiniz. ayse@aaro.com.tr)
	Aaro açık olan tarayıcımızdan bu sayfaya erişim sağlayamayız. Terminal ve kullanıcı sayfasını aynı anda kullanmak istiyorsak farklı bir tarayıcıdan giriş yapmamız gerekmektedir.
- Terminal sistemini aktif kullanabilmemiz için [Operasyon Makine Eşleştirme](/Uretim/OperasyonMakineEslestirme.md "Operasyon Makine Eşleştirme") gerekmektedir. 
	Reçeteleri eşleştirip işlem yapabilmemiz için eşleştirme yapmamız gerekmektedir.
	Makinenin işlemleri eşleştirip tanımladıktan sonra,
- Terminal sisteminin çalışması için, terminal ile makine eşleştirmemişse makineyi kullanıcı ile eşleştirme yapmamız gerekmektedir. 
- Terminal ile makineyi eşleştirdiğimizde, terminal sistemimizde makine ve yapılacak operasyon aktif olacaktır. 
- Terminal sisteminde hangi makineyi kullanacaksak aaro logosunun altında bulunan makinelerden seçim yapabiliriz ya da kullanıcı bilgilerimizden makine seçemimizi gerçekleştirebiliriz.
- Makine terminal sisteminde aktif olduktan sonra canlı üretim terminal kısmımıza geçebiliriz.
- Terminali açınız, işlem yapacağınız makineyi seçiniz.

- Terminal sistemine giriş yaptığımızda bizi karşılayan ekranda;

	**Devam Eden İş Emri**
		Burada yarım kalan, devam etmemiz gereken işlerimizi görüntülenir.
		Devam etmek istediğimiz işi seçerek canlı üretim terminalimize başlayabiliriz.

	**Üretim Planı**
		Burada otomatik planlanan ya da yapmış olduğumuz planlamalar görüntülenir.
		İşleme başlayacağımız operasyonu seçerek işleme başlayabiliriz.
		Başlangıç Tarihi, Bitişi Tarihi, Aktiflik, Sipariş Hareket, Stok, İş emri seçeneklerinden filtrelemeler yaparak istediğimiz verilere kolayca ulaşabiliriz.

	**Üretim Hareketleri**
		Burada yapmış olduğumuz operasyonları görüntülenir.
		İstediğimiz aralıkları seçerek filtreleme yapabiliriz.
		Personel, Sipariş hareket, Stok, İş emri, Operasyon, Makine, Reçete, Son Operasyon Mu. seçeneklerinden filtrelemeler yaparak istediğimiz verilere kolayca ulaşabiliriz.

- Üretim yapılacak iş emrini seçtikten sonra üretim hareketi sayfamız açılacaktır. Açılan ekranda;
	**Hazırlık Başlat** Makinenin ısınmasını beklediğimiz zaman diliminde ya da üretim hazırlık aşamlarına başladığımızda burayı aktif etmemiz gerekmektedir.
	**Üretim Başlat** Hazırlık aşamamız bittikten sonra üretimi başlat aşamasına geçebiliriz.
		**Durakla** Makine arıza verdiğinde ya da duraklamamız gereken bir durum olduğunda duraklaya basarak durma eylemimizi aktif bir şekilde işlemiş olmaktayız.
			Bu butona bastığımızda neden ekranı karşılamaktadır. Durma nedemizi buraya girmemiz gerekmektedir makine arızalandı gibi detayları belirtmemiz gerekmektedir.
		**Mola Ver**
			Bu butonu seçtiğimizde üretim süresi sayma durar. 
			Mola verdiğimiz zaman burayı işaretlememiz gerekmektedir. Kaç dk sürdüğünü sistem otomatik hesaplar.
			Devam et dediğimizde süre, üretim süresininden devam eder. 
		**Bitir**
			Bu butona bastığımızda üretim hareket ekranı açılacaktır; 
			Bu ekran üzerinde, üretim hareketlerinde sisteme kaydedilenden farklı bir işlem gerçekleştiğinde müdahale edebilirsiniz. 
			Örneğin makine saatte 10 adet ürün olacak şekilde tanımlı fakat biz yavaş üretimden kaynaklı saatte 8 adet ürün çıkardık buradan verileri güncelleyebiliriz.
			Makine saatte 10 adet ürün olacak şekilde tanımlıyken makine saatte 11 adet üretim yaptı aynı şekilde mamül miktarını değiştirebiliriz.
			Bir başka senaryoda ise, hammadde kullanımı tanımlandığı miktarın üzerine çıkmış ya da daha az kullanılmış olabilir. Bu durumda, hammadde miktarını güncelleyebilirsiniz. 
			Operasyon sırasında çalışan personel bilgilerini de operasyon ekranından ekleyebilirsiniz.O operasyonda çalışan personelleri, personel listesinden eklemesini yapabiliriz.
			Üretim süreçlerindeki saatlerin yanlış kaydedilmiş veya eksik olduğunu fark ederseniz, bu bilgileri güncelleyebilirsiniz.
			Üretimde bir duraklama olmuşsa, duraklama nedenini bu ekrandan girebilirsiniz. 
			Ek olarak, operasyona ait açıklamaları üretim açıklama kısmına ekleyebilirsiniz. 
			Bu sayede üretim süreçlerinin daha doğru ve verimli bir şekilde yönetilmesi sağlanır.

			Gelişmiş -> Atlandı: Terminal ekranında atlamak, üretim sürecinde belirli bir adıma geçişi ifade eder. 
			Örneğin, bir üretim işçisi veya yönetici, ürünlerin üretim aşamalarını takip ederken, terminal ekranında belirli bir aşamadan diğerine geçişi için kullanım sağlar.
			Üretim aşamasının atlandığını veya tamamlandığını göstermek için kullanılır.

Verileri kontrol ettikten sonra kaydet butonuna basarak üretim operasyonu kaydet işlemini tamamlayabilirsiniz.
