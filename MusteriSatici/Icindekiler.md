---
SayfaID: CariModulu
SayfaTipi: Modul
---

# Müşteri / Satıcı Modülü

**Erişim Linki :** [erp.aaro.com.tr/CariModulu](https://erp.aaro.com.tr/CariModulu)

Müşteri / Satıcı Modülü, işletmenizin müşteri ilişkilerini yönetmek, satış ve alış süreçlerini izlemek için kullanabilirsiniz. 
Bu modül, müşteri bilgilerini saklamak, alış ve satış işlemlerini takip etmek ve müşteri memnuniyetini artırmak için tasarlanmıştır.

- Müşterilerinizle ilgili temel bilgilerin saklanmasını sağlar. Bu; müşteri adı, iletişim bilgileri, adres bilgileri gibi bilgiler içerir.
- Müşterilerden gelen siparişleri kaydedebilir ve izleyebilirsiniz. Müşteri siparişlerinizi almak, onaylamak ve işleme koymak için kullanılır.
- Müşterilerinize gönderilecek faturaların oluşturulmasını ve yönetilmesini sağlar. Satış işlemlerinizin faturalandırılması ve müşteriye gönderilmesi için kullanılır.
- Müşterilerinizle etkileşimlerinizi izlemek ve yönetmek için kullanılır. Müşteri ile yapılan telefon görüşmeleri, e-posta alışverişleri ve toplantılar gibi etkileşimleri kaydetmek için kullanılır.
- Alış ve Satış verileriyle ilgili detaylı raporlar ve analizler sunar. Bu, işletmenizin alış ve satış performansını değerlendirmesine ve stratejik kararlar almasına yardımcı olur.

## Bu modülde yer alan işlemler;

### Kartlar

- [Müşteri / Satıcı Kartı Listesi](../MusteriSatici/MusteriSaticiKartiListesi.md)
- [Müşteri / Satıcı Kod Ağacı](../MusteriSatici/MusteriSaticiKodAgaci.md)
- [Müşteri / Satıcı Ziyaret Listesi](../MusteriSatici/MusteriSaticiZiyaretListesi.md)

### Listeler

- [Müşteri / Satıcı Hareketleri Listesi](../MusteriSatici/MusteriSaticiHareketleriListesi.md)

### Hareketler

- [Hareket Oluştur](../MusteriSatici/HareketOlustur.md)

### İşlemler 

- [Borç - Alacak Eşleştirme](../MusteriSatici/HareketOlustur.md)

### Raporlar

- Hareket Raporları
    - [Müşteri / Satıcı Ekstre](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri / Satıcı Dövizli Ekstre](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri / Satıcı Malzeme Detaylı Ekstre](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri / Satıcı Malzeme Detaylı Dövizli Ekstre](../MusteriSatici/MusteriSaticiKartiListesi.md)

- Bakiye Raporları
    - [Müşteri / Satıcı Bakiye](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri / Satıcı Bakiye Dövizli](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri / Satıcı Mutabakat Yazısı](../MusteriSatici/MusteriSaticiKartiListesi.md)

- Toplam Raporları
    - [Alış / Satış Analizi](../MusteriSatici/MusteriSaticiKartiListesi.md)
    - [Müşteri Satıcı Hareketleri Tutar Toplamları (Tarihe göre Gruplu)](../MusteriSatici/MusteriSaticiKartiListesi.md)


### Parametreler

- Cari Parametreleri
    - Genel_CariKartKoduOtomatikUzunluk (Genel): Müşteri/Satıcı Kartların kodunun otomatik kaç hane olacağını belirtir. Ön Değeri:15
    - Cari_CRMSorumulusu (Müşteri/Satıcı Kartı): CRM (Müşteri İlişkileri Yönetimi) Sorumlusu , cari ziyaret vb. kayıtlar için verilen görevlerden sorumlu yöneticidir.
    - Cari_StandarVergiDairesi (Vergi Dairesi): Rehberden Hızlı Kayıt yapabilmek için kullanılacak olan standart vergi dairesidir.Tüm hızlı cari kayıtlarınızda bu vergi dairesi kullanılacaktır.
    - Cari_StandartMuhasebeBorc (Müşteri/Satıcı Kartı): Rehber Seçeneklerinden hizli cari kaydı yapabilmek için standart muhasebe borç kodunuzu belirleyiniz.Tüm hızlı cari kayıtlarında bu kod kullanılacaktır.
    - Cari_StandartMuhasebeAlacak (Müşteri/Satıcı Kartı): Rehber Seçeneklerinden hızlı cari kaydı yapabilmek için standart muhasebe alacak kodunuzu belirleyiniz.Tüm hızlı cari kayıtlarında bu kod kullanılacaktır.
    - Cari_StandartTip (Müşteri/Satıcı Kartı): Hızlı cari kaydı için standart olarak bir tip girmeniz gerekmektedir.Hızlı kayıt işlemlerinde bu cari tipi kullanılacaktır. || Musteri=102001 - Satici=102002 - Karaliste=102003 - Potansiyel=102004 - Personel=102005 - Kamu=102006 - Ortak=102007 ||

- Risk Limitleri Parametreleri
    - CariRisk_Calissin (Müşteri/Satıcı Risk Limitleri): Cari Risk kontrol Sisteminin çalışıp çalışmayacağını belirler.
    - CariRiskLimitiUyariOrani (Müşteri/Satıcı Risk Limitleri): Hareket kaydı esnasında carinin risk limitinin % x'i dolduğunda kullanıcıyı uyarması içindir.
    - CariRiskBakiyeliSistem (Müşteri/Satıcı Risk Limitleri): Bakiyeli kontrol yapılır. AçıkHesap, KendiSenedi, MüsteriSenedi, KendiÇeki, MüşteriÇeki olarak sıralıdır. Sıradan toplanarak işlem yapılır.Ör:Müşteri senedi kontrol edilirken Açıkhesap ve Kendisenedi mevcutları ve limitleri değerlendirilir.
    - CariRiskBelgeBasinaRiskEsnemeOrani (Müşteri/Satıcı Risk Limitleri): Kayıt işlemi yapılan belge için risk limiti hesaplaması yapılırken tanımlanan bu oran kadar fazladan risk tanımlaması varmış gibi davranır. Örn: Belge Tutarı 50 kalan risk limiti 75 olsun risk limiti 75+(50*1/100) olur
    
- Tasarım Parametreleri
    - Tasarim_CariDetay (Genel): Hareketlerde ve Müşteri/Satıcı kartlarında cari detayı aktif eder.
    - Tasarim_CariKod1Baslik (Kod): Cari sayfalarında Kod 1 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 1 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariKod2Baslik (Kod): Cari sayfalarında Kod 2 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 12başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariKod3Baslik (Kod): Cari sayfalarında Kod 3 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 3 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariKod4Baslik (Kod): Cari sayfalarında Kod 4 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 4 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariKod5Baslik (Kod): Cari sayfalarında Kod 5 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 5 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariKod6Baslik (Kod): Cari sayfalarında Kod 6 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, stok sayfalarında Kod 6 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariEtiket1Baslik (Etiket): Cari sayfalarında Etiket 1 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, cari sayfalarında Etiket 2 başlığı yerine Ünvan başlığı gelir.'
    - Tasarim_CariEtiket2Baslik (Etiket): Cari sayfalarında Etiket 2 için istenilen label yazısını ayarlar. Örn: 'Ünvan olarak girilirse, cari sayfalarında Etiket 2 başlığı yerine Ünvan başlığı gelir.'

### İlişkili Modüller
