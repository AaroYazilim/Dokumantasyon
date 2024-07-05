---
SayfaID: SatisIadeFaturasi
SayfaTipi: Fatura
---

# Sat�� �ade Faturas�

**Eri�im Linki :** [erp.aaro.com.tr/FaturaSatisIadeFaturasi](erp.aaro.com.tr/FaturaSatisIadeFaturasi)

### Ula��m

- Sol sekmede Aaro kullan�c� bilgilerinin hemen alt�nda yer alan arama motorundan "sat�� iade" aratarak ula��m sa�layabilirsiniz.
- Sol men�den Musteri/Satici -> Hareket Olu�tur -> Sat�� �ade Faturas� �eklinde ula��m sa�layabilirsiniz. 
- Sol men�den Sat�� & Pazarlama -> Listeler -> Sat�� �ade Faturas� Listesi -> Yeni Hareket Ekle �zerinden ula��m sa�layabilirsiniz. 

## Tan�m 

Sat�� iade faturas�, m��terinin sat�n ald��� mal veya hizmeti geri iade etmesi durumunda d�zenlenen bir faturad�r. 
Bu fatura, iade edilen �r�n veya hizmetin bedelinin m��teriye geri �denmesi veya borcunun d���lmesi i�in kullan�l�r. 
�adenin nedeni (�rne�in, �r�n�n kusurlu olmas�, yanl�� �r�n g�nderimi, m��teri memnuniyetsizli�i vb.) fatura �zerinde a��klanmal�d�r.
Sat�� iade faturas� d�zenlemek, muhasebe kay�tlar�n�n d�zg�n tutulmas� ve yasal gerekliliklerin yerine getirilmesi a��s�ndan �nemlidir.

## Genel

**�irket-�ube:** Kart�n ait oldu�u �irket ve �ubeyi belirtir. �irket-�ube kullan�m detaylar� i�in linke t�klay�n�z. [�irket-�ube](../TemelOzellikler/SirketSubeKart.md)

**Tarih:** ��lemin yap�ld��� tarihi belirtir. 

**Belge No:** Belge numaras�n� ifade eder. Otomatik s�radaki numara gelir. �stenirse seri kullan�labilir.

**M��teri:** ��lemin yap�ld���n� cari kart�n� ifade eder. 

**D�viz:** Bu banka hesab�n�n �al��t��� d�viz cinsini belirtir.T�rk liras� haricinde ba�ka bir d�viz se�ildi�inde sadece o d�viz cinsinden hareket i�lenmesine izin verir. 
Banka hesab�n�n bakiyesi se�ilen d�viz cinsinden takip edilir.

**Depo:** Bu i�lemin kulland��� depoyu belirtir.

**Vade** ��lemin yap�ld��� vadeyi belirtir. Cari ile ilgili i�lem yap�ld���nda otomatik buradaki vade gelecektir.
	Ay sonu se�ene�i belirtilen g�nden sonraki ay sonuna al�r. 0 ise ay�n sonuna al�r. Vade ile ilgili detayl� [Vade](../TemelOzellikler/Vade.md)

**A��klama** ��leme ait a��klamay� belirtir. A��klama kullan�m detaylar� i�in linke t�klay�n�z.[A��klama](../TemelOzellikler/Aciklama.md)

**KDV Dahil** Kalemlerde birim fiyat ve tutar�n 'KDV Dahil' oldu�unu belirtir. KDV dahil kullan�m detaylar� i�in linke t�klay�n�z.[KDV Dahil](../TemelOzellikler/KDVdahil.md)

## Detay

**Beklenen Tahsilatlar ve �demeler** Bir i�letmenin, belirli bir zaman dilimi i�inde m��terilerinden almay� bekledi�i �demelerdir. 
	Bu, genellikle sat��lardan kaynaklanan alacaklar� ve di�er gelir kalemlerini i�erir. Beklenen Tahsilatlar ve �demeler kullan�m detaylar� i�in linke t�klay�n�z. [Beklenen Tahsilatlar ve �demeler](../TemelOzellikler/BeklenenTahOd.md)

**Cari Detay:**

**Alt Tip:** Alt hareket tipini belirtir.

**S�zle�me:** Bu hareketin hangi s�zle�meye ait oldu�unu g�sterir. S�zle�me kullan�m detaylar� i�in linke t�klay�n�z.[S�zle�me](../TemelOzellikler/Sozlesme.md)

**Proje:** Bu hareketin hangi projeye ait oldu�unu belirtir. Kalemlerde de�i�tirilebilir. Proje kullan�m detaylar� i�in linke t�klay�n�z.[Proje](../TemelOzellikler/Proje.md)

**Plasiyer:** Bu hareketin hangi plasiyere ait oldu�unu belirtir. Kalemlerde de�i�tirilebilir. Plasiyer kullan�m detaylar� i�in linke t�klay�n�z.[Plasiyer](../TemelOzellikler/Plasiyer.md)

**Cari Adres:** Girilen carinin birden �ok adresi varsa ve farkl� adrese g�nderilecekse se�ilmelidir. Carinin adresini belirtir. Kalemlerde de�i�tirilebilir.

**Ref. �thalat �hracat:** Bu hareket bir ithalat ya da ihracata ait oldu�unu belirtir. Kalemlerde de�i�tirilebilir.

### A��klamalar

- **A��klamalar:** Ek a��klamalar� belirtir. �ade nedeni burada belirtilebilir. [A��klama](/TemelOzellikler/Aciklama.md "A��klama")	

### Etiketler

- **Etiketler:** Bu kart� gruplamak ve ileride gruplu rapor alabilmek i�in kullan�l�r. [Etiketler](/TemelOzellikler/Etiketler.md "Etiketler")

## Doldurmam�z gereken bilgileri doldurduktan sonra kaydet butonuna basarak bir sonraki kalem ekleme a�amam�za ge�ebiliriz.

- A��lan ekranda kalem(kart) ekleme alan�m�z a��lacakt�r. 
- Sat�� iade faturam�zda iade edilen stok, gelir gider, demirba� olabilir. En ba�ta ki kutucuktan se�im yap�labilir, sistem otomatik stok olarak getirir.
- Kart Ad�: Stok, demirba� ya da gelir gider sat���n� ger�ekle�tirece�imiz kart� belirtir.
- Miktar: �ade yap�lan �r�n�n stok miktar�n� belirtir, bu alan�n doldurdurulmas� gerekmektedir.
- Br�t Fiyat: Bir �r�n veya hizmetin vergiler ve ek �cretler dahil toplam sat�� fiyat�n� belirtir. 
	Buraya t�klayarak yeni fiyat eklenebilir, son 3 ay i�in al�� ve sat�� ortalama fiyatlar�n� g�sterir.
- �skonto: Sat���n� yapt���m�z i�lemlerin iskonto oran�n� belirtir. Uygulad���m�z iskonto var ise buraya oran� girebiliriz.
- Net Fiyat: Bir �r�n veya hizmetin vergiler ve ek �cretler hari�, sadece temel maliyetini ifade eden fiyat� belirtir. 
	Buraya t�klayarak yeni fiyat eklenebilir, son 3 ay i�in al�� ve sat�� ortalama fiyatlar�n� g�sterir.
- Tutar: Bir mal veya hizmetin toplam mali de�erini ifade eden miktar� belirtir. 
- KDV oran: KDV oran�n� ifade eder.
- Depo: Bu kalemin kulland��� depoyu belirtir.
- A��klama: Kaleme ait a��klamay� belirtir.
- Proje: Bu kalemin hangi projeye ait oldu�unu belirtir.
- S�zle�me: Bu kalemin hangi s�zle�meye ait oldu�unu g�sterir.
- Proje: Bu kalemin hangi projeye ait oldu�unu belirtir.

- Sat�� iade faturas�nda 1 kalem belirtilecekse kaydet diyerek bir sonraki a�amaya ge�ebiliriz.
- Ba�ka kalemlerde mevcut ise yukar�da a�amalar� tekrar ederek yeni kalemleri ekleyebilirsiniz.

- Sa� �st k��ede faturaya ait toplam fiyat k�s�mlar�n� i�erir;
	- Toplam: Sat�� iade faturas�n�n KDV hari� toplam tutar�n� i�erir.
	- �skonto Sonras�: Sat�� iade faturas�n�n KDV dahil fiyat�ndan uygulanan iskonto tutar�n� ifade eder.
	- KDV: Sat�� iade faturas�n�n KDV oran�n�n kar��l�k geldi�i tutar� ifade eder.
	- Genel Toplam: Sat�� iade faturas�n�n t�m kalemlerin KDV dahil tutar�n�n toplam�n� belirtir.

### Kalem Ekleme Ek �zellikler

- Yeni Stok Kalemi Ekle: Stok kalemi eklemek i�in buray� se�erek ekleme sa�layabilirsiniz.
- Yeni Gelirgider Kalemi Ekle: Gelir gider kalemi eklemek i�in buray� se�erek ekleme sa�layabilirsiniz.
- Yeni Demirba� Kalemi Ekle: Demirba� kalemi eklemek i�in buray� se�erek ekleme sa�layabilirsiniz.
- �rsal�yeden Kalem Ekle: �rsaliyeden kalemleri se�erek buraya aktar�m yapabiliriz.

## Notlar 

��leme ait �zel notlar belirtebiliriz. 
�nemli bir detay var ise bu detaylar� burada belirtebiliriz.
Notlar kullan�m detaylar� i�in linke t�klay�n�z. [Notlar](../TemelOzellikler/Notlar.md)

## Belgeler

Yapaca��m�z i�lem i�in elimizde belgeler var ise jpeg, png, pdf vb. formatlarda bu belgeleri buraya y�kleyebiliriz.
Buraya i�lem ger�ekle�irken ki g�rselleri y�kleyebiliriz.

Belge eklemek i�in t�klayal�m ;

- Daha �nce y�klediklerimden se� -> belgeyi se�elim -> �li�kilendir �eklinde belge y�kleme i�lemimizi ger�ekle�tirebiliriz.
- Y�klenecek belge veya resimleri se�in -> belgeyi ya da belgeleri se�elim -> Y�kle �eklinde belge y�kleme i�lemimizi ger�ekle�tirebiliriz.

Belge kullan�m detaylar� i�in linke t�klay�n�z. [Belge](../TemelOzellikler/Belgeler.md)

## Kay�t Bilgileri

Kart�n hangi kullan�c� taraf�ndan ve hangi tarihlerde olu�turuldu�u ve de�i�tirildi�i bilgisini i�erir.

Kart i� ak�� s�re�lerine dahil edildi�inde hangi kullan�c� taraf�ndan hangi tarihte onayland��� bilgilerini i�erir. 

## Kaydetme ve Silme

- Doldurulmas� gereken alanlar girildikten sonra sa� alt k��ede bulunan Kaydet butonuna t�klayarak M��teri/Sat�c� kart� a�ma i�lemimizi tamamlayabilirsiniz.
- Kay�tl� bir kart� silmek i�in sol altta bulunan sil butonuna t�klayarak silebilirsiniz.

## Yazd�r

- Sayfan�n sa� �st�nde bulunan yaz�c� sembol� ile faturan�n ��kt�s� al�nabilir. 

## Ek ��lemler

 Sayfan�n sa� �st�nde bulunan alt altta �� �izgi �eklinde olan d��me ile ek i�lemlere ula��l�r.
- Yevmiye Fi�: Yevmiye fi�i, i�letmelerde ger�ekle�en her t�rl� mali i�lemin tarih, miktar ve a��klama bilgileri ile birlikte kaydedildi�i muhasebe belgesidir.
- Kopyala: Faturay� kopyalamak i�in kullan�l�r.
- T�m Kalemlerde De�i�tir: Buradan depo, proje, s�zle�me, vergi muafiyeti, vergileri yenile, iskonto oran�, ref. ithalat ihracat, plasiyer, Ref teslim tarihi bilgilerini t�m kalemlerde de�i�tirebiliriz.
- D�viz T�r� De�i�tir: D�viz t�r� de�i�ikli�i yapabiliriz.
- Depo Terminaline Aktar: 
- G�rev Olu�tur: Sipari� i�in g�rev olu�turup, ki�i atayabiliriz, a��klama, tarih biti�, hat�rlatma s�resi, y�netici, kullan�c�, tamamlanma tipi, tekrar �ekli bilgilerini ekleyerek g�rev tan�mlama i�lemimizi ger�ekle�tirebiliriz.
- G�rev Ba�la: A��lan listede ki g�revlerden g�revi ba�layaca��m�z, birle�tirece�imiz g�revi se�elim, kaydet diyerek g�revi ba�layabiliriz.
- �rsaliyelerini G�r: �ade faturas�n� olu�turdu�umuz faturan�n irsaliyesini g�rmek i�in h�zl� eri�im sa�lar.

