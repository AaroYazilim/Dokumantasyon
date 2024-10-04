
# Alt Reçete

## Tanım

Alt reçete, ana üretim sürecinin bir parçası olan ve daha küçük bileşenlerin veya alt reçetelerin üretiminde kullanılan detaylı bir bileşen listesidir.  

Alt reçeteler, her bir alt yarı mamulün üretiminde hangi malzemelerin, parçaların ve işçilik işlemlerinin kullanılacağını belirtir.  
Bu reçeteler, üretim sürecinin her aşamasında ihtiyaç duyulan kaynakların planlanmasına ve yönetilmesine yardımcı olur.  
Alt reçeteler karmaşık reçetelerin sadeleştirerek daha anlaşılır hale getirerek ana reçeteye iş emri verilerek tüm alt reçetelerine de iş emri oluşturulur. 

İş emri verildiğinde, o reçeteye ait alt reçetelere de otomatik olarak iş emri atanır ve bu sayede stoklar alt reçetelerle birlikte güncellenir.  
Alt reçete kullanımı, özellikle yarı mamulün birden fazla nihai ürünün üretiminde kullanılacağı durumlarda tercih edilir. 

Örneğin, bir malzemeden 10 farklı renk veya özellikte ürün üreteceğiniz bir senaryoda, bu ürünlerin tümünde aynı yarı mamul kullanılıyorsa, 
her seferinde bu yarı mamulü tekrar girmek yerine bir alt reçete tanımlayabilirsiniz.  
Alt reçeteyi tanımladıktan sonra, bu reçeteyi diğer tüm reçetelerle ilişkilendirirsiniz.   
Örneğin, 10 farklı renk üretmek istediğinizde, alt reçeteden toplam 1000 adet yarı mamul üretimi için iş emri verirsiniz ve 
bu alt reçeteyi tüm ana reçetelere bağlayarak süreci kolaylaştırabilirsiniz. 
Bu sayede, her bir reçete için ayrı ayrı yarı mamul girmek yerine, tek bir alt reçete üzerinden tüm üretimi yönetebilirsiniz.

Alt reçete oluşturmak istediğimiz reçeteyi açalım ve bölmek istediğimiz yarı mamulü seçelim.

Örneğin:

Reçetemiz *kurşun kalem* olsun. Yarı mamullerimiz *kalem minesi, grafit, kil* ve *emprenyeden* oluşur. Bu yarı mamullerin hepsi bir üretim aşamasından geçer ve hepsini alt reçetelere bölebiliriz. Örneğin, kalem minesi için bir alt reçete oluşturabiliriz.

Reçete oluşturma aşamalarını şu şekilde tanımlayalım:

***Üretim -> Taslak Reçete Listesi -> Yeni Reçete Taslağı Ekle*** 

Reçete Kodu olarak *KRSNKLM*, Reçete Adı olarak *Kurşun Kalem* diyelim.
Açıklama, kodlar, döviz, etiketler gibi bilgileri dolduralım.
mamul Bilgileri kısmına geçelim; ilk yarı mamulümüz kalem minesi olduğu için, mamulümüze kalem minesini ekleyelim.
*mamul: Kalem Minesi -> Miktar: 10 -> Açıklama* ve *Ek Maliyet* bilgilerini dolduralım.  
Ham madde bilgileri kısmına geçelim;

Ham madde: Grafit -> Miktar, Birim Fiyatı, Açıklama kısımlarını dolduralım.  
Operasyon Bilgileri kısmına geçelim;  
Operasyon: Karışım -> Kullanacağımız makineyi seçelim -> Çalışacak işçi adedi, hazırlık süresi, üretim süresi gibi bilgileri girelim.  
Gelişmiş kısmında, Şirket-Şube seçimimizi yapalım ve şarj kg bilgisini ekleyelim.
Kaydet diyerek reçete taslağımızın ilk aşamasını tamamlayalım.
Reçetemizi detaylandırmaya devam edelim:

Kalem minesi yarı mamulümüz grafit, kil ve emprenye karışımından oluşmaktadır. Bu yarı mamul için ham maddelerimizi girelim:  
Yarı mamulümüzü elde ettiğimiz operasyona tıklayalım -> Ham madde Ekle -> Ham maddemiz kil -> Miktar, birim fiyatı, açıklama kısımlarını dolduralım -> Kaydet.  

Diğer Ham madde olarak emprenyeyi de aynı şekilde ekleyelim.
Kalem minelerini hazırladıktan sonra, bunları lata ile bir yapıştırıcı yardımıyla birleştireceğiz.

   Şimdi, *lata*'yı reçetemize tanımlayalım.

Yarı mamulümüz kalem minesi olarak görünüyor, **mamul Düzelt** diyerek adını güncelleyelim.
Lata ve kalem minesini birleştireceğimiz birleştirme operasyonunu ekleyelim:  
Kalem minesine tıklayalım -> Operasyon Ekle Öncesi -> Operasyonumuzu girelim.

Operasyona tıklayalım -> Ham madde Ekle -> Ham maddemizi lata olarak girelim.  
Lata ve kalem minesini birleştirmek için kullanılan yapıştırıcıyı da ham madde olarak tanımlayalım.  
Birleştirme aşamasından sonra, lata tabakası üzerindeki yapıştırıcı kuruyana kadar bir kurutma fırınında basınç ile sıkıştırılır. 
 
 Bunu bir operasyon olarak tanımlayalım:

Yarı mamule tıklayalım -> Operasyon Ekle -> Operasyonumuzu ekleyelim.  
Yarı mamul adımızı düzeltelim; üzerine tıklayalım -> mamul Düzelt -> Fırınlanmış Lata olarak güncelleyelim.  
Bu aşamadan sonra latalara şekil verme operasyonumuzu tamamlayalım:

Yarı mamul -> Operasyon Ekle -> Operasyonumuzu ve makinemizi seçelim.
Oluşan yarı mamul adımızı değiştirelim; mamul Düzelt diyerek Kurşun Kalem olarak tanımlayalım.

Kurşun kalem reçetemizi tamamladık. Şimdi alt reçete bölme işlemini gerçekleştirelim:

Kalem minesini alt reçete yapmak istiyoruz.     
 Kalem minesi yarı mamulüne tıklayalım -> Alt Reçete Olarak Böl seçelim.  
Alt reçetenin adını Kalem Minesi olarak belirleyelim.  
Sayfayı yenileyelim; kalem minesi yarı mamulümüz turuncu renge dönüşecektir. Bu, reçetemizin bir alt reçetesi olduğunu gösterir.

Alt reçetelere bölmek, üretim aşamalarından geçen birçok yarı mamul ürünün tek reçetede karmaşık görünmesini önleyerek daha sade bir reçete yapısı oluşturur.

Alt Reçetemizi Nasıl Görebiliriz?

Alt reçeteyi görmek için:  
Yarı mamulümüzün ham madde olarak göründüğü ham maddeye tıklayalım -> Ham madde Düzelt -> Gelişmiş kısmında Alt Reçete alanına tıklayalım.
Kartı aç dediğimizde, alt reçetemizi yeni sekmede görüntüleyebiliriz.  
**Ana Reçeteye Alt Reçete Bağlama**  
Ana reçetede ham madde olarak görünen yarı mamulümüzü, alt reçete ile ilişkilendirmek için şu adımları izleyebiliriz:

Ana reçetedeki ham maddeye tıklayalım -> Ham madde Düzelt diyelim.  
Gelişmiş kısmında Alt Reçete alanına tıklayalım -> Alt reçetemizi seçelim -> Kaydet diyelim.  
Bu adımları takip ederek, ana reçetedeki yarı mamulü tanımlı bir alt reçete ile ilişkilendirip kullanabiliriz. Böylece, üretim süreçlerimizde hem daha düzenli bir yapı oluşturmuş oluruz hem de süreçlerimizi kolaylaştırırız.

