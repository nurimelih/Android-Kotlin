# <img src="assets/logo.svg" alt="Kodluyoruz.ORG" class="logo"/> 

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
* İş Bulma, İşe Yerleşme ve İş Hayatında Başarılı olabilme İpuçları

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

#### ReadMe Günncelemesi

Geliştirdiğiniz veya çözdüğünüz tüm Ev Ödevi ve Projeler için ReadMe dosyasına bu Ev Ödevi veya Proje sonrasında hangi yetenekleri kazandığınızı not ediniz.

## Eğitim Detayı

      Önemli Not: Sınıfın hızına bağlı olarak, Eğitim Detayındaki tüm bilgiler anlatılmayabilir 
      veya fazlası anlatılabilir. Bazı derslerin programdaki önceliği ve/veya yeri değiştirilebilir. 
      Sınıfın yavaş ilerlemesi durumunda, direkt işe yerleşmenizde birincil dereceden etkili olmayan 
      konular atlanabilecek ve araştırma ödevi olarak verilebilecektir.

### Git ve GitHub

* Git ve GitHub nedir? Farkları nelerdir? Niye kullanmalıyız?
* GitBash kurulumu yapmak.
* Repo Nedir? Localde ve Uzak sunucuda nasıl Repo oluşturabiliriz?
* Command Line (CMD, CML, Terminal) üzerinde temel Git Komutları
    * Add (Ekleme) ve Staging Area (Ara Bölge)
    * Status (Durum) ve Diff Alma (Fark Alma)
    * Commit (Bitirmek-Teslim Etmek) İşlemi
    * Commit Mesajı Best Practices (En İyi Pratikleri)
    * Push (Commitleri, Repoya göndermek) & Pull (Commitleri, Repodan Çekmek)
    * Fecth (Projeyi Çekmek, Sync İşlemi)
    * Branch (Dallanma) Nedir? Future - Branch Modelleri
    * Merge (Birleştirme) ve Branchler Arası Diff Alma
    * Cherry Pick (Commit Taşıma)
    * Clone (Kopyalama) ve Fork(Çatallandırma) İşlemleri
    * Pull Request (PR - Değişiklik Gönderim İsteği) Kavramı 
* GitHub Üzerinde Organizasyon Hesapları
* Issue Mekanizması
* Pull Request (PR) İnceleme ve Code Review İşlemleri
* Pull Request İşlemleri - File Changed (Değişen Dosyalar), Comment (Yorum Yapma), Approve (Onaylama), Request Changes(Değişiklik Talebi)
* Repo Ayarları
* GitHub ile Entegre Çalışan Araçlar (Slack-OttoTree)
* GitHub'ın Çok Bilinmeyen Yönleri

### Kotlin

* Neden Kotlin'e Cevap Bulacağımız; "Kotlin vs Java" Sunumu
* IntelliJ IDEA Kurulumu ve Tanıtımı
* main() fonksiyonu ve ilk uygulama: "Merhaba Bebek!"
* Run ve Debug Kavramları
* Comment (Yorum Atma) Formatları

* Reference (Referans)
    * Keywords and Operators (Anahtar Kelimeler)
    * İsimlendirmeler

* Basics (Temeller)
    * Basic Types (Temel Tipler)
    * Packages (Paketler) and Imports (Eklemeler)
    * Control Flow (Kontrol Yapıları) & Loops (Döngüler)
    * Returns (Geri Dönüşler) and Jumps (Atlamalar)

* Classes & Objects (Sınıflar ve Objeler)
    * Classes and Inheritance (Sınıflar ve Miras Alma)
    * Properties and Fields (Özellikler ve Sınıf Elemanları)
    * Interfaces (Arayüzler)
    * Visibility Modifiers (Görünürlük Değiştiriciler)
    * Extensions (Uzantı Yapılar)
    * Data Classes (Veri Sınıfları)
    * Sealed Classes (Kilitli Sınıflar)
    * Generics (Eş Değer) - Burada anlatılmayacak. Android 401 içerisinde bahsedilecek
    * Nested and Inner Classes (İç içe Sınıflar ve İç Sınıflar)
    * Enum Classes (Sayım? Ne kadar doğru bir çeviri?)
    * Object Expressions and Declarations (Nesne İfadeleri ve Bildirimleri)
    * Class Delegation (Sınıf Yetkilendirme)
    * Delegated Properties (Özellik Yetkilendirme)
    
 * Functions & Lambdas (Temeller)
    * Functions (Fonksiyonlar)
    * Higher-Order Functions and Lambdas (Üst Düzey Fonksiyonlar ve Lambda?)
    * Inline Functions (Satıriçi Fonksiyonlar)
    * Coroutines (Eş-Yordamlar) - Burada anlatılmayacak. Android 401 içerisinde bahsedilecek
    
 * Other (Diğerleri)
    * Destructuring Declarations (Çoklu Değişken Oluşturma)
    * Collections: List, Set, Map (Koleksiyonlar) - Burada anlatılmayacak. Android 401 içerisinde bahsedilecek
    * Ranges (Değer Aralıkları)
    * Type Checks and Casts: 'is' and 'as' (Tip Kontrolleri ve Dönüştürücüler)
    * This Expression (This İfadesi)
    * Equality (Eşitlik)
    * Operator overloading (Operatör Aşırı Yükleme)
    * Null Safety (Güvenli Null Kullanımı)
    * Exceptions (İstisna Yönetimi)
    * Annotations (Dip Notasyon) - Ders Programına Dahil Değil. Sadece kavram olarak bahsedilecek
    * Reflection (Yansıtma)
    * Type-Safe Builders (Tip Güvenli Yapılar)
    * Type aliases (Mevcut Tiplerin Yerine Geçecek Tipler Sağlama)
    
* Java Interop (Java ile Birlikte Çalışma)
    * Calling Java code from Kotlin (Kotlin üzerinde Java yazma)
    * Calling Kotlin from Java (Java üzerinde Kotlin yazma)
    * Java Projesini Kotlin Projesine Çevirme

### Android 201

* [Güncellenecek](http://googlecom)

### Android 301

* [Güncellenecek](http://googlecom)

### Android 401

* [Güncellenecek](http://googlecom)



## Kullanılacak IDE'ler

* IntelliJ IDEA, Android Studio


## Kaynaklar

### Başlangıç Seviyesinde Materyaller

* [Güncellenecek](http://googlecom)

### Demirbaş Referanslar

* [Güncellenecek](http://googlecom)

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

* [Güncellenecek](http://googlecom)

### Bloglar

* [Güncellenecek](http://googlecom)

### Kişiler

* [Güncellenecek](http://googlecom)

### Yardımcı Araçlar

* [Güncellenecek](http://googlecom)


### Eğitmen Hakkında

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
[Info@Kodluyoruz.ORG](Info@Kodluyoruz.ORG)
