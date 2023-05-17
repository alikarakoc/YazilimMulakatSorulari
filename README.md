 


## Yazılım Mülakatı Soruları (Junior, Mid, Senior)
-  Repo yenidir. Sürekli olarak güncellenmektedir. Takibe almayı unutmayın. (Stars, Watch)
## Virtual yapısı nedir?

- Virtual yapısı, nesne yönelimli programlama (OOP) konseptlerinden biridir ve bir sınıfın üye işlevlerinin, türetilmiş sınıflar tarafından yeniden tanımlanabileceği anlamına gelir. Bu, türetilmiş sınıfların üye işlevlerinin davranışını kontrol etmesine izin verir.

## Partial yapısı nedir?

- Partial yapısı, bir sınıfın tanımının iki veya daha fazla kaynaktan geldiği durumlarda kullanılır. Bu, sınıfın tanımının farklı dosyalara bölünebileceği anlamına gelir ve bu dosyalarda farklı üye işlevleri tanımlanabilir.

## Static durumları ve kullanımı hakkında açıklama yapınız?

- Static, OOP'de kullanılan bir anahtar sözcüktür ve sınıf üyeleri veya değişkenler tanımlarken kullanılabilir. Bu, sınıfın örneğine bağlı olmayan bir değişken veya fonksiyon olduğunu gösterir ve bu değişken veya fonksiyona sınıfın adıyla erişilebilir.

## nopCommerce projesi nedir? (Gireceğiniz mülakat firmasının sektörü e-ticaret ise...)

- nopCommerce, açık kaynaklı bir e-ticaret platformudur ve .NET teknolojileri kullanılarak geliştirilmiştir. Bu proje, birçok dilde ve para biriminde çeviri desteği, esnek ürün yönetimi ve ödeme entegrasyonu gibi özellikler sunar.

## Elasticsearch nedir?

- Elasticsearch, açık kaynaklı bir arama ve analiz motorudur ve büyük miktardaki verileri işlemek ve aramak için kullanılır. Elasticsearch, bir ilişkisel veritabanından farklıdır ve verileri JSON belgeleri olarak saklar.

## Redis nedir?

- Redis, açık kaynaklı bir anahtar-değer depolama sistemidir ve en çok performanslı ve ölçeklenebilir uygulamalarda kullanılır. Redis, verileri bellek içinde saklar ve bu nedenle hızlı bir şekilde erişilebilir.

## İlişkisel ve NoSQL veritabanlarını açıklayınız?

- İlişkisel veritabanları, verileri birbirleriyle ilişkili tablolarda saklar. Bu, SQL dilinin kullanılmasıyla yapılandırılmıştır. NoSQL veritabanları ise yapılandırması daha esnektir ve genellikle yüksek performanslı uygulamalarda kullanılır.

## Lazy loading, encapsulation, polymorphism, inheritance verileri nedir?

- Bu konular, OOP'nin temel prensipleridir ve yazılım geliştirme sürecinde sık sık kullanılır. Lazy loading, uygulamanın ihtiyacı olduğu anda verileri yükler ve gereksiz yere kaynak tüketimini önler. Encapsulation, sınıfın içindeki verilerin ve işlevlerin korunmasını sağlar ve sınıfın dışındaki etkileşimlerin kısıtlanmasına yardımcı olur. Polymorphism, bir nesnenin farklı şekillerde davranabilmesini sağlar. Inheritance, bir sınıfın başka bir sınıftan türetilmesini ve üye işlevlerinin ve değişkenlerinin miras alınmasını sağlar.

## SOLID prensipleri hakkında açıklama yapabilirmisin?

- SOLID, yazılım geliştirme dünyasında sık sık kullanılan bir prensipler kümesidir. SOLID, Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation ve Dependency Inversion olmak üzere beş prensipten oluşur. Bu prensipler, yazılım geliştiricilerinin yazılımın esnekliğini artırmasına ve daha sürdürülebilir bir kod tabanı oluşturmasına yardımcı olur.
- Solid prensipleri, yazılım geliştirme sürecinde kaliteli, sürdürülebilir ve esnek bir kod oluşturmayı hedefleyen bir dizi kurallardır. SOLID, Robert C. Martin tarafından önerilen ve beş temel prensibi içeren bir akronimdir:
- Single Responsibility Principle (Tek Sorumluluk Prensibi): Her sınıf veya modül, yalnızca bir tek sorumluluğa sahip olmalı ve bu sorumluluğu başarılı bir şekilde yerine getirmelidir.
- Open/Closed Principle (Açık/Kapalı Prensibi): Bir yazılım birimi (sınıf, fonksiyon, modül) değişikliklere kapalı (closed) olmalı, ancak yeni işlevsellik eklemek için açık (open) olmalıdır. Yani mevcut kodu değiştirmek yerine, yeni özellikler eklemek için genişletilebilir olmalıdır.
- Liskov Substitution Principle (Liskov Yerine Geçme Prensibi): Bir üst sınıfın nesneleri, onun alt sınıfları tarafından yerine geçebilmelidir. Yani alt sınıflar, üst sınıfın belirlediği davranışları korumalı ve bu davranışları değiştirmeden genişletebilmelidir.
- Interface Segregation Principle (Arayüz Ayrım Prensibi): İstemcilerin kullanmadığı özellikleri içeren geniş arayüzler yerine, daha küçük ve özelleştirilmiş arayüzler kullanılmalıdır. Bir sınıf, sadece ihtiyaç duyduğu metotları içeren arayüzleri uygulamalıdır.
- Dependency Inversion Principle (Bağımlılığı Tersine Çevirme Prensibi): Yüksek seviyeli modüller, düşük seviyeli modüllere doğrudan bağlı olmamalıdır. Bunun yerine, her iki seviyenin de soyutlamalara (abstractions) bağımlı olması gerekmektedir.
- Bu prensipler, yazılımın daha kolay bakım yapılabilir, test edilebilir ve genişletilebilir olmasını sağlar. Aynı zamanda kodun tekrar kullanılabilirliğini artırır ve bağımlılıkları azaltır.

## Procedure ve Function arasındaki fark nedir, ne amaçla kullanırız?

- Prosedürler ve fonksiyonlar, programlarda tekrar kullanılabilir kod blokları oluşturmak için kullanılan yapısal programlama araçlarıdır. İkisi arasındaki temel fark, geri dönüş değeri olup olmamasıdır. Prosedürler, belirli bir görevi gerçekleştirmek için kullanılan kod bloklarıdır. Geri dönüş değeri yoktur veya değeri yok sayılır. Genellikle verileri işlemek, ekrana çıktı yazdırmak veya başka bir işlemi gerçekleştirmek gibi işlevleri yerine getirmek için kullanılırlar.

- Fonksiyonlar ise prosedürlerden farklı olarak geri dönüş değeri olan kod bloklarıdır. Fonksiyonlar, belirli bir hesaplama yapar ve sonucu çağıran yere döndürür. Fonksiyonlar, genellikle bir değeri hesaplamak, işlemek ve bu değeri geri döndürmek için kullanılır. Hangisini tercih edeceğiniz, yapmanız gereken işin doğası ve ihtiyaçlarınıza bağlıdır. Eğer bir görevi gerçekleştirmek için geri dönüş değeri gereksizse veya dikkate alınmayacaksa, prosedür kullanabilirsiniz. 
- Örneğin, ekrana bir metin yazdırmak veya verileri sıralamak için bir prosedür kullanabilirsiniz. Ancak, bir hesaplama yapmanız veya bir değeri döndürmeniz gerekiyorsa, fonksiyonları tercih etmek daha uygun olabilir. Örneğin, iki sayının toplamını hesaplamak veya bir liste içindeki en büyük sayıyı bulmak için bir fonksiyon kullanabilirsiniz. Özetlemek gerekirse, prosedürler genellikle görevleri gerçekleştirmek için kullanılırken, fonksiyonlar hesaplamalar yapmak ve sonuçları döndürmek için tercih edilir. Hangisini seçeceğiniz, işin doğasına ve ihtiyaçlarınıza bağlıdır.

## Dependency injection nedir?

- Dependency Injection (DI), yazılım geliştirme sürecinde sık sık kullanılan bir tasarım desenidir. Bu desen, bir nesnenin ihtiyaç duyduğu bağımlılıkları dışarıdan almasına ve sınıfın içinde doğrudan oluşturulmamasına izin verir. Bu, sınıfların daha bağımsız hale gelmesini ve daha kolay test edilebilir hale gelmesini sağlar.
- Dependency Injection, bir yazılım tasarım deseni olarak, bağımlılıkların (dependencies) dışarıdan bir bileşenin içine enjekte edilmesini sağlar. Bu desen, bir bileşenin bağımlılıklarını oluşturmak ve yönetmek yerine, bu bağımlılıkların dışarıdan bir kaynak tarafından sağlanmasını sağlar.
- Bir örnekle açıklamak gerekirse, bir Araba nesnesi oluşturmak istediğimizi düşünelim. Araba'nın bir motor, lastikler, direksiyon vb. gibi birçok bağımlılığı vardır. Geleneksel bir yaklaşımda, Araba nesnesi oluşturulurken bu bağımlılıkların her biri tek tek oluşturulur veya oluşturulması için başka bir bileşen çağrılır.
- Fakat bu yaklaşım, kodun karmaşıklaşmasına ve sıkı bir şekilde bağımlı hale gelmesine neden olabilir. Bu durumda, Dependency Injection kullanarak Araba nesnesini oluşturmak daha uygun olacaktır.
- Dependency Injection kullanarak, Araba bileşenini oluşturmak istediğimizde, Araba'nın bağımlılıkları dışarıdan bir kaynaktan (örneğin bir IOC Container) alınır ve Araba bileşenine enjekte edilir. Bu sayede Araba bileşeni, bağımlılıklarını yönetmek yerine, bunları dışarıdan gelen kaynak tarafından sağlanır.
- Özetle, Dependency Injection, kodun daha modüler ve esnek olmasını sağlar. Bu desen, yazılım bileşenlerinin birbirlerine sıkı bir şekilde bağımlı olmaktan kurtulmasına ve daha kolay test edilebilmesine olanak tanır.

## Örnek;

```
public class Araba {
    private Motor motor;
    private Tekerlekler tekerlekler;
    private Direksiyon direksiyon;
    
    public Araba(Motor motor, Tekerlekler tekerlekler, Direksiyon direksiyon) {
        this.motor = motor;
        this.tekerlekler = tekerlekler;
        this.direksiyon = direksiyon;
    }
     // Araba'nın diğer metotları...
}

```

## Abstract ve interface benzerlik farklılıkları nelerdir?

- Abstract ve Interface, OOP'de sık kullanılan kavramlardır. Abstract sınıflar, bir sınıfın soyut bir temel sınıfı olduğunu belirtir ve soyut işlevleri veya değişkenleri içerebilir. Interface'ler ise, bir sınıfın uygulaması gereken belirli işlevleri tanımlar ve sınıflar arasındaki bağımlılıkları azaltmak için kullanılır.

## Docker nedir kısaca açıklarmısınız?

- Docker, yazılım uygulamalarının hızlı bir şekilde dağıtılmasını, yönetilmesini ve çalıştırılmasını sağlayan bir platformdur. Docker, uygulamanın bağımlılıklarını ve konfigürasyonunu içeren sanal ortamlar oluşturur.

## RabbitMQ nedir?

- RabbitMQ, açık kaynaklı bir mesajlaşma aracıdır ve uygulamalar arasındaki mesajlaşmayı kolaylaştırır. Bu araç, birçok farklı protokolü destekler ve birçok dilde kullanılabilir.

## Microservice ve monolitik sistemler arasındaki farklılıklar nelerdir?

- Microservice mimarisi, bir uygulamanın farklı işlevlerinin farklı servisler halinde ayrılmasıdır. Bu yaklaşım, uygulamayı daha esnek hale getirir, ölçeklenebilirliği artırır ve hata ayıklama ve bakımı kolaylaştırır. Monolitik mimari ise, tüm uygulamanın tek bir yapıda oluşturulmasıdır. Bu yaklaşım, uygulama geliştirmeyi daha kolay hale getirir, ancak büyük uygulamalarda ölçeklenebilirlik sorunlarına neden olabilir. Microservice yaklaşımı, uygulamanın her bir işlevini ayrı ayrı yönetme ve ölçekleme imkanı sağlar.



