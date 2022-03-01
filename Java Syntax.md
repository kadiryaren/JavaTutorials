## Java Syntax Yapısı

Bir önceki bölümde Main.java adında bir Java dosyası oluşturduk ve ekrana "Merhaba Dünya" yazdırmak için aşağıdaki kodu kullandık:

```Java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

### Örneğin Açıklaması

Java'da çalışan her kod satırı bir sınıfın içinde olmalıdır. Örneğimizde, sınıfa Main adını verdik. Bir sınıf her zaman büyük harfle başlamalıdır.

Not: Java büyük/küçük harf duyarlıdır: "MyClass" ve "myclass" farklı anlamlara sahiptir.

Java dosyasının adı, sınıf adıyla eşleşmelidir. Dosyayı kaydederken sınıf adını kullanarak kaydedin ve dosya adının sonuna ".java" ekleyin. Yukarıdaki örneği bilgisayarınızda çalıştırmak için Java'nın düzgün şekilde yüklendiğinden emin olun.

Örneğimizin çıktısı şu şekilde olmalıdır. 

> Hello World

## Main Fonksiyonu

Programın başlangıcında bir Main() fonksiyon gereklidir ve şu şekilde görünür:

```Java
public static void main(String[] args)
```

Tüm program Main() method (fonskiyon) içerisinde çalıştırılır. `public` , `static` , `void`, `String[] args` gibi anahtar kelimeleri bilmeniz şu an için gerekli değil. İnanın ki göründüğü gibi karmaşık değiller. Eğitimin ilerleyen kısımlarında bunlara da deyineceğiz :)

### Ekrana çıktı bastırma

Javada konsol ekranına yani çıktıları gördüğümüz yere bir metinsel veya sayısal ifadeyı basmak için `System.out.println()` fonskiyonunu kullanırız.

```Java
public static void main(String[] args) {
  System.out.println("Hello World");
}
```