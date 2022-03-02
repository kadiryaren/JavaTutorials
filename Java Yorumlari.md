Yorum satırları kodu açıklamak icin kullanılan özel karakterlerdir. Kod çalışırken hiçbir sekilde isleme dahil edilmezler. Yani sadece kaynak kodunu yazarken/okurken bize veya ekipteki arkadaşımıza  yol gösterici  olması Açısından kullanılır.

### Tek Satir Yorum

> // çift slash kullandıktan sonra yazdıklarımız hiçbir şekilde kod çaliştirilirken etki etmezler.

```Java
// Bu bir yorum satiridir ve koda etkisi yoktur.
System.out.println("Hello World");
```

Tek satir yorumları komutlardan sonra da kullanabiliriz: 

```Java
System.out.println("Hello World"); // Buradan sonrakiler yorum olarak değerlendirilir.
```

### Çoklu Satır Yorumlar

Yorumları tek satır kullanabileceğimiz gibi çoklu satırlar şeklinde de kullanabiliriz. 

> Bunun için yorumumuzu /* Yorum */ işaretleri arasına almamız gerekmektedir. 

```Java
/* Bu işaretler arasına yazdığımız ifadeler
yorum olarak değerlendirilecektir */
System.out.println("Hello World");
```