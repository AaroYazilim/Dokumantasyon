---
SayfaID: Yetkiler/Liste
SayfaTipi: Lıste
---

# Yetkiler

**Erişim Linki :** [erp.aaro.com.tr/Yetkiler/Liste](erp.aaro.com.tr/Yetkiler/Liste)

## Ulaşım 

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "yetki" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Ayarlar -> Modül Sayfası -> Yetki Listesi -> Yeni Yetki Ekle şeklinde yeni parametre ekleyebilirsiniz.
- Sol menüden Ayarlar -> Yetki Listesi şeklinde yetki listesine ulaşım sağlayabilirsiniz. 

## Tanım

Yetkiler, ERP (Enterprise Resource Planning) sistemlerinde kullanıcıların belirli işlevleri gerçekleştirmek veya belirli verilere erişmek için sahip oldukları izinlerdir. 
Bu, sistemi kullanırken belirli rollerin veya kullanıcıların belirli işlemleri yapma veya belirli verilere erişme yetkisine sahip olmasını sağlar.

- Kullanıcı Rollerine Dayalı Yetkilendirme: ERP sistemleri, farklı kullanıcı rolleri oluşturarak belirli işlevleri gerçekleştirmek için izinler tanımlar. 
Örneğin, bir satış yöneticisi rolü belirli satış işlemlerini yapma yetkisine sahip olabilirken bir muhasebe görevlisi sadece finansal kayıtlara erişebilir.
- Modül veya İşlev Bazlı Yetkilendirme: ERP sistemi, belirli modüllere veya işlevlere (örneğin; satış, muhasebe, stok yönetimi) özgü yetkilendirme seçenekleri sunar. 
Bu, bir kullanıcının sadece belirli bir modülde veya işlevde çalışmasına izin verir ve diğerlerine olan erişimi kısıtlar.
- Veri Erişim Yetkileri: ERP sistemi, kullanıcıların belirli veri kümelerine (örneğin; müşteri bilgileri, mali veriler, stok kayıtları) erişimi kontrol eder. 
Bu, hassas veya gizli bilgilere sadece yetkili kullanıcıların erişmesini sağlar.
- İşlem Yetkileri: ERP sistemi, kullanıcıların belirli işlemleri gerçekleştirme yetkisini kontrol eder. 
Bu, bir kullanıcının belirli bir işlemi yapabilmesi için gerekli olan yetkilere sahip olmasını sağlar.

Yetkilerin doğru bir şekilde yapılandırılması, güvenlik ve veri bütünlüğünün korunmasına yardımcı olurken aynı zamanda iş süreçlerinin verimli bir şekilde yürütülmesini sağlar. 
Bu nedenle ERP sistemlerinde yetkilendirme ve erişim kontrolleri önemli bir rol oynar ve dikkatle yönetilmelidir.

Yetki listesini açtığınızda, karşınıza kullanıcıların yetkilerini gösteren bir liste çıkar. 
Listenin en üst kısmında yer alan filtreleme özelliği sayesinde, yetki veya kullanıcı aratarak hızlıca filtreleme yapabilir ve yetki açma veya kapatma işlemlerini gerçekleştirebilirsiniz.

## Yeni Yetki Ekleme

**Şirket-Şube:** Bu kartın ait olduğu şirket ve şubeyi belirtir. [Şirket-Şube](../TemelOzellikler/SirketSubeHareket.md)

**Kim İçin:** Bu bölümde, yetkinin kullanıcı bazlı mı yoksa kullanıcı grupları(satış,muhasebe vb.) bazlı mı olacağını ifade eder.

**Kullanıcı:** Yetkilendirme yapacağımız kullanıcıyı ifade eder.

**Kullanıcı Grup:** Yetkilendirme yapacağımız kullanıcı gruplarını(muhasebe, satış, satın alma vb.) ifade eder.

**ProgramID:** Yetkilendirme ismini ifade eder. Örneğin; Cari Borç Alacak Eşleme (Listeler), Stok Kartı (Kartlar) vb. şeklinde açmak istediğiniz yetkileri seçebilirsiniz.

**Okuma:** Belirlenen kullanıcı grubu veya kullanıcıların seçilen program ID'sinin hareket, liste (satış faturaları, cari kartları vb.) görme durumunu ifade eder.

**Ekleme:** Belirlenen kullanıcı grubu veya kullanıcıların seçilen program ID'sine hareket eklemeyi ifade eder.
	Örneğin; Seçilen ProgramID: Satış Faturası(Hareketler) ekleme seçeneği aktif ettiğimiz kullanıcı ya da kullanıcı grupları satış faturası oluşturabilir.

**Silme:** Belirlenen kullanıcı grubu veya kullanıcıların seçilen program ID'sine hareketi veya kartı silmeyi ifade eder.
	Örneğin; Seçilen ProgramID: Satış Faturası(Hareketler) silme seçeneği aktif ettiğimiz kullanıcı ya da kullanıcı grupları satış faturasını silebilir.

**Düzeltme:** Belirlenen kullanıcı grubu veya kullanıcıların seçilen program ID'sine hareketi veya kartı düzeltmeyi ifade eder.
	Örneğin; Seçilen ProgramID: Satış Faturası(Hareketler) düzeltme seçeneği aktif ettiğimiz kullanıcı ya da kullanıcı grupları satış faturasında düzenleme yapabilirler.

**İndirme:** Belirlenen kullanıcı grubu veya kullanıcıların seçilen program ID'sine hareket listesi veya kart listesinin excel dökümü indirmeyi ifade eder.
	Örneğin; Seçilen ProgramID: Satış Faturası(Hareketler) ekleme seçeneği aktif ettiğimiz kullanıcı ya da kullanıcı grupları satış faturası hareketlerini Listeyi Excele Aktar diyerek dökümünü alabilir.

***Kaydet* diyerek yetkileri aktif hale getirilir.**


