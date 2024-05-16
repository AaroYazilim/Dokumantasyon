
## Kodlar

### Tanım 

Kodlar kartı gruplamak ve ileride gruplu rapor alabilmek için kullanılan hiyerarşik tanımlardır.
Kodlar, sistemde belirli kayıtları veya varlıkları benzersiz bir şekilde tanımlamak için kullanılan bir kategorilendirmedir.
Bu kodlar genellikle işletmenin içinde kullanılan ve farklı kayıtları veya varlıkları ayırt etmek için kullanılan benzersiz kimliklerdir.
Sistemimizde kodlar kısmı altı adete kadar desteklenmektedir. 
Kategoriler gibi her kod bir sonrakinin alt kategorisi olacak şekilde birbirlerine beğlı şekilde ilerlemektedir.
Kod1 Ana kategori, kod2 detay, kod3 kategori vb. şekilde ilerlemektedir.
Stok, gelir-gider gibi işlemlerde ürünleri detaylandırarak bu işlemlerde ki kargaşayı azaltarak daha kolay bulmanıza, raporlayıp analiz yapmanıza yardımcı olur.

Çok sık kullanılan kodlar için; Bu parametreye özel tanımlar, ek özellikler ekleyebiliriz.

Örneğin, müşteri kayıtları için müşteri numaraları, ürünler için SKU (Stock Keeping Unit) kodları,
tedarikçiler için tedarikçi kodları, ürünün özellikleri(boyalı, tanklı vb.) gibi özel seçenekleri kod kısmında kullanalabilirsiniz.

Bu kodlar, işletme içindeki veri yönetimini kolaylaştırır ve çeşitli süreçlerde kullanılan kayıtların hızlı bir şekilde tanımlanmasını, bulmayı, filtrelemeyi kolaylaştırır. 
Kodlar sayesinde verilerin sınıflandırılması, izlenmesi ve raporlanması daha etkin bir şekilde gerçekleştirilebilir.

İşletmemizde stok yönetimi için kullanılan Kod2 veya Kod3 gibi belirli bir kod kategorisini ele alalım. 
Bu kod kategorisini "boyalı" olarak grupladığımızı düşünelim. 
Yani, işletmemizdeki farklı stok kalemlerini tanımlarken, bazılarını "boyalı" olarak etiketledik ve bu kategoride bir araya getirdik.
Şimdi, bu kod kategorisinde "boyalı" olarak tanımlanan her stok kalemi için toplu işlem yapma imkanına sahibiz. 
İşletmemizde bulunan tüm "boyalı" ürünler için aynı anda bir dizi işlem gerçekleştirebiliriz. 
Örneğin, bu ürünlerin fiyatlarını güncellemek, stok seviyelerini kontrol etmek veya bir promosyon kampanyası düzenlemek gibi işlemler toplu olarak gerçekleştirilebilir daha kolay analiz yapıp rapor çıkartmamıza yardımcı olur.

Öncelikle, Kapı, Dolap ve Masa gibi ürünleri temsil eden stok kalemlerini sisteme girdiğimizde, her birinin Kod1 kısmına ilgili ürünü belirten bir kod atarız. 
Örneğin, Kapı için "KAP", Dolap için "DLP", Masa için "MSA" gibi.
Ardından, her bir ürün için özellikle "Boyalı" gibi belirli bir özelliği temsil eden kodları Kod2 kısmına gireriz. 
Yani, boyalı olan Kapılar için "BOY", boyalı olan Dolaplar için "BOY" ve boyalı olan Masalar için de "BOY" kodlarını atarız.
Şimdi, eğer bir stok kaleminin "Boyalı" özelliğini silmek istiyorsak, bu ürünün stok girişi yapıldığı bütün kayıtlarda Kod2 kısmında "BOY" kodunu silmeliyiz. 
Yani, ilgili stok kalemi için yapılan bütün girişlerde, boyalı olma özelliğini temsil eden bu kodu kaldırmamız gerekmektedir.
Bu işlemi gerçekleştirmek için, ilgili stok kaleminin tüm girişlerini sisteminizde bulup, bu girişlerin Kod2 kısmında "BOY" kodunu silmek için bir düzenleme yapmanız gerekmektedir. 
Böylece, boyalı özelliğini kaldırmış olursunuz.
Ancak, bu işlemi gerçekleştirirken dikkatli olmalı ve diğer özelliklerin veya verilerin etkilenmemesini sağlamalısınız. Eğer sisteminizde bu tür bir işlemi gerçekleştirmek için bir araç veya işlem mevcut değilse, genellikle veritabanı sorguları veya özel bir yazılım geliştirme süreci gerekebilir. 
Bu nedenle, işlemi gerçekleştirmeden önce dikkatlice plan yapmanız ve gerekli önlemleri almanız önemlidir.
Bu yaklaşım, işletmenin verimliliğini artırır çünkü benzer özelliklere sahip ürünleri gruplayarak yönetme ve işlem yapma sürecini kolaylaştırır. Ayrıca, bu gruplama yöntemi, raporlama ve analiz süreçlerini de iyileştirir çünkü benzer ürünleri bir araya getirerek daha anlamlı veri setleri elde etmemizi sağlar. 
Bu sayede, işletmenin stok yönetimi süreçleri daha etkili ve verimli bir şekilde yürütülebilir.

### Kod Ekleme

- Sol menüden Stok -> Stok Kartları Kod Ağacı -> Kod Ekle şeklinde kod ekleme işlemini gerçekleştirebiliriz.
- Kodlar kısmında Detaylı Ekle şeklinde kod ekleme işlemini gerçekleştirebiliriz.
- Kodlar kısmında Listeden Seç yapabilirsiniz.
- Kodlar kısmında -> Listeden Seç -> Yeni Kod Ekle şeklinde yeni etiket ekleyebilirsiniz.

### Ek Özellikler 

**Anasayfaya Kısayol Olarak Ekle** Etiketler listesine hızlı erişim sağlamak istediğinizde kısayol olarak ekleyebilirsiniz. [Anasayfaya Kısayol Olarak Ekle](/TemelOzellikler/KisaYollaraEkleme.md "Anasayfaya Kısayol Olarak Ekle") 