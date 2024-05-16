
# Canl� �retim Terminali 

Canl� �retim terminaliyle �retim an�ndaki s�re�lerini detayl� olarak izleyebilirsiniz.
Operat�rler, i��iler ve y�neticiler, �retim s�re�lerini terminal �zerinden takip edebilir ve gerekirse m�dahale edebilirler.
�retime ba�land��� an sistem �zerinden ba�lad�klar�n� i�aretlemeli, mola verdiklerinde mola nedeni ile birlikte mola detaylar�n� girmeli ve i�lem bitti�inde bitirmelidir.
Personel bitiri se�ti�inde i�lemi canl� takipte g�remeyiz, i�lem yap�lma a�amas�nda canl� g�r�nt�lenmektedir.
�retim bitti�i andan itibaren canl� �retimden takip edemeyiz.
Biten i�lemler i�in; �retim -> Listeler -> �retim Hareketleri Listesinden g�r�nt�leyebiliriz.

�lk i�lem olarak bir terminal kullan�c�s� eklememiz gerekmektedir.

- [Terminal Kullan�c� Ekleme](/Uretim/TerminalKullaniciEkleme.md "Terminal Kullan�c� Ekleme"), kullan�c�m�z� tan�mlayarak terminal sistemine eri�imimiz ba�layacakt�r.
- �retim terminaline kullan�c�m�z� tan�mlad�ktan sonra terminal sistemine giri� yapabiliriz.
- https://erp.aaro.com.tr/ adresini a��n�z, �retim terminali kullanc�n�z� ve �ifrenizi giriniz. (Aaro hesab� yazan yerde ki mail ile giri� yapabilirsiniz. ayse@aaro.com.tr)
	Aaro a��k olan taray�c�m�zdan bu sayfaya eri�im sa�layamay�z. Terminal ve kullan�c� sayfas�n� ayn� anda kullanmak istiyorsak farkl� bir taray�c�dan giri� yapmam�z gerekmektedir.
- Terminal sistemini aktif kullanabilmemiz i�in [Operasyon Makine E�le�tirme](/Uretim/OperasyonMakineEslestirme.md "Operasyon Makine E�le�tirme") gerekmektedir. 
	Re�eteleri e�le�tirip i�lem yapabilmemiz i�in e�le�tirme yapmam�z gerekmektedir.
	Makinenin i�lemleri e�le�tirip tan�mlad�ktan sonra,
- Terminal sisteminin �al��mas� i�in, terminal ile makine e�le�tirmemi�se makineyi kullan�c� ile e�le�tirme yapmam�z gerekmektedir. 
- Terminal ile makineyi e�le�tirdi�imizde, terminal sistemimizde makine ve yap�lacak operasyon aktif olacakt�r. 
- Terminal sisteminde hangi makineyi kullanacaksak aaro logosunun alt�nda bulunan makinelerden se�im yapabiliriz ya da kullan�c� bilgilerimizden makine se�emimizi ger�ekle�tirebiliriz.
- Makine terminal sisteminde aktif olduktan sonra canl� �retim terminal k�sm�m�za ge�ebiliriz.
- Terminali a��n�z, i�lem yapaca��n�z makineyi se�iniz.

- Terminal sistemine giri� yapt���m�zda bizi kar��layan ekranda;

	**Devam Eden �� Emri**
		Burada yar�m kalan, devam etmemiz gereken i�lerimizi g�r�nt�lenir.
		Devam etmek istedi�imiz i�i se�erek canl� �retim terminalimize ba�layabiliriz.

	**�retim Plan�**
		Burada otomatik planlanan ya da yapm�� oldu�umuz planlamalar g�r�nt�lenir.
		��leme ba�layaca��m�z operasyonu se�erek i�leme ba�layabiliriz.
		Ba�lang�� Tarihi, Biti�i Tarihi, Aktiflik, Sipari� Hareket, Stok, �� emri se�eneklerinden filtrelemeler yaparak istedi�imiz verilere kolayca ula�abiliriz.

	**�retim Hareketleri**
		Burada yapm�� oldu�umuz operasyonlar� g�r�nt�lenir.
		�stedi�imiz aral�klar� se�erek filtreleme yapabiliriz.
		Personel, Sipari� hareket, Stok, �� emri, Operasyon, Makine, Re�ete, Son Operasyon Mu. se�eneklerinden filtrelemeler yaparak istedi�imiz verilere kolayca ula�abiliriz.

- �retim yap�lacak i� emrini se�tikten sonra �retim hareketi sayfam�z a��lacakt�r. A��lan ekranda;
	**Haz�rl�k Ba�lat** Makinenin �s�nmas�n� bekledi�imiz zaman diliminde ya da �retim haz�rl�k a�amlar�na ba�lad���m�zda buray� aktif etmemiz gerekmektedir.
	**�retim Ba�lat** Haz�rl�k a�amam�z bittikten sonra �retimi ba�lat a�amas�na ge�ebiliriz.
		**Durakla** Makine ar�za verdi�inde ya da duraklamam�z gereken bir durum oldu�unda duraklaya basarak durma eylemimizi aktif bir �ekilde i�lemi� olmaktay�z.
			Bu butona bast���m�zda neden ekran� kar��lamaktad�r. Durma nedemizi buraya girmemiz gerekmektedir makine ar�zaland� gibi detaylar� belirtmemiz gerekmektedir.
		**Mola Ver**
			Bu butonu se�ti�imizde �retim s�resi sayma durar. 
			Mola verdi�imiz zaman buray� i�aretlememiz gerekmektedir. Ka� dk s�rd���n� sistem otomatik hesaplar.
			Devam et dedi�imizde s�re, �retim s�resininden devam eder. 
		**Bitir**
			Bu butona bast���m�zda �retim hareket ekran� a��lacakt�r; 
			Bu ekran �zerinde, �retim hareketlerinde sisteme kaydedilenden farkl� bir i�lem ger�ekle�ti�inde m�dahale edebilirsiniz. 
			�rne�in makine saatte 10 adet �r�n olacak �ekilde tan�ml� fakat biz yava� �retimden kaynakl� saatte 8 adet �r�n ��kard�k buradan verileri g�ncelleyebiliriz.
			Makine saatte 10 adet �r�n olacak �ekilde tan�ml�yken makine saatte 11 adet �retim yapt� ayn� �ekilde mam�l miktar�n� de�i�tirebiliriz.
			Bir ba�ka senaryoda ise, hammadde kullan�m� tan�mland��� miktar�n �zerine ��km�� ya da daha az kullan�lm�� olabilir. Bu durumda, hammadde miktar�n� g�ncelleyebilirsiniz. 
			Operasyon s�ras�nda �al��an personel bilgilerini de operasyon ekran�ndan ekleyebilirsiniz.O operasyonda �al��an personelleri, personel listesinden eklemesini yapabiliriz.
			�retim s�re�lerindeki saatlerin yanl�� kaydedilmi� veya eksik oldu�unu fark ederseniz, bu bilgileri g�ncelleyebilirsiniz.
			�retimde bir duraklama olmu�sa, duraklama nedenini bu ekrandan girebilirsiniz. 
			Ek olarak, operasyona ait a��klamalar� �retim a��klama k�sm�na ekleyebilirsiniz. 
			Bu sayede �retim s�re�lerinin daha do�ru ve verimli bir �ekilde y�netilmesi sa�lan�r.

			Geli�mi� -> Atland�: Terminal ekran�nda atlamak, �retim s�recinde belirli bir ad�ma ge�i�i ifade eder. 
			�rne�in, bir �retim i��isi veya y�netici, �r�nlerin �retim a�amalar�n� takip ederken, terminal ekran�nda belirli bir a�amadan di�erine ge�i�i i�in kullan�m sa�lar.
			�retim a�amas�n�n atland���n� veya tamamland���n� g�stermek i�in kullan�l�r.

Verileri kontrol ettikten sonra kaydet butonuna basarak �retim operasyonu kaydet i�lemini tamamlayabilirsiniz.
