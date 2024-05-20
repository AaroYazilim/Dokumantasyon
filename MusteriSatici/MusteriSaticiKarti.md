
# Müşteri/Satıcı Kartı

### Ulaşım

- Sol menüden Aaro kullanıcı bilgilerinin hemen altında yer alan arama motorundan "müşteri satıcı kartı" aratarak ulaşım sağlayabilirsiniz.
- Sol menüden Musteri/Satici -> Modül Sayfası -> Yeni Musteri/Satici Kartı şeklinde ulaşım sağlayabilirsiniz.
- Sol menüden Musteri/Satici -> Kartlar -> Müşteri/Satıcı Kartı Listesi üzerinden ulaşım sağlayarak yeni kart ekleyebilir yada mevcutları düzenleyebilirsiniz.

### Tanım

Müşteri/Satıcı kartı, işletmenizin müşteri, satıcı, personel, kamu ve ortaklarla olan ilişkilerini yönetmek için kullanılacağı bir karttır. 
Bu kişiler hakkında genel bilgileri içerir ve işletmenin onlarla olan etkileşimlerini, ziyaretlerinizi, borç/alacak takibi gibi işlemleri izlemeyi sağlar.
Aşağıdaki bilgiler doldurularak müşteri/satıcı kartınızı tanımlayabilirsiniz.

### Genel

**Adı:** Bu kartın kendine özel adıdır.

**Kodu:** Bu kartın kendine özel kodudur.Seri takibi yapılabilir. Detaylı tanım için linke tıklayınız. [Kart Kodu](../TemelOzellikler/KartKodu.md)

**Tip:** Müşteri/Satıcı kartının tipini belirtir. Müşteri, satıcı, karaliste, potansiyel, personel, kamu veya ortak değerlerinden biri olabilir.

**Vergi Dairesi:** Bu carinin vergi dairesini belirtir.Şahıslar için 'TC' giriniz.**Girilmesi Zorunludur.**

**Vergi No:** Tüzel kişiler için vergi numarasını, Gerçek kişiler için TC numarasını belirtir. **Girilmesi Zorunludur.**
	Sistem mükerrer vergi no girişini otomatik olarak engellemektedir. Yani aynı vergi numarası ile birden çok Müşteri/Satıcı kartı açıulması engellenmektedir.
	Aynı vergi numarası ile birden çok kart açılması ek yetkilerle ayarlanabilmektedir. Belirli kullanıcılara yetki vererek onların mükerrer vergi no ile kart açmalarına izin verebilirsiniz.
	[Yetkiler](../TemelOzellikler/Yetkiler.md)

**Kodlar:** Kartları hiyerarşik olarak gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Kodlar](../TemelOzellikler/Kodlar.md)

**Etiketler:** Gruplamak için kullanılır. Detaylı tanım için linke tıklayınız. [Etiketler](../TemelOzellikler/Etiketler.md)


### Adres Bilgileri

#### Müşteri Satıcı kartına bir veya daha fazla adres bilgisi ekleyebilirsiniz.

> Hareketlerde farklı adreslere sevk için karta tanımlı olan adres bilgilerini kullanabilirsiniz.

**Adres Adı:** Adres bilgisini adlandırabilirsiniz. Örn: Merkez, Şube vs.

**İlçe:** Karta ait adres bilgisinin ilçesini ifade eder.

**Sokak Adı:** Karta ait adresin sokak adını ifade eder.

**Bina Adı:** Karta ait adresin bina adını ifade eder.

**Bina No:** Karta ait bina numarasını ifade eder.

**Kapı No:** Karta ait adres bilgisinin kapı numarasını ifade eder.

**Posta Kodu:** Karta ait adresin posta kodunu belirtir.

**Telefon:** Karta ait telefon numarasını ifade eder.

**Fax:** Karta ait fax numarasını ifade eder.

**Email:** Karta ait mail adresini ifade eder.

**Web:** Karta ait web adresini ifade eder.

**Öncelik:** Öncelik belirterek belirli bir adrsin ön tanımlı olarak kullanılmasını sağlayabilirsiniz.


### İlgili Bilgileri

#### Müşteri Satıcı kartına bir veya daha fazla ilgili bilgisi ekleyebilirsiniz.

**İlgili Adı:** Bu karta ait ilgili kişinin adını ifade eder.

**Telefon:** Bu karta ait ilgili kişinin telefon numarasını ifade eder.

**Fax:** Bu karta ait ilgili kişinin fax numarasını ifade eder.

**Email:** Bu karta ait ilgili kişinin mail adresini ifade eder.

**Not 1:** İlgili kişiye ait notları ifade eder.

**Not 2:** İlgili kişiye ait notları ifade eder.

**Doğum:** İlgili kişiye ait doğum tarihini ifade eder.

**Ünvan:** İlgili kişiye ait ünvanı ifade eder.


### Banka Hesapları

#### Müşteri Satıcı kartına bir veya daha fazla banka hesap bilgisi ekleyebilirsiniz.

**Iban No:** Cari kartının banka hesap iban bilgilerini belirtir. Iban nosunu kaydederek Havale/Eft gönderme işlemlerinde kolayca kullanabilirsiniz.

**Banka Şube:** Cari kartının banka hesap şube bilgilerini belirtir.


### Risk Limitleri: 

Müşteri/Satıcı kartına risk limitleri tanımlayarak ve gerekli parametreleri aktive ederek, risk yönetim sistemini kullanabilirsiniz.
[Risk Limitleri](../TemelOzellikler/RisLimitleri.md)
[Parametreler](../TemelOzellikler/Parametreler.md)

### Muhasebe Tanımları: 

Muhasebeleşme tanımlarını ayarlayarak bu kart için hareket işlendiğinde otomatikman belirli muhasebe hesaplarına gerekli kayıtların oluşmasını sağlayabilirsiniz.
[Muhasebeleşme Tanımları](../TemelOzellikler/MuhasebelesmeTanimlari.md)

### Gelişmiş

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-Şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Durum:** Kartın kullanabilirliğini belirtir. Pasif kartlar işlemde kullanılamaz.

**Çalışma Para Birimi:** Bu kartın çalıştığı döviz cinsini belirtir. Bilgi amaçlıdır.

**Vade:** Bu carinin çalışma vadesidir. Hareketler oluşturulurken otomatik olarak belirtilen vade getirilir. Detaylı tanım için linke tıklayınız. [Vade](../TemelOzellikler/CariVade.md)

**Fiyat Grup:** Carinin hangi fiyat listesinden % kaç iskonto alacağını belirten fiyat grubudur. Detaylı tanım için linke tıklayınız. [Fiyat Grup](../EkOzellikler/FiyatGrup.md)

**Plasiyer:** Hareketin hangi plasiyere (kullanıcıya) ait olduğunu belirtir. Kalemlerde değiştirilir.

**Muhtelif Cari:** Sadece muhtelif kart açılacağı zaman kullanılmalıdır. Kartın herhangi bir cariye ait olmadığını ortak hesap olduğunu belirtir. Detaylı tanım için linke tıklayınız. [Muhtelif Cari](../EkOzellikler/MuhtelifCari.md)

**Görüntülenme:** Kartın ve hareketlerinin hangi kullanıcılar tarafından görüntülenebileceğinin ayarlanması için kullanılır. Detaylı tanım için linke tıklayınız. [Görüntülenme](../EkOzellikler/Goruntulenme.md)


Doldurulması gereken alanlar girildikten sonra sağ alt köşede bulunan Kaydet butonuna tıklayarak Müşteri/Satıcı kartı açma işlemimizi tamamlayabilirsiniz.