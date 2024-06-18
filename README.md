# Object-Orientented-Programming-Nedir


![12](https://github.com/basrioglumehmet/Object-Orientented-Programming-Nedir/assets/166669195/d4f93898-73af-444a-a8b8-900339a84d5c)

### Cupra Leon bir arabadır. Bmw M5 başka bir arabadır. Ortak sınıfımız Araba isimli sınıftır.

- Yazılımların boyutları ve karmaşıklığı arttığı için bazı yazılım gereksinimlerini karşılamak amacıyla doğmuştur.
- Yazılım kodunun bakımı kolaylaştırır
- Neredeyse her dil OOP benimsemiştir.
- Her işlevin nesneler olarak soyutlandığı bir programlama yaklaşımıdır.

## Temel Prensipleri
### Encapsulation (Kapsülleme)

Sınıf field'ların dışarıdan müdaheleye kapanması ve gizlenmesidir. Gizlemeler access modifiers ile yapılmaktadır.
- Public: Dışarıya veya heryerden erişime açıktır
- Private: Sınıfa özeldir dışarıdan erişim yoktur
- Protected: Sınıf veya sınıftan türemişler erişebilir
- Internal: Aynı paket/proje içerisindekiler erişebilir.

### Abstraction (Soyutlama)

Soyutlama, karmaşıklığı yönetmek ve bir nesnenin veya sistemin önemli özelliklerini vurgulayarak gereksiz detaylardan arındırma sürecidir. 
İkiye ayrılır:
- Abstract sınıflar : Ortak metodları barındırır ve newlenemez.
- Interface'ler : Sadece metod imzalarını (ad ve parametreler) barındırır, metodun nasıl uygulanacağını ise içermez ve newlenemez.

### Inheritance (Kalıtım Miras)
![bedtime-boss-baby](https://github.com/basrioglumehmet/Object-Orientented-Programming-Nedir/assets/166669195/da2f070d-cb0d-4cba-a87c-14038f4ee67b)

Bir base sınıfın başka bir sınıfa aktarımı söz konusudur. Anne Baba Çocuk ilişkisidir. Javada extends iken c sharp'da : ile tanıtılır.


### Polymorphism (Çok Biçimlilik)
Alt sınıflar üst sınıfın gösterdiği davranışları göstermek zorunda değildir. Alt sınıfların farklı davranışları göstermesine Çok biçimlilik denilmektedir.
