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

## **Lavinia Uygulama Mağazası Nedir?**
Lavinia uygulama mağazası, LaviniaCode içinde çalışan bir bağımsız geliştirici uygulama dağıtım istasyonudur. 

### **Nasıl Hesap Açılır?**
Hesaplar, sizin cihaz kimlikleriniz ile otomatik olarak tarafımızca şifrelenir ve oluşturulur. Siz aynı cihaz ile girdiğiniz sürece otomatik olarak giriş yapılır. Uygulamayı silip yeniden yükleseniz bile hesap açık kalır.

### **Uygulama Nasıl Yüklenir?**
* İstediğiniz bir uygulamayı seçin ve 'Kur' butonuna tıklayın.
* Kurulum tamamlandığında uygulama kurulum paneli gelecektir.

Kurulum ekranı geldiğinde eğer Lavinia'ya güvenlik izinlerini vermediyseniz güvenlik izinlerini verin.

* 'Install' yada 'Yükle' butonlarını kullanarak yükleyin.
* Yüklü olan uygulamalar, Lavinia'da 'Aç' ibaresi barındırır.
### **Neler oluyor?**
'Neler oluyor?' sekmesi, o gün içinde olan olayları kullanıcılara bildirir.
### **Pano Hakkında**
* **Geliştirici Sayısı:** LaviniaCode içinde kaç geliştirici hesabı olduğunu bildirir.
* **Uygulama Sayısı:** LaviniaCode içindeki toplam uygulama sayısını bildirir.
* **Toplam İndirme:** Tüm uygulamaların toplam indirmesi.

### **Taze ve Yepyeni!**
O gün içinde paylaşılan uygulamaları gösterir.

## **Geliştirici Portalı Nedir?**
Geliştirici portalı, geliştiricilerin profilidir. Orada uygulamalarınız hakkında işlemler yapabilirsiniz.

### **Uygulama Nasıl Paylaşılır?**
Geliştirici portalına girdikten sonra, adınızın karşısında yer alan butona tıklayın. Aşağıdaki bilgileri, tarif edildiği şekilde doldurun.

* Uygulamanız için bir Github Repo'su oluşturun.
* 'Assets' adında bir klasör içine uygulama logonuzu ekleyin.
* 'Download' adında bir klasör içine uygulamanızı apk formatında ekleyin.
* Repo içine README.md dosyası oluşturun.

#### **Logo Direkt Bağlantısı Nasıl Alınır?**
Uygulamanızın logosu için direkt bağlantı oluşturmak adına az önce bir repo içine 'Assets' adında bir klasör açtık ve logoyu içine attık.
1. Logoya tıklayın ve açılsın.
2. Görsel ekrana geldiğinde sağ tıklayın ve 'Resim bağlantısını kopyala' butonuna tıklayın.
3. Verdiği bağlantıyı tarayıcıya yapıştırın ve gönderin.
4. Resim tarayıcıda açıldığında link değişmiş olacak. Sonu .jpg, .png veya .jpeg gibi bir dosya uzantısı ile bitmeli.
5. O sizin logonuzun direkt bağlantısı.
 
#### **Uygulama Direkt Bağlantısı Nasıl Alınır?**
Uygulamanızın indirilebilir bir direkt bağlantısına mı ihtiyacınız var? Uygulamanız için direkt bağlantı oluşturmak adına az önce bir repo içine 'Download' adında bir klasör açtık ve uygulamayı içine attık.
1. Uygulama dosyasının üzerine tıklayın.
2. Sağ tarafta 'Download' adında bir buton göreceksiniz.
3. Butona sağ tıklayıp, bağlantıyı kopyalayın.
4. O sizin uygulamanızın direkt indirme bağlantısı.

#### **Uygulama Nasıl Paylaşılır?**


1. Uygulama adı: Uygulamanızın adını yazın.
2. Kısa açıklama: Menüde görünmesi için uygulamanızı birkaç cümle ile özetleyin.
3. Markdown README: Github reposunun bağlantısını verin.
4. Uygulama logosu: Uygulama logonuzun direkt bağlantısını ekleyin.
5. Uygulama Direkt Bağlantısı: Uygulamanızın direkt indirme bağlantısını verin.
6. Paket adı: Uygulamanızın kullanıcılara düzgün bir şekilde sunulabilmesi ve uygulama içinden açılabilmesi adına paket adını eksiksiz bir şekilde verin.
7. Gizlilik Politikası: Bir gizlilik politikası bağlantısı verin. Bir web sitesi veya github bağlantısı olabilir.


## **Lavinia Gizlilik Sözleşmesi**
Lavinia, ücretli, ücretsiz ve reklam destekli bir uygulama olarak geliştirildi. Lavinia, amacına uygun kullanılması için geliştirildi ve amacı dışında olan kullanımlardan ByBug ekibi ve JeaFriday sorumlu tutulamaz.

Bu sayfa, herhangi birinin hizmetimizi kullanmaya karar vermesi durumunda Kişisel Bilgilerin toplanması, kullanılması ve ifşa edilmesi ile ilgili politikalarımız hakkında ziyaretçileri bilgilendirmek için kullanılır.

Hizmetimizi kullanmayı seçerseniz, bu politika ile ilgili bilgilerin toplanmasını ve kullanılmasını kabul etmiş olursunuz. Topladığımız Kişisel Bilgiler, Hizmeti sağlamak ve geliştirmek için kullanılır. Bilgilerinizi bu Gizlilik Politikasında açıklananlar dışında hiç kimseyle kullanmayacağız veya paylaşmayacağız.

**Bu Gizlilik Politikasında kullanılan terimler, bu Gizlilik Politikasında aksi belirtilmedikçe erişilebilen Şartlar ve Koşullarımızdakiyle aynı anlamlara sahiptir.**

### **Bilgi Toplama ve Kullanma Hakkında**
Daha iyi bir deneyim için, Hizmetimizi kullanırken, bize kişisel olarak tanımlanabilecek belirli bilgileri sağlamanızı isteyebiliriz. Talep ettiğimiz bilgiler tarafımızca saklanacak ve bu gizlilik politikasında açıklandığı gibi kullanılacaktır.

Uygulama, sizi tanımlamak için kullanılan bilgileri toplayabilecek üçüncü taraf hizmetlerini kullanıyor.

* Google Analytics for Firebase
* Log Data
* Firebase Database
* Firebase Auth
* One Signal
* Cloudinary
* Unity Ads
* Telegram API
* WordPress API
* Github

Hizmetimizi her kullandığınızda, uygulamada bir hata olması durumunda, telefonunuzda Günlük Verileri adı verilen veri ve bilgileri (üçüncü taraf ürünleri aracılığıyla) topladığımızı size bildirmek istiyoruz. Bu Günlük Verileri, cihazınızın İnternet Protokolü (“IP”) adresi, cihaz adı, işletim sistemi sürümü, Hizmetimizi kullanırken uygulamanın yapılandırması, Hizmeti kullanımınızın saati ve tarihi ve diğer istatistikler gibi bilgileri içerebilir.

Ayrıca 'Geliştirici Portalı' size özel bir hesap açarken; model numarası, cihaz adı, benzersiz kimlik, İnternet Protokolü (“IP”) gibi bilgilerinizi topluyor ve daha sonra kullanmak üzere kaydediyor. Bu bilgiler sistem tarafından kullanılıyor ve siz istemediğiniz sürece bilgiler başka amaçlarla kullanılmıyor.

### **Çerezler Hakkında**
Çerezler, genellikle anonim benzersiz tanımlayıcılar olarak kullanılan az miktarda veri içeren dosyalardır. Bunlar, ziyaret ettiğiniz web sitelerinden tarayıcınıza gönderilir ve cihazınızın dahili belleğinde saklanır.

Bu Hizmet, bu “çerezleri” açıkça kullanmaz. Ancak uygulama, bilgi toplamak ve hizmetlerini iyileştirmek için “çerezler” kullanan üçüncü taraf kod ve kitaplıkları kullanabilir. Bu çerezleri kabul etme veya reddetme ve cihazınıza bir çerezin ne zaman gönderileceğini bilme seçeneğiniz vardır. Çerezlerimizi reddetmeyi seçerseniz, bu hizmetin bazı kısımlarını kullanamayabilirsiniz.


### **Servis sağlayıcıları Hakkında**
Aşağıdaki nedenlerden dolayı üçüncü taraf şirketleri ve kişileri istihdam edebiliriz:

Hizmetimizi kolaylaştırmak için;

Hizmeti bizim adımıza sağlamak için;

Hizmetle ilgili hizmetleri gerçekleştirmek için; veya

Hizmetimizin nasıl kullanıldığını analiz etmemize yardımcı olmak için.

Bu Hizmetin kullanıcılarını, bu üçüncü tarafların Kişisel Bilgilerinize erişimi olduğu konusunda bilgilendirmek istiyoruz. Bunun nedeni, kendilerine verilen görevleri bizim adımıza yerine getirmektir. Ancak, bilgileri başka bir amaçla açıklamamak veya kullanmamakla yükümlüdürler.

### **Güvenliğiniz Hakkında**
Bize Kişisel Bilgilerinizi sağlama konusundaki güveninize değer veriyoruz, bu nedenle bunları korumak için ticari olarak kabul edilebilir yöntemler kullanmaya çalışıyoruz. Ancak internet üzerinden hiçbir aktarım yönteminin veya elektronik depolama yönteminin %100 güvenli ve güvenilir olmadığını ve mutlak güvenliğini garanti edemeyeceğimizi unutmayın.

### **Diğer Sitelere Bağlantılar Hakkında**
Bu Servis diğer sitelere bağlantılar içerebilir. Üçüncü taraf bir bağlantıya tıklarsanız, o siteye yönlendirileceksiniz. Bu harici sitelerin bizim tarafımızdan işletilmediğini unutmayın. Bu nedenle, bu web sitelerinin Gizlilik Politikasını incelemenizi şiddetle tavsiye ederiz. Üçüncü taraf sitelerin veya hizmetlerin içeriği, gizlilik politikaları veya uygulamaları üzerinde hiçbir kontrole sahip değiliz ve sorumluluk kabul etmiyoruz.


### **Çocukların Kullanımı ve Güvenliği Hakkında**
Bu Hizmetler, 16 yaşın altındaki hiç kimseye hitap etmez. 16 yaşın altındaki çocuklardan kişisel olarak tanımlanabilir bilgileri bilerek toplamıyoruz. 16 yaşın altındaki bir çocuğun bize kişisel bilgi verdiğini fark edersek, bunu derhal sunucularımızdan sileriz. Bir ebeveyn veya veli iseniz ve çocuğunuzun bize kişisel bilgiler verdiğini biliyorsanız, lütfen gerekli işlemleri yapabilmemiz için bizimle iletişime geçin.





### **Bu Gizlilik Politikasındaki Değişiklikler Hakkında**
Gizlilik Politikamızı zaman zaman güncelleyebiliriz. Bu nedenle, herhangi bir değişiklik için bu sayfayı periyodik olarak gözden geçirmeniz önerilir. Yeni Gizlilik Politikasını bu sayfada yayınlayarak herhangi bir değişikliği size bildireceğiz.

Bu politika 2022-12-16 tarihinden itibaren geçerlidir.

Bu Gizlilik Politikası hakkında geribildirim bırakmak için lütfen bybugofficial@gmail.com’a veya jeafriday@gmail.com'a e-posta göndermekten çekinmeyin.
