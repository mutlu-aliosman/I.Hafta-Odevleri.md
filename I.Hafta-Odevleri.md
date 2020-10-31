# I.Hafta-Odevleri.md
## Açılması gereken hesaplar ;

- [Hackerrank](https://www.hackerrank.com/mutlu_aliosman)
- [Stackoverflow](https://stackoverflow.com/users/14513833/ali-osman-mutlu)
- [Linkedin](https://www.linkedin.com/in/ali-osman-mutlu-a343331b9/)
## Docker Nedir ?  Docker'a ait kavramlar nelerdir ?
- Docker; geliştirme ekiplerinin heryerde uygulama oluşturup yönetmesine ve güvenli hâle
Getirmesine olanak tanıyan yeni bir teknolojidir.
- Docker işletim sisteminin bir klonudur ancak boyut olarak çok çok küçük boyutlardadır.

  Docker öncesinde VM (Virtual Machine) ler ile bazı çözümlere ulşabiliyorduk Vm ile Docker arasında farklara biraz bakalım.
  
| VM                                    |                                   DOCKER|
:---------------------------------------|:----------------------------------------| 
| Tam İşletim Sistemi                   |Küçültülmüş İşletim Sistemi İmajı        |
|Yüksek İzolasyon                       |Daha Küçük İzolasyon                     |
|Dakikalar içinde Çalışılabilirlik      |Saniyet İçinde Çalışılabilirlik          |
|Versiyonlaması Yok                     |Versiyonlaması Yüksek                    |
|Kolay Paylaşılabilirlik Yok            |Kolay Paylaşılabilirlik Yüksek           |
## Docker Mimarisi Nedir ?
- İki temel parçadan oluşur.
  - 1. Linux kernel ile direk iletişimde olan docker daemon yani motor.
  - 2. Daemon ile iletişimde olan Docker CLI (Command Line Interface).
 * TCP ile harbeleşirler. 
 ## Container Nedir ?
 - Linux çekirdeği içerisinde birbirinden izole çalıştırılan processleri herbirine verilem isimdir.
 - Milisamiyeler içerisinde başlatılabilir duraklatılabilir ve ya durdurulabilir.
 
## Image Ve Dockerfile Nedir?
- Docker Daemon ile çalıştırılacak conteinerların baz alacağı işletim sistemi veya başka image dosya sisteminin
yapısı ve içerisindeki dosyaların çalıştırılacağı programı veya programları belirleleyen içeriği metin bazlı bir Dockerfile ile 
belirlenen bir ikilidir.
- Yukarıda ki metinde anlatılmak istenen aslında; benim bir image dosyam var ve dosya yolları bunlar buraya git bunları çalıştır 'image ve Dockerfile birlikte kullanılır.'

## Docker Daemon Nedir ?
- Çalıştırılacak Containerların birbirinden izole şekilde çalışmaları için gerekli ortamı sağlar.
- Bütün işlerin halledildiği kısımdır.
## Docker CLI (Command Line Interface) Nedir?
- Kullanıcının Docker Daemon ile haberleşmesini sağlayan komut sistemidir.
## Docker Registry Nedir?
- Oluşturulan dockerların kullanıcıların ulaşımına açılmasıdır.

(Docker registry'i c# daki uzaylar yada referanslar gibi düşünebilir miyiz ?)

## Docker Repohistory Nedir?
- Bir grup Image'ın oluşturulduğu yapıdır.

## Net Core Versiyonları Ve Bu Versiyonlar Arasındaki Farklar Nelerdir?
- Şuradaki [linki](https://docs.microsoft.com/tr-tr/aspnet/core/whats-new/2020-09?view=aspnetcore-3.0) inceleyip pek de birşey anlamadığım başlıktır.

## .Net 5 Geçilme İhtiyaçları Nelerdir, Geçiş Sürecinin Tamamlanmasıyla Neler Hedeflenmektedir.
- Temel hedef, .netcore,.net framework xamerin ve mono'nun avantajlarını tek çatı altında toplamaktır.
- Daha önceki versiyonlarda .netcore için yazılan kütüphanler .net frameworkde çalışmaya biliyordu bunun önüne geçilmek istenmesi.
- HTTP3 desteğinin gelmesi.(Daha hızlı daha günvenli.)
- Oyun platformları için Unity desteklenmesi.
- Mobil platformlara Xamarin kullanılarak uygulama geliştirilebilmesi.
- Asp.met Web form desteğinin sona ermesi.

## Markdown Yazımı ve Kullanımı
- Bu oluşturmuş olduğum belge bir markdown yazım örneğidir.:wink:

## Yazılım Alanında Takip Ettiğiniz Kişiler Kimlerdir?
- [Burak Selim Şenyurt](https://github.com/buraksenyurt)
- [Armağan Amcalar](https://www.youtube.com/channel/UCANCsbie9EorvBNWfpVntGQ)
- [Mehmet Dursun İnce](https://twitter.com/mdisec)(Siber Güvenlik)
- [Can Değer](https://twitter.com/Candeger)(Siber Güvenlik)

## Microsoft Azure Tarafında Ne Gibi Hizmetler Vardır?
  Kendi üzerinde bulut servisi sunarak burada;
  - Web sunucuları barındırma
  - Veri tabanı sunucusu oluşturma
  - Dosya depolama
  - Kullanıcı dizinleri
  - Mobil uygulamalar
  - Sanal makineler ve e-mail sunucusu oluşturma gibi servislerden yararlanmamızı sağlar.
    #### Azure Hizmetlerinden Kısaca Bahsetmek İstersek;
      - Compute Hizmetleri: Diskler,işlemciler,bellek,ağ ve işletim sistemleri gibi işlem kaynakları sağlar.
      - Kaynaklar dakikalar içinde ve ya saniyeler içinde kullanılılabilir hâle gelir.
      - Kullanım başına ödeme.
      
   #### Ortak Talep Üzerine Azure Hizmetleri Şunlardır;
  - Sanal Makineler
  - Containers
* Azure ile ilgili daha detaylı bilgi için [inceleyebilirsiniz.](http://www.msazureturkey.com/az-900-microsoft-azure-temelleri-sertifika-sinavina-hazirlik-egitimi-modul-2/)
## Beğendiğiniz Beş Tane İş İlanı
- [DoğuşTeknoloji](https://www.kariyer.net/is-ilani/dogus-teknoloji--net-developer-2576562)
- [INGBANK](https://www.linkedin.com/jobs/search/?currentJobId=2192932693&keywords=.net)
- [BursalıGrubu](https://www.kariyer.net/is-ilani/bursali-yazilim-yoneticisi-2603128)
- [İletişimYazılım](https://www.kariyer.net/is-ilani/iletisim-bilgisayar-yazilim-sistemleri-ihracat-ith-yazilim-uzmani-2604973)
- [PandoraX](https://www.kariyer.net/is-ilani/pandora-x-yazilim-arastirma-gelistirme-danismanlik-yazilim-gelistirme-uzmani-2595012)
## Kodun Kalitesinin Metrik Olarak Ölçülmesinden Ne Anlamaktasınız?
  * Doğrudan ölçüm
      - Kaynak kodun boyutu(LOC yani kod satırı ile ölçülebilir.)
      - Test süreci programı(Geçen süre saat cinsinden ölçülebilir.)
      - Tespit edilen hata sayısı(Defect sayımı ile ölçülebilir.)
      - Bir programcının projeye harcadığı zaman(Çalışılan aylara göre ölçülebilir.)
   * Türetilmiş Ölçüm
      - Geliştirici üretkenliği(Üretilen LOC/Ay-adam eforu)
      - Modül defet yoğunluğu(Defect sayısı/Modül boyutu)
      - Defect tespit verimliliği(Tespit edilen defect sayısı/Toplam defect sayısı)
      - Gereksinim Kararlılığı(Ele alınan test gereksinimlerinin sayısı/toplam test gereksinisimleri sayısı)
      - Sistem arıza ölçümü(Hataları düzeltmek için harcanan efor/Toplam proje eforu)
      
   * Daha ayrıntılı bir şekilde incelemek isterseneniz [buyrun.](http://www.arakatman.com/yazilim-kalite-metrikleri/)
    
   * Benim yorumum;
      - Kodun sadeliği
      - Kodun anlaşılabilirliği
      - Takım arkadaşımın benim yazdığımı anlayabilmesi.
      - Hızlı olması
      - Güvenilir olması
      
