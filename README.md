<h1>I. HAFTA ÖDEVİ</h1>
<h3> Hackerrank Profiim</h3>
<a href="https://www.hackerrank.com/onur753_com" target="_blank">Hackerrank</a>

<h3>Docker Nedir?</h3>
Docker, uygulamalarınızı hızla derlemenize, test etmenize ve dağıtmanıza imkan tanıyan bir yazılım platformudur.

Docker Container Nedir? 
Docker Container'lar docker imajlarının çalışan örnekleridir. Bir imajı çalıştırmak bir docker container oluşturur. İmajlar container oluşturmakta kullanılabilecek bir şablon sağlar. Container oluşturmak için neyin gerektiğinin bilgisini içerirler. İmajlar yerel olarak veya uzakta depolanabilir.

Docker Image Nedir:
Docker image adından da anlaşılacağı gibi çalışacak uygulamanızın ve uygulamanızın altyapısında çalışan gerekli işletim sistemi kütüphanelerinin bulunduğu bir yapıdır. İmajları, container yaratmak için gereken talimatların bulunduğu bir şablon olarak düşünebiliriz. docker image build komutu ile bir Dockerfile üzerinden oluşturduğumuz yapılardır.

Docker Registry Nedir:
İmajların tutulduğu ve dağıtıldığı bir ortamdır. Aynı Github'da olduğu gibi elimizdeki imajları docker registry'sine push edebilir veya daha önceden yüklenmiş olan bir docker imajı kendi localimize çekebiliriz. Bu sayede ihtiyaçlarınızı karşılayacak bir imaja çok hızlı bir şekilde erişebilir, gerekirse üzerinde değişiklik yapabilir ve tag'leyerek farklı bir versiyon olarak yeniden gönderebiliriz.


.Net 5 geçilme ihtiyaçları nelerdir?

Büyük değişiklikler için büyük hazırlık süreçleri gerekir, günlük hayatta her zaman kurulan yapıları, üretilen çözümleri güncellemek zorunda olduğumuz bir mesleğin içerisindeyiz.
.Net Core ile platformlar arası bir geçişe başlayan Microsoft .Net 5 ile
yeniden bir araya geliyor.
.Net dünyasını yakın zamanda bekleyen 2 büyük release vardı, .Net Core 3.0 ve .Net 5.
.Net Core 3.0 versiyonu tamamlandı, şimdi sıra .Net 5'de.
Aslında bu geçiş aşamasında .Net Core 3 ve 3.1 versiyonları bence en önemli ve en değerli versiyonlardı.Köprüden önceki son çıkış gibi düşünebilirsiniz. :)
.Net Core 3.x versiyonunda gRPC, Blazor gibi yeni özelliklerini pazara çıkartan Microsoft, benim gözlemlerim doğrultusunda oldukça başarılı oldu diyebilirim. Çünkü .Net Core 3 .Net’in en hızlı kabul gören versiyonu oldu.
Temel olarak .Net 5 ile hedeflenen, .Net Core, .Net Framework, Xamarin ve Mono’nun avantajlarını tek bir çatı altında toplamaktır.
.Net 5 ile artık tek bir .Net olacak, yani Xamarin,Unity,ML.Net dahil olmak üzere tüm framework’ler tek bir çatı altında birleşiyor.
Release tarihi olarak şu anda planlanan tarih Kasım 2020 ancak Preview versiyonları ile .Net 5'i daha yakından tanıyabiliriz.
Şimdiye kadar .Net Core için yazdığımız kütüphaneler .Net Framework’te çalışmayabiliyordu, bu benim gün içerisinde sürekli karşılaştığım bir problem, .Net Framework ile yazılmış bir uygulamayı .Net Core’a geçirirken shared library olarak bazı tanımlamalar yapmak gerekebiliyor.
Çözüm olarak tanımlamalarımızı .Net Standart ile geliştirmemiz gerekiyordu ancak .Net 5 ile birlikte artık tek bir Base Class Library olacak.
Şu anda Xamarin uygulamaları Mono Base Class Library kullanırken artık .Net 5 ile .Net Core Base Class Library kullanabilecek.
Her yeni sürümde olduğu gibi performans iyileştirmeleri mevcut tabi.
BCL’de daha hızlı algoritmaların yanı sıra HTTP3 desteğide .Net 5 ile .Net dünyasına giriş yapacaktır.
Game Development
.Net 5 mobil, Xbox ve diğer oyun platformları için oyun geliştirebileceğiniz unity’yi destekleyecek.


.Net Core versiyonları ve bu versiyonlar arasındaki farklar

.Net Core 2.0:

1.NETStandard2'ye inanılmaz sayıda API eklenmiştir.

2.SUSE ile desteklenen platform serisine heyecan verici bir eklentimiz var. Debian ve Fedora, son zamanlarda 2.0'da da desteklenen güncellemeleri yayınladı.

3.Yükleyici Paket Adı Değişiklikleri

4.C# ve F#'ı desteklemektedir.

5..NET Core Visual Basic 2017'yi desteklemektedir.

.Net Core 3.0:

1.En büyük geliştirmelerden biri, Windows Masaüstü uygulamaları için destek içerir (yalnızca Windows). .NET Core 3.0 SDK bileşeni Windows Masaüstünü kullanarak Windows Forms ve Windows Presentation Foundation (WPF) uygulamalarınızın bağlantı noktası oluşturabilirsiniz.


Yazılım alanında takip ettiğiniz kişiler kimlerdir?
<ul>
  <li>Atil SAMANCIOĞLU <a href="https://www.youtube.com/channel/UCnmAu7FF7LeoyTozrMVtTxQ" target="_blank">Atil SAMANCIOĞLU Youtube</a></li>
  <li>Yazılım Bilimi <a href="https://www.youtube.com/channel/UCZNZj3mkdCGJfCoKyl4bSYQ" target="_blank">Yazılım Bilimi  Youtube</a></li> 
</ul>

Markdown yazımı ve kullanımı

Tanım
2004 yılında John Gruber ve Aaron Swartz tarafından geliştirilen bir yazım formatıdır. En basit tanımıyla text-to-HTML yani yazıyı HTML'e çevirmemizi sağlar.

Markdown formatı ile yazarken herhangi bir html etiketi yazmayız, markdown'ın syntax'ına uygun şekilde yazarız ve kulladığımız front-end ya da back-end dili ile bunu parse ederek html çıktısını alırız. Böylece yazan kişininde hata payı minimuma iner, daha okunaklı bir yazım tarzı oluşur.

Gelin html'de yazdığımız şekilde markdown'da nasıl yazarız temel olarak inceleyelim.

Kullanımı

<img src="https://images.dnomia.com/ceaksan/r-markdown.jpg" alt="Markdown" title="Markdown Trendline">



