
## Kodlar

### Taným 

Kodlar kartý gruplamak ve ileride gruplu rapor alabilmek için kullanýlan hiyerarþik tanýmlardýr.
Kodlar, sistemde belirli kayýtlarý veya varlýklarý benzersiz bir þekilde tanýmlamak için kullanýlan bir kategorilendirmedir.
Bu kodlar genellikle iþletmenin içinde kullanýlan ve farklý kayýtlarý veya varlýklarý ayýrt etmek için kullanýlan benzersiz kimliklerdir.
Sistemimizde kodlar kýsmý altý adete kadar desteklenmektedir. 
Kategoriler gibi her kod bir sonrakinin alt kategorisi olacak þekilde birbirlerine beðlý þekilde ilerlemektedir.
Kod1 Ana kategori, kod2 detay, kod3 kategori vb. þekilde ilerlemektedir.
Stok, gelir-gider gibi iþlemlerde ürünleri detaylandýrarak bu iþlemlerde ki kargaþayý azaltarak daha kolay bulmanýza, raporlayýp analiz yapmanýza yardýmcý olur.

Çok sýk kullanýlan kodlar için; Bu parametreye özel tanýmlar, ek özellikler ekleyebiliriz.

Örneðin, müþteri kayýtlarý için müþteri numaralarý, ürünler için SKU (Stock Keeping Unit) kodlarý,
tedarikçiler için tedarikçi kodlarý, ürünün özellikleri(boyalý, tanklý vb.) gibi özel seçenekleri kod kýsmýnda kullanalabilirsiniz.

Bu kodlar, iþletme içindeki veri yönetimini kolaylaþtýrýr ve çeþitli süreçlerde kullanýlan kayýtlarýn hýzlý bir þekilde tanýmlanmasýný, bulmayý, filtrelemeyi kolaylaþtýrýr. 
Kodlar sayesinde verilerin sýnýflandýrýlmasý, izlenmesi ve raporlanmasý daha etkin bir þekilde gerçekleþtirilebilir.

Ýþletmemizde stok yönetimi için kullanýlan Kod2 veya Kod3 gibi belirli bir kod kategorisini ele alalým. 
Bu kod kategorisini "boyalý" olarak grupladýðýmýzý düþünelim. 
Yani, iþletmemizdeki farklý stok kalemlerini tanýmlarken, bazýlarýný "boyalý" olarak etiketledik ve bu kategoride bir araya getirdik.
Þimdi, bu kod kategorisinde "boyalý" olarak tanýmlanan her stok kalemi için toplu iþlem yapma imkanýna sahibiz. 
Ýþletmemizde bulunan tüm "boyalý" ürünler için ayný anda bir dizi iþlem gerçekleþtirebiliriz. 
Örneðin, bu ürünlerin fiyatlarýný güncellemek, stok seviyelerini kontrol etmek veya bir promosyon kampanyasý düzenlemek gibi iþlemler toplu olarak gerçekleþtirilebilir daha kolay analiz yapýp rapor çýkartmamýza yardýmcý olur.

Öncelikle, Kapý, Dolap ve Masa gibi ürünleri temsil eden stok kalemlerini sisteme girdiðimizde, her birinin Kod1 kýsmýna ilgili ürünü belirten bir kod atarýz. 
Örneðin, Kapý için "KAP", Dolap için "DLP", Masa için "MSA" gibi.
Ardýndan, her bir ürün için özellikle "Boyalý" gibi belirli bir özelliði temsil eden kodlarý Kod2 kýsmýna gireriz. 
Yani, boyalý olan Kapýlar için "BOY", boyalý olan Dolaplar için "BOY" ve boyalý olan Masalar için de "BOY" kodlarýný atarýz.
Þimdi, eðer bir stok kaleminin "Boyalý" özelliðini silmek istiyorsak, bu ürünün stok giriþi yapýldýðý bütün kayýtlarda Kod2 kýsmýnda "BOY" kodunu silmeliyiz. 
Yani, ilgili stok kalemi için yapýlan bütün giriþlerde, boyalý olma özelliðini temsil eden bu kodu kaldýrmamýz gerekmektedir.
Bu iþlemi gerçekleþtirmek için, ilgili stok kaleminin tüm giriþlerini sisteminizde bulup, bu giriþlerin Kod2 kýsmýnda "BOY" kodunu silmek için bir düzenleme yapmanýz gerekmektedir. 
Böylece, boyalý özelliðini kaldýrmýþ olursunuz.
Ancak, bu iþlemi gerçekleþtirirken dikkatli olmalý ve diðer özelliklerin veya verilerin etkilenmemesini saðlamalýsýnýz. Eðer sisteminizde bu tür bir iþlemi gerçekleþtirmek için bir araç veya iþlem mevcut deðilse, genellikle veritabaný sorgularý veya özel bir yazýlým geliþtirme süreci gerekebilir. 
Bu nedenle, iþlemi gerçekleþtirmeden önce dikkatlice plan yapmanýz ve gerekli önlemleri almanýz önemlidir.
Bu yaklaþým, iþletmenin verimliliðini artýrýr çünkü benzer özelliklere sahip ürünleri gruplayarak yönetme ve iþlem yapma sürecini kolaylaþtýrýr. Ayrýca, bu gruplama yöntemi, raporlama ve analiz süreçlerini de iyileþtirir çünkü benzer ürünleri bir araya getirerek daha anlamlý veri setleri elde etmemizi saðlar. 
Bu sayede, iþletmenin stok yönetimi süreçleri daha etkili ve verimli bir þekilde yürütülebilir.

### Kod Ekleme

- Sol menüden Stok -> Stok Kartlarý Kod Aðacý -> Kod Ekle þeklinde kod ekleme iþlemini gerçekleþtirebiliriz.
- Kodlar kýsmýnda Detaylý Ekle þeklinde kod ekleme iþlemini gerçekleþtirebiliriz.
- Kodlar kýsmýnda Listeden Seç yapabilirsiniz.
- Kodlar kýsmýnda -> Listeden Seç -> Yeni Kod Ekle þeklinde yeni etiket ekleyebilirsiniz.

### Ek Özellikler 

**Anasayfaya Kýsayol Olarak Ekle** Etiketler listesine hýzlý eriþim saðlamak istediðinizde kýsayol olarak ekleyebilirsiniz. [Anasayfaya Kýsayol Olarak Ekle](/TemelOzellikler/KisaYollaraEkleme.md "Anasayfaya Kýsayol Olarak Ekle") 