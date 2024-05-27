
# Planlama

Planlama işletmenizin belirli bir zaman diliminde hangi ürünleri ne zaman, ne kadar ve hangi kaynaklarla üreteceğinizi planlama sürecidir. 
Üretim faaliyetlerini etkin bir şekilde organize etmeyi ve kaynakların en verimli şekilde kullanılmasını sağlar.
Üretim planlamasının amacı, üretim süreçlerini optimize ederek stok maliyetlerini düşürmek, teslimat sürelerini iyileştirmek, müşteri taleplerini karşılamak ve işletme verimliliğini artırmaktır.
Üretim planlaması, işletmenizin mevcut üretim kapasitesini ve kaynaklarını değerlendirir. 
Makine kapasitesi, işçi sayısı, malzeme stokları ve diğer üretim kaynaklarını içerir.
Üretim planlaması, malzeme ihtiyaçlarını belirlemek için malzeme ihtiyaçları planlaması (MRP) yöntemini kullanır. 
MRP, üretim sürecinin her aşamasında hangi malzemelerin ne zaman ve ne kadar gerektiğini hesaplar.

[İş Emri Ekleme](../Uretim/YeniIsEmri.md) yaparak planlama aşamanıza başlayabilirsiniz. 

# Üretim Planı

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "Üretim Planı" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Kartlar -> İş Emri Listesi -> İş Emrini açınız -> Plan Göster şeklinde ulaşım sağlayabilirsiniz.
- Sol menüden Üretim -> Listeler -> Üretim Planı şeklinde ulaşım sağlayabilirsiniz.

## Tanım 

Üretim planı, bir işletmenin üretim yapacağı ürünleri, kullanılacak hammadde miktarını, üretim sürecinin zamanlamasını ve kaynak dağılımını içeren bir planlama belgesidir. Bu plan, üretim sürecinin verimli bir şekilde yönetilmesini sağlar ve işletmenizin hedeflerine ulaşmasına yardımcı olur.

Burada planlamalarda değişiklik yapmak için sürükleyerek kolayca değişiklik yapabiliriz.

### Toplu Plan Kaydırma

Üretim planlarında esneklik sağlayarak, beklenmedik durumlara hızlıca adapte olmayı mümkün kılar.

**Tarih:** İşlem yapılacak tarihi seçelim.
**Ertelenecek Gün Sayısı:** Üretim planımızı erteleyeceğimiz gün sayısını girelim.
	Örneğin; bugün üretim planımızda koltuk takımı rutin üretimimiz var, acil iş geldi 3 gün içerisinde teslim edilmesi gerekli. 
	Ertelenecek gün sayısına 3 yazıyoruz acil işimiz bittikten sonra üretimimize kaldığımız yerden devam edebiliriz.
**İş Emri:** Ertelenecek olan iş emrini seçelim.
**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)
**Operasyon:** Ertelenecek operasyonu seçelim.
**Makine:** Makineyi seçelim.

### Toplu Makine Değiştir

Toplu Makine Değiştir işlemi, belirli üretim süreçlerinde kullanılan makinelerin toplu olarak değiştirilmesi veya güncellenmesi gereken durumlarda kullanılan bir fonksiyondur. 
Üretim süreçlerinde esneklik ve verimlilik sağlar ve makine arızaları, bakım ihtiyaçları veya kapasite değişiklikleri gibi durumlara hızlı bir şekilde adapte olmayı mümkün kılar.
Üretim hattındaki makinelerin değiştirilmesi gereken yerler ve bu değişikliğin üretim süreçlerine etkisi analiz edebilirsiniz. 
Hangi makinelerin hangi üretim emirlerinde kullanıldığı ve bu değişikliğin ne tür bir etki yaratacağı belirleyebilirsiniz.

**Başlangıç Tarihi:** Makine değişikliğinin başlayacağı tarihi seçelim.
**Operasyon:** Hangi operasyonda makine değişikliği yapılacaksa o operasyonu seçelim.
**Kaynak Makine:** Operasyonda değişim yapacağımız makineyi seçelim.

**Bitiş Tarihi:** Makine değişikliğinin biteceği tarihi seçelim.
**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)
**HedefMakine:** Operasyonda değişim sonrası kullanılacak makineyi seçelim.

### Geçmiş Tarihli Planı Bugüne Taşı 

Geçmiş Tarihli Planı Bugüne Taşı işlemi, planlanmış ancak belirli bir nedenle gerçekleştiremediğimiz üretim faaliyetlerini yeniden planlayarak bugüne alınmasıdır. 
Bu işlem, özellikle üretim süreçlerinde gecikmelerin telafi edebilmemiz ve üretim hedeflerinin zamanında gerçekleştirebilmemiz için önemlidir.
Geçmiş tarihteki üretim emirleri, mevcut üretim planına eklenir. 
İşlerin ne zaman ve hangi sırayla yapılacağı belirlenir. 
Üretim takvimi, mevcut kaynakları en verimli kullanılacak şekilde güncellenir.

**Şirket-Şube:** Hareketin ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeHareket.md)

### Tüm Üretimi Planla

Hazır olan tüm iş emirlerinin otomatik planlamasının yapılmasıdır. 
Alternatif makinelerini değerlendirerek en uygun üretim planını hazırlar.
İşlem yaptığımız gün itibariyle tüm üretimi, teslim tarihi ve önceliklere göre otomatik olarak planlanacaktır.

**Şirket-Şube:** Hareketin ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeHareket.md)
**Plan Başlangıç Tarihi:** Planlamaya hangi gün başlayacaksak tarihini girelim.
**Plan Başlangıç Vardiya:** Plana başladığımızda kaçıncı vardiyada isek o vardiyayı seçelim.
**Alternatif Makineleri Degerlendir:** Bu seçeneği aktif ederek alternatif makineleri değerlendirerek en uygun planlamayı yapar.
**Minimum BirGune Planlanabilecek Miktar:** Bir gün için en düşük ne kadar ürün çıkaracaksak minimum ürünün miktarını girelim.
**Minimum Bir Gune Planlanabilecek Sure Dk:** Bir gün için en az ne kadar sürede planlama yapılmasını istiyorsak minimum süreyi girelim.

Kaydet butonuna basarak planlamamızı gerçekleştirebiliriz.