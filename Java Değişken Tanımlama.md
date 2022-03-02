Değişkenler verileri içlerinde depolayan programlama elemanlarıdır. Javada değişkenler tip tanımlı şekilde yapılır. Yani bir değişkeni tanımlamak istiyorsanız değişkenin tipini önceden belirtmelisiniz.

`String` değişken tipi içerisinde metinsel ifadeleri barındırır. Örnek olarak 'Kadir internete bağlandı' gibi bir metinsel ifadeyi String değişkeni ile tutabilliriz.

`Integer` değişken tipi içerisinde tam sayıları yani `1,5,593` gibi ifadeleri tutabilir.

`Float` değişken tipi içerisinde ondalıklı yanı virgüllü sayıları tutabilir. `1.56 , 4.68 , 5343.2342` gibi ifadeleri tutabilir.

`Char` değişken tipi içerisinde tekil karakterleri tutar. Yani 'Kadir' metinsel ifadesindeki her bir harf 'K','a','d','i','r' char veri tipi olarak saklanabilir.

`boolean` değişken tipi içerisinde mantıksal ifadeleri yani 1-0 yani True False ifadelerini tutar.

***`Önemli Uyarı` programlamada virgül parametreler arasında kullanılır. Yani float tanımlarken 1,56 gibi bir kullanım yanlıştır. 1.56 seklinde kullanılmalıdır.***

### Javada Değişken Tanımlama

Java daha önce belirttiğimiz gibi tip tanımlı bir dildir yani değişken tanımlarken öncesinde değişkenin tipini belirtmeliyiz.

> String varName = "string ifade";

şeklinde bir değişkeni tanımlayabiliriz.

Her ifade bitişinde noktalı virgül ile ifademizi bitirmeliyiz.

```Java
// String tanimlama
String ifade = "welcome to house!";
System.out.println(ifade);


// integer tanimlama
int sayi = 56;
System.out.println(sayi);


// float tanimlama
float ondalikSayi = 45.01;
System.out.println(ondalikSayi);


// Char tanimlama
char karakter = "c";
System.out.println(karakter);


// boolean
boolean mantiksal = true;
System.out.println(mantiksal);
```

Javada değişkenleri tanımladıktan sonra içerisine tekrar tekrar atama yapabiliriz.

Yani: 

```Java
int sayi = 5;
sayi = 10; // şimdi sayı 10 oldu
```

fakat `final` anahtar kelimesini kullanırsak değişkenin başında tanımlarken değişkenin sadece tanımlarkenki değerinde sabit kalmasını sağlayabiliriz.

```Java
final int sayi = 5;
sayi = 10;  // sayı değerı hala 5
```

### Değişkenlerin Ekrana Basılması

Javada ekrana çıktı alırken `println` fonksiyonunu kullandığımızı geçen derslerden biliyoruz. println() fonksiyonu aynı zamanda içerisinde işlem yapmaya veya farkli string ifadeleri bir arada bastırmaya da izin verir.

```Java
// iki string ifadeyi println içerisinde bastırmak.
String brandName = "Logitech";
String modelName = "MX Keys";

System.out.println(brandName + modelName);



// iki sayısal ifadenin toplamını ekrana basmak 
int sayi1 = 10;
int sayi2 = 20;

System.out.println(sayi1 + sayi2);
```

### Değişkenlerin tek satırda  tanımlanması

Javada değişkenleri tek satırda ekranda tanımlayabiliriz. Ayni tipteki değişkenleri tek satırda tanımlayabiliriz.

```Java
String s1 = "Mehmet", s2 = "Akif", s3= "Ersoy";
```

### Javada değişken isimlendirmesi kuralları

Herhangi bir programlama dilinde program yazarken oluşturacağımız değişken ismini  içinde tuttuğu değeri en iyi açıklayabilecek şekilde belirlemeliyiz.

`m` `x` `a` `z` gibi harf şeklindeki değişken isimlendirmeleri programda hataya yol açmasa da program büyüdükçe içinden çıkılamaz bir hal almasına neden olabilir. Bu nokta çoğu yeni başlayan arkadaş tarafından göz ardı edilmektedir fakat ilerleyen yıllarda daha komplex kodlar yazdığımızda anlıyoruz ki değişkenlerin isimlendirmeleri başımızı baya ağrıtabiliyor ve zaman maliyeti olarak geri dönüyor. Bundan dolayı değişken isimlendirmelerini olabildiğince kısa ve açıklayıcı, kısa olamıyorsa mutlaka açıklayıcı yazmalıyız.

```Java
// Yanlış  kullanim
int s = 0;
String tmt = 0;

// Doğru kullanım
int sayac = 0;
String tabloMaliyetTutucu = 0;
```

### snake_case vs camelCase

Biz programcılar değişkenleri tanımlarken genellikle iki tip yazım şekli kullanırız. `camel case` yani baslangıçtaki kelimenin baş harfi küçük diğerleri büyük giden camelCase, tabloMaliyetTutucu gibi kullanılır. Bir de `snake case` kullanımı vardır. Bunda da her kelimenin arasına alt\_tire konur --> snake\_case, tablo\_maliyet\_tutucu şekline kullanılabilir.