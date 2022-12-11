<p align="center">
  <img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/christmasLaviniaLogo.png" width="300" />
</p>


## **🎄Lavinia'ya Yeni Yıl Coşkusu Geldi!🎉**
Lavinia, yepyeni yılbaşı teması ile kullanıcılarına sürpriz yapmaya hazırlanıyor! Yılbaşı temasının adı: **Süslü Noel🎄**


<h3 align="center"><b>Topluluk ve Sosyal Medya:</b></h3>
<p align="center"> <a href="https://t.me/laviniacode" target="_blank"> <img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/Icons/telegram.png" alt="Telegram" width="40" height="40"/> </a> <a href="https://www.youtube.com/@KirmiziPatika" target="_blank"><img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/Icons/youtube.png" alt="YouTube" width="40" height="40"/> </a> <a href="https://instagram.com/kirmizipatika.ml" target="_blank"> <img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/Icons/instagram.png" alt="Instagram" width="40" height="40"/> </a> <a href="https://discord.com/invite/8E4atXXZbn" target="_blank"> <img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/Icons/discord.png" alt="Discord" width="40" height="40"/> </a></p>



## **Lavinia Code Nedir?**
Lavinia Code, içerisinde bulunan araçları sayesinde, cihaz ile kendi sistemi arasında bağ kurarak normalde yapılması karmaşık olan işlemleri kolayca yapmanıza olanak tanır. Yerel ağ’da kodlar yürütmek, global ağ’da get/post requests yapmak, Telegram botları yaratmak/yönetmek, mini uygulamalar yürütmek gibi özellikleri bulunuyor. İçerisine geliştirdiğiniz veya önceden geliştirilmiş mini uygulamaları yükleyebileceğiniz bu program; cihazınıza yerleşmiş mini bir işletim sistemi gibi davranıyor. Temel amacı, insan hayatını daha anlaşılabilir ve kolay bir hale getirmek. Gelecekte sağlık, seyahat (turizm), muhasebe, şirket yönetimi gibi alanlarda da kullanılması planlanıyor.



<p align="center">
  <img src="https://raw.githubusercontent.com/JeaFrid/LaviniaCode/main/AssetsGlobal/LaviniaPhone1.png" width="300" />
</p>




## **Lavinia Code Dökümanları**
### **Kodlama Paneli Nasıl Çalışır?**

Lavinia kodları, kısa ve anlamlı olacak şekilde düzenlenmiştir. Bir cümle yapısına sahip, giriş-gelişme-sonuç prensibiyle çalışır. Giriş; kod parçacığının hangi modül içerisinde çalışacağını belirtir. Gelişme; modül içerisinden hangi komutu çalıştıracağını belirtir. Sonuç; parametreleri aldıktan sonra kodu çalıştırıp sonuç vermeyi hedefler.

Lavinia kodlama panelinde prosedür bellidir;


```
ModülAdı Method: (değer parametresi) [referans parametre] {anahtar parametre}: mesaj-girdi
```
`ModülAdı` Kullanılan modül. *(örn: lavinia)*

`Method` Kullanılan modül için bir method. *(örn: web)*

`(parametre)` Method'un ihtiyacı olan veri. *(örn: https://...)*

`[referans parametre]` Method'un ihtiyacı olan veri. *(örn: [dosya/dizin])*

ek olarak;

`{anahtar parametre}` Method'un ihtiyacı olan veri. *(örn: {@chatID})*

operatörler;

`:` İki ayaklı kodlamalarda, bir tanım yazar. *(örn: ...{@chatID}: Merhaba!)*

`""` Method'un dışına mesaj yazabilir. (her zaman çalışmaz.) *(örn: "Merhaba!")*

`(())` Liste tanımlar. (her zaman çalışmaz.) *(örn: (("1","2")) )*

`%` Değişken tanımlar. (her zaman çalışmaz.) *(örn: %değişkenİçeriği%)*


Tüm veriler doğru bir şekilde makineye teslim edildiğinde işlemler gerçekleşir.




### **Kütüphaneler Nasıl Çalışır?**
Kütüphaneler, kütüphane kodundan sonra süslü parantezler arasına yazılan bir lavinia methodudur. Evet, bir method'dur. Yani tek başına çalışamaz. lavinia modülü içinden çağırılabilir.

Örnek;

```
lavinia kütüphane {jeafriday internet (al) [https://]}
```

**Bu method, normalde işlenmeyen komutları işleyebilir bir hale getirmek ve kolay bir yazıl klavuzuna geçebilmek adına yapıldı. Yani her komut için bir modül kullanmak yerine, artık kütüphaneler ile derli toplu bir yazım mekaniği kullanılıyor.**

### **Uygulamalar Menüsü Nasıl Çalışır?**

Uygulamalar menüsü, kodlama panelinden bağımsız bir kodlama paneline sahiptir. Komutları içerisinde dolar ($) işareti bulunur ve bu yüzden kodlama panelinde dolar işareti kullanılamaz. Bu özellik yalnızca uygulamalar menüsüne özeldir.


Uygulamalar menüsünde, önceden tanımlanmış özellikler bulunur. Web oturumu başlatmak, aktivite başlatmak veya liste/metin işlemek gibi yetenekleri vardır.

## **Kodlama Dökümanları**

Kodlama dökümanları, size tüm kod parçacıklarını sağlar. Unuttuğunuz kodların ne işe yaradığını burada inceleyerek hatırlayabilirsiniz.

### **Lavinia**
'Lavinia' kod parçacığı, Lavinia araçlarında kullanılır. Ekrana yazı yazdırmak, web araçlarını kullanmak gibi.

> `yazdır`

* Ekrana bir yazı yazdırır.

Örnek;

`lavinia yazdır: (Merhaba Dünya!)`

----------

> `güncelle`

* Lavinia'nın tüm modüllerini günceller.

Örnek;

`lavinia güncelle`

----------

> `internet`

* İnternet bağlantısını sınar.

Örnek;

`lavinia internet`

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




### **dosya**
'Dosya' kod parçacığı, cihazın yerel dosya araçlarında kullanılır. Uygulamayı yüklemek, dosya veya klasör açmak gibi.

> `kontrol`

* Bir dizin veya dosyanın varlığını kontrol eder.

Örnek;

`dosya kontrol: (/Download) [dizin]`

----------


> `yükle`

* Dizinden bir uygulama dosyasını cihaza kurmaya çalışır.

Örnek;

`dosya yükle: (/Download/test.apk)`

----------


> `yeni`

* Bir dosya yaratır ve içine yazı yazar.

Örnek;

`dosya yeni: [/Download/yeni.txt] (Merhaba günlük..)`

----------




### **paket**
'paket' kod parçacığı, cihazın yerel araçlarında paket işlemleri için kullanılır. Uygulamayı yüklemek veya kaldırmak gibi.

> `kur`

* Dizinden bir uygulama dosyasını cihaza kurmaya çalışır.

Örnek;

`paket kur: (/Download/test.apk)`

----------


> `kaldır`

* Uygulamanın paket adından, uygulamayı kaldırmayı dener.

Örnek;

`paket kaldır: (lavinia.bybug.net)`


----------



### **telegram**
'telegram' kod parçacığı, cihazın global Telegram araçlarında kullanılır. Mesaj göndermek gibi.

> `bot (gönder)`

* Telegram Bot ile mesaj gönderir.
* 'gönder' adlı komut ile çalıştırılır.

Örnek;

`telegram bot (gönder) [%botTOKEN%] {@chatID}: Merhaba!`

----------



### **bybug**
'bybug' kod parçacığı, ByBug araçlarını kullanmanıza izin verir.

> `ads`

* Reklamlandırma servisiyle ilgili modül.

Örnek;

`bybug ads (kaynak)`


----------


### **özel**
Özel araçlar.

> `github`

* Github ile bağ kuran bir araç. Bu araç Lavinia Creator için geliştirilmiştir. Daha fazla bilgi için [buraya](https://github.com/JeaFrid/LaviniaCode/tree/main/Lavinia%20Creator/Create%20Apps) tıklayın.

Örnek;

`özel github (oluştur) [https://]`


## **Kütüphaneler**

Kütüphaneler, kütüphane kodundan sonra süslü parantezler arasına yazılan bir lavinia methodudur. Evet, bir method'dur. Yani tek başına çalışamaz. lavinia modülü içinden çağırılabilir.

Örnek;

```
lavinia kütüphane {jeafriday internet (al) [https://]}
```

**Bu method, normalde işlenmeyen komutları işleyebilir bir hale getirmek ve kolay bir yazıl klavuzuna geçebilmek adına yapıldı. Yani her komut için bir modül kullanmak yerine, artık kütüphaneler ile derli toplu bir yazım mekaniği kullanılıyor.**

▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼ ▼

### **jeafriday**
JeaFriday kütüphanesi(modül), çeşitli araçlar içerir.

### **internet**
* Requests işlemlerini barındırır.
> `al`

Örnek;

`{jeafriday internet (al) [https://]}`


----------



