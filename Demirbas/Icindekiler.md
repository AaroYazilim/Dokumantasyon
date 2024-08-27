---
SayfaID: DemirbasModulu
SayfaTipi: Modul
---

# Demirbaş Modülü

**Erişim Linki :** [erp.aaro.com.tr/DemirbasModulu](erp.aaro.com.tr/DemirbasModulu)

Bir işletmenin sahip olduğu sabit kıymetlerin (demirbaşların) kayıt altına alındığı ve izlendiği bir muhasebe sürecidir. 
Demirbaşlar, genellikle uzun süreli kullanım için satın alınan ve işletmenin faaliyetlerini sürdürmek için gerekli olan varlıklardır. 
Ofis mobilyaları, bilgisayar ekipmanları, araçlar, makinalar gibi ögeler demirbaşlar arasında yer alabilir.

- İşletmenizin sahip olduğu sabit varlıkların (demirbaşların) detaylı kayıtlarını tutar. Bu kayıtlar genellikle demirbaşın adı, kodu, türü, satın alma tarihi, maliyeti, yerleştirildiği departman veya birim gibi bilgileri içerir.
- Demirbaşların amortisman süreçlerini yönetir. Bu, demirbaşların amortisman planlarını oluşturma, amortisman giderlerini hesaplama ve ilgili muhasebe kayıtlarını otomatik olarak güncelleme işlemlerini içerir.
- Demirbaşların transferi, tahsisi veya hurda edilmesi gibi tüm hareketlerin izlenmesini sağlar. Bu, demirbaşların hangi departman veya birimde olduğunu takip etmeyi kolaylaştırır.
- Demirbaşların bakımı ve onarımıyla ilgili işlemlerinizi yönetir. Periyodik bakım planları oluşturabilir, bakım masraflarını izleyebilir ve bakım geçmişini kaydedebilirsiniz.
- Demirbaşlarla ilgili detaylı raporlar ve analizler sunar. Bu raporlar, işletmenin demirbaş varlıklarının durumunu değerlendirmenize ve gerektiğinde stratejik kararlar almanıza yardımcı olur.

Demirbaş modülü, işletmenizin sabit varlıklarını etkin bir şekilde yönetmenize ve izlemenize yardımcı olur. 
Bu modül sayesinde, demirbaşların satın alınmasından bakımına kadar olan süreçlerini izleyebilir aynı zamanda varlık değerlerinin korunmasını ve optimize edilmesini sağlayabilirsiniz.

## Bu modülde yer alan işlemler;

### Kartlar

- [Demirbaş Kartı](../Demirbas/DemirbasKarti.md)
- [Demirbaş Kartı Listesi](../Demirbas/DemirbasKartiListesi.md)
- [Demirbaş Kod Ağacı](../Demirbas/DemirbasKartiListesi.md)

### Listeler 

- [Demirbaş Hareketleri Listesi](../Demirbas/DemirbasHareketleriListesi.md)

### Hareketler

- [Hareket Oluştur](../Banka/HareketOlustur.md)

### İşlemler

...........

### Raporlar

- ...
	- DemirbaşHareketListesi Gruplu

### Parametreler

- Demirbaş Parametreleri
	- Demirbas_EksiBakiyeKontrolu (Demirbaş): Demirbaş bakiyelerinin eksiye düşemeyeceğini tanımlar.
	- eFatura_GelenEFaturaOtomatikGelirGiderDemirbasID (E-Fatura): Gelen e-faturalarda zorunlu demirbaş olan kalemlerde geçici olarak kaydedilecek olan demirbaş kartını tanımlar.

- Tasarım Parametreleri
	- Tasarim_DemirbasYedekD1Baslik (Demirbaş): Demirbaş sayfalarında Ek Sayısal 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_DemirbasYedekD2Baslik (Demirbaş): Demirbaş sayfalarında Ek Sayısal 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_DemirbasYedekD3Baslik (Demirbaş): Demirbaş sayfalarında Ek Sayısal 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_DemirbasYedekS1Baslik (Demirbaş): Demirbaş sayfalarında Ek Metin 1 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_DemirbasYedekS2Baslik (Demirbaş): Demirbaş sayfalarında Ek Metin 2 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.
	- Tasarim_DemirbasYedekS3Baslik (Demirbaş): Demirbaş sayfalarında Ek Metin 3 için istenilen label yazısını ayarlar. 0 olarak girilirse, ekranda gözükmez.

- Muhasebeleşme Parametreleri 
	- Muhasebelesme_DemirbasAlisMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Alış Harekeketleri için ön değeri 255'dir.
	- Muhasebelesme_DemirbasSatisMuhKodu (Muhasebeleşme Kartları): Hesap planında hangi ana hesabın altına otomatik olarak hesap açılacağını tanımlar. Satış Harekeketleri için ön değeri 255'dir.
	- Muhasebelesme_DemirbasOtomatikYeniAc (Muhasebeleşme Kartları): Yeni Demirbaş Kartı açılırken otomatik Yeni Muhesebeleşme Kartı mı yapılsın yoksa mevcut Muhesebeleşme Kartlarından mı seçsini belirtir.
	- Muhasebelesme_DemirbasStandart (Muhasebeleşme Kartları): Yeni Demirbaş Kartı açılırken otomatik hangi Muhesebeleşme Kartı ile eşleştirileceğini belirtir. 'OtomatikYeniAc' parametresi 'Hayır' seçildi ise çalışır.
