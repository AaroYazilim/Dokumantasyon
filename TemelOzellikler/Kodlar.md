
## Kodlar

### Tan�m 

Kodlar kart� gruplamak ve ileride gruplu rapor alabilmek i�in kullan�lan hiyerar�ik tan�mlard�r.
Kodlar, sistemde belirli kay�tlar� veya varl�klar� benzersiz bir �ekilde tan�mlamak i�in kullan�lan bir kategorilendirmedir.
Bu kodlar genellikle i�letmenin i�inde kullan�lan ve farkl� kay�tlar� veya varl�klar� ay�rt etmek i�in kullan�lan benzersiz kimliklerdir.
Sistemimizde kodlar k�sm� alt� adete kadar desteklenmektedir. 
Kategoriler gibi her kod bir sonrakinin alt kategorisi olacak �ekilde birbirlerine be�l� �ekilde ilerlemektedir.
Kod1 Ana kategori, kod2 detay, kod3 kategori vb. �ekilde ilerlemektedir.
Stok, gelir-gider gibi i�lemlerde �r�nleri detayland�rarak bu i�lemlerde ki karga�ay� azaltarak daha kolay bulman�za, raporlay�p analiz yapman�za yard�mc� olur.

�ok s�k kullan�lan kodlar i�in; Bu parametreye �zel tan�mlar, ek �zellikler ekleyebiliriz.

�rne�in, m��teri kay�tlar� i�in m��teri numaralar�, �r�nler i�in SKU (Stock Keeping Unit) kodlar�,
tedarik�iler i�in tedarik�i kodlar�, �r�n�n �zellikleri(boyal�, tankl� vb.) gibi �zel se�enekleri kod k�sm�nda kullanalabilirsiniz.

Bu kodlar, i�letme i�indeki veri y�netimini kolayla�t�r�r ve �e�itli s�re�lerde kullan�lan kay�tlar�n h�zl� bir �ekilde tan�mlanmas�n�, bulmay�, filtrelemeyi kolayla�t�r�r. 
Kodlar sayesinde verilerin s�n�fland�r�lmas�, izlenmesi ve raporlanmas� daha etkin bir �ekilde ger�ekle�tirilebilir.

��letmemizde stok y�netimi i�in kullan�lan Kod2 veya Kod3 gibi belirli bir kod kategorisini ele alal�m. 
Bu kod kategorisini "boyal�" olarak gruplad���m�z� d���nelim. 
Yani, i�letmemizdeki farkl� stok kalemlerini tan�mlarken, baz�lar�n� "boyal�" olarak etiketledik ve bu kategoride bir araya getirdik.
�imdi, bu kod kategorisinde "boyal�" olarak tan�mlanan her stok kalemi i�in toplu i�lem yapma imkan�na sahibiz. 
��letmemizde bulunan t�m "boyal�" �r�nler i�in ayn� anda bir dizi i�lem ger�ekle�tirebiliriz. 
�rne�in, bu �r�nlerin fiyatlar�n� g�ncellemek, stok seviyelerini kontrol etmek veya bir promosyon kampanyas� d�zenlemek gibi i�lemler toplu olarak ger�ekle�tirilebilir daha kolay analiz yap�p rapor ��kartmam�za yard�mc� olur.

�ncelikle, Kap�, Dolap ve Masa gibi �r�nleri temsil eden stok kalemlerini sisteme girdi�imizde, her birinin Kod1 k�sm�na ilgili �r�n� belirten bir kod atar�z. 
�rne�in, Kap� i�in "KAP", Dolap i�in "DLP", Masa i�in "MSA" gibi.
Ard�ndan, her bir �r�n i�in �zellikle "Boyal�" gibi belirli bir �zelli�i temsil eden kodlar� Kod2 k�sm�na gireriz. 
Yani, boyal� olan Kap�lar i�in "BOY", boyal� olan Dolaplar i�in "BOY" ve boyal� olan Masalar i�in de "BOY" kodlar�n� atar�z.
�imdi, e�er bir stok kaleminin "Boyal�" �zelli�ini silmek istiyorsak, bu �r�n�n stok giri�i yap�ld��� b�t�n kay�tlarda Kod2 k�sm�nda "BOY" kodunu silmeliyiz. 
Yani, ilgili stok kalemi i�in yap�lan b�t�n giri�lerde, boyal� olma �zelli�ini temsil eden bu kodu kald�rmam�z gerekmektedir.
Bu i�lemi ger�ekle�tirmek i�in, ilgili stok kaleminin t�m giri�lerini sisteminizde bulup, bu giri�lerin Kod2 k�sm�nda "BOY" kodunu silmek i�in bir d�zenleme yapman�z gerekmektedir. 
B�ylece, boyal� �zelli�ini kald�rm�� olursunuz.
Ancak, bu i�lemi ger�ekle�tirirken dikkatli olmal� ve di�er �zelliklerin veya verilerin etkilenmemesini sa�lamal�s�n�z. E�er sisteminizde bu t�r bir i�lemi ger�ekle�tirmek i�in bir ara� veya i�lem mevcut de�ilse, genellikle veritaban� sorgular� veya �zel bir yaz�l�m geli�tirme s�reci gerekebilir. 
Bu nedenle, i�lemi ger�ekle�tirmeden �nce dikkatlice plan yapman�z ve gerekli �nlemleri alman�z �nemlidir.
Bu yakla��m, i�letmenin verimlili�ini art�r�r ��nk� benzer �zelliklere sahip �r�nleri gruplayarak y�netme ve i�lem yapma s�recini kolayla�t�r�r. Ayr�ca, bu gruplama y�ntemi, raporlama ve analiz s�re�lerini de iyile�tirir ��nk� benzer �r�nleri bir araya getirerek daha anlaml� veri setleri elde etmemizi sa�lar. 
Bu sayede, i�letmenin stok y�netimi s�re�leri daha etkili ve verimli bir �ekilde y�r�t�lebilir.

### Kod Ekleme

- Sol men�den Stok -> Stok Kartlar� Kod A�ac� -> Kod Ekle �eklinde kod ekleme i�lemini ger�ekle�tirebiliriz.
- Kodlar k�sm�nda Detayl� Ekle �eklinde kod ekleme i�lemini ger�ekle�tirebiliriz.
- Kodlar k�sm�nda Listeden Se� yapabilirsiniz.
- Kodlar k�sm�nda -> Listeden Se� -> Yeni Kod Ekle �eklinde yeni etiket ekleyebilirsiniz.

### Ek �zellikler 

**Anasayfaya K�sayol Olarak Ekle** Etiketler listesine h�zl� eri�im sa�lamak istedi�inizde k�sayol olarak ekleyebilirsiniz. [Anasayfaya K�sayol Olarak Ekle](/TemelOzellikler/KisaYollaraEkleme.md "Anasayfaya K�sayol Olarak Ekle") 