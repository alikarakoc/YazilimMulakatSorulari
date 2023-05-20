 


## Yazılım Mülakatı Soruları (Junior, Medior, Senior)
-  Repo yenidir. Sürekli olarak güncellenmektedir. Takibe almayı unutmayın. (Star, Watch)
-  Eklemek istediğiniz soru ve cevapları tarafıma gönderebilirsiniz.


## Virtual class nedir?

- Virtual yapısı, nesne yönelimli programlama (OOP) konseptlerinden biridir ve bir sınıfın üye işlevlerinin, türetilmiş sınıflar tarafından yeniden tanımlanabileceği anlamına gelir. Bu, türetilmiş sınıfların üye işlevlerinin davranışını kontrol etmesine izin verir.

## Partial class nedir?

- Partial sınıflar, C# programlama dilindeki bir özelliktir. Bir sınıfı bölümlere ayırmak ve farklı dosyalarda tanımlamak için kullanılırlar. Partial sınıflar, aynı sınıfa ait kodun farklı dosyalarda veya ayrı bölmelerde dağıtılmasına izin verir.
- Bu özellik, büyük ölçekli projelerde sınıfların daha iyi organize edilmesini sağlar ve birden fazla geliştirici aynı sınıf üzerinde çalışırken çakışmaları azaltır. Örneğin, bir sınıfın uygulama mantığını, arayüz tanımlarını veya veritabanı işlemlerini farklı dosyalarda belirli bölümlere ayırabilirsiniz.
- Partial sınıfların kullanımı, sınıfın kodunun karmaşıklığını azaltır ve sınıfın bakımını ve genişletilebilirliğini kolaylaştırır. Ayrıca, otomatik kod üreten araçlar veya tasarım araçları tarafından üretilen kodu manuel olarak genişletebilir ve değiştirebilirsiniz.
- Kısacası, partial sınıflar, bir sınıfın kodunu farklı dosyalarda veya bölmelerde organize etmek ve büyük projelerde sınıfın geliştirilmesini kolaylaştırmak için kullanılan bir C# özelliğidir.


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

## AddScope, AddSingleton, AddTransient nedir kısa ve net bir şekilde açıklayabilirmisin?

- AddScope: Bu metot, bağımlılık enjeksiyonu konteynerine bir servis kaydederken, bu servisin her talep edildiğinde bir kapsam (scope) boyunca aynı örneğini döndürmesini sağlar. Kapsam boyunca aynı örneğin kullanılması, örneğin bir HTTP isteği süresince aynı servis nesnesinin paylaşılmasını sağlar. Bu genellikle, bir istek içinde birden fazla bileşenin aynı verilere veya durumlara erişmesi gerektiği durumlarda kullanılır.
- AddSingleton: Bu metot, bağımlılık enjeksiyonu konteynerine bir servis kaydederken, bu servisin uygulama ömrü boyunca yalnızca bir kez oluşturulup paylaşılmasını sağlar. Herhangi bir talep edildiğinde aynı örneği döndürür. Bu, uygulama boyunca tek bir örnek kullanmak istediğiniz durumlarda faydalıdır. Örneğin, bir konfigürasyon ayarını veya veritabanı bağlantısını paylaşmak için kullanılabilir.
- AddTransient: Bu metot, her talep edildiğinde yeni bir örnek oluşturarak her bir talep için farklı bir örneği döndürmek üzere bir servis kaydeder. Yani her talep edildiğinde bir örnek oluşturulur ve bu örnek sadece bu talep için kullanılır. Bu, hafızada paylaşımlı bir durumu veya veriyi saklamak yerine, her talep edildiğinde taze bir örneğe ihtiyaç duyduğunuz durumlarda kullanışlıdır. Örneğin, geçici bellek kullanıcı oturumlarını veya işlem durumunu depolamak için kullanılabilir.
- Bu üç metot, bağımlılıkların nasıl kaydedileceği ve hangi örneklerin nasıl döndürüleceği konusunda farklı davranışları temsil eder. Uygulamanızın gereksinimlerine göre doğru yöntemi seçmek önemlidir.

## Int32 ve Int64 arasında ki fark nedir?

- Int32 ve Int64, tamsayı veri tiplerini ifade eder. Farkları, temsil ettikleri tamsayı değerlerinin boyutlarından kaynaklanır.
- Int32, 32 bit (4 byte) uzunluğunda bir tamsayıyı temsil eder. Bu veri tipi, -2,147,483,648 ile 2,147,483,647 arasındaki tamsayı değerlerini alabilir. Negatif ve pozitif değerler için aynı miktarda alan ayrılır.
- Int64 ise 64 bit (8 byte) uzunluğunda bir tamsayıyı temsil eder. Bu veri tipi, -9,223,372,036,854,775,808 ile 9,223,372,036,854,775,807 arasındaki tamsayı değerlerini alabilir. Negatif ve pozitif değerler için aynı miktarda alan ayrılır.
- Bu nedenle, Int32 daha küçük bir değer aralığına ve daha az bellek kullanımına sahiptirken, Int64 daha büyük bir değer aralığına ve daha fazla bellek kullanımına sahiptir. Seçiminiz, temsil etmek istediğiniz değerlerin aralığına bağlı olacaktır.

## DataRow ve DataReader arasındaki fark nedir?
- DataRow ve DataReader, .NET Framework'teki ADO.NET kütüphanesindeki farklı sınıflardır ve veritabanı işlemleriyle ilgili farklı amaçlar için kullanılırlar.
- DataRow, DataTable nesnesindeki bir veri kaydını temsil eder. DataTable, tablo yapısında verileri depolamak için kullanılan bir sınıftır. DataRow ise DataTable içindeki her bir veri kaydını temsil eder. Bir DataRow nesnesi, tablodaki her bir sütunun değerlerini saklar.
- DataReader ise veritabanı işlemlerinde verileri okumak için kullanılan bir sınıftır. Bir veritabanı sorgusu çalıştırıldığında, DataReader sorgu sonucundaki veri akışını temsil eder ve verileri satır satır okur. DataReader, verileri sorgudan döndürerek, bellekte daha az yer kaplayarak daha hızlı ve verimli bir şekilde çalışır. Verileri tek yönlü (forward-only) olarak okur, yani ileri doğru hareket ederek verilere erişir. DataReader, veritabanı bağlantısı açık olduğu sürece verileri okumaya devam eder.
- Özetle, DataRow verileri tablo yapısında saklamak ve işlemek için kullanılırken, DataReader verileri veritabanından okumak ve işlemek için kullanılır.

## Dictionary ile List arasında ki fark nedir hangisi daha hızlı çalışır?

- C# dilinde Dictionary ve List, farklı veri yapılarıdır ve farklı amaçlar için kullanılırlar. İkisi arasındaki ana fark, verileri nasıl depoladıkları ve erişim süreleridir.
- Depolama Yapısı:
- List: List, elemanları bir sıra içinde depolar. Her eleman bir indeks numarasıyla erişilebilir ve elemanlar eklenme sırasına göre tutulur.
- Dictionary: Dictionary, bir anahtar-değer çiftleri koleksiyonunu depolar. Her bir anahtar benzersiz olmalıdır ve her anahtarın karşısında bir değer bulunur. Anahtarlar, elemanları hızlı bir şekilde erişmek için kullanılır.
- Erişim Süresi:
- List: List, indeks numarasına dayalı olarak elemanlara erişir. Dolayısıyla, bir elemana erişmek için indeks numarasını bilmek gereklidir. Elemanlara erişim süresi O(1) olarak kabul edilir.
- Dictionary: Dictionary, anahtarlar aracılığıyla elemanlara erişir. Anahtarın değeri bulmak için bir karma işlev kullanılır. Bu karma işlemi sayesinde elemanlara hızlı bir şekilde erişilebilir. Elemanlara erişim süresi de O(1) olarak kabul edilir.
- Sonuç olarak, Dictionary ve List arasında erişim hızı açısından bir fark yoktur, her ikisi de O(1) süresinde elemanlara erişir. Ancak, elemanlara erişmek için kullanılan yöntemler farklıdır. Listeler, indeks numaralarına dayalı olarak elemanlara erişim sağlar, Dictionary'ler ise anahtarlar aracılığıyla elemanlara erişir. Dolayısıyla, kullanmanız gereken veri yapısı, işlevsel gereksinimlerinize ve verilerinizi nasıl organize etmek istediğinize bağlıdır.

## Sealed class nedir?

- C# dilinde "sealed" (mühürlü) bir sınıf, miras alınmasını engellemek için kullanılan bir özelliktir. Sealed sınıflar, alt sınıfların oluşturulmasını ve bu sınıflardan türetilmelerini önler. Yani, bir sınıfı sealed olarak işaretlerseniz, başka bir sınıfın bu sınıftan türemesine izin vermezsiniz.
- Sealed sınıflar genellikle, tamamen oluşturulmuş ve genişletilmesine veya değiştirilmesine ihtiyaç duyulmayan sınıflar için kullanılır. Bu, sınıfın davranışını veya yapısını değiştirmemeyi ve sağlam bir şekilde korumayı amaçlayan tasarım kararlarında kullanışlı olabilir.
- Bir sınıfı sealed olarak işaretlemek, kodunuzun belirli bir noktada kesintiye uğramasını engellemeye yardımcı olabilir. Sealed sınıflar aynı zamanda performans açısından da iyileştirme sağlayabilir, çünkü C# derleyicisi, sealed sınıfların daha verimli bir şekilde optimize edilebileceğini bilir.
- Sonuç olarak, sealed sınıflar C# dilinde miras alınmasını engelleyen sınıflardır. Bu özellik, kodunuzun sağlamlığını korumak ve belirli bir tasarımı güvence altına almak için kullanılabilir.

## Record class nedir?

- C# 9.0 ile birlikte gelen "record" sınıfı, sadece veri taşıyan ve genellikle değişmez olan veri yapılarını temsil etmek için kullanılan bir sınıf türüdür. "record" sınıfları, değer nesneleri (value objects) olarak adlandırılan ve özellikleri üzerinden eşitlik ve eşleştirme gibi işlemler gerçekleştiren sınıfları tanımlamak için kullanılır.
- "record" sınıfları, verileri depolamak için otomatik olarak gerekli tüm kodu oluştururlar. Bu, özellikleri tanımlarken getter ve setter gibi ayrı kodları yazmanıza gerek kalmadan basit bir şekilde özellikleri belirtebileceğiniz anlamına gelir. Ayrıca, "record" sınıfları varsayılan olarak "değer eşitliği" (value equality) olarak adlandırılan işlemleri destekler. Yani, iki "record" nesnesi aynı değere sahipse, bunlar eşit olarak kabul edilir.
- Aşağıda basit bir "record" sınıfı örneği verilmiştir:

```
public record Person
{
    public string FirstName { get; init; }
    public string LastName { get; init; }
    public int Age { get; init; }
}
```
- Yukarıdaki örnekte, "Person" sınıfı, bir kişinin adını, soyadını ve yaşını depolayan bir "record" sınıfıdır. "init" özelliği, özelliklerin sadece başlatıcı tarafından ayarlanabileceğini belirtir, yani sınıf oluşturulduktan sonra değerleri değiştirilemez.
- "record" sınıfları, özellikleri üzerinden desen eşleştirmesi (pattern matching) gibi işlemleri kolaylaştırır ve hızlıca verileri kopyalayıp değiştirmenizi sağlar. Ayrıca, "record" sınıfları, diğer sınıflarla birlikte kullanıldığında kodun daha okunabilir ve sürdürülebilir olmasını sağlayabilir.
- Bu nedenlerle, C# "record" sınıfları genellikle verileri taşımak, eşleştirmek ve karşılaştırmak için kullanılan basit veri yapısı sınıflarını tanımlamak için tercih edilir.

### CQRS Design Pattern nedir?

- Hazırlanıyor...

### DDD Design Pattern nedir?

- Hazırlanıyor...

### Outbox Design Pattern nedir, ne için kullanılır?

- Hazırlanıyor...

### Aggregate Root nedir?

- Hazırlanıyor...

### Value Object, Reference Object arasındaki farklar nelerdir. Açıklayınız?

- Hazırlanıyor...

### Entity kavramları nedir kısaca özetleyiniz?

- Hazırlanıyor...

### Event sourcing pattern hakkında ne biliyorsunuz nedir açıklayabilirmisiniz?

- Hazırlanıyor...

### RabbitMQ Exchange Nedir ? Exchange Tipleri nelerdir?

- Hazırlanıyor...

### Fair Dispatch nedir? Nasıl kullanılır?

- Hazırlanıyor...

### Builder Design Pattern nedir ne amaçla kullanılır?

- Hazırlanıyor...

### Spesification Design Pattern nedir ne amaçla kullanılır? 

- Hazırlanıyor...

### Factory Design Pattern nedir ne amaçla kullanılır?

- Hazırlanıyor...

### Saga Distributed Transactions Pattern nedir ne amaçla kullanılır?

- Hazırlanıyor...

### ConcurrentBag nedir ne için kullanırız?

- Hazırlanıyor...

### Lock mekanizması nedir hiç kullandın mı ? Ne için kullandın?

- Hazırlanıyor...

### Thread Safe – ConcurrentQueue, ConcurrentDictionary, ConcurrentBag, ConcurrentStack ve BlockingCollection Koleksiyonları hakkında neler biliyorsunuz?

- Hazırlanıyor...

### Asenkron programlama nedir? Hangi problemlere çözüm sağlamaktadır?

- Hazırlanıyor...

### ORM nedir? .Net/.Net Core platformlarında yaygın olarak kullanılan ORM teknolojileri hangileridir?

- Hazırlanıyor...

### Hangfire nedir? Hangi amaçla kullanılmaktadır?

- Hazırlanıyor...

### CI/CD nedir?

- Hazırlanıyor...

### Daha önce .Net/.Net Core platformlarında hangi test framework'lerini kullandınız?

- Hazırlanıyor...

