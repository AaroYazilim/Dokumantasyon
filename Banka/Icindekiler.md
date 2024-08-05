---
SayfaID: BankaModulu
SayfaTipi: Modul
---

# Banka Modülü

**Erişim Linki :** [erp.aaro.com.tr/BankaModulu](erp.aaro.com.tr/BankaModulu)

Bu modül, işletmelerin banka hesaplarını yönetmek için gereken çeşitli işlevleri sağlar. 

- İşletmenizin sahip olduğu banka hesaplarını kaydedebilir ve izleyebilirsiniz. Bu, işletmenizin farklı bankalardaki hesaplarınızı tek bir yerden yönetmenize olanak tanır.
- Banka hesaplarıyla yapılan tüm finansal işlemlerinizi izleyebilir. Bu işlemler, para yatırma, para çekme, havale, EFT gibi işlemleri içerir.
- Banka hesaplarında gerçekleşen işlemlerinizi ERP sistemiyle uyumlu hale getirerek hesaplar arası tutarların doğrulanmasını ve uyumun sağlanmasını kolaylaştırır.
- Tekrarlayan banka işlemlerini düzenli bir şekilde kontrol ve takibini sağlayabilirsiniz. Düzenli fatura ödemeleri veya otomatik ödemeleriniz gibi işlemlerinizi bu şekilde yönetilebilirsiniz.
- İşletmenizin banka hesaplarının anlık durumunu ve geçmiş hareketlerini gösteren raporlar sunar. Bu raporlar, işletmenizin finansal durumunu takip edebilmenize ve gerektiğinde kararlar almanıza yardımcı olur.

Banka hesap modülü, işletmelerin finansal yönetimini kolaylaştırmak ve etkinleştirmek için önemli bir araçtır. 
Bu modülden, işletmenizin nakit akışını, hesap hareketlerinizi ve banka ilişkilerinizi daha etkili bir şekilde yönetebilirsiniz.

## Bu modülde yer alan işlemler;

### Kartlar

- [Banka Hesap Kartı Listesi](../Banka/BankaHesapListesi.md)
- [Pos Hesaba Geçiş Tanımı Listesi](../Banka/PosHesabaGecisTanimiListesi.md)

### Listeler

- [Banka Hareketleri Listesi](../Banka/BankaHareketleriListesi.md)

### Hareketler

- [Hareket Oluştur](../Banka/HareketOlustur.md)

### İşlemler

- [Banka Hesap Kartı](../Banka/BankaHesapKarti.md)

### Raporlar

- Hareket Raporları
	- Banka Ekstre
	- Banka Ekstre Detaylı
	- Banka Ekstre Dövizli
	- Banka Hareketleri (Açıklamalar)
	- Banka Hareketleri Pos Detaylı
	- Kredi Pos Hareketleri

- Kart Listeleri Raporları
	- Banka Hesap Kartları
	- Banka Hesap Kartları Etiketler
	- Banka Hesap Kartları Kodlar
	- Kredi Pos Kartları 
	- Kredi Pos Kartları Komisyonları
	- Kredi Pos Koşul Tanımları

- Toplam Raporları
	- Banka Gün Bazında Kümülatif Bakiye
	- Banka Gün Bazında Kümülatif Bakiye (Grafik)
	- Banka Hareketleri Tutar Toplamları (Tarihe Göre Gruplu)
	- Banka Hesapları Gün Sonu Toplamları
	- Banka Hesapları Gün Sonu Toplamları
	- Banka Hesapları Gün Sonu Toplamları
	- Banka Hesapları Toplamları
	- Banka Hesapları Toplamları (Gruplu)
	- Pos Toplam Raporu (Tarih)
	- Pos Toplam Raporu (Vade)

### Parametreler

- Banka Hesap Parametleri 
	- BankaHesap_StandartTip: Banka hesap rehberinden hizli kayit yapabilmek için standart olarak kullanılacak banka hesap tipini belirtir.Tipler Cari = 108001,TahSenet = 108002,TahCek = 108003,Pos = 108004
	- BankaHesap_StandartBankaSube: Banka hesap rehberinden hizli kayit yapabilmek için standart olarak kullanılacak banka şubeyi belirtir.Seçimden sonra tüm hızlı kayıtları belirtilen banka şubeye atacaktır.
	- BankaHesap_StandartDoviz: Banka hesap rehberinden hizli kayit yapabilmek için standart olarak kullanılacak dövizi belirtir.Seçimden sonra tüm hızlı kayıtları belirtilen dövizde kaydedilecektir.
	- BankaHesap_StandartMuhasebeBorc: Rehber Seçeneklerinden hizli banka hesap kayıdı yapabilmek için standart muhasebe borc kodunuzu belirleyiniz.Tüm hızlı cari kayıtlarında bu kod kullanılacaktır.
	- BankaHesap_StandartMuhasebeAlacak: Rehber Seçeneklerinden hizli banka hesap kayıdı yapabilmek için standart muhasebe alacak kodunuzu belirleyiniz.Tüm hızlı cari kayıtlarında bu kod kullanılacaktır.
	- Genel_BankaKartKoduOtomatikUzunluk (Genel): Banka Hesap Kartların kodunun otomatik kaç hane olacağını belirtir. Ön Değeri:15
	- BankaHesap_RapordaYerAlacakHesapNumarasi (Banka Hesap Kartı): Şubelerin merkez şirketten farklı olarak raporlarda gözükmesini istediği banka hesap numarasıdır.

- Tasarım Parametreleri 
	- Tasarim_BankaHesapYedekD1Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Sayısal 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_BankaHesapYedekD2Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Sayısal 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_BankaHesapYedekD3Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Sayısal 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_BankaHesapYedekS1Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Metin 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_BankaHesapYedekS2Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Metin 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_BankaHesapYedekS3Baslik (Banka Hesap Kartı): BankaHesap sayfalarında Ek Metin 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.

- Muhasebeleşme Parametreleri
	- Muhasebelesme_BankaHesapBorcMuhKodu: Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Banka Hesap Borç için ön değeri 102'dir.
	- Muhasebelesme_BankaHesapAlacakMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Banka Hesap Alacak için ön değeri 102'dir.
	- Muhasebelesme_BankaHesapTahsildekiCekMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Banka Hesap Tahsildeki Çek için ön değeri 101'dir.
	- Muhasebelesme_BankaHesapTahsildekiSenetMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Banka Hesap Tahsildeki Senet için ön değeri 121'dir.
	- Muhasebelesme_BankaHesapOtomatikYeniAc (Muhasebeleşme Kartları): Yeni BankaHesap Kartı açılırken otomatik Yeni Muhesebeleşme Kartımı yapılsın yoksa mevcut Muhesebeleşme Kartlarından mı seçsin onu belirtir.
	- Muhasebelesme_BankaHesapStandart (Muhasebeleşme Kartları): Yeni Banka Kartı açılırken otomatik hangi Muhesebeleşme Kartı ile eşleştirilecegini belirtir. 'OtomatikYeniAc' parametresi 'Hayır' secildi ise çalışır.


### İlişkili Modüller



