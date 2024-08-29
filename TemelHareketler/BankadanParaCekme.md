---
SayfaID: KasaBankadanParaCekme
SayfaTipi: BankaHareketleri
---

# Bankadan Gider Hareketi

**Erişim Linki :** [erp.aaro.com.tr/KasaBankadanParaCekme](erp.aaro.com.tr/KasaBankadanParaCekme)

## Ulaşım

- Sol sekmede Aaro kullanıcı bilgilerinin hemen altındaki arama motorundan 'Banka gider' şeklinde aratarak ulaşım sağlayabilirsiniz.
- Sol sekmede yer alan modüller kısmından *Banka -> Hareket Oluştur -> Bankadan Para Çekme* şeklinde ulaşım sağlayabilirsiniz.

## Tanım

Bankadan para çekme hareketi, bir işletmenin banka hesabından belirli bir tutarda nakit çekerek bu tutarı kasasına veya başka bir ödeme aracı olarak kullanması sürecini ifade eder. 

Bu işlem, işletmenin günlük nakit ihtiyaçlarını karşılamak, çeşitli ödemeleri yapmak veya banka hesabındaki parayı başka amaçlar için kullanmak üzere yapılır.
Banka, belirtilen tutarı işletme hesabından nakit olarak çıkarır ve bu tutar, işletmenin belirlediği kasa hesabına ya da elde edilecek şekilde işletmeye teslim edilir.

İşlem, muhasebe kayıtlarına yansıtılır. Çekilen tutar, banka hesabında bir çıkış ve kasa hesabında bir giriş olarak kaydedilir.
Bankadan para çekme hareketleri, işletmenin nakit akışını düzenlemek ve gerekli nakit ihtiyaçlarını karşılamak için önemli bir işlemdir.

Bu işlem, hem banka hesaplarının hem de kasa hareketlerinin doğru ve düzenli bir şekilde yönetilmesini gerektirir.

### Genel 

**Şirket-Şube:** Bu kartın ait olduğu şirket ve şubeyi belirtir. [Şirket-Şube](../TemelOzellikler/SirketSubeHareket.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir. **Girilmesi Zorunludur.**

**Belge No:** Belge numarasını ifade eder. Otomatik olarak sıradaki numara gelir. İstenilirse seri kullanılabilir.

	## Kasa için;

	- **Kasa** Nakit girişin yapılacağı kasa hesabını belirtir.

	- **Döviz:** Bu işlemin çalıştığı döviz cinsini belirtir.
	
	- **Tutar:** Bankadan çekilecek nakit miktarını belirtir.

	- **Açıklama:** Kasa için ek detaylar burada belirtilebilir. 

	## Banka Hesap için;

	- **Banka Hesap:** Nakit çekiminin yapılacağı banka hesabını belirtir.

	- **Döviz:** Bu işlemin çalıştığı döviz cinsini belirtir.
	
	- **Tutar:** Transfer edilecek nakit miktarını belirtir.

	- **Açıklama:** Banka Hesap için ek detaylar burada belirtilebilir. 

### Detay

**Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir. Proje kullanım detayları için linke tıklayınız.[Proje](../TemelOzellikler/Proje.md)

**Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir. Plasiyer kullanım detayları için linke tıklayınız.[Plasiyer](../TemelOzellikler/Plasiyer.md)

**Tip:** Alt hareket tipini belirtir.

### Açıklamalar

- **Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](../TemelOzellikler/Aciklama.md)

### Etiketler KasaHareketleri

- **Etiketler:** Bu kartı gruplamak ve ileride gruplu rapor alabilmek için kullanılır. [Etiketler](../TemelOzellikler/Etiketler.md)

### Etiketler BankaHareketleri

- **Etiketler:** Bu kartı gruplamak ve ileride gruplu rapor alabilmek için kullanılır. [Etiketler](../TemelOzellikler/Etiketler.md)

 **Kaydet** butonuna tıklayarak belge ve notlar ekleme sayfasına ulaşabilirsiniz. 
Bu sayfada, ilgili işlemle ilgili belgeleri yükleyebilir ve açıklayıcı notlar ekleyebilirsiniz.

## Notlar 

İşleme ait özel notlar belirtebiliriz. 
Önemli bir detay var ise bu detayları burada belirtebiliriz.
Notlar kullanım detayları için linke tıklayınız. [Notlar](../TemelOzellikler/Notlar.md)

## Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlardaki belgeleri buraya yükleyebiliriz.
Buraya işlem esnasındaki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;

- *Daha önce yüklediklerimden seç -> belgeyi seç -> İlişkilendir* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.
- *Yüklenecek belge veya resimleri seç -> belgeyi ya da belgeleri seç -> Yükle* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

## Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akış süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

## Ek İşlemler

 Sayfanın sağ üstünde bulunan alt alta üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- Yevmiye Fiş: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Kasa hareketi işlemini kopyalamak için kullanılır.
- Görev Oluştur: Kasa hareketi için görev oluşturup, kişi atayabiliriz. Açıklama, tarih bitiş, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemimizi gerçekleştirebiliriz.


