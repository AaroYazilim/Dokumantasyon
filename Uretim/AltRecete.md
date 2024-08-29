
# Alt Reçete

## Tanım

Alt reçete, ana üretim sürecinin bir parçası olan ve daha küçük bileşenlerin veya alt reçetelerin üretiminde kullanılan detaylı bir bileşen listesidir. 
Alt reçeteler, her bir alt yarı mamülün üretiminde hangi malzemelerin, parçaların ve işçilik işlemlerinin kullanılacağını belirtir.
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

### Alt Reçete Nasıl Yapılır ?

Alt reçete oluşturmak istediğimiz reçeteyi açalım; 
Bölmek istediğimiz yarı mamülü seçelim,
Örneğin; Reçetemiz kurşun kalem olsun yarı mamüllerimiz Kalem minesi, grafit, kil ve emprenyeden oluşur. 
Bu yarı mamüllerimizde hepsi bir üretim aşamasından geçiyor hepsini alt reçetelere bölebiliriz. 
Kalem minesi için bir alt reçete oluşturabiliriz.
Reçete oluşturarak aşamaları beraber tanımlayalım;
Üretim -> Taslak Reçete Listesi -> Yeni Reçete Taslağı Ekle -> Reçete Kodu KRSNKLM diyelim -> Reçete Adı Kurşun Kalem diyelim -> Açıklama, kodlar, döviz, Etiketler kısmını dolduralım -> 
Mamül Bilgileri kısmına geçelim; İlk yarı mamülümüz kalem minesi olduğu için mamülümüze yarı mamülümüz olan kalem minesini gireceğiz.
Mamül -> Kalem Minesi -> Miktar 10 olsun -> Açıklama, Ek Maliyet dolduralım.
Hammadde Bilgileri kısmına geçelim; 
Hammadde -> Grafit -> Miktar, Birim Fiyatı, Açıklama kısımlarını dolduralım.
Operasyon Bilgileri kısmına geçelim;
Operasyon -> Karışım -> Makine karışımda kullanacağımız makinemizi seçelim -> Bu operasyonda çalışacak işçi adedini, hazırlık süremizi, üretim süremizi, açıklama, hesap açıklaması, işçilik / Saat, Çalışma Mal.Saat bilgilerini girelim.
Gelişmiş -> Şirket-Şubemizi seçelim -> Şarj Kg 

*Kaydet* diyerek reçete taslağımızın ilk aşamasını tamamlayalım.
Reçetemizi detaylandıralım;
Kalem minesi yarı mamülümüz grafit, kil ve emprenye karışımdan oluşmaktadır.

Kalem minesi yarı mamülümüz için hammaddelerimizi girelim;
Yarı mamülümüzü elde ettiğimiz operasyonumuza tıklıyoruz -> Hammadde Ekle -> Hammaddemiz Kil -> Miktarı, birim fiyatını, Açıklama, hesap açıklamasını girelim -> *Kaydet* diyelim.
Diğer hammaddemiz emprenye girişini de yapalım aynı şekilde ekliyoruz hammadde adına emprenye olarak giriyoruz.

Kalem minelerini hazırladığımız mamülü lata ile bir yapıştırıcı yardımıyla birleştireceğiz. Şimdi ise lata'yı reçetemize tanımlayalım.

Yarı mamülümüz kalem minesi olarak gözükmekte mamül düzelt diyerek adını güncelleyelim.
Lata ve kalem minesi birleştireceğimiz birleştirme operasyonunu girelim;
Kalem minesi tıklayalım -> Operasyon Ekle Öncesi -> Operasyonumu girelim.
Operasyona tıklayalım -> Hammadde Ekle -> Hammaddemizi lama olarak girelim.
Lama ve kalem minesini birleştirmek için yapıştırıcı kullanıyoruz, yapıştırıcımızı da hammadde olarak tanımlayalım.

Birleştirme aşamasından sonra lata tabakası, üzerindeki yapıştırıcı kuruyana kadar bir kurutma fırınında basınç ile sıkıştırılır.
Operasyon olarak tanımlayalım; yarı mamüle tıklayalım -> Operasyon Ekle Sonrası -> operasyonumuzu ekleyelim.

Yarı mamül adımızı düzeltelim; üzerine tıklayalım -> Mamül Düzelt Fırınlanmış lata olarak düzeltelim.

Bu aşamadan sonra latalara şekil verme operasyonumuzu tamamlayalım.
Yarı mamül -> Operasyon Ekle Sonrası -> Operasyonumuzu ve makinemizi seçelim.

Oluşan yarı mamül adımızı değiştirelim; Mamül düzelt kurşun kalem olarak mamülümüzü tanımlayalım.

Kurşun kalem reçetimizi tamamladık alt reçete bölme işlemimizi gerçekleştirelim;

Kalem minesini Alt reçete yapmak istiyorum, Kalem minesi yarı mamülümüme tıklıyorum Alt Reçete Olarak Böl seçiyorum.
Alt reçetemizin adını girelim; kalem minesi diyelim.
Sayfamızı yenileyelim, kalem minesi yarı mamülümüz turuncu renge dönüştü bu bir alt reçetesi olduğunu göstermektedir.

Bu şekilde alt reçetelere bölmek üretim aşamalarından geçen bir çok yarı mamül ürünün tek reçetede karmaşık görünmesinin önüne geçerek daha sade bir reçete görüntüsü oluşturmaktadır. 

Alt reçetemizi nasıl görebiliriz;
Alt reçetimizi görmek için; 
Yarı mamülümüzün hammadde olarak gözüktüğü hammaddeye tıklayalım -> Hammadde Düzelt -> Gelişmiş kısmında Alt Reçete kısmından reçete adımızın yanında üç noktaya tıklayalım -> 
Kartı aç dediğimizde Alt reçetemizi yeni sekmede görüntüleyebiliriz.

### Ana Reçeteye Alt Reçete Bağlama 

Ana reçetemizde hammadde olarak görünen yarı mamülümüzün için, ana reçetede ki hammaddeye tıklayalım -> Hammadde düzelt diyelim -> 
Gelişmiş kısmında Alt Reçete -> Alt reçetemizi seçelim -> *Kaydet* diyelim bu şekilde ana retemize alt reçetemizi tanımlayabiliriz.

Ana reçetenizde hammadde olarak görünen yarı mamulü alt reçete ile ilişkilendirmek için şu adımları izleyebilirsiniz; 
Ana reçetede ki hammaddeye tıklayalım -> Hammadde düzelt diyelim -> Gelişmiş kısmında Alt Reçete -> Alt reçetemizi seçelim -> *Kaydet*
Bu adımları takip ederek, ana reçetenizdeki yarı mamulü, tanımlı bir alt reçete ile ilişkilendirip kullanabilirsiniz. 
Bu sayede, üretim süreçlerinizde hem daha düzenli bir yapı oluşturmuş olur hem de süreçlerinizi kolaylaştırırsınız.