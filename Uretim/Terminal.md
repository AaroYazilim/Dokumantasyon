
# Canlı Üretim Terminali 

Canlı üretim terminali ile üretim anındaki süreçleri detaylı olarak izleyebilirsiniz. Operatörler, işçiler ve yöneticiler, üretim süreçlerini terminal üzerinden takip edebilir ve gerektiğinde müdahale edebilirler.

- Üretime başlandığında, sistem üzerinden "başla" seçeneği işaretlenmelidir.  
- Mola verildiğinde, mola nedeni ve detayları girilmelidir.
- İşlem bittiğinde, "bitir" seçeneği ile işlem sonlandırılmalıdır.  
- Personel "bitir" seçeneğini seçtiğinde, işlem canlı takipte görünmez. Canlı görüntüleme yalnızca işlem devam ederken mümkündür.   
Üretim tamamlandığında ise canlı takip sona erer.

Biten işlemler, *Üretim -> Listeler -> Üretim Hareketleri Listesi* üzerinden görüntülenebilir.

İlk adım olarak, bir terminal kullanıcısı eklememiz gerekmektedir.

Terminal Kullanıcı Ekleme adımlarını izleyip kullanıcıyı tanımladıktan sonra terminal sistemine erişimimiz başlayacaktır.   
Üretim terminaline kullanıcıyı tanımladıktan sonra terminal sistemine giriş yapabilirsiniz.  

- https://erp.aaro.com.tr/ adresini açınız, üretim terminali kullanıcı adınızı ve şifrenizi giriniz. (Aaro hesabı kısmına, örneğin ayse@aaro.com.tr e-posta adresiniz ile giriş yapabilirsiniz.)  
Aaro açık olan bir tarayıcıdan bu sayfaya erişim sağlanamaz.     Terminal ve kullanıcı sayfasını aynı anda kullanmak için farklı bir tarayıcıdan giriş yapmanız gerekmektedir.  
- Terminal sistemini aktif kullanabilmek için Operasyon Makine Eşleştirme işleminin yapılması gerekmektedir.  
Reçeteleri işleyebilmek için makine işlemlerini eşleştirip tanımlamanız gerekmektedir.  
- Terminal sisteminin çalışması için, makineyi kullanıcı ile eşleştirmeniz gerekir. Makine ve operasyon eşleştirmesi yapıldığında, terminal sisteminde makine ve yapılacak işlem aktif hale gelecektir.  
- Terminal sisteminde kullanacağınız makineyi seçmek için, ekranın altında bulunan makinelerden seçim yapabilir veya kullanıcı bilgileriniz üzerinden makine seçimi gerçekleştirebilirsiniz.  
- Makine terminal sisteminde aktif olduktan sonra canlı üretim terminaline geçebilirsiniz.   Terminali açın ve işlem yapacağınız makineyi seçin. 

Terminal sistemine giriş yaptığınızda sizi karşılayan ekranda şu bölüm yer alır:

### Devam Eden İş Emri:

Burada, yarım kalmış ve devam etmeniz gereken iş emirleri görüntülenir.
Devam etmek istediğiniz işi seçerek canlı üretim terminalini başlatabilirsiniz.

### Üretim Planı

Bu bölümde, otomatik olarak planlanan veya yaptığımız üretim planlamalarını görüntüleyebiliriz. İşleme başlamak istediğimiz operasyonu seçerek işleme başlayabiliriz.

Başlangıç Tarihi, Bitiş Tarihi, Aktiflik, Sipariş Hareketi, Stok, İş Emri gibi seçeneklerle filtreleme yaparak istediğimiz verilere kolayca ulaşabiliriz.

### Üretim Hareketleri

Bu bölümde, gerçekleştirdiğimiz tüm operasyonları görüntüleyebiliriz.

İstediğimiz tarih aralıklarını seçerek filtreleme yapabiliriz.
Personel, Sipariş Hareketi, Stok, İş Emri, Operasyon, Makine, Reçete, Son Operasyon Mu gibi filtreleme seçenekleri ile ihtiyacımız olan verilere kolayca ulaşabiliriz.


-Üretim yapılacak iş emrini seçtikten sonra üretim hareketi sayfası açılacaktır. Açılan ekranda:

**Hazırlık Başlat:** Makinenin ısınmasını beklediğinizde ya da üretim hazırlık aşamalarına başladığınızda bu butonu aktif hale getirmeniz gerekir.

**Üretim Başlat:** Hazırlık aşaması tamamlandıktan sonra, üretimi başlatabilirsiniz.

**Durakla:** Makine arıza verdiğinde ya da duraklamanız gereken bir durum olduğunda bu butona basarak durma işlemini aktif hale getirmiş olursunuz. Bu butona bastığınızda bir neden ekranı çıkar; durma nedeninizi (örneğin, makine arızası gibi) girmeniz gerekmektedir.

**Mola Ver:** Bu butonu seçtiğinizde üretim süresi sayımı durur. Mola verdiğinizde burayı işaretleyip, sürenin kaç dakika olduğunu sistem otomatik olarak hesaplar. Devam et dediğinizde, süre üretim süresinden kaldığı yerden devam eder.

**Bitir:** Bu butona bastığınızda üretim hareket ekranı açılır. Bu ekranda, üretim hareketlerinde sisteme kaydedilenden farklı bir işlem gerçekleştiyse müdahale edebilirsiniz.

Örneğin, makine saatte 10 ürün üretecek şekilde tanımlanmış, fakat siz saatte 8 ürün üretmişseniz, buradan verileri güncelleyebilirsiniz.  
Aynı şekilde, makine saatte 11 ürün üretmişse mamul miktarını da değiştirebilirsiniz. 

-Ham madde kullanımı, tanımlanan miktarın üzerinde ya da altında gerçekleşmişse, ham madde miktarını buradan güncelleyebilirsiniz.  
-Operasyon sırasında çalışan personellerin bilgilerini de ekleyebilirsiniz. Personel listesinden o operasyonda çalışanları seçerek işlem yapabilirsiniz.  
-Üretim süreçlerindeki saatlerde yanlışlık veya eksiklik fark ederseniz, bu bilgileri de güncelleyebilirsiniz.  
-Üretim sırasında duraklama olmuşsa, duraklama nedenini bu ekrandan girebilirsiniz.  
-Operasyona ait açıklamaları da Üretim Açıklama kısmına ekleyebilirsiniz. Bu sayede üretim süreçlerinin daha doğru ve verimli bir şekilde yönetilmesi sağlanır.  
-Gelişmiş -> Atlandı: Terminal ekranında "atlamak", üretim sürecinde belirli bir aşamadan diğerine geçişi ifade eder. Örneğin, bir işçi veya yönetici, üretim aşamalarını takip ederken, belirli bir adımdan diğerine geçmek için bu özelliği kullanabilir. Üretim aşamasının atlandığını ya da tamamlandığını göstermek için tercih edilir.

Verileri kontrol ettikten sonra *Kaydet* butonuna basarak üretim operasyonu *Kaydet* işlemini tamamlayabilirsiniz.

## Terminal Kullanıcı Ekleme 

Canlı üretim terminal sistemi, üretim anında gerçekleşen tüm işlemlerin gerçek zamanlı olarak sisteme aktarılmasını sağlar.

Operasyon başladığında "başla" butonuna,  
Mola verildiğinde "mola verildi" butonuna,  
Durma gerçekleştiğinde "durma" butonuna,  
İşlem bittiğinde "bitti" butonuna
 basılarak sürelerin hesaplanması sağlanır.
Bu sistem, anlık verilerin canlı olarak görüntülenmesine yardımcı olur ve daha hızlı planlamalar yapılmasına, işin ve siparişlerin durumu hakkında hızlı veriler elde edilmesine olanak tanır. 

### Ulaşım 

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "terminal" şeklinde aratarak ulaşım sağlayabilirsiniz.
- Sol menüden *Ayarlar -> Kartlar -> Terminal Kullanıcı Listesi -> Yeni Terminal Ekle* şeklinde ulaşım sağlayabilirsiniz.

#### Genel 

**Kullanıcı Kodu:** Kullanıcıya ait koddur ve bu kod ile oturum açılır.

**Kullanıcı Adı:** Kullanıcının adını giriniz.

**Aaro Hesabı:** Oturum açma hesap bilgilerini belirtir. Sisteme girdiğiniz her adın yanına sistem otomatik olarak "@aaro.com.tr" ekler.

Örneğin: "ayse" yazdığınızda, sistem otomatik olarak "ayse@aaro.com.tr" adresini verir ve bu adres ile giriş yapabilirsiniz.   
Telefon: Kullanıcının telefon numarasını giriniz. Bu numara, ikinci güvenlik adımı ve şifre sıfırlama işlemleri için gereklidir.

**e-Posta:** Kullanıcının kullandığı e-posta adresini giriniz.

**Şifre:** Kullanıcı girişi için şifre belirleyiniz. Şifreniz 8 karakterden uzun olmalıdır.

**Makine:** Kullanıcının erişim sağlayacağı makineyi ekleyiniz.

**Etiketler:** Kullanıcıları gruplamak için kullanılır. Detaylı bilgi için Etiketler linkine tıklayınız.

### Yetkiler 

**Oturum Açma Yetkisi:** Kullanıcının oturum açabileceği Şirket ve Şubeyi belirtir.

**Oturum Açma Saatleri:**
Vardiyalı çalışan yerlerde, başka bir kullanıcının başkası adına işlem yapmaması için güvenlik amacıyla çalışma saatleri belirtilir. Kullanıcının başlangıç ve bitiş saatlerini buradan ayarlayabilirsiniz.

**Gelişmiş:**
Kullanıcının aktif ya da pasif durumunu bu bölümden seçebilirsiniz.

*Kaydet* butonuna basarak kullanıcı tanımlama işlemini tamamlayabilirsiniz.

Eğer kullanıcı birden fazla makineden sorumluysa veya başka bir makinede işlem yapacaksa, terminal kullanıcısı ile makine arasında eşleştirme yapılmalıdır.