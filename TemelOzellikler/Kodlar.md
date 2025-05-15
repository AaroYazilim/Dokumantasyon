
## Kodlar

### Tanım 

Kodlar, kartı gruplamak ve sonrasında gruplu rapor alabilmek için kullanılan hiyerarşik tanımlardır.
Sistemde belirli kayıtları veya varlıkları benzersiz bir şekilde tanımlamak için kullanılan bir kategorilendirmedir. Kayıtları veya varlıkları ayırt etmek için benzersiz kimlikler atama işlevini gerçekleştirir.

Sistemimizde kodlar kısmı altı adete kadar desteklenmektedir. 

Kategoriler gibi, her kod bir sonrakinin alt kategorisi olacak şekilde birbirlerine bağlı olarak ilerlemektedir.

Kod 1, en kapsayıcı olanıdır; sonrasında gelenler daha detaylı alt kategoriler şeklinde sırasıyla Kod 6'ya kadar ilerler.

Stok, gelir-gider gibi işlemlerde, ürünleri detaylandırarak işlemlerdeki kargaşayı azaltır, böylece ürünleri daha kolay bulmanızı, raporlamanızı ve analiz yapmanızı sağlar.

Çok sık kullanılan kodlar için bu parametreye özel tanımlar ve ek özellikler ekleyebiliriz.

Örneğin; müşteri kayıtları için müşteri numaraları, ürünler için SKU (Stock Keeping Unit) kodları,
tedarikçiler için tedarikçi kodları, ürünün özellikleri(boyalı, tanklı vb.) gibi özel seçenekleri kod kısmı altında kullanabilirsiniz.

Bu kodlar, işletme içindeki veri yönetimini kolaylaştırır ve çeşitli süreçlerde kullanılan kayıtların hızlı bir şekilde tanımlanmasını, bulunmasını ve filtrelenmesini sağlar.
Kodlar sayesinde verilerin sınıflandırılması, izlenmesi ve raporlanması daha etkin bir şekilde gerçekleştirilebilir.

İşletmemizde stok yönetimi için kullanılan Kod2 veya Kod3 gibi belirli bir kod kategorisini ele alalım.
Bu kod kategorisini "boyalı" olarak grupladığımızı varsayalım. Yani, işletmemizdeki farklı stok kalemlerini tanımlarken, bazılarını "boyalı" olarak etiketledik ve bu kategoride bir araya getirdik.
Şimdi, bu kod kategorisinde "boyalı" olarak tanımlanan her stok kalemi için toplu işlem yapma imkanına sahibiz.
İşletmemizde bulunan tüm "boyalı" ürünler için aynı anda bir dizi işlem gerçekleştirebiliriz.

Örneğin; bu ürünlerin fiyatlarını güncellemek, stok seviyelerini kontrol etmek veya bir promosyon kampanyası düzenlemek gibi işlemler toplu olarak gerçekleştirilebilir. Bu, daha kolay analiz yapmamıza ve rapor almamıza yardımcı olur.

Öncelikle Kapı, Dolap ve Masa gibi ürünleri temsil eden stok kalemlerini sisteme girdiğimizde; her birinin Kod1 kısmına ilgili ürünü belirten bir kod atarız.   
Örneğin; Kapı için "KAP", Dolap için "DLP", Masa için "MSA" gibi.
Ardından, her bir ürün için özellikle "Boyalı" gibi belirli bir özelliği temsil eden kodları Kod2 kısmına gireriz. 
Yani, boyalı olan Kapılar için "BOY", boyalı olan Dolaplar için "BOY" ve boyalı olan Masalar için de "BOY" kodlarını atarız.

Eğer bir stok kaleminin "Boyalı" özelliğini silmek istiyorsak, bu ürünün stok girişi yapıldığı bütün kayıtlarda Kod2 kısmında yer alan "BOY" kodunu silmemiz gerekmektedir.

Yani, ilgili stok kalemi için yapılan bütün girişlerde, boyalı olma özelliğini temsil eden bu kodu kaldırmamız gerekmektedir. Bu işlemi gerçekleştirmek için, sisteminizdeki ilgili stok kaleminin tüm girişlerini bularak, Kod2 kısmında bulunan "BOY" kodunu silmeniz gerekmektedir. Bu sayede, boyalı özelliğini kaldırmış olursunuz.


### Kod Ekleme

- Sol menüden *Stok -> Stok Kartları Kod Ağacı -> Kod Ekle* şeklinde kod ekleme işlemini gerçekleştirebiliriz.
- Kodlar kısmında Detaylı Ekle şeklinde kod ekleme işlemini gerçekleştirebiliriz.
- Kodlar kısmında Listeden Seç yapabilirsiniz.
- Kodlar kısmında -> Listeden Seç -> Yeni Kod Ekle şeklinde yeni etiket ekleyebilirsiniz.



