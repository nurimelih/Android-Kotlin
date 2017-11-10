# <img src="bg_home.jpeg" alt="Kodluyoruz.ORG" class="logo"/> 

## Kotlin ile Android Uygulama Geliştirme Programı (Syllabus - İzlence)

* **Dersler   :** Git ve GitHub | Kotlin | Androd-201 | Android-301 | Android-401 |
* **Eğitmen   :** Gökhan ÖZTÜRK, [GokhanOzturk@AndroidEdu.IO](mailto:GokhanOzturk@AndroidEdu.IO)

* **Yardıma ihtiyacın mı var?**
    * [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Kodluyoruz-ORG/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
        * Odada aktif olarak kimse bulunmasa bile, siz sorunuzu sorun. Odaya bir sonraki girişimizde, sorunuzu görebiliriz ve cevaplandırabiliriz.
    * Syllabus'ı lütfen inceleyiniz; öneri ve düzeltmeler için lütfen "issue" açınız -> [issues](https://github.com/AndroidEduIO/Android-Kotlin/issues)

## Program Açıklaması

Bu program ile Git ve GitHub kullanarak, Sıfırdan - Orta ve İleri seviye Android Uygulama Geliştirme bilgisine sahip olacaksınız. Profesyonel bir iş yerine yerleşebilmeniz ve profesyonel hayatta karşılacağınız gerçek problemlere çözümler üretebilmeniz için gerekli olan tüm yeteneklere sahip olmanızı sağlamaya çalışacağız.

## Ön Şartlar

* Temel düzeyde Algoritma bilgisi gerekmektedir.
* Değişken tanımlama, temel veri tipleri, operatörler, kontrol yapıları, döngüler, istisna yönetimi ve nesne yönelimli programlama (OOP) konularında bilgi sahibi olunmalıdır.
* Fonksiyonel Programlama kavramı, en azından, üzerine bir şeyler konuşabilecek düzeyde biliniyor olmalıdır.

Bir ön şart değil; ancak Java ve/veya temel Android Uygulama Geliştirme konusunda bilginizin olması bir avantajdır.

## Programa Genel Bakış

Git ve GitHub ile başlayıp, Kotlin söz dizimine (syntax) göz atacağız. 
Neden Java yerine Kotlin'e geçiş yapıyoruz ve Kotlin bize neler sunuyor, bunları öğreneceksiniz. 
Android Studio'nun kurulumundan itibaren ciddi bir Android Uygulama Geliştirme eğitimi alacaksınız. 
Bu eğitim sırasında öğretilen yapıların profesyonel iş hayatında nerelerde kullanılacağını, işin en iyi pratiklerini (best practices), yanlış yaptığımızda karşılacağımız sorunları ve bunları aşmanın yollarını öğreneceksiniz. 
Sadece yeni bir şeyler üretmeyecek, bozuk yapıları nasıl "debug" yaparak çözebileceğinizi de öğreneceksiniz.
Jr. olsanız bile saygı görmenizi sağlayacak işin yazılı olmayan tüm kurallarını da bileceksiniz.

Eğitim temelde 4 ana başlıkta olacak. Bunlar şöyle ki;

* Git ve GitHub Eğitimi
* Kotlin Eğitimi
* Android Eğitimi
    * Android 201
    * Android 301
    * Android 401
* İş Bulma, İşe Yerleşme ve İş Hayatında Başarılı Olabilme İpuçları

Bu başlıklar hakkında daha detaylı bilgiyi, aşağıda, #Eğitim Detayı kısmında bulabilirsiniz.

## Ev Ödevi ve Projeler

Tüm ödevler Resmi Kodluyoruz GitHub adresinde yayınlanacaktır. Örnekler için -> [GitHub | Kodluyoruz](https://github.com/Kodluyoruz)

### Ev Ödevi ve Proje Akışı

Eğer GitHub Desktop kullanıyorsanız, aşağıdaki dokümanlar giriş seviyesinde yardımcı olacaktır.

* <https://guides.github.com/activities/forking/>
* <https://help.github.com/desktop/guides/contributing/>

1. Ev Ödevi veya Projeyi "Forklayın" (Ev Ödevi ve Projeler için -> [GitHub.Com/Kodluyoruz](https://github.com/Kodluyoruz)).
1. Forkladıktan sonra Ev Ödevi veya Projeyi "Clonelayın"
1. Kendi adınızda açılmış olan Branch'e geçiş yapın.
1. Tüm isterleri karşılayacak olan kod düzenlemesini yapın.
1. Tüm değişikliklerin  yapıldığına emin olduktan sonra "Commitleyin"
1. GitHub adresinize "Pushlayın"
1. Orjinal repo üzerine [Yeni bir Pull Request Oluşturun](https://help.github.com/articles/creating-a-pull-request/)
1. Pull Request'inizin incelenmesi için bekleyin.
1. Bu bekleme sırasında arkadaşlarınızın yaptığı Pull Request'leri inceleyin ve daha iyi olabilmeleri için "Code Review" yapıp yorumda bulunun.
1. Kapsamlı bir hata gördüğünüzde düzeltilmesi için arkadaşınızın forkladığı proje üzerinde [issue] açın.

#### ReadMe Güncellemesi

Geliştirdiğiniz veya çözdüğünüz tüm Ev Ödevi ve Projeler için ReadMe dosyasına bu Ev Ödevi veya Proje sonrasında hangi yetenekleri kazandığınızı not ediniz.

## Eğitim Detayı

      Önemli Not: Sınıfın hızına bağlı olarak, Eğitim Detayındaki tüm bilgiler anlatılmayabilir 
      veya fazlası anlatılabilir. Bazı derslerin programdaki önceliği ve/veya yeri değiştirilebilir. 
      Sınıfın yavaş ilerlemesi durumunda, direkt işe yerleşmenizde birincil dereceden etkili olmayan 
      konular atlanabilecek ve/veya araştırma ödevi olarak verilebilecektir.

### Git ve GitHub

* Git ve GitHub Nedir? Farkları Nelerdir? Niye Kullanmalıyız?
* GitBash Kurulumu.
* Repo Nedir? Yerelde (Local) ve Uzak Sunucuda (Remote Server) Nasıl Repo Oluşturabiliriz?
* Command Line (CMD, CML, Terminal) Üzerinde Temel Git Komutları
    * Ekleme (Add) ve Ara Bölge (Staging Area)
    * Durum (Status) ve Fark Alma (Diff Alma)
    * Bitirmek-Teslim Etmek (Commit) İşlemi
    * Commit Mesajı En İyi Pratikleri (Best Practices)
    * Commitleri Repoya Göndermek (Push) & Commitleri Repodan Çekmek (Pull)
    * Projeyi Çekmek, Sync İşlemi (Fecth)
    * Dallanma (Branch) Nedir? Future - Branch Modelleri
    * Birleştirme (Merge) ve Branchler Arası Diff Alma
    * Commit Taşıma (Cherry Pick)
    * Kopyalama (Clone) ve Çatallandırma (Fork) İşlemleri
    * Değişiklik Gönderim İsteği (PR - Pull Request) Kavramı 
* .gitIgnore
* GitHub Üzerinde Organizasyon Hesapları
* Issue Mekanizması
* Pull Request (PR) İnceleme ve Code Review İşlemleri
* Pull Request İşlemleri - Değişen Dosyalar (File Changed), Yorum Yapma (Comment), Onaylama (Approve), Değişiklik Talebi (Request Changes)
* Repo Ayarları
* GitHub ile Entegre Çalışan Araçlar (Slack-OctoTree)
* GitHub'ın Çok Bilinmeyen Yönleri

### Kotlin

* "Neden Kotlin?" Sorusuna Cevap Bulacağımız; "Kotlin vs Java" Sunumu
* IntelliJ IDEA Kurulumu ve Tanıtımı
* main() Fonksiyonu ve İlk Uygulama: "Merhaba Bebek!"
* Run ve Debug Kavramları
* Yorum Atma (Comment) Formatları
* Referans (Reference)
    * Anahtar Kelimeler (Keywords and Operators)
    * İsimlendirmeler

* Temeller (Basics)
    * Temel Tipler (Basic Types)
    * Paketler (Packages) ve Eklemeler (Imports)
    * Kontrol Yapıları (Control Flow) & Döngüler (Loops)
    * Geri Dönüşler (Return) ve Atlamalar (Jumps)

* Sınıflar ve Objeler (Classes & Objects)
    * Sınıflar ve Miras Alma (Classes and Inheritance)
    * Özellikler ve Sınıf Elemanları (Properties and Fields)
    * Arayüzler (Interfaces)
    * Görünürlük Değiştiriciler (Visibility Modifiers)
    * Uzantı Yapılar (Extensions)
    * Veri Sınıfları (Data Classes)
    * Kilitli Sınıflar (Sealed Classes)
    * Eş Değer (Generics) - (401 kurunda daha detaylı bahsedilecek)
    * İç içe Sınıflar ve İç Sınıflar (Nested and Inner Classes)
    * Enum Classes (Sayım? Ne kadar doğru bir çeviri?)
    * Nesne İfadeleri ve Bildirimleri (Object Expressions and Declarations)
    * Sınıf Yetkilendirme (Class Delegation)
    * Özellik Yetkilendirme (Delegated Properties)
    
 * Fonksiyonlar ve Lamdalar (Functions & Lambdas)
    * Fonksiyonlar (Functions)
    * Üst Düzey Fonksiyonlar ve Lambda? (Higher-Order Functions and Lambdas)
    * Satıriçi Fonksiyonlar (Inline Functions)
    * Eş-Yordamlar (Coroutines) - (401 kurunda daha detaylı bahsedilecek)
    
 * Diğerleri (Other)
    * Çoklu Değişken Oluşturma (Destructuring Declarations)
    * Koleksiyonlar (Collections: List, Set, Map) - (401 kurunda daha detaylı bahsedilecek)
    * Değer Aralıkları (Ranges)
    * Tip Kontrolleri ve Dönüştürücüler (Type Checks and Casts: 'is' and 'as')
    * This İfadesi (This Expression)
    * Eşitlik (Equality)
    * Operatör Aşırı Yükleme (Operator overloading)
    * Güvenli Null Kullanımı (Null Safety)
    * İstisna Yönetimi (Exceptions)
    * Dip Notasyon (Annotations) - Ders Programına Dahil Değil. Sadece kavram olarak bahsedilecek
    * Yansıtma (Reflection) - (401 kurunda daha detaylı bahsedilecek)
    * Tip Güvenli Yapılar (Type-Safe Builders)
    * Mevcut Tiplerin Yerine Geçecek Tipler Sağlama (Type aliases)
    
* Java ile Birlikte Çalışma (Java Interop)
    * Kotlin Üzerinde Java Yazma (Calling Java code from Kotlin)
    * Java Üzerinde Kotlin Yazma (Calling Kotlin from Java)
    * Java Projesini Kotlin Projesine Çevirme

### Android 201

* Android Cihazlar ve İşletim Sistemi Üzerine Genel Bilgiler
* Android Studio Kurulumu ve Gerekenler
    * JDK (Java Development Kit) Java Geliştirme Kiti
    * Android SDK (Software Development Kit) Android Yazılım Geliştirme Kiti
* İlk Uygulama "Selam Bebek !"
* Android Studio & Android Projesi Bileşenlerinin Tanıtımı
    * XML formatı & manifest.xml
    * src dosyaları
    * Android Resource (res- kaynak) Dosyaları
      * drawable
      * layout
      * mipmap
      * values ( attrs - style - dimen - string - color )
      * raw
      * assest
    * Gradle Yapısı (401 kurunda daha detaylı bahsedilecek)
    * Proguard (401 kurunda daha detaylı bahsedilecek)
    * Android Monitör & Logcat
    * TODO
    * Terminal
    * Version Control
    * Menu Çubuğu ve Menu Seçenekleri
* Sanal Cihaz (Emulator) Oluşturma veya Android Cihazların "Emulator" Olarak Kullanımı
* Log Sınıfı
* Activity Sınıfı
    * Android Layout Yapısı & Android Bileşenlerini (Component) Java Classlarına Bağlama
    * Activity Yaşam Döngüsü (Activity Life Cycle)
    * Intent Kavramı ve Çeşitleri & Activityler Arası Geçiş
    * Activityler Arası Veri Taşıma İşlemleri
      * Intent
      * Bundle
      * Singleton Pattern
      * Interface
      * Shared Preference (301 kurunda daha detaylı bahsedilecek)
      * EventBus
      * Serialization & Deserialization
      * Parcellable
* Fragment Sınıfı
    * Fragment Yaşam Döngüsü (Fragment Life Cycle)
    * Fragmentların Activity'lere Eklenmesi
      * Layout Üzerinden Fragment Ekleme
      * Çalışma Zamanında Fragment Ekleme (Programmatically)
      * Fragment Ekleme İşlemlerinin Performans Yaşam Döngüsü Farklılıkları
      * replace() ve backstack() İşlemleri
    * Activity-Fragment & Fragment-Activity & Fragment-Fragment Arası Veri Taşıma
      * Arguments
      * Public Activity Methodları (Düşük Memory Sızıntısı - Memory Leak!)
* Activity - Fragment Arasındaki Temel Farklar. Ne Zaman Hangisi Kullanılmalı?
* Toast
* AlertDialog
* Android View Hierarchy
* Grafik Arayüzü Bileşenleri (Graphical User Interface - GUI)
   * Layouts
      * FrameLayout
      * RelativeLayout
      * LinearLayout
      * ConstraitLayout
      * fragment
      * GridLayout
      * TableLayout
   * Widgets
      * TextView
      * Button
      * EditText
      * ToggleButton
      * CheckBox
      * RadioButton
      * Switch & ToggleButton
      * Spinner
   * Images
      * ImageView
      * ImageButton
      * VideoView
   * Containers
      * RadioGroup
      * ScrollView
      * WebView
      * ListView & Adapter
   * AppCompat
      * CardView
      * RecyclerView & Adapter & ViewHolder Pattern
      * Toolbar & Menu
   * Google
      * MapView (Harita-Konum İşlemleri)
      * AdView (Reklam Ekleme)
      * YoutubePlayerView - YoutubeAPI
   * Advanced
      * include
      * requestFocus
      * merge
      * TabLayout
      * ViewPager
      * PullToRefresh
      * Pagination
      * NavigationDrawer
      * ProgressBar
      * Floating Action Button
      * Floating EditText
      * UI Katmanı Yazımı
* Android Bileşenlerinin Ortak Özellikleri (Properties) ve Olayları (Events)
* SubComponent - CustomComponent & Base Class Mantığı ve Kullanım Sebepleri
* HTML Kodlarıyla Çalışma
* Zaman ve Tarih (Date-Time) İşlemleri
* Uygulamayı Bekletmek (Sleep)
* Timer & CountDownTimer
* Threadler
* Projeye Ses ve Titreşim Ekleme
* Module Oluşturma
* Üçüncü Parti Kütüphanelerin Projeye Eklenmesi (3rd Party Libraries)
* UI Yerleşim Grafiği ve Layout Performans Grafiği
* İşlemci ve Ram Monitör İşlemleri
* İsimlendirme Standartları ve Temiz Kod Prensipleri
* SOLID Prensipleri
* Özel Dosya Şablonları (Custom File Templates)
   
### Android 301

* Shared Preference
* Temel SQL İşlemleri & Belki Room Framework
* Android İzinlerdeki Değişiklikler (API M (6.0) Öncesi ve Sonrası)
* Rehbere Erişim
* JailBreak & Super User Yetkisi Almış & Root'lanmış Cihazların Tespiti
* Enumaration (Enum)
* Interface ve Abstract Yapılar
* Android Bilidirimleri Alma ve Atma (Notification)
* Paylaşma Özelliği
* Çoklu Dil Desteği Yapısı
* Crash Ekranlarının Düzenlenmesi
* Animasyonlar
* Web Servisler ile Çalışma
   * Request - Response Mantığı
   * Json & XML Formatı
   * Request Methodları
   * SOAP ve RESTful Servisler
   * PostMan & JsonParserOnline.Com & MyJson.Com
   * Network Kütüphaneleri ve Birbirlerine Göre Avantaj ve Dezavantajları
      * Volley (Sadece Volley ile Network İşlemleri Yapılacak
      * Retrofit
      * OkHttp
      * Android HttpURLConnection Sınıfı
   * Volley
      * Json Object Request
      * Json Array Request
      * String Request
      * Param & Header Paslama
      * Öncelik (Priority) Belirleme
      * ParseNetwork
      * Response Ayıklama İşlemleri
      * GSON ve Jackson Kütüphaneleri (Otomatik Response Cast İşlemleri)
      * ImageCache & NetworkImageView
      * Network Katmanı Yazımı
* Firebase Entegrasyonu
   * Kayıt (Register) - Giriş (Login İşlemleri)
   * Basit Chat Uygulaması (Ufak Wassappp'lar :)

### Android 401

* Yayın Dinleyiciler (Broadcast Receiver)
   * Sms Dinleme ve Okuma
   * Internet & Bluetooth & GPS Açık Kapalı Kontrolleri
   * Özel (Custom) Broadcast Receiver Tanımlama ve Kullanma
* Android Servisler
   * Önyüzde (Foreground) Çalışan Servisler
   * Arkayüzde (Background) Çalışan Servisler
   * Bound Servisler
* Android Sensörler
* Sesden Yazıya Aktarma (Text to Speech) İşlemleri
* Yazıdan Sese Aktarma (Speech to Text) İşlemleri
* AsynTask Kullanımı ve Riskleri
* Cursor Loader (Verileri Arka Planda Yükleme)
* Doğru Context Kullanımı ve Bellek Sızıntısı (Memory Leak)
* Tasarım Desenleri (Design Pattern)
* Genel Türler (Generic Types)
* Yansıtma (Reflection)
* BuildType & ProductFlavors
* Proguard RuleSet Tanımları
* APK Küçültme Teknikleri
* APK Oluşturma ve Yayınlama
* Java Collection
   * Set
      * HashSet
      * SortedSet
      * TreeSet
   * List
      * ArrayList
      * LinkedList
   * Map
      * HashMap
      * SortedMap
      * TreeMap
* Test Driven Development Mantığı
   * Espresso Aracının Kullanımı ve Test Case Yazma
* Continues Integration - Continues Delivery Kavramları
   * Jenkins Kurulumu
   * HockeyApp Bağlantısı
* Fabric
* Google Analytics
* DeepLink Kavramı ve Branch.IO

## Kullanılacak IDE'ler

* IntelliJ IDEA, Android Studio


## Kaynaklar

### Demirbaş Referanslar
* [Developer.Android](https://developer.android.com/index.html)
* [EveryProgrammerShouldKnow](https://github.com/mr-mig/every-programmer-should-know)

### Her Android Geliştiricinin Bilmesi Gereken Kütüphaneler

* [Güncellenecek](http://googlecom)

### Haftaklık veya Günlük RSS Kayıtları

* [Güncellenecek](http://googlecom)

### Slack Kanalları

* [Güncellenecek](http://googlecom)

### PodCast'ler

* [Güncellenecek](http://googlecom)

### Facebook Sayfa ve Grupları

* [Güncellenecek](http://googlecom)

### Mutlaka Okunması Gereken Kaynaklar
* [Okumanız Gereken En Önemli Kitaplar Listesi](https://github.com/chhantyal/influential-cs-books)

### Code Pratiği Yapılabilecek Siteler
* [HackerRank](https://www.hackerrank.com/)
* [CodinGame](https://www.codingame.com/start)
* [HackerEarth](https://www.hackerearth.com/)
* [TopCoders](https://www.topcoder.com/)
* [CodeWars](https://www.codewars.com/)
* [Exercism](http://www.exercism.io/)
* [CodeFights](https://codefights.com/)
* [InterviewBit](https://www.interviewbit.com/)

### Bloglar

* [Güncellenecek](http://googlecom)

### Kişiler

* [Güncellenecek](http://googlecom)

### Yardımcı Araçlar

* [Güncellenecek](http://googlecom)

### Filmler ve Diziler

* [Güncellenecek](http://googlecom)

### Eğitmen Hakkında

<img src="profile.png" alt="Gökhan ÖZtürk" class="logo"/> 

* Gökhan ÖZTÜRK, 17 Haziran 1990 İstanbul  doğumlu.
* Lise          -> Nuri Cıngıllıoğlu "Süper" Lisesi (2004~2008 | Derece = 3.84/5)
* Lisans        -> Maltepe Üniversitesi, Mühendislik ve Doğa Bilimleri Fakultesi, Yazılım Mühendisliği (2009-2013 | Derece 3.21/4)
* Yüksek Lisans -> Maltepe Üniversitesi, Fen Bilimleri Enstitüsü, Bilgisayar Mühendisliği Tezli Yüksek Lisansı (2015~Devam Ediyor)

* Profesyonel iş hayatıma 2013 yılı Haziran ayında, "Nomad Commerce" isimli "FinTech" üzerine yoğunlaşan ve dış kaynak (outsource) modelini benimseyen bir firma ile başladım. 
* İlk iş günümden itibaren toplamda 3 yıl 9 ay boyunca "Akbank" bünyesinde "["Akbank Direkt Mobil"](https://play.google.com/store/apps/details?id=com.akbank.android.apps.akbank_direkt) projesinin "Android" kanadında yer aldım.
* 2015 yılında Akbank Direkt Mobil projesinin dış kaynağa aktarılan (outsource edilen) bölümünde "Android ve iOS'dan sorumlu Takım Liderliği" görevine getirildim. 
* 2 yıl kadar bu sorumluluğu taşıdıktan sonra Mart 2017 tarihi itibariyle Nomad Commerce'den, dolayısıyla "Akbank Direkt Mobil" projesinden ayrılarak, kadrolu çalışan olarak (insource) "Demirören Medya Grubuna" giriş yaptım. 
* Demirören Medya Grubunda, "Yeni İş Geliştirme" biriminde, "Native Mobil Uygulama Geliştirme Uzmanı" olarak ["Sonra Ne Oldu?"](https://play.google.com/store/apps/details?id=com.demirorenmedya.sonraneoldu) isimli "Habercilik" uygulaması üzerinde çalışmaktayım.

Bu kariyer akışıyla beraber, Bir Sosyal Sorumluluk Projesi olan ["Kodluyoruz"](http://kodluyoruz.org/) derneğinin "Kurucu, Yönetim Kurulu Üyesiyim" aynı zamanda -şuan için- Eğitim Koordinatörlüğü görevini götürmekteyim. Tüm bunların yanında bu syllabus'ı da yazma sebebimiz olan Android Uygulama Geliştirme Eğitimini vermekteyim. Kodluyoruz ile ilgili detaylara;

* http://Kodluyoruz.Org/
* http://KodluyoruzAkademi.Com/
* https://www.fb.Com/KodluyoruzTR/

adreslerinden ulaşabilirsiniz...

## Kendimizi geliştirmemiz için lütfen Geri Bildirim (Feedback) vermekten çekinmeyiniz..
[Info@Kodluyoruz.ORG](mailto:Info@Kodluyoruz.ORG)
