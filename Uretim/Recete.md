
# Reçete

Üretim sürecinin başlangıçını reçete oluşturmaktadır. 
Reçete bir ürünün yapımında kullanılan malzemenin ve bu malzemlerin hangi oranlarda ve nasıl kullanılacağının belirtildiği bir belgedir.
Üretim endüstrisinde ürünlerin seri üretiminde, restoran ve yemekhane gibi yerlerde yemeklerin hazırlanmasında, ilaç endüstrisinde ilaçların formülasyonunda ve daha birçok alanda reçeteler kullanılır.
Reçete, malzemelerin nasıl kullanılacağını ve işlem adımlarını içerir. 
Bu adımlar sırayla listelenir ve ürünün yapımının adım adım nasıl gerçekleştirileceğini açıklar.
Malzeminin miktarı belirli ölçü birimleriyle belirtilir. Örneğin; kg, gram, litre gibi ayrıca her malzemenin toplam miktar içindeki oranı da belirtilmelidir.
Reçetelerde belirtilen adımların nasıl uygulanacağını ve malzemelerin nasıl hazırlanacağını detaylı olarak açıklanmalıdır.

Reçetede renklerin anlamları;

**Mavi renkli:** Operasyon belirtir.
**Turuncu renkli:** Hammadde belirtir.
**Bordo renkli:** Mamül belirtir.
**Bordo-Turuncu renkli:** Hem hammadde hem mamül belirtir.

Reçeteleri girebilmemiz için her bir hammadde, mamul ve yarı mamul için stok kaydımızın olması gerekmektedir.

Taslak Reçete oluşturarak üretim aşamalarına başlayabiliriz.

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "reçete" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Kartlar -> Taslak Reçete Listesi -> Yeni Reçete Taslağı Ekle şeklinde ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Kartlar -> İş Emri Reçete Listesi -> Yeni Reçete Taslağı Ekle şeklinde ulaşım sağlayabilirsiniz.

### Yeni Reçete Taslağı Ekle

#### Genel

**Reçete Kodu** Sistem otomatik kod atıyor kodu kullanabiliriz ya da kendi kodumuzu oluşturabiliriz.
**Reçete Adı** Reçete adımızı girebiliriz.
**Açıklama** Reçeteye ait detay açıklaması eklemesi yapabilirsiniz. Açıklamalar hakkında detaylı bilgiler için tıklayınız. [Açıklama](../TemelOzellikler/Aciklama.md)
**Kodlar** Reçeteyi gruplamak ve ileride gruplu rapor alabilmek için kullanılanabilirsiniz. Kodlar hakkında detaylı bilgiler için tıklayınız. [Kodlar](../TemelOzellikler/Kodlar.md)
**Etiketler** Reçeteyi gruplamak ve ileride gruplu rapor alabilmek için kullanılanabilirsiniz. Etiketler hakkında detaylı bilgiler için tıklayınız. [Etiketler](../TemelOzellikler/Etiketler.md)
**Döviz** Bu işleme ait döviz birimini seçiniz.

#### Mamül Bilgileri

Hazırladğınız bu reçetede üretmek istediğiniz mamül bilgilerini ifade eder. Daha sonra diagram üzerinden düzenleyebilirsiniz.

**Mamül** Oluşturacağımız mamülü seçelim, olmayan stoğumuzu için detaylı ekle, hızlı ekle yaparakta mamül girişi yapabiliriz.
**Miktar** Kaç adet oluşturacağımızı girelim.
**Açıklama** Reçeteye ait detay açıklaması eklemesi yapabilirsiniz. Açıklamalar hakkında detaylı bilgiler için tıklayınız. [Açıklama](../TemelOzellikler/Aciklama.md)
**Ek Maliyet** Birim başı ek maliyeti gösterir. Mamül için ek maliyetimiz var ise onu girelim.

#### Hammadde Bilgileri

**Hammmadde** Oluşturacağımız mamül için hammadde seçelim, detaylı ekle, hızlı ekle yaparakta mamül girişi yapabiliriz.
**Miktar** Oluşturacağımız mamül için birim başına ne kadar hammadde gireceğini girelim. 
**Birim Fiyatı** Oluşturacağımız mamül için birim başına hammadde maliyetini girelim. (Alış işlemi girilmiş ise sistem bize en son alım maliyetini otomatik getirecektir.)
**Açıklama** Reçeteye ait detay açıklaması eklemesi yapabilirsiniz. Açıklamalar hakkında detaylı bilgiler için tıklayınız. [Açıklama](../TemelOzellikler/Aciklama.md)

#### Opeasyon Bilgileri

**Operasyon** Operasyon makinemizi seçelim. Yeni bir operasyon eklemek için Detaylı Ekleyerek ekleme yapabiliriz.
**Makine** Operasyonda kullanılacak makineyi ifade eder. Kullanacağınız makine seçiniz makine kayıtlı değil ise detaylı ekle yaparak ekleme yapabiliriz.
**İşci Adedi** Operasyonda çalışacak işçi sayısını belirtie, bu opersayonda kaç işçi çalışacaksa sayısını girelim.
**Hazırlık Süre** Makinenin ısınması gibi süreçleri ifade eder.
**Üretim Süresi** Ne kadar sürede üretildiğini ifade eder. Üretim süresini girelim.
**Açıklama** Reçeteye ait detay açıklaması eklemesi yapabilirsiniz. Açıklamalar hakkında detaylı bilgiler için tıklayınız. [Açıklama](../TemelOzellikler/Aciklama.md)
**Hesap Açıklaması** Maliyet hesaplamaların yapıldığı formülü ifade eder. Özel hesaplamalar burada belirtilmelidir.
**İşçilik/Saat** Operasyonda çalışan işçinin saatlik ücretini ifade eder. Maliyet hesaplaması detayları için tıklayınız. [İşçiliyet Maliyeti](../Uretim/IscilikMaliyeti.md)
**Çalışma Mal/Saat** Operasyonda çalışan işçi, makine, elektrik gibi giderlerin saatlik ücretini ifade eder. Maliyet hesaplaması detayları için tıklayınız. [Birim Maliyeti](../Uretim/BirimMaliyeti.md)

#### Gelişmiş

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)
**Şarj Kg**


# Sonradan Reçete Düzenlemesi Yapmak 

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "reçete" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Kartalar -> İş Emri Reçeteleri Listesi şeklinde ulaşım sağlayabilirsiniz. 

Reçete ekranımızı açalım, işlem yapacağımız yani önüne ya da arkasına ürün gelecek operasyonu seçiniz. 

### Hammaddeye tıklayalım hammadde düzelttebilir, hammadde silebilir, operasyon ekleyebilir(öncesi ve sonrası), reçete getirebiliriz.

Reçetede hammadde de yapabileceğimiz işlemleri linkten inceleyebiliriz. [Hammadde](../Uretim/HammaddeEkle.md)


### Operasyona tıklayalım Operasyon düzeletebilir.

Reçetede operasyonda yapabileceğimiz işlemleri linkten inceleyebiliriz. [Operasyon](../Uretim/OperasyonEkle.md)
