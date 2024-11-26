
# XSLT ile Fatura Tasarımı 

UBL (Universal Business Language), işletmeler arasında elektronik ticaretin standartlaştırılması ve kolaylaştırılması için geliştirilmiş bir XML tabanlı bir dil ve belirli bir veri modelidir. 
UBL, uluslararası standartlarla uyumlu olarak geliştirilmiştir. 
UBLTR, Türkiye'deki elektronik ticaret ve işletme çözümlerinde kullanılan bir XML tabanlı veri modeli ve standarttır. 
"UBLTR", "Universal Business Language Türkiye"nin kısaltmasıdır.

## XSLT

UBLTR XML şemasına dayanarak, istenen çıktıyı elde etmek için bir veya daha fazla XSLT dosyası oluşturulur. 
XSLT dosyaları, XML belgesini hedef formata dönüştüren veya biçimlendiren XSLT şablonlarını içerir.

Bu XSLT dili aracılığıyla faturalarımızı devletin belirlemiş olduğu çerçevede özelleştirerek işletmemize ait logolar, metin, renk, font vb. gibi stil özelliklerini düzenleyebilirsiniz.

## XSLT Tasarımını Aaro'ya Yükleme 

Xslt tasarımlarınız, AARO üzerinden oluşturulan fatura, e-arşiv ve diğer belgelerin düzenini belirleyen önemli bir bileşendir. 
Bu tasarımları AARO’ya yüklemezseniz, sistem varsayılan şablonlarla çalışır ve bu da belgelerinizin istediğiniz formatta olmamasına yol açabilir. 
Özelleştirilmiş bir XSLT dosyasını kullanarak belgelerinizi işletmenizin ihtiyaçlarına göre uyarlayabilirsiniz. 
Ancak, bu dosyaların yalnızca AARO’ya yüklenmesi yeterli değildir; aynı zamanda entegratör firmanıza da bu tasarımları tanımlamanız gerekir. Böylece hem sistem hem de entegratör firması arasında tam uyum sağlanır.

Aşağıda, .XSLT tasarım dosyanızı doğru şekilde yüklemek için izlemeniz gereken adımlar detaylı bir şekilde açıklanmıştır:

#### Tasarımın Hazırlanması:

Tasarımınızı oluştururken işletmenizin fatura, e-arşiv veya diğer belgelerde görmek istediğiniz tüm detayları eklediğinizden emin olun.
Kullanacağınız XSLT düzenleyicisiyle şablonlarınızı kontrol edin ve çalışır durumda olduğundan emin olun.

#### Dosya Formatının Doğrulanması:

Yüklemeye başlamadan önce dosyanızın .XSLT formatında ve sistemin desteklediği yapı ile uyumlu olduğundan emin olun.
Dosyanızda XML hatalarının olmadığını doğrulamak için bir XML doğrulayıcı aracı kullanabilirsiniz.

#### Yedek Alma (Opsiyonel):

Mevcut tasarımlarınızı kaybetmemek için AARO üzerinden önceki şablonunuzu indirin ve yedekleyin.
Bunun için sistemde Mevcut .XSLT Şablonu İndir seçeneğini kullanabilirsiniz.
Bu hazırlıkları yaptıktan sonra, aşağıdaki adımları takip ederek XSLT tasarımınızı AARO’ya yükleyebilirsiniz.

#### Aaro'ya .XSLT Tasarımı Yüklenmesi:

- Aaro'yu açın: erp.aaro.com.tr
- Ayarlar → Şirket Listesi → İlgili şirketinizi seçin → e-Fatura Ayarları bölümüne gidin.
- Var olan tasarımlarınızı incelemek için Mevcut .XSLT Şablonu İndir seçeneğini kullanabilirsiniz. Bu işlem, mevcut fatura şablonunuzu bilgisayarınıza indirir.
- Mevcut Şablonu Değiştir seçeneğine tıklayın. Tasarladığınız .XSLT dosyasını seçin. Yükle butonuna tıklayın. Değişikliklerinizi kaydetmek için Kaydet butonuna basın.
Bu adımları tamamladıktan sonra, yeni .XSLT tasarımınız sisteme başarıyla yüklenmiş olacaktır. Artık fatura çıktılarınız, yüklediğiniz tasarıma uygun şekilde düzenlenecektir. 

#### Entegratör Firma Sovosa Yüklenmesi:

Tasarım dosyanızı yalnızca AARO’ya yüklemek yeterli değildir. Bu dosyayı entegratör firmayada yüklenmesi gerekmektedir.
- Sovos'a giriş yapın: cloud.fitbulut.com
- Ayarlar → Ürün Ayarları → e-Fatura → Gelişmiş Ayarları açalım → E-Fatura .XSLT tasarımı yükle → Kaydet butonuna basın.
Bu adımları tamamladıktan sonra, yeni .XSLT tasarımınız sisteme başarıyla yüklenmiş olacaktır. Artık fatura çıktılarınız, yüklediğiniz tasarıma uygun şekilde düzenlenecektir. 

## Web Servis Üzerinden Bilgi Kaydetme

Web servisler, AARO’nun sistemle entegre çalışmasını sağlayan önemli araçlardır. Aaro ile entegratör firma işlemlerini yaparken pk ve gb kodlarını almamız gerekmektedir.

- Sovos sisteminde PK (Posta Kutusu) ve GB (Gönderici Birim) etiket bilgilerine erişmek için aşağıdaki adımları izleyebilirsiniz:
Sovos Bulut Portalına Giriş Yapın:
Web tarayıcınız üzerinden https://cloud.fitbulut.com/ adresine gidin.
Kullanıcı adı ve şifrenizle giriş yapın.
Giriş yaptıktan sonra, üst menüden "Ayarlar" sekmesine tıklayın.
Ayarlar menüsünde, "e-Fatura Ayarları" bölümünü seçin.
Bu bölümde, "Etiket" alanının karşısında PK ve GB etiket bilgilerinizi bulabilirsiniz.
Bu kodları kopyalayalım.

- Aaro ERP Programına Giriş Yapın:
Web tarayıcınız üzerinden https://erp.aaro.com.tr/ adresine gidin.
Kullanıcı adı ve şifrenizle giriş yapın.
Giriş yaptıktan sonra, üst menüden "Ayarlar" sekmesine tıklayın. 
Şirket Listesine tıklayın, ilgili şirketi seçin, "e-Fatura Ayarları" bölümünü seçin. 
e-Fatura Aktif ve e-Arşiv Aktif seçeneklerini seçelim.
Entegratör: Foriba'yı seçelim,
Kullanıcı Adı: Entegratör firma tarafından gönderilen web servis bilgilerinin kullanıcı bilgileridir. Foriba'da geçerli olan kullanıcı adını girelim,
Şifre: Entegratör firma hesabına giriş yapmak için kullandığımız şifre bilgilerini ifade eder. (Şifre entegratör firma ile işlemleri gerçekleştirebilmek için gereklidir.)
TCVKN: Firmanıza ait TC kimlik numarası veya Vergi kimlik numarasıdır.
PK Etiketi: Sistem tarafından e-fatura alımı için entegratör firma tarafından gönderilen etkiket bilgisidir. Kopyaladığımız PK etiketini buraya yapıştıralım.
GB Etiketi: Sistem tarafından e-fatura gönderimi için entegratör firma tarafından gönderilen etiket bilgisidir. Kopyaladığımız GB etiketini buraya yapıştıralım.
- Kaydet diyerek web servis tanımlama işleminizi tamamlayın.
- Faturalarınızı test ederek işlemlerin başarılı bir şekilde tamamlandığını doğrulayınız.

Bu işlemlerle, hem tasarımlarınızı sisteme yükleyebilir hem de web servisleri kullanarak verileri entegre bir şekilde kaydedebilirsiniz. 
Gerekli durumlarda sistem yöneticinize veya entegratör firmanıza danışarak sürecin sorunsuz ilerlemesini sağlayabilirsiniz.