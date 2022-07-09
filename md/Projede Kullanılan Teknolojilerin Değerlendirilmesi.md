[İndex](../index.md)

## Projede Kullanılan Teknolojilerin Değerlendirilmesi

### i. Mikro Denetleyici (Micro Controller)

Mikro denetleyici programlanabilme, bir programı içerisinde depolayıp daha sonra çalıştırabilme özelliklerine sahip tek bir chip‘ten oluşan bilgisayardır. Bu özelliği mikro denetleyicileri mikroişlemcilerden ayıran özelliğidir.

Mikro denetleyicilerde bir CPU (Central Process Unit) , RAM (Random Access Memory)  ROM (Read Only Memory) , input – output (giriş – çıkış  I/O) uçları , seri ve parelel portlar , sayıcılar (counter) ve bazı mikro denetleyicilerde de Analog ‘dan Digital ‘e (A/D) ya da Digital‘den Analog ‘a (D/A) çeviriciler (konvertör) bulunur. Mikroişlemciler kullanılarak oluşturulan sistemlerde ise (örneğin kullandığımız bilgisayarlar) bu özelliklerin her biri için ayrı mikroişlemci kullanılır.

Mikro denetleyicileri mikroişlemcilerden ayıran diğer bir özellikleri gerçek zamanlı uygulamalarda çalışmalarıdır. Gerçek zamanlı uygulamalarda işlemcinin dışındaki elektronik ortamdan gelen işaretler çok hızlı değişim gösterebilir. Bu nedenle bunları işleyip gereken çıkışları aynı hızlılıkta dış dünyaya uygulamak gerekebilir. Mikro denetleyiciler böyle bir performansı, çok küçük boyutlarda ve çok daha az güç tüketerek gerçekleştirebilirler.

Mikro denetleyiciler ucuz olmaları, tek mikro denetleyici ile elektronik çözümler üretebilme imkanı ve mikro denetleyici içinde program depolayabilme ve istenildiğinde çalıştırabilme olanağı gibi nedenlerle tercih edilirler.

### ii. 3D Yazıcı Arayüzü & Octoprint

OctoPrint, 3D yazıcıları kontrol etmek için açık kaynaklı hızlı bir web arayüz sistemidir. Octoprint.org adresinden web sitesine ulaşılabilir.

Octoprint herkesin ücretsiz olarak kullanabileceği bir yazılım olup Raspberry pi gibi tek karta indirgenmiş bilgisayarlar üzerinde sorunsuzca çalışabilmektedir.

Octoprint ile;

-	3D yazıcı ve yazdırma işlemi her yönüyle doğrudan web tarayıcıdan kontrol edilip izlenebilir.
-	Bağlı web kamerasının görüntüsüne uzaktan erişilebilir ve yazıcının nesneyi nasıl ürettiği web tarayıcıdan izlenebilir.
-	Bağlı web kamerasının baskı boyunca çektiği fotoğraflardan modelin oluşturulmasının zaman atlamalı videosu otomatik olarak oluşturulabilir.
-	Yazdırma işinin mevcut ilerlemesi hakkında web tarayıcısı üzerinden sürekli geri bildirim alınabilir.
-	Entegre GCODE görselleştiricisi ile yazdırılmakta olan GCODE hakkında bilgi alınabilir.
-	Baskı kafası ve tabla sıcaklıkları izlenebilir ve ayarlanabilir.
-	Baskı kafasını tüm eksenler boyunca hareket ettirilip baskı kafasına filaman sürülebilir.
-	PC’de hazırlık yapmadan, yazıcının basacağı GCODE dosyası, STL model dosyası direkt olarak dilimlenerek oluşturulabilir.
-	Yazdırma işi başlatılabilir, durdurulabilir veya duraklatılabilir.

Ethernet bağlantısı ile Octoprint sunucusu ağa tanıtılabilmekte ve web tarayıcıları üzerinden sunucuya erişilebilmektedir.

### iii. Restfull Servis Mimarisi & React Kütüphanesi

- *REST/Restfull*
  
REST (Representational State Transfer), 2000 yılında tanıtılmış ve tanımlanmıştır. REST, dağıtık sistemler tasarlamak için kullanılan bir mimari tarzdır.

REST, client-server arasındaki haberleşmeyi sağlayan HTTP protokolü üzerinden çalışan bir mimaridir. REST, servis yönelimli mimari üzerine oluşturulan yazılımlarda kullanılan bir transfer yöntemidir. İstemci ve sunucu arasında XML ve JSON verilerini taşıyarak uygulamanın haberleşmesini sağlar. REST mimarisini kullanan servislere ise RESTful servis denir.

- *React*

Bir JavaScript kütüphanesi olarak React, hızlı ve interaktif kullanıcı arayüzleri oluşturmaya olanak tanır. Facebook tarafından üretilmiş olan kütüphane, bir framework özelliği taşımaz. Mimari katmanla ilgisi yoktur ve yalnızca görünüm katmanına odaklanır. Tek işlevi, arayüzdeki tüm işlemleri mantıklı, kolay, maliyetsiz ve yüksek performanslı olarak yapmasıdır. React, element bazlı ve sanal DOM mimarisini kullanır.

React Sanal DOM mimarisini kullanan ve render işlemini hızlı şekilde fiile döken bir kütüphanedir. Bu yüzden değişikliğin çok fazla yaşandığı projeler üzerinde kullanılır. İşlemlerin daha çok kullanıcı arayüzü tarafında olduğu projelere uygundur denilebilir.

JSX, XML’in JavaScript içerisine yerleştirilmesi için dilbilgisi olarak tarfi edilebilecek olan bu araç, kodun biçimlendirme dili içine yazılmasına olanak tanır. Artılarına bakıldığında;

- Zaman kazandırır.
- IOS ve Android için harmanlanabilen kod tabanının oluşturulmasına olanak tanır.
- Yüksek kalibreli modern bir kullanıcı deneyimi sunar.
- Çok yönlü bir uygulama geliştirilmesini sağlar.
- Kullanıcı arabirimi duyarlıdır.
- Daha hızlı yükleme süresine sahip web siteleri oluşturulmasını sağlar.
- React DOM işlemini verimli şekilde günceller ve web bazlı uygulamalarda sorun yaşanmasını engeller. Sanal DOM’lar oluşturmaya yarayan araç, bunları bir hafızada tutmayı sağlar. Herhangi bir değişiklik olması durumunda sanal olan DOM da aynı anda günceller.

[İndex](../index.md)
