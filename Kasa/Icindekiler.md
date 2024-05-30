---
SayfaID: KasaModulu
SayfaTipi: Modul
---

# Kasa Modülü

**Erişim Linki :** [erp.aaro.com.tr/KasaModulu](erp.aaro.com.tr/KasaModulu)

Bu kısımda; Kasadan gerçekleşen her işlem için bu kısmı kullanmamız gerekmektedir. 
Kasa ile ilgili kartları bu modül aracılığıyla ekleyebilir ve düzenleyebiliriz.
Tahsilatlar, transferler, giriş, çıkışlar bütün hareketleri işlemleri işleyeceğimiz yerdir. 
Düzenli tutmamız hareket takibi yapabilmemiz için çok önemlidir.

- İşletmenizin kasa hesabına yapılan nakit giriş ve çıkış işlemlerinizi kaydedebilirsiniz. Bu, nakit satışlar, nakit ödemeler, nakit tahsilatlar gibi işlemleri içerir.
- Kasa hesabınızdaki tüm işlemleri izleyebilir ve kaydedebilirsiniz. Bu, herhangi bir zamanda kasanın ne kadar nakit varlığa sahip olduğunu görmeyi kolaylaştırır.
- Müşterilerinizden alınan nakit ödemeleri veya tedarikçilere yapılan nakit ödemeleri yönetebilirsiniz. Bu işlemler genellikle fatura ödemeleri, tedarik ödemeleri, personel maaşları gibi nakit çıkışlarını içerir.
- Kasa hesabınızın fiziksel olarak var olan nakit miktarıyla sisteminizdeki kayıtlı nakit miktarı arasındaki uyumu sağlar. Bu, kasa hesabınızın doğruluğunu ve güvenilirliğini korur.
- Kasa hesabı ile ilgili detaylı raporlar sunar. Bu raporlar, kasa hareketlerinizi, nakit giriş ve çıkışlarınızı, günlük veya aylık nakit durumunuzu gösterir.

## Bu modülde yer alan işlemler;

### Kartlar

- [Kasa Kartı](../Kasa/KasaKarti.md)
- [Kasa Kartı Listesi](../Kasa/KasaKatiListesi.md)

### Listeler 

- [Kasa Hareketleri Listesi](../Kasa/KasaHareketleriListesi.md)

### Hareketler 

- [Hareket Oluştur](../Banka/HareketOlustur.md)

### İşlemler 

............

### Raporlar

- Hareket Raporları
	- Kasa Detaylı Ekstre	
	- Kasa Dövizli Ekstre
	- Kasa Ekstre
	- Kasa Ekstre (KasaDefteri)
	- Kasa Hareketleri (Açıklamalar)

- Kart Listeleri Raporları
	- Kasa Kartları Etiket Listesi
	- Kasa Kartları Kod Listesi
	- Kasa Kartları Listesi

- Toplam Raporları
	- Kasa Toplam Raporu

### Parametreler

- Kasa Parametreleri
	- Genel_KasaKartKoduOtomatikUzunluk (Genel): Kasa Kartların kodunun otomatik kaç hane olacağını belirtir. Ön Değeri:15

- Tasarım Parametreleri
	- Tasarim_KasaYedekD1Baslik (Kasa Kartı): Kasa sayfalarında Ek Sayısal 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_KasaYedekD2Baslik (Kasa Kartı): Kasa sayfalarında Ek Sayısal 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_KasaYedekD3Baslik (Kasa Kartı): Kasa sayfalarında Ek Sayısal 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_KasaYedekS1Baslik (Kasa Kartı): Kasa sayfalarında Ek Metin 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_KasaYedekS2Baslik (Kasa Kartı): Kasa sayfalarında Ek Metin 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_KasaYedekS3Baslik (Kasa Kartı): Kasa sayfalarında Ek Metin 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.

- Muhasebeleşme Parametreleri
	- Muhasebelesme_KasaBorcMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Kasa Borç için ön değeri 100'dür.
	- Muhasebelesme_KasaAlacakMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Kasa Alacak için ön değeri 100'dür.
	- Muhasebelesme_KasaOtomatikYeniAc (Muhasebeleşme Kartları): Yeni Kasa Kartı açılırken otomatik Yeni Muhesebeleşme Kartımı yapılsın yoksa mevcut Muhesebeleşme Kartlarından mı seçsin onu belirtir.
	- Muhasebelesme_KasaStandart (Muhasebeleşme Kartları): Yeni Kasa Kartı açılırken otomatik hangi Muhesebeleşme Kartı ile eşleştirilecegini belirtir. 'OtomatikYeniAc' parametresi 'Hayır' secildi ise çalışır.