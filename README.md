# Python
Python başlangıç notları
PYTHON NOTES

Saturday, March 19, 2022
9:04 AM

NUMERIC DATA & VARIABLE TYPES
Integer: Tam sayılar
Float: Ondalıklı sayılar
	Ø Değişkenin veri tipine sonradan değiştirebilirsin.
	Ø Değişken isimleri sayı ile başlayamaz
	Ø Değişken ismi kelimelerden oluşuyorsa aralarında boşluk olamaz.
	Ø Sadece _ sembolü değişken ismi içerisinde kullanılabilir.
	Ø Pythonda tanımlı anahtar kelimeler değişken ismi olarak kullanılamaz. (while, not vs)
	Ø Değişken değerlerini değiştirebilirsin. (a=3 b=4) ----- (a,b = b,a)----- (a=4 b=3)
	Ø i=5 -----( i= i+1 )----- i=6 or (i += 1) ----- i=6
	Ø Yorum satırları ekleyebilirsin. 
	Ø Tekli yorum satırı : #
	Ø Çoklu yorum satırı : alta ve üste """
	Ø Tamsayı bölmesi "  // "
	Ø Kalanı bulma operatörü " % "
	Ø Üs bulma operatörü " ** "
	Ø Karekök bulmak için ** 0.5
	Ø küp kök bulmak için ** (1/3)

STRING
	Ø ' , " , "' ile string oluşturulur.
	Ø Kaçış dizisi " \ "
	Ø Karakterlerin yerleri indeks olarak adlandırılır.( stringlerin indekslenmesi 0 ile başlar)
	Ø Son karakter -1'den başlar.
	Ø a= "çağla"           a[-1]   = a
	a[3]   = l
	Ø String parçalama =  başlama indeksi : bitiş indeksi : artış miktarı
	Ø Son karakteri dahil etmez.
	Ø Len = stringin boyunu yazar.
	Ø String direkt olarak değiştirilemez.
	Ø a = "çağla"
	Ø a = a + "çağla gürcer"
	Ø a = çağla gürcer

VERİ TİPİ DÖNÜŞÜMLERİ
	Ø a = 32                                b = 2.5                    
	Ø float(a) = 32.0                 int(b) = 2

PRINT FONKSİYONU VE FORMATLAMA
	Ø \n = alt satıra geçme operatörü
	Ø \t = Bir tab boşluk bırakma operatörü
	Ø type fonksiyonu = hangi veri tipi olduğunu gösterir.
	Ø sep = yazılan değerler arasına istenen karakterin yerleştirilmesini sağlar.
	Ø print ("*Python") = P y t h o n

LİSTE VERİ TİPLERİ
Stringlerle yapı gereği benzerdir ama stringlerden farklı olarak listeler değiştireilebilir.
	Ø Append metodu, verdiğimiz değeri listeye eklememizi sağlar. ( liste.append)
	Ø Pop metodu, verdiğimiz indeks numarasına göre listeden atar. (liste.pop () )
	Ø Sort metodu, listenin elemanlarını sıralamayı sağlar. alfabetik veya küçükten büyüğe.( liste.sort() )
	Ø Eğer tam tersi sıralama istiyorsak. ( liste.sort( reverse = True) )
	Ø Bir listenin içinde başka bir liste bulundurmak mümkündür. Buna da iç içe listeler adı verilir.

DEMETLER(TUPLES)
Listeler benzer fakat demetler değiştirilemez.
	Ø Count = içine verdiğimiz değerin demette kaç defa geçtiğini bulabiliriz. (demet.count)
	Ø Index = içine verdiğimiz elemanın hangi indekste olduğunu bulabiliriz.(demet.index)

SÖZLÜK VERİ TİPLERİ(DICTIONARIES)
Aynı sözlükler gibilerdir. Sözlüğün içindeki her bir eleman indeks ile değil anahtar(key) ve değer(value) olarak tutulur.
	Ø Sözlüklerde  listelerdeki gibi değer değiştirebiliriz.
	Ø Listelerdeki gibi iç içe sözlükler oluşturulabilir.
	Ø Values = Sözlüğün değerlerini bir liste olarak döner ( .values() )
	Ø Keys = Sözlüğün anahtarlarını bir liste olarak döner.(.keys() )
	Ø Items = Sözlüğün anahtar ve değerlerini bir liste içinde demet olarak döner.(.items() )

INPUT FONKSİYONU 
	Ø Kullanıcıdan girdi almak için input() fonksiyonu kullanılır.
	Ø Eğer int'e çevirmezsen hata verir.

KOŞULLU DURUMLAR
	Ø Boolean = true ve false
	Ø * Değer atamak istemiyorsak none yazabiliriz.
	Ø 00 - eşit
	Ø != - eşit değil
	Ø > - büyüktür
	Ø < - küçüktür
	Ø >= - büyükse veya eşitse
	Ø <= - küçükse veya eşitse
	Ø * AND = hepsinin true olması lazım, diğer durumlarda false çıkar.
	Ø * OR = En az birinin true olması gerekiyor, diğer durumlarda false çıkar.
	Ø * NOT = mantıksal bir bağlaç değildir. Sadece bir mantıksal değeri veya karşılaştırma işlemini tam tersi sonuca çevirir.
	Ø  if i not in [2, 5]:
	    #code
	Ø if letter in "aeiöü":
	 print("sesli harf")
	
	

   ****   IF - ELIF - ELSE  ****
Pythonda bir blok tanımlama işlemi girintiler sayesinde olur. (tab ile 4 boşluk bırakma)
	Ø IF BLOGU = Herhangi bir yerde belli bir koşulu kontrol edeceksek kullanılır.Koşul false olursa blok çalışmaz.Ifler sağlandığında her zaman çalışır.
	Ø ELSE BLOGU = If bloğunun false olması haline oluşacak durum için oluşturulacak blok.
	Ø ELIF BLOGU = If dışındaki koşulları yazmak için kullanılır.
	Ø IF olmadan elif ve else kullanılamaz.ELSE VE ELIF Sadece yukarıdaki işlem sağlanmadığında çalışır.

DÖNGÜ YAPILARI
Program belli koşularda sürekli çalışmasını ve devam etmesini sağlar.
	Ø IN OPERATÖRÜ =  Bir elamanın başka bir listede, demette veya stringde olup olmadığını kontrol eder.
	Ø FOR DÖNGÜSÜ =  Listelerin ,demetlerin, stringlerin ve hatta sözlüklerin üzerinde dolaşmamızı sağlayan bir döngü türüdür.
	
	                                      "for eleman in veri_yapısı (liste vb):"
	
	Ø liste=[1,2,3,4,5,6,7]
	for eleman in liste : 
		print("Eleman",eleman)
		
	Ø liste=[(1,2),(3,4),(5,6),(7,8)]
	For (i,j )in liste :
		print(i,j)
		
	Ø sözlük={"bir":1,"iki":2,"üç":3,"dört":4}
	for(i,j )in sözlük.items() :
	print("Anahtar:",i,"Değer:",j)
	
	Ø WHILE DÖNGÜSÜ = Bir koşul sağlandığı sürece bloğundaki işlemleri gerçekleştirmeye devam eder. While döngülerinin sona ermesi için koşul durumunun bir süre sonra False olması gereklidir.
	while (koşul):
                             " İşlem1"
                               İşlem2
                               İşlem3
                                  //
                                  //
	Ø While True = Sonsuz döngü
	Ø i=0 
	while (i<10) :
	print("i'nin değeri ",i)
	i+=1
	
	Ø  While döngü koşulunun bir süre sonra False olması gerekecek ki döngümüz sonlanabilsin. Ancak eğer biz while döngülerinde bu durumu unutursak , döngümüz sonsuza kadar çalışacaktır. Böyle bir durumda Windows'ta "crtl c" ile döngüyü sonlandırabiliriz.
	
	Ø RANGE FONKSİYONU =Bu yapı başlangıç, bitiş ve opsiyonel olarak artırma değeri alarak listelere benzeyen bir sayı dizisi oluşturur. 
	print(*range(0,20))       
	Ø Yazdırmak için başına "*" koymamız gerekiyor.
	
	Ø Başlangıç değeri vermediğimizde 0'dan başlar 
	
	Ø Sürekli yukarı gitme eğilimde olduğu için geriye doğru gitmek istiyorsak arttırmaya "-1" yazmamız gerekiyor.
	
	Ø BREAK İFADESİ = Döngü çalışmasını bir anda durdurur. Böylelikle döngü hiçbir koşula bağlı kalmadan sonlanmış olur.
	Ø Break ifadesi sadece ve sadece içindeki bulunduğu döngüyü sonlandırır. Eğer iç içe döngüler bulunuyorsa ve en içteki döngüde break kullanılmışsa sadece içteki döngü sona erer.
	
	Ø CONTINUE İFADESİ = Continue ifadesi kullanıldığı zaman geri kalan işlemlerini yapmadan direkt bloğunun başına döner.
	Ø Jupyter'de sonsuz döngü "kernel" sekmesi ile sonlandırılabilir.
	
	Ø LIST COMPREHENSION = Bir listeden başka bir liste oluşturmamızı sağlar.
	Ø liste1=[1,2,3,4,5]
           liste2=[i for i in liste1]
           print(liste2)

	Ø liste=[[1,2,3],[4,5,6,7,8],[9,10,11,12,13,14,15]]
	liste2=list()
	for i in liste :
	For x in i: 
	print("x:",x) 
	liste2.append(x)
	print(liste2)
	
	Ø liste=[[1,2,3],[4,5,6,7,8],[9,10,11,12,13,14,15]]
	Liste2 = [ x for i in liste for x in i] 
	print(liste2)
	
	METODLAR
	
	Metodlar bir obje üzerinde belli işlemleri gerçekleştiren objelere özgü fonksiyonlardır
	
	Ø Help(metod) yazarak metodun ne yaptığını öğrenebilirsin.
	
	FONKSİYONLAR
	
	Fonksiyonlar programlamada belli işlevleri olan ve tekrar tekrar kullandığımız yapılardır
	
	Ø Bizim hazır kullandığımız fonksiyonlara(print(),type() vs.) gömülü fonksiyonlar(built-in function) denilmektedir. Ancak bunlardan hariç olarak biz kendi özel fonksiyonlarımızı(user-defined functions) da tanımlayabiliriz.
	 
	Ø Def selamla():
	print("Selam") or selamla()
	
	Ø Function Call =  fonksiyon_adı(Argüman1,Argüman2....)
	Ø Parametreler ve Argümanlar = Bizim fonksiyon tanımlarken tanımladığımız herbir değişken birer Parametre , fonksiyon çağrısı yaptığımız zaman içine gönderdiğimiz değerler ise Argüman olmaktadır.

            FONKSİYONLARDA RETURN
	
	Return ifadesi fonksiyonun işlemi bittikten sonra çağrıldığı yere değer döndürmesi anlamı taşır. Böylelikle, fonksiyonda aldığımız değeri bir değişkende depolayabilir ve değeri programın başka yerlerinde kullanabiliriz.
	
	Ø Def toplama(a,b,c):   
	        return a+b+c
	Def ikiyle_çarp(a):
	        return a*2
	
	Toplam = toplama (3,4,5)
	Print (ikiyle_çarp(toplam))  = 24
	
	Ø Return ifadesinden sonra fonksiyonumuz tamamıyla sona erer. Yani, return ifadesinden sonra yapılan herhangi bir işlem çalıştırılmaz.
	Ø Fonksiyonlarda çağrıldığı yere herhangi bir değer döndürmeyen (return kullanılmayan) fonksiyonlara void fonksiyonlar denmektedir.
	
	Fonksiyonlarda Parametre Türleri
	Def selamla (isim="İsimsiz"):
	print("Selam",isim)
	Selamla()
	Selam İsimsiz
	Ø Ancak böyle bir durumda argümanları gönderirken değerleri sıralı vermemiz gerekiyor. 
	Bilgilerigöster (numara="123456") # numara parametresini özel olarak belirtiyoruz.

	Ø  Esnek Sayıda Değerler = 
	Def toplama (*parametreler):  # Artık parametreler değişkenini bir demet gibi kullanabilirim.
	Toplam = 0
	Print ("Parametreler:",parametreler)
	For i in parametreler: 
	Toplam + = i 
	Return toplam
	
	GLOBAL VE YEREL DEĞİŞKENLER
	
	Pythonda her bir değişkenin, fonksiyonun ve  sınıfların(class) aslında bir kapsamı(scope) bulunur ve Python herbir değişkeni bir isim alanında (namespace) tanımlar. Değişkenlerin İsim alanı ise, bu değişkenlerin nerelerde var olduğunu ve nerelerde kullanılabileceğini gösterir.
	
	Pythonda fonksiyonlarda tanımlanan değişkenler Python tarafından Yerel (Local) değişkenler olarak tanımlanırlar. Yani bir fonksiyon bloğunda oluşturulan değişkenler fonksiyona özgüdür ve fonksiyon çalışmasını bitirdikten sonra bu değişkenler bellekten silinir ve yok olur. Böylelikle , fonksiyon içinde tanımlanmış bir değişkene başka bir yerden erişilemez.
	
	Pythonda en genel kapsama sahip değişkenler ise Global değişkenler olarak tanımlanırlar ve global değişkenlere tanımlandığı andan itibaren programın her yerinden ulaşabiliriz.
	
	Ø c=10     # Globalde tanımlanmış bir değişken
	 Def fonksiyon():
		c=2      # Yerelde tanımlanmış bir değişken
		Print ( c)       # Yerel değişken kullanılıyor.
	fonksiyon()
	print(c)
	2
10
	Kodumuz çalıştığında ilk olarak c isimli global değişken oluşuyor. fonksiyon çağrıldığında ise c isimli başka bir yerel değişken oluşuyor gibi düşünebilirsiniz. Böyle bir durumda elimizden iki tane c değişkeni var. Python bu durumda global c değişkeni yerine kendi yerel c değişkenini kullanıyor.
	
	Ø d=10
	Def fonksiyon():
		Globald 
		d=4
		print(d)
	 fonksiyon()
	print(d)
	4
4
	Bu durumda kodumuz ne yapıyor ? İlk olarak program başladığı zaman, bir tane global d değişkeni oluşuyor ve fonksiyonumuz çağrıldığında global d ifadesiyle globaldeki d değişkenini kullanmak istediğimizi söylüyoruz. Böyle d = 4 ifadesiyle bir tane daha d değişkeni oluşturmuyoruz. Böylelikle d =4 ifadesiyle globaldeki değişkeninin değerini değiştirmiş oluyoruz.
	
	Ø Burada gördüğümüz gibi, if ve while bloklarında tanımlanan değişkenler yerel bir değişken yerine global bir değişken olmaktadır.
  
	LAMBDA İFADELERİ

	etiket = lambda parametre1,parametre2.... :  İşlem
	
	Ø Def ikiyleçarp (x) : # Klasik fonksiyon tanımlama 
		return x * 2 
	 ===============================================
	
	İkiyleçarp = lambda x : x * 2             # x parametre x* 2 return ifadesi ve ikiyleçarp değeri de bir etikettir(değişken gibi düşünelim)
	
	Ø Lambda ifadeleri uzun fonksiyonlarda kullanılmıyor.


	MODÜLLER
	Pythonda aslında herbir dosya bir modüldür ve her bir modül içinde fonksiyonlar, sınıflar ve objeler barındırır. Biz de bu modülleri programımıza dahil ederek içindeki fonksiyonlardan, sınıflardan ve objelerden faydalanabiliriz.
	
	Ø import  math      # Modülü içeri aktarıyoruz. Artık bu modülün tüm fonksiyonlarını kullanabiliriz.
	
	Ø Dir (math)    # Math modülünün içindekileri görmek için dir fonksiyonunu kullanabiliriz.
	
	
	Ø Help (math)    # Fonksiyonların görevlerini görebilmek için help fonksiyonunu kullanabiliriz.

	Ø İmport math as matematik     #Bu şekilde modülü istediğimiz isimle kullanabiliriz.

	Ø From math import*    # Yıldızın anlamı math modülünün içindeki bütün fonksiyonları almak istediğimizi belirtiyor.

	Ø From math import factorial,floor      # Sadece 2 tanesini dahil ettik.

	Ø Bu yöntemde bazı sıkıntılar çıkabiliyor. Python son gördüğü fonksiyonu aldığı için başta tanımladığımız fonksiyonu görmüyor.


	KENDİ MODÜLLERİMİZİ YAZMAK
	Ø  1. Herhangi bir tane klasör oluşturuyoruz.
	Ø  2. Modülümüz ve deneme Python dosyamız aynı dizinde olması gerektiği için 2 tane Python dosyasını da
 bu klasör altında oluşturuyoruz.
	Ø  3. modul1.py ve deneme.py dosyası oluşturuyoruz.
	Ø  4. modul1.py dosyasının içine istediğimiz kadar fonksiyonu yazıyoruz.
	Ø  5. Son olarak da deneme.py dosyasının içinde bu modul1.py modülünü kullanıyoruz.

	v Yazdığımız bir modülü her yerden kullanmak için yazdığımız modul1.py dosyasının Python35/Lib klasörünün altına atmamız gerekiyor.

	NESNE TABANLI PROGRAMLAMA
	
	Object Oriented Programming en basit anlamıyla gerçek hayatı programlamaya uyarlamaktır.
	
	Ø OBJE = Etrafımıza baktığımızda aslında her bir eşyanın bir obje olduğunu görüyoruz. Örneğin bir tane televizyon kumandasını düşünelim. Bu kumandanın kendi içinde değişik özellikleri (attribute) ve fonksiyonları(metod) bulunuyor. Örneğin, kumandanın markası, tuşları aslında bu kumandanın özellikleridir(attribute). Kumandanın kırmızı tuşuna bastığımızda televizyonun kapanması ve sesi kapatma tuşuna bastığımızda televizyonun sesinin kapanması bu kumandanın metodlarıdır. Bunun gibi Pythondaki aslında her şey bir objedir.
	
	Ø liste=[1,2,3,4,5]   # Liste objesi oluşturmak

	Ø liste.append(6)   # Append metodu

	Ø CLASS = Kendi veri tiplerimizi oluşturmak ve bu veri tiplerinden objeler üretmemiz için öncelikle objeleri üreteceğimiz yapıyı tanımlamamız gerekiyor. Bunu tasarladığımız yapıya da sınıf veya ingilizce ismiyle class diyoruz. 
	Sınıflar veya Classlar objelerimizi oluştururken objelerin özelliklerini ve metodlarını tanımladığımız bir yapıdır ve biz herbir objeyi bu yapıya göre üretiriz. 
	
	Ø Oluşturduğumuz objelerin özelliklerinin değeri aynıdır. Çünkü aslında  tanımladığımız özellikler birer sınıf özelliğidir. Yani biz bir obje oluşturduğumuzda bu özelliklerin değerleri varsayılan olarak gelir. Bu özelliklerin değerlerine , herhangi bir obje oluşturmadan da erişebiliriz.
	
	Ø init metodu Pythonda yapıcı(constructor ) fonksiyon olarak tanımlanmaktadır. Bu metod objelerimiz oluşturulurken otomatik olarak ilk çağrılan fonksiyondur. Bu metodu özel olarak tanımlayarak objelerimizi farklı değerlerle oluşturabiliriz.
	                                                              """   def__init__(self):   """
	
	Ø self anahtar kelimesi objeyi oluşturduğumuz zaman o objeyi gösteren bir referanstır ve metodlarımızda en başta bulunması gereken bir parametredir. Yani biz bir objenin bütün özelliklerini ve metodlarını bu referans üzerinden kullanabiliriz.
	Objeler oluşturulurken, Python bu referansı metodlara otomatik olarak kendisi gönderir. Özel olarak self referansını göndermemize gerek yoktur.
	İstersek init metodunu varsayılan değerlerle de yazabiliriz.
	
	Ø INHERITANCE =  Inheritance veya kalıtım bir sınıfın başka bir sınıftan özelliklerini(attribute ) ve metodlarını miras almasıdır. Ortak özellikleri ve metodları tekrar tekrar sınıfların içinde tanımlamak yerine, bir tane ana class tanımlayıp bu classların bu classın özelliklerini ve metodlarını almalarını sağlayabiliriz. 
	
	Class Yönetici(Çalışan):         # Çalışan sınıfından miras alıyoruz.
	          Pass                      # Pass Deyimi bir bloğu sonradan tanımlamak istediğimizde kullanılan bir deyimdir.
	
	Ø OVERRIDING(İPTAL ETME) = Eğer biz miras aldığımız metodları aynı isimle kendi sınıfımızda tekrar tanımlarsak , artık metodu çağırdığımız zaman miras aldığımız değil kendi metodumuz çalışacaktır. Buna Nesne Tabanlı Programlamada bir metodu override etmek denmektedir.
	
	Ø SUPER = miras aldığımız sınıfın metodlarını alt sınıflardan kullanmamızı sağlar.
	
	Super ( ) .__init__ (isim,maaş,departman)   # 3 tane özelliği Çalışan fonksiyonunun init fonksiyonuyla hallediyoruz. Ekstra özelliği de kendimiz yazıyoruz.
	
	ÖZEL METODLAR 
	Özel metodlar,  bizim özel olarak çağırmadığımız ancak her classa ait metodlardır. Bunların çoğu biz tanımlamasak bile Python tarafından varsayılan olarak tanımlanır. Ancak bu metodların bazılarını da özel olarak bizim tanımlamamız gerekmektedir. init metodu bu metodlara bir örnektir.
	
	Ø İnit metodunu kendimiz tanımlarsak artık kendi init fonksiyonumuz çalışacaktır. ---
	Ø Str  metodunu tanımladığımızda print fonksiyonunun nasıl bir işleve dönüştüğünü görebilirsiniz. ---
	Ø Len metodu biz tanımlamassak tanımlı gelmez. O yüzden bizim tanımlamamız gerekir. ---
Del  metodu objeyi siler. Farklı işlevlerde verebilirsiniz kendisine. ---![image](https://user-images.githubusercontent.com/86996274/160302613-93a62905-570b-4d73-9d5b-cd1c6aea31c4.png)
