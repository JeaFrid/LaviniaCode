# Lavinia Code
## Lavinia Code Nedir?
Lavinia Code, içerisinde bulunan araçları sayesinde, cihaz ile kendi sistemi arasında bağ kurarak normalde yapılması karmaşık olan işlemleri kolayca yapmanıza olanak tanır. Yerel ağ’da kodlar yürütmek, global ağ’da get/post requests yapmak, Telegram botları yaratmak/yönetmek, mini uygulamalar yürütmek gibi özellikleri bulunuyor. İçerisine geliştirdiğiniz veya önceden geliştirilmiş mini uygulamaları yükleyebileceğiniz bu program; cihazınıza yerleşmiş mini bir işletim sistemi gibi davranıyor. Temel amacı, insan hayatını daha anlaşılabilir ve kolay bir hale getirmek. Gelecekte sağlık, seyahat (turizm), muhasebe, şirket yönetimi gibi alanlarda da kullanılması planlanıyor.
## Lavinia Code Dökümanları
### **Kodlama Paneli Nasıl Çalışır?**

Lavinia kodları, kısa ve anlamlı olacak şekilde düzenlenmiştir. Bir cümle yapısına sahip, giriş-gelişme-sonuç prensibiyle çalışır. Giriş; kod parçacığının hangi modül içerisinde çalışacağını belirtir. Gelişme; modül içerisinden hangi komutu çalıştıracağını belirtir. Sonuç; parametreleri aldıktan sonra kodu çalıştırıp sonuç vermeyi hedefler.

Lavinia kodlama panelinde prosedür bellidir;


```
ModülAdı Method: (değer parametresi) [referans parametre]
```
`ModülAdı` Kullanılan modül. *(örn: lavinia)*

`Method` Kullanılan modül için bir method. *(örn: web)*

`(parametre)` Method'un ihtiyacı olan veri. *(örn: https://...)*

`[referans parametre]` Method'un ihtiyacı olan veri. *(örn: [dosya/dizin])*

Tüm veriler doğru bir şekilde makineye teslim edildiğinde işlemler gerçekleşir.

### **Uygulamalar Menüsü Nasıl Çalışır?**

Uygulamalar menüsü, kodlama panelinden bağımsız bir kodlama paneline sahiptir. Komutları içerisinde dolar ($) işareti bulunur ve bu yüzden kodlama panelinde dolar işareti kullanılamaz. Bu özellik yalnızca uygulamalar menüsüne özeldir.


Uygulamalar menüsünde, önceden tanımlanmış özellikler bulunur. Web oturumu başlatmak, aktivite başlatmak veya liste/metin işlemek gibi yetenekleri vardır.

## Kodlama Dökümanları

Kodlama dökümanları, size tüm kod parçacıklarını sağlar. Unuttuğunuz kodların ne işe yaradığını burada inceleyerek hatırlayabilirsiniz.

### **Lavinia**
'Lavinia' kod parçacığı, Lavinia araçlarında kullanılır. Ekrana yazı yazdırmak, web araçlarını kullanmak gibi.

> `yazdır`

* Ekrana bir yazı yazdırır.

Örnek;

`lavinia yazdır: (Merhaba Dünya!)`

----------


> `web`

* Global Web’de bir bağlantıyı açar.

Örnek;

`lavinia web: (https://bybug.net)`

----------


> `webHTML`

* Yerel Web’de bir html kodu çalıştırır.

Örnek;

`lavinia webHTML: (html kodu)`

----------


> `aksiyon`

* Bir aksiyon başlatır.

Örnek;

`lavinia aksiyon: (https://bybug.net) [android.intent.action.VIEW]`

----------


> `test`

* Bir görevi çalıştırır.

Örnek;

`lavinia test: [sensör]`




