# 3.	KULLANILAN ARAÇ VE YÖNTEM

## 3.1. Ön Uç Bileşenleri
### 3.1.1. Node.js 
Node.js [32], platformlar arası çalışabilen JavaScript çalıştırma ortamıdır. Ayrıca Node.js, asenkron ve olay tabanlı bir yapıya sahiptir. Bu, Node.js'in aynı anda birçok işlemi yönetebilmesini sağlar. 
#### 3.1.1.1. React 
JavaScript uygulamaları geliştirmek için bir kütüphanedir. Kullanıcı arayüzü bileşenlerini oluşturmak ve yönetmek için kullanılır. React [33], sanal DOM (Document Object Model) kullanarak performansı artırır. Sanal DOM, gerçek DOM ağacının hafızada bir 

kopyasını oluşturur ve her güncellemede bu kopyayı gerçek DOM ile karşılaştırır. Bu sayede sadece değişen parçalar güncellenir, bu da uygulamanın daha verimli çalışmasını sağlar.
#### 3.1.1.2. Vite 
Vue.js, React ve Svelte gibi modern JavaScript kütüphaneleri ve çerçeveleri için optimize edilmiş bir geliştirme sunucusu ve derleyicidir. Geleneksel derleme süreçlerinden farklı olarak, Vite [34], geliştirme sunucusunu gerçek zamanlı olarak kodu derlemek ve hızlıca değişiklikleri görmek için kullanır. Bu, geliştirme sürecini hızlandırır ve anlık geri bildirim alınmasını sağlar. Ayrıca, sadece gerekli olan kod parçalarını yükleyip gereksiz yüklemelerden kaçınarak daha kısa yükleme süreleri sağlar.
#### 3.1.1.3. @fortawesome/fontawesome-svg-core 
Font Awesome [35], çeşitli semboller ve ikonlar kullanımını sağlar.
#### 3.1.1.4. axios 
Axios [36], HTTP istekleri yapmak için kullanılan bir JavaScript kütüphanesi.
#### 3.1.1.5. i18next 
i18next [37], metin çevirisi ve dil değiştirme işlevlerini sağlar.
#### 3.1.1.6. ApexCharts 
ApexCharts [38], web tabanlı veri görselleştirme için kullanılan açık kaynaklı bir JavaScript kütüphanesidir.  Çizgi grafikleri, alan grafikleri, sütun grafikleri, dağılım grafikleri, pasta grafikleri, radar grafikleri gibi çeşitli grafik türlerini destekler. Grafiklerin renkleri, etiketleri, eksenleri, arka planı ve diğer birçok özelliği özelleştirilebilir. Dinamik olarak veri eklemek, güncellemek veya kaldırmak için API'lar sağlar. Grafikler, farklı ekran boyutlarına uyacak şekilde otomatik olarak yeniden boyutlandırılabilir.
## 3.2. Arka Uç Bileşenleri
### 3.2.1. Spring Boot 
Java tabanlı bir açık kaynaklı bir çerçevedir. Bu, Java uygulamalarının hızlı bir şekilde oluşturulmasını ve dağıtılmasını sağlayan bir altyapı sunar. Spring Boot [32], Spring Framework'ün üzerine inşa edilmiştir ve Spring projelerinin yapılandırma ve dağıtım süreçlerini büyük ölçüde kolaylaştırır. Spring Boot, varsayılan değerler, otomatik yapılandırma ve sürüm bağımsızlığı gibi birçok özelliği sayesinde geliştiricilerin gereksiz yapılandırma kodunu yazmaktan kaçınmasını sağlar ve geliştirme sürecini hızlandırır.
Spring Boot, birçok popüler Java teknolojisini ve dış sistemleri entegre etmek için kolay kullanım sağlar. Veri tabanları, mesaj kuyrukları, güvenlik çözümleri ve diğer dış sistemlerle kolayca entegre edilebilir.Spring Boot, yerleşik olarak Tomcat, Jetty veya Undertow gibi popüler web sunucularını destekler. Bu, uygulamaların kendi içinde bir web sunucusunda çalıştırılmasını sağlar ve ayrı bir web sunucusuna ihtiyaç duymaz.
### 3.2.2. jsoup 
Jsoup [39], HTML ve XML belgelerini işlemek için kullanılan bir kütüphanedir. Belirli bir web sayfasından veri çekmek veya belirli bir yapıyı analiz etmek gibi işlemler için kullanılır.HTML belgesini DOM (Document Object Model) ağacına dönüştürür ve bu ağaç üzerinde gezinme ve işlem yapma imkânı sağlar. Bu, HTML belgesindeki belirli elementlere, özelliklere veya metinlere erişmeyi kolaylaştırır. CSS seçicilerini kullanarak belirli HTML elementlerini seçmenizi sağlar. Bu, belirli bir yapıdaki elementlere kolayca erişmenizi ve işlemenizi sağlar. HTML formlarını analiz ederek form verilerine erişmenizi sağlar. Bu, web sayfalarındaki form verilerini otomatik olarak doldurmak veya form gönderme işlemlerini simüle etmek için kullanılabilir. HTML belgelerinden istenmeyen verilerin temizlemesine olanak tanır. Bu, web kazıma veya veri madenciliği gibi işlemler için kullanılabilir.
## 3.3. Yapay Zekâ Bileşenleri
### 3.3.1. NumPy 
Python programlama dilinde bilimsel hesaplamalar için kullanılan açık kaynaklı bir kütüphanedir. NumPy [40], çok boyutlu dizileri ve matrisleri işlemek için temel veri yapısı olan ndarray'i (N-dimensional array) sağlar. Ayrıca, bu diziler üzerinde matematiksel, mantıksal, istatistiksel ve diğer işlemleri gerçekleştirmek için geniş bir matematiksel fonksiyon ve metot koleksiyonu sunar.
Diziler üzerinde toplama, çıkarma, çarpma, bölme, üs alma, trigonometrik fonksiyonlar, logaritmik fonksiyonlar gibi matematiksel işlemleri gerçekleştirmeyi sağlar.
### 3.3.2. pandas 
Python programlama dilinde veri analizi ve veri manipülasyonu için kullanılan güçlü ve esnek bir açık kaynaklı kütüphanedir. Pandas [41], veri yapılarını ve veri analizi araçlarını sağlayarak veri işleme süreçlerini büyük ölçüde kolaylaştırır. DataFrame pandas'ın en önemli veri yapısıdır. DataFrame, satırlar ve sütunlar içeren bir tabloyu temsil eder. Veri analizi ve manipülasyonu için çeşitli fonksiyonları ve yöntemleri içerir. Series tek boyutlu etiketli bir diziyi temsil eder. DataFrame'deki her sütun aslında bir Series nesnesidir. Series, Python'un yerleşik liste veya dizi veri yapısına benzer ancak etiketli indekslerle daha esnek bir şekilde çalışır.
Pandas, CSV, Excel, SQL veri tabanları, JSON ve diğer birçok veri formatından veri içe aktarma ve dışa aktarma işlemlerini destekler. Pandas, eksik verileri ele alma, veri dönüşümleri yapma, veri filtreleme, gruplama, sıralama ve birleştirme gibi veri temizleme ve düzenleme işlemleri için geniş bir işlev yelpazesi sunar. Pandas, veri analizi için bir dizi istatistiksel fonksiyon ve metod sağlar. Bu, toplam, ortalama, standart sapma, kovaryans, korelasyon gibi temel istatistiksel hesaplamaları gerçekleştirmeyi içerir.
### 3.3.3. TensorFlow 
Google tarafından geliştirilen açık kaynaklı bir makine öğrenimi ve derin öğrenme kütüphanesidir. Genel olarak, büyük ölçekli yapay zekâ projeleri geliştirmek için kullanılır. TensorFlow [42], makine öğrenimi modellerinin oluşturulması, eğitilmesi, değerlendirilmesi ve dağıtılması için bir dizi araç ve kaynağı içerir. TensorFlow, grafik tabanlı bir hesaplama modeli kullanır. Bu, modeli oluştururken ve eğitirken bir dizi işlemi tanımlamanıza ve bu işlemleri optimize etmek için TensorFlow'un otomatik farklılaşma yeteneklerinden yararlanmanıza olanak tanır. Bu model, veri akışı grafiği olarak adlandırılır ve birbiriyle bağlantılı düğümlerden oluşur, her bir düğüm bir matematiksel işlemi temsil eder.
TensorFlow, farklı makine öğrenimi ve derin öğrenme modelleri oluşturmanıza olanak tanır. Evrişimli sinir ağları (CNN'ler), uzun-kısa süreli bellekli ağlar (LSTM'ler), derin sinir ağları (DNN'ler) ve diğer birçok model türünü destekler. TensorFlow, model oluşturma, eğitim, hiperparametre ayarlama, model değerlendirme ve dağıtım için bir dizi araç ve kaynağı içerir. Bu, kullanıcıların projelerini daha verimli bir şekilde yönetmelerini sağlar. TensorFlow, derin öğrenme, görüntü işleme, doğal dil işleme, ses tanıma gibi pek çok alanında kullanılır.
### 3.3.4. Keras 
TensorFlow 2.0'den itibaren Keras [43], TensorFlow'un içinde bulunan yüksek seviyeli bir derin öğrenme API'ıdır. TensorFlow'un güçlü hesaplama yeteneklerini ve altyapısını kullanarak derin öğrenme modellerini oluşturmak, eğitmek ve değerlendirmek için bir arayüz sağlar. Keras evrişimli sinir ağları (CNN'ler), tekrarlayan sinir ağları (RNN'ler), uzun-kısa süreli bellekli ağlar (LSTM'ler), derin sinir ağları (DNN'ler) ve diğer birçok model türünü oluşturulmasını sağlar. Farklı optimizasyon algoritmaları ve hiperparametre ayarları kullanarak modelleri optimize edilir.
#### 3.3.4.1. Adam
Adaptive Moment Estimation (Adam) optimizasyon algoritması, birinci dereceden bir gradyan tabanlıdır. Adam, veri özelliklerine dayalı olarak öğrenme hızını ayarlama yeteneği nedeniyle, zaman değişkenli süreçleri öğrenmek için uygundur.
#### 3.3.4.2. Adadelta
Optimizasyon algoritması, makine öğrenmesi projelerinde büyük veri kümeleriyle başa çıkmak için geleneksel dereceli alçalma yöntemlerinin hesaplamalı verimsizliğini ele alan Gradient Descent algoritmasının bir çeşididir.
#### 3.3.4.3. Adamax
Optimizasyon algoritması, Adam’ın bir çeşidi olup, sonsuz norma dayanır. Adamax, birinci dereceden bir gradyan tabanlı optimizasyon yöntemidir.
#### 3.3.4.4. Stochastic Gradient Descent
Stochastic Gradient Descent (SGD) optimizasyon algoritması, bir hedef fonksiyonun negatif gradyanını takip eden bir optimizasyon algoritmasıdır. SGD, her iterasyonda bir veri alt kümesini kullanarak gradyanı tahmin eder.
#### 3.3.4.5. RMSprop
Root Mean Square Propagation (RMSprop) optimizasyon algoritması, SGD algoritmasını bazı sorunlarını çözmek için tasarlanmıştır. RMSprop, karelerinin hareketli bir ortalamasını kullanarak öğrenme hızını adapte eder. Bu, her parametrenin öğrenme hızını adaptif bir şekilde ayarlayarak eğitim sırasında daha stabil bir konverjans sağlar.
## 3.4. Geliştirilen Çevrimiçi Ürün Fiyat Takip Uygulaması
Kullanıcı tema değiştirme, ürün arama, ürünleri kategorilerine göre filtreleme, favorilere ekleme, favorilerden kaldırma, profiline erişme, ürün detaylarını görme gibi çoğu işlemi yapabileceği Şekil 3.4.1. de gösterilmiştir.

   ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/1.png)
   
Şekil 3.4.1. Uygulama anasayfa ekran görüntüsü.

### 3.4.1. Kullanıcı Kayıt İşlemi
Kullanıcı ad, soyad, e-posta ve şifresini istenilen formatta girerek kayıt işlemini gerçekleştirir. Şekil 3.4.1.1. de gösterilmiştir. Eğer kullanıcı istenilen bilgileri yanlış formatta girerse veya boş bırakırsa uyarı gösterilir ve “Kayıt ol” butonuna tıklaması engellenir. Şekil 3.4.1.2. de gösterilmiştir. Kullanıcı bilgileri istenen şekilde girdiyse kayıt başarılı mesajı döndürülür. Şekil 3.4.1.3 de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/2.png)
  
Şekil 3.4.1.1. Uygulama kullanıcı kayıt ekranı ekran görüntüsü.

Çizelge 3.4.1. Kayıt Girdi Şartları.
Ad	Zorunlu, sadece harfler ve boşluk kullanılabilir.
Soyad	Zorunlu, sadece harfler ve boşluk kullanılabilir.
E-Mail	Zorunlu, ???@???.?? formatında olmalıdır.
Şifre	Zorunlu, en az bir küçük harf, bir büyük harf ve bir rakam içermeli ve altı karakter ya da daha uzun olmalıdır.
Tekrar Şifre	Zorunlu, “Şifre” ile aynı olmalıdır.

Çizelge 3.4.1. de kullanıcıların kayıt olması için istenilen veriler, bu verilerin kayıt işlemi için zorunlu ya da isteğe bağlı olma durumu ve bu verilerin hangi formatlarda olması gerektiği gösterilmektedir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/3.png)
  
Şekil 3.4.1.2. Kayıt Hatası.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/4.png)
  
Şekil 3.4.1.3. Kayıt Tamamlandı.

Çizelge 3.4.2. de kullanıcıların veri tabanında nasıl tutulduğu gösterilmektedir. Veri tabanında bulunan id sütunu, her kullanıcıya benzersiz bir kimlik numarası atar ve birincil anahtar olarak kullanılır. Bu sayede her kullanıcı veri tabanında tekil olarak tanımlanır ve diğer tablolarda bu kimlik numarası ile ilişkilendirilebilir. Veri tabanında bulunan first_name sütunu, kullanıcının adını içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu sütun, kullanıcıların kişisel isim bilgilerini saklamak için kullanılır. Veri tabanında bulunan last_name sütunu, kullanıcının soyadını içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu sütun, kullanıcıların aile adlarını saklamak için kullanılır. Veri tabanında bulunan email sütunu, kullanıcının e-posta adresini saklar. Maksimum 255 karakter uzunluğunda olabilir ve benzersiz olmalıdır. Ayrıca, e-posta adresleri doğrulanmış olmalıdır, bu da kullanıcılarla iletişim kurmak ve kimlik doğrulama işlemlerinde kullanılmak üzere güvenli bir yol sağlar. Veri tabanında bulunan password sütunu, kullanıcının şifresini saklar. Maksimum 255 karakter uzunluğunda olabilir. Şifreler güvenlik için Bcrypt ile hashlenmiş olarak saklanır, böylece düz metin olarak kaydedilmez ve yetkisiz erişimlere karşı korunur. Veri tabanında bulunan activation sütunu, kullanıcının hesabının aktif olup olmadığını belirtir. true değeri hesap aktif, false değeri ise hesabın pasif olduğunu gösterir. Bu sütun, kullanıcıların hesaplarını etkinleştirme ve devre dışı bırakma işlemlerini yönetir. Veri tabanında bulunan activation_token sütunu, kullanıcı hesabının aktivasyonu için kullanılan tokenı içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu token, hesap doğrulama ve aktivasyon süreçlerinde kullanılır. Veri tabanında bulunan image sütunu, kullanıcının profil resmi URL'sini saklar. Maksimum 255 karakter uzunluğunda olabilir. Bu sütun, kullanıcıların profil resimlerini sunucuda veya bulut tabanlı bir depolama hizmetinde saklamak için kullanılır.Veri tabanında bulunan password_reset_token sütunu, Kullanıcının şifresini sıfırlamak için kullanılan tokenı içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu token, şifre unutma veya sıfırlama işlemlerinde kullanılır.Veri tabanında bulunan provider sütunu, kullanıcının kayıt olduğu sağlayıcıyı belirtir. Bu sütun, kullanıcının hangi platformdan kayıt olduğunu göstermek için kullanılır ve 'LOCAL', 'GOOGLE', 'FACEBOOK' gibi seçenekler içerebilir. Bu bilgi, kullanıcıların hangi üçüncü parti hizmetler üzerinden giriş yaptığını takip etmek için önemlidir. Veri tabanında bulunan role sütunu, kullanıcının rolünü belirtir. Bu sütun, kullanıcının yetki seviyesini ve sistemdeki rolünü tanımlar. Örneğin, 'USER' standart kullanıcıyı, 'ADMIN' ise yönetici kullanıcıyı temsil edebilir. Bu, farklı kullanıcı türlerine farklı erişim hakları vermek için kullanılır.

Çizelge 3.4.2. Kullanıcılar Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama

id	int	birincil anahtarıdır ve her kullanıcıya benzersiz bir kimlik numarası atar.
first_name	varchar(255)	Kullanıcının adı. Maksimum 255 karakter uzunluğunda olabilir.
last_name	varchar(255)	Kullanıcının soyadı. Maksimum 255 karakter uzunluğunda olabilir.
email	varchar(255)	Kullanıcının e-posta adresi. Maksimum 255 karakter uzunluğunda olabilir. Benzersiz ve doğrulanmış olmalıdır.
password	varchar(255)	Kullanıcının şifre bilgisi. Maksimum 255 karakter uzunluğunda olabilir. Şifreler genellikle hashlenmiş olarak saklanır.
activation	boolean	Kullanıcının hesabının aktif olup olmadığını belirtir. true aktif, false pasif anlamına gelir.
activation_token	varchar(255)	Kullanıcı hesabının aktivasyonu için kullanılan token. Maksimum 255 karakter uzunluğunda olabilir.
image	varchar(255)	Kullanıcının profil resmi URL'si. Maksimum 255 karakter uzunluğunda olabilir.
password_reset_token	varchar(255)	Kullanıcının şifresini sıfırlamak için kullanılan token. Maksimum 255 karakter uzunluğunda olabilir.
provider	enum	Kullanıcının kayıt olduğu sağlayıcıyı belirtir (örneğin, 'LOCAL', 'GOOGLE', 'FACEBOOK').
role	enum	Kullanıcının rolünü belirtir (örneğin, 'USER', 'ADMIN').

### 3.4.2. Kullanıcı Giriş İşlemi

Kullanıcı kayıtlı ise e-posta ve şifre bilgisini kullanarak ya da “Google ile Giriş” butonunu kullanarak giriş yapabilir. Şekil 3.4.2.1. de gösterilmiştir. Eğer şifresini unuttuysa şifremi unuttum seçeneğine tıklayabilir. Eğer kullanıcı Çizelge 3.1'deki uygun olmayan formatta girdi yazarsa uyarı gösterilir ve “Giriş” butonuna basması engellenir. Şekil 3.1.2.2. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/5.png)
  
Şekil 3.4.2.1. Uygulama giriş arayüzü ekran görüntüsü.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/6.png)
  
Şekil 3.4.2.2. Uygulama hatalı giriş arayüzü ekran görüntüsü.

### 3.4.3. Hesap Doğrulama
Kullanıcıya kayıt işleminin başarılı bir şekilde gerçekleştirdiğinde hesabını onaylaması için e-posta gönderildiğini gösteren bir pop-up gösterilir. Şekil 3.4.3.1. de gösterilmiştir. Eğer kullanıcının aktivasyon durumu onaylanmadıysa profilinden “Email Aktifleştirme” butonuna basıp gelen e-postadan hesabını aktifleştirdikten sonra giriş sayfasından hesabına giriş yapıp hesabını kullanabilir. Şekil 3.4.3.2. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/7.png)
  
Şekil 3.4.3.1. Örnek Aktivasyon E-Postası Örneği.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/8.png)
  
Şekil 3.4.3.2. Aktivasyon E-Postası Göndermeyi Sağlayan Ekranın Örneği.

Şekil 3.4.3.3. de kullanıcıların hesaplarını yeni oluşturduklarında detayları Çizelge 3.4.2. de bulunan olan activation ve activation_token değişiminin örneği gösterilmektedir. Kullanıcı yeni bir hesap oluşturduğunda rastgele bir token oluşturulur. Kullanıcı Şekil 3.4.3.1. de gösterilmiş olan e-postada bulunan “Buraya tıklayın” yazısına tıkladığında token silinir ve activation değeri 0’dan 1’e çevirilir. Kullanıcı bu işlemi yapmadan sistemi kullanamamaktadır.
  

 ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/9.png)
 
Şekil 3.4.3.3. Aktivasyon Durumunu Gösteren Veri Tabanı Tablosu Kayıtları Örneği

### 3.4.4. Şifre Sıfırlama

Kullanıcı şifresini unutması durumunda e-posta bilgisini girerek şifre sıfırlama talebinde bulunabilir. Şekil 3.4.4.1. de gösterilmiştir. Kullanıcıya şifre sıfırlaması benzersiz bir bağlantı gönderilir. Şekil 3.4.4.2. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/10.png)
  
Şekil 3.4.4.1 Şifre Sıfırlama Talebi Ekranı Örneği.

 ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/11.png)
 
Şekil 3.4.4.2 Şifre Sıfırlama Elektronik Postası Örneği

### 3.4.5. Profil Bilgileri

Kullanıcı adının üstüne tıklayıp profiline ulaşabilir. Profilinden ad, soyad, e-posta veya şifre bilgilerini güncelleyebilir. Kullanıcının veri tabanından bulunan bilgileri inputlarda placeholder olarak gösterilir. Kullanıcı bilgi güncellemesi yapmak istemiyorsa iptal butonuna basarak çıkabilir. Kullanıcı e-posta adresi aktif değilse "Email Aktifleştirme" butonuna basarak hesap aktifleştirme maili alabilir. Şekil 3.4.5. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/12.png)
  
Şekil 3.4.5. Profil Ekranı Örneği.

#### 3.4.5.1. E-Posta Güncelleme

Kullanıcının mevcut e-posta adresi yer tutucu şeklinde gösterilir. Kullanıcı yeni e-posta bilgisini girip güncelle butonuna basarak e-posta adresi bilgisini güncelleyebilir. Kullanıcının oturumu sonlandırılır ve yeni e-posta adresiyle girmesi istenir. Ayrıca yeni e-posta adresine bir aktifleştirme maili gönderilir. Şekil 3.4.5.1. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/13.png)
  
Şekil 3.4.5.1. E-Posta Güncelleme Ekranı Örneği.

#### 3.4.5.2. Şifre Güncelleme

Kullanıcı şifre güncelleme sayfasına gelir. Mevcut şifre ve yeni şifresinin girilmesi istenir. Girilecek şifrenin bir büyük harf, bir küçük harf ve bir sayı içermesi ve altı karakter ya da daha uzun olması istenir. Kullanıcı güncelle butonuna bastığında oturumu sonlandırılır ve yeni şifre ile giriş yapması istenir. Şekil 3.4.5.2. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/14.png)
  
Şekil 3.4.5.2. Şifre Güncelleme Ekranı Örneği.

### 3.4.6. Ürün Arama

Kullanıcı bir ürünün linkini aradığında jsoup ile ürünün bilgileri tanımlanmış olan “id” veya “class” attribute'larından çekilir ve aranan link veri tabanına kaydedilir. Jsoup kazıma işlemini gerçekleştikten sonra elde edilen veriler veri tabanına kaydedilir. Kullanıcının kazıdığı ürünler yeniden eskiye doğru sıralı bir şekilde gösterilir. Veri tabanına kaydedilen ürünün detaylarına, ürün görsel üzerine tıklanarak ya da ürün ismine tıklanarak ulaşılabilir. Ürünü, listeden sil butonuna basıp silebilir veya favorilere ekle butonuna basıp ürünü favorilere ekleyebilir. Şekil 3.4.6.1. de gösterilmiştir. Favoriler sayfasında eklenen ürünleri listesini taşınabilir belge biçimi (PDF) halinde indirebilir. Ürünlerin fiyatları “favorites” tablosunda “id”leri olduğu sürece her saat başı kontrol edilir. Bunun için arka tarafta bir zamanlayıcı kullanılır. @Scheduled(cron = "0 0 */1 * * *") ile her saat başı kontrol edilir. 

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/15.png)
  
Şekil 3.4.6.1. Ürün Arama Ekranı Örneği.

Ürünlerin veri tabanında nasıl tutulduğu Çizelge 3.4.3. de gösterilmektedir. Veri tabanında bulunan product_id sütunu, her ürüne benzersiz bir kimlik numarası atar ve birincil anahtar olarak kullanılır. Bu sayede her ürün veri tabanında tekil olarak tanımlanır ve diğer tablolarda bu kimlik numarası ile ilişkilendirilebilir. Bu sütun, ürünlerin kolayca izlenebilmesini ve yönetilebilmesini sağlar. Veri tabanında bulunan product_name sütunu, ürünün adını içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu sütun, ürünlerin adlarını saklamak için kullanılır ve kullanıcıların veya müşterilerin ürünleri tanımlamasına yardımcı olur. Veri tabanında bulunan product_price sütunu, ürünün fiyatını içerir. Ondalık sayı olarak saklanır, bu da ürünlerin fiyat bilgilerini kesin ve doğru bir şekilde tutmayı sağlar. Fiyat bilgisi, e-ticaret işlemlerinde kritik öneme sahiptir ve bu sütun, ürünlerin satış fiyatlarını içerecek şekilde tasarlanmıştır. Veri tabanında bulunan product_url sütunu, ürünün detaylı sayfasına yönlendiren bağlantıyı içerir. Bu alan uzun metin olarak saklanır, çünkü URL'ler uzun olabilir. Bu sütun, kullanıcıların ürünün detaylı bilgilerini görmek için tıklayabilecekleri bir bağlantıyı saklar. Veri tabanında bulunan product_image sütunu, ürünün resminin URL'sini içerir. Maksimum 255 karakter uzunluğunda olabilir. Bu sütun, ürünlerin görsel tanıtımını yapmaya yarayan resimlerin URL'lerini saklar. Müşterilerin ürünleri görsel olarak tanıması ve değerlendirmesi için önemlidir. Veri tabanında bulunan product_description sütunu, ürünün detaylı açıklamasını içerir. Uzun metin olarak saklanır, böylece ürün hakkında ayrıntılı bilgi verilebilir. Bu sütun, ürünlerin özelliklerini, kullanım alanlarını ve diğer önemli bilgileri açıklamak için kullanılır. Veri tabanında bulunan product_category sütunu, ürünün kategorisini belirtir. Kategori tablosuna bir dış anahtar olarak kullanılır, böylece ürünler kategorilere ayrılabilir. Bu sütun, ürünlerin belirli kategoriler altında gruplanmasını sağlar ve kategoriler arasında ilişkiler kurarak ürünlerin yönetimini ve aranılabilirliğini kolaylaştırır.

Çizelge 3.4.3. Ürünler Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama
product_id	int	birincil anahtarıdır ve her ürüne benzersiz bir kimlik numarası atar.
product_name	varchar(255)	Ürünün adını içerir. Maksimum 255 karakter uzunluğundadır.
product_price	double	Ürünün fiyatını içerir. Ondalık sayı olarak saklanır
product_url	longtext	Ürünün detaylı sayfasına yönlendiren bağlantıyı içerir. Bu alan uzun metin olarak saklanır, çünkü URL'ler uzun olabilir.
product_image	varchar(255)	Ürünün resminin URL'sini içerir. Maksimum 255 karakter uzunluğundadır.
product_description	longtext	Ürünün detaylı açıklamasını içerir. Uzun metin olarak saklanır, böylece ayrıntılı bilgi verilebilir.
product_category	int	Ürünün kategorisini belirtir. Kategori tablosuna bir dış anahtar olarak kullanılır, böylece ürünler kategorilere ayrılabilir.

### 3.4.7. Favorilerin Görüntülenmesi

Favorilere eklenen ürünler, favoriler sayfasında listelenir. Aynı zamanda favorilerden çıkarma işlemini burada da yapılabilir. Şekil 3.4.7.1. de gösterilmektedir. Favorilerin veri tabanı tablosunun sütunlarının bilgileri ve bu sütunların amaçları Çizelge 3.4.4. de gösterilmektedir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/16.png)
  
Şekil 3.4.7.1. Favoriler Sayfası Ekranı Örneği.

Veri tabanında bulunan id sütunu, her ürün-kullanıcı ikilisine benzersiz bir kimlik numarası atar ve birincil anahtar olarak kullanılır. Bu sayede her her ürün-kullanıcı ikilisi veri tabanında tekil olarak tanımlanır ve bu sayede kullanıcı ile ilişkili ürünler favoriler sayfasında gösterilir. Veri tabanında bulunan user_id sütunu, kullanıcılar tablosunun id sütunundan yabancı anahtar olarak alınır. Veri tabanında bulunan product_id sütunu, ürünler tablosunda bulunan product_id sütundan yabancı anahtar olarak alınır.

Çizelge 3.4.4. Kullanıcı Favorileri Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama

id	int	Birincil anahtarıdır ve her favori kaydına benzersiz bir kimlik numarası atar.
user_id	int	Favori ürünü belirten kullanıcının kimlik numarasını içerir. users tablosuna yabancı anahtar olarak kullanılır.
product_id	int	Kullanıcının favori olarak işaretlediği ürünün kimlik numarasını içerir. products tablosuna yabancı anahtar olarak kullanılır.

### 3.4.8. Ürün Detayları

Kullanıcı ürün detaylarını açtığında veri tabanından ürünün adı, resmi ve fiyat geçmişi bilgileri çekilir. ApexCharts.js ile fiyat bilgileri grafik haline getirilip, ürünün renk bilgisi JavaScript ile renk bloğu haline dönüştürülür ve kullanıcıya gösterilir. Şekil 3.4.8.1. de gösterilmiştir. Kullanıcı ürünün satış sayfasına erişmek istediğinde ürünün görseline tıklayıp satışın yapıldığı e-ticaret sitesine ulaşabilir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/17.png)
  
Şekil 3.4.8.1. Ürün Detayları Sayfası Örneği.

Şekil 3.4.8.1. de gösterilen fiyat grafiğinin oluşturulabilmesi için fiyatların düzenli olarak kazınıp saklandığı veri tabanı tablosu Çizelge 3.4.5. de gösterilmiştir. 

Çizelge 3.4.5. Ürün Fiyatları Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama
id	int	birincil anahtarıdır ve her fiyat kaydına benzersiz bir kimlik numarası atar.
product_id	int	Fiyat kaydının hangi ürüne ait olduğunu belirtir. products tablosuna dış anahtar olarak kullanılır.
product_price	double	Ürünün belirli bir tarihteki fiyatını içerir. Ondalık sayı olarak saklanır.
scraping_date	date	Fiyat bilgisinin kaydedildiği tarihi içerir. Bu, fiyat değişikliklerini zaman içinde izlemeyi sağlar.
Kullanıcı ürün hakkında düşüncesini yorum yapabilir ve ürüne puan verebilir. Ayrıca diğer kullanıcıların yapmış olduğu değerlendirmeleri de görebilir. Şekil 3.4.8.2. de gösterilmiştir.

   ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/18.png)
   
Şekil 3.4.8.2. Ürün Yorumu Sayfası Örneği.

Şekil 3.4.8.2 de gösterilen yorumlar, Çizelge 3.4.6. da gösterilen veri tabanı tablosu sütunlarında saklanmaktadır.

Çizelge 3.4.6. Ürün Yorumları Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama

id	int	Birincil anahtarıdır ve her yorum kaydına benzersiz bir kimlik numarası atar.
user_id	int	Yorumu yapan kullanıcının kimlik numarasını belirtir. “users” tablosuna dış anahtar olarak kullanılır.
product_id	int	Yorumu yapılan ürünün kimlik numarasını belirtir. “products” tablosuna dış anahtar olarak kullanılır.
comment	varchar(500)	Kullanıcının ürün hakkında yaptığı yorumu içerir. Maksimum 500 karakter uzunluğundadır.
star	tinyint	Kullanıcının ürün için verdiği yıldız derecelendirmesini belirtir.  tinyint veri tipi kullanılarak, genellikle 1-5 arası bir değer alır.
date	datetime	Yorumun yapıldığı tarih ve saat bilgisini içerir. Bu veri, yorumların zaman çizelgesinde izlenmesine olanak tanır.

### 3.4.9. Takip Edilen Üründe Değişiklik

Kullanıcının takip ettiği ürünlerden birinde fiyat değişikliği olduğunda kullanıcıya mail gönderilerek haber verilir. Şekil 3.4.9. da gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/19.png)
  
Şekil 3.4.9. Ürünün Fiyatı Düştü Maili Örneği.

### 3.4.10. Yeni Ürün Eklenmesi

Kullanıcının yeni bir ürün kazıması durumunda, ürün başarıyla eklendi bilgi verilir. Şekil 3.4.10. da gösterilmiştir. Ayrıca ürünlerin kategori bilgilerinin tutulduğu tablonun sütunları ve bu sütunların amaçları Çizelge 3.4.7. de gösterilmektedir









  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/20.png)
  
Şekil 3.4.10. Yeni Ürün Eklendi Bildirimi Örneği.

Çizelge 3.4.7. Kategoriler Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama
category_id	int	Birincil anahtarıdır ve her kategoriye benzersiz bir kimlik numarası atar.
category_name	varchar(45)	Kategorinin adını içerir. Maksimum 45 karakter uzunluğundadır.

### 3.4.11. Veri Güvenliği ve Gizliliği

Kullanıcıların verilerini korumak için kullanıcı şifreleri Bcrypt ile şifrelenmiş olarak tutulmaktadır. Bu şifrelemenin örneği Şekil 3.4.11. de gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/21.png)
  
Şekil 3.4.11. Kullanıcı Bilgi Güvenliği.

#### 3.4.11.1. Verilerin Saklanması

Şekil 3.4.11.1.’de verilen veritabanı Varlık-İlişki diyagramında sunulan tablolar; Çizelge 3.4.2. de veri tabanındaki kullanıcı bilgilerinin saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.3. de veri tabanındaki ürün bilgilerinin saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.4. de veri tabanındaki kullanıcıların favori olarak eklediği ürün bilgilerinin saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.5. de veri tabanındaki belirli aralıklarla kazınan ürün fiyatlarının saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.6. de veri tabanındaki ürünlere kullanıcılar tarafından yapılan yorumların saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.7. da veri tabanındaki ürünlere atanabilecek kategori bilgilerinin saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları, Çizelge 3.4.9. de veri tabanındaki kazınan ürün ve kazıyan kullanıcı bilgilerinin saklandığı tablonun sütunlarının tuttuğu veri türleri ve amaçları gösterilmiştir.

  ![image](https://github.com/muhammetclk/Derin-Ogrenme-Temelli-Cevrimici-Fiyat-Takip-Sistemi/blob/main/reactspring/src/main/resources/static/22.png)
  
Şekil 3.4.11.1. Geliştirileb veri tabanı şemasının Varlık-İlişki diyagramı.

### 3.4.12. Ürün Kategori Belirleme Algoritması

Kategorilerin belirlenmesi için model oluştururken aşağıdaki Çizelge 3.4.8. de verilen Python kodu kullanılmıştır. Bu kod Keras kütüphanesini kullanarak bir dizi evrişimsel sinir ağı (Convolutional Neural Network - CNN) katmanı ve tam bağlantılı (Dense) katmanları içerin bir derin öğrenme modeli oluşturur. 

Çizelge 3.4.8. Model Oluşturma Kodu Örneği

from keras.optimizers import Adam

model = Sequential()
model.add(Conv2D(32, (3, 3), input_shape=(64, 64, 3), activation='relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Conv2D(64, (3, 3), activation='relu'))
model.add(MaxPooling2D(pool_size=(2, 2)))
model.add(Flatten())
model.add(Dense(64, activation='relu'))
model.add(Dense(42, activation='softmax'))

adam_optimizer=Adam(lr=0.135)

model.compile(optimizer=adam_optimizer, loss='categorical_crossentropy', metrics=['accuracy'])

history=model.fit(train_generator, epoks=13)
İlk olarak, Adam optimizasyon algoritması lr=0.135 öğrenme hızıyla başlatılır. Ardından, Sequential modeli oluşturulur. Bu, katmanların sıralı bir şekilde eklenmesine olanak sağlar. İlk katman, 32 filtre (nöron) ve (3,3) boyutunda bir filtre matrisi kullanır. Giriş şekli (64,64,3) olarak belirlenmiştir ve ReLU aktivasyon fonksiyonu kullanılır. Ardından, bir MaxPooling2D katmanı eklenir. Bu, her 2x2 piksel bloğunda maksimum değeri alarak görüntü boyutunu yarıya indirir. Bir sonraki Conv2D katmanı, 64 filtre ve (3,3) boyutunda bir filtre matrisi kullanır. Yine ReLU aktivasyon fonksiyonu kullanılır. Başka bir tane daha MaxPooling2D katmanı eklenir. Flatten katmanı, çok boyutlu tensörleri tek boyutlu bir vektöre dönüştürür. Bu, evrişimli ve havuzlama katmanlarından gelen çıktıları tam bağlantılı katmanlara beslemek için gereklidir. İki tam bağlantılı katman eklenir. İlk katman, 64 nöron ve ReLU aktivasyon fonksiyonu kullanır. İkinci katman, 42 nöron ve Softmax aktivasyon fonksiyonu kullanır. Softmax aktivasyonu, çok sınıflı sınıflandırma problemlerinde genellikle çıktı katmanında kullanılmaktadır. Model, compile metodu ile derlenir. Bu aşamada, optimizasyon algoritması, kayıp fonksiyonu ve metrikler belirlenir. Son olarak, model fit metodu ile eğitilir. Bu aşamada, eğitim verileri ve epok sayısı belirtilir. Bir epok, tüm eğitim örneklerinin ağdan geçtiği bir iterasyondur.

### 3.4.13. Kullanılabilirlik

Kullanıcı arayüzü, basit ve anlaşılır bir tasarıma sahiptir. Ana sayfa düzeni net ve kullanıcıların istedikleri ürünleri hızlı bir şekilde bulmalarını ve kolayca gezinmelerini sağlayacak şekilde düzenlenmiştir. Ürün fiyatlarını saatlik olarak takip etme, kategorilendirme yapma ve fiyat değişimlerinde kullanıcıya bildirme gibi işlevselliklere sahiptir. Kullanıcıların istedikleri ürünleri takip etmelerine ve fiyat değişikliklerinden haberdar olmalarına olanak tanır. Ürün fiyatlarının tutulduğu veri tabanı tablosu Çizelge 3.4.9. da gösterilmektedir.

Çizelge 3.4.9. Kazıma İşlemleri Tablosunun Tanımları

Sütun Adı	Sütun Tipi	Açıklama
user_id	int	Kazıma işlemini gerçekleştiren kullanıcının kimlik numarasını belirtir. users tablosuna dış anahtar olarak kullanılır.
product_id	int	Kazınan fiyat verisinin hangi ürüne ait olduğunu belirtir. products tablosuna dış anahtar olarak kullanılır.
scrape_date	date	Fiyat bilgisinin kazındığı (scraping) tarihi içerir. Bu tarih, verinin hangi gün toplandığını belirtir.
scraped_price	double	Kazıma işlemi sırasında toplanan fiyat bilgisini içerir. Ondalık sayı olarak saklanır.
Hızlı yükleme süreleri ve düşük gecikme süreleri ile karakterizedir. Veri kazıma işlemleri ve kategori belirleme işlemleri milisaniyeler içerisinde hızlı bir şekilde gerçekleştirilir. Kullanıcılar, uygulamayı hızlı bir şekilde erişebilir ve istedikleri ürünlerin fiyatlarını anında kontrol edebilirler. Kullanıcılar, ürünler hakkında geri bildirimde bulunabilirler. Ama kullanıcıların uygulamada oluşabilecek hataları bildirebilecekleri bir iletişim kısmı yoktur. Kullanıcılar çoklu dil desteği sayesinde verimli bir şekilde uygulamadan yararlanabilir.

