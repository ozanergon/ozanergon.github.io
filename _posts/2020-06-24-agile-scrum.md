---
layout: post
title: Agile Metodolojisi ve Scrum Framework
---

Bir manifesto olarak yayınlanan Agile bize çeviklik sağlayıp daha rahat ve daha doğru bir yöntem sunup bu kriterlerde başarı oranımızı arttırır. Scrum ise bir agile yazılım geliştirme framework’ü olup en çevik şekilde yazılım geliştirmemizi sağlar.

Yazılımlar aslında bir üründür ve ürünlerin bir yaşam döngüsü vardır. Bu döngü yazılım hem üretilirken hem de müşteri kullanırken gerçekleştirilen tüm aşamaları ifade eder. Yazılımların yaşam döngüsü tek yönlü veya doğrusal değildir ve birkaç temel adımdan oluşur. Bu adımlar sırasıyla şöyledir:
-	Planlama
-	Analiz
-	Tasarım
-	Gerçekleştirme
-	Bakım

Yazılım ekipleri süreç boyunca bu adımları izler.
Planlama kısmında yazılımın planlanması ve görev dağılımı yapılır. Analizde projenin ne kadar süreceği ve ne gibi risklerin olacağı belirlenir. Tasarımda yazılım projesinin nasıl sürdürüleceği tasarlanır. Gerçekleştirme kısmı projenin kodlandığı ve test işlemine tabi olunduğu yerdir. Bakım ise yazılım projesinin ürün olarak sunulduktan sonra belli aralıklarla taleplere ve eksiklere göre güncellemenin ve bakımının yapılmasıdır.
Yazılım yaşam döngüsünde birden fazla model vardır. Birden fazla olmasının sebebi yazılım projesinin büyüklüğü, projenin kimler için kullanılacağı gibi parametrelere bağlıdır.
Gelişigüzel Model: Bir modelde bir yötenm yoktur ve kişiye özeldir. Takibi zordur. Günümüzde kullanılmamaktadır.
Şelale(Waterfall) Model: Bu model günümüzde kullanılan güncel modellerin temelidir.Geleneksel bir modeldir  ve geçmişte en popüler döngü modeliydi. Bazı ekipler farketmeden ve uyguladığını bilmeden aslında bu modeli kullanıyor diyebiliriz. Bu modelde her aşama en bir kez tekrar edilir. Bu model iş tanımı çok iyi tanımlanmış ve kısa sürede bitebilecek projelerde kullanılır.

![image tooltip here](/assets/img/software-cycle.jpg)

**V Süreç Modeli:** V- model şelale modelinin gelişmiş hali olarak düşünülebilir. Bu model belirsizliklerin az olduğu, iş tanımlarının ise belirgin olduğu projelerde kullanılır. Bu tür projelere örnek olarak Bilgi Teknolojileri için geliştirilen projeler verilebilir.

![image tooltip here](/assets/img/v-surec-modeli.jpg)

**Helezonik(Spiral) Model:** Bu model klasik model ve prototipleme modellerinin iyi yönlerinin birleştirilmesiyle oluşturulmuştur.
Bu modelde kullanıcının kesin olarak gereksinimlerinin bir kısmı belirlenir ve bunlardan bir kısım ister tanımlanır. Bunların gerçekleştirimi yapıldıktan sonra ürünün testi yapılarak müşteriye teslim edilir. Art arda tekrarlanan 4 aşamadan oluşur.

Sol kanat üretim etkinlikleri, sağ kanat test etkinlikleri ile ilgilidir.
- Planlama aşaması; amaçların, olası seçeneklerin ve kısıtlamaların değerlendirildiği aşama
- Risk çözümlemesi; risklerin tanımlandığı ve çözüm yöntemlerinin irdelendiği aşama
- Mühendislik; ürünün geliştirildiği aşama
- Değerlendirme, ürünün müşteriyle birlikte değerlendirildiği aşama.
Bu aşamalar ürününün tamamlanmasına kadar geçen sürede tekrarlandığı için spiral halinde gösterilmektedir. Her bir çeyrek bir diğerinin girdisini oluşturarak devam eder.

![image tooltip here](/assets/img/spiral-model.jpg)

Birkaç model daha vardır. Bunlar: 
- Artımsal Geliştirme Modeli
- Kodla ve Düzelt Yaşam Döngü Modeli
- Evrimsel Geliştirme Modeli
- Prototipleme/Örnekleme Modeli
### Peki Agile Nedir? 
Agile yazılım sistemlerindeki genel giderlerin azaltılmasını sağlayan ve büyük değişikliklere neden olmadan istenilen değişikliklere hızlı bir şekilde cevap verebilmeyi amaçlayan yazılım geliştirme yöntemidir. Müşteriyi memnun etmek için uzun vadeli katı planlama ve geliştirme süreçleri yerine, değişen koşullara hızla adapte olup (hem değişen koşulların getirdiği riskleri bertaraf etme anlamında hem de değişen koşulların doğurduğu fırsatları yakalayabilme anlamında) çok kısa aralıklarla yeni sürümler çıkarmayı öne çıkaran bir yazılım geliştirme disiplinidir. Agile yöntemi, diğer sektörlerdeki yaklaşımların bir devamı olarak 1970’li yıllardan itibaren yazılım sektöründe uygulanmaya başlanmıştır. Yazılım geliştirme sürecini hızlandırmak, daha etkin kullanmak ve gerektiğinde dokümante etmek amacıyla ortaya çıkan, dünyada birçok yazılım firmasının farklı projelerinde benimsediği bu metodun kullanımı 1990’larda artmıştır.
Aşırı kuralcı klasik yazılım süreç modellerine tepki olarak ortaya çıkan Agile Manifestosu öncesinde yazılımlar daha yüksek maliyetli ve daha yavaş geliştirilmekteydi.
2001 yılında yazılım dünyasının önde gelen isimlerinde oluşan 17 kişilik ekip Amerika’nın Utah eyaletinde bir araya gelerek 2 gün süren bir toplantı yaptılar. Bu toplantının sonucunda fikir birliğine varılan 4 maddelik “Çevik Yazılım Geliştirme Manifestosu” nu yayınladılar.

![image tooltip here](/assets/img/agile-manifesto.jpg)

Yapılan bu toplantıda Agile Manifesto’nun yanı sıra Çevik Yazılım Prensipleri de yayınlandı.

### Çevik Yazılımın On İki Prensibi

- En önemli önceliğimiz değerli yazılımın erken ve devamlı teslimini sağlayarak müşterileri memnun etmektir.
-	Değişen gereksinimler yazılım sürecinin son aşamalarında bile kabul edilmelidir. Çevik süreçler değişimi müşterinin rekabet avantajı için kullanır.
-	Çalışan yazılım, tercihen kısa zaman aralıkları belirlenerek birkaç haftada ya da birkaç ayda bir düzenli olarak müşteriye sunulmalıdır.
-	İş süreçlerinin sahipleri ve yazılımcılar proje boyunca her gün birlikte çalışmalıdırlar.
-	Projelerin  temelinde  motive  olmuş bireyler yer almalıdır. Onlara ihtiyaçları olan ortam ve destek sağlanmalı, işi başaracakları konusunda güven duyulmalıdır.
-	Bir yazılım takımında bilgi alışverişinin en verimli ve etkin yöntemi yüz yüze iletişimdir.
-	Çalışan yazılım ilerlemenin birincil ölçüsüdür.
-	Çevik süreçler sürdürülebilir geliştirmeyi teşvik etmektedir. Sponsorlar, yazılımcılar ve kullanıcılar sabit tempoyu sürekli devam ettirebilmelidir.
-	Teknik mükemmeliyet ve iyi tasarım konusundaki sürekli özen çevikliği artırır.
-	Sadelik, yapılmasına gerek olmayan işlerin mümkün olduğunca arttırılması sanatı, olmazsa olmazlardandır.
-	En iyi mimariler, gereksinimler ve tasarımlar kendi kendini örgütleyen takımlardan ortaya çıkar.
-	Takım, düzenli aralıklarla nasıl daha etkili ve verimli olabileceğinin üzerinde düşünür ve davranışlarını buna göre ayarlar ve düzenler.

![image tooltip here](/assets/img/agile.jpg)

Agile metodolojisi altında çeşitli framework’leri barındırır. Bunlardan en çok kullanılanları aşağıdaki gibi sıralayabiliriz.

-	Scrum
-	Kanban
-	Lean
-	Extreme Programming (XP)
-	Test-Driven Development
-	Feature-Driven Development (FDD)
-	Dynamic Systems Development Method (DSDM)

Bu araştırma konusunda Scrum üzerine durulmuştur. Peki Scrum nedir? Scrum; Agile proje yönetim metodolojilerinden biridir. Kompleks yazılım süreçlerinin yönetilmesi için kullanılır. Bunu yaparken bütünü parçalayan; tekrara dayalı bir yöntem izler. Düzenli geri bildirim ve planlamalarla hedefe ulaşmayı sağlar. Bu anlamda ihtiyaca yönelik ve esnek bir yapısı vardır. Müşteri ihtiyacına göre şekillendiği için müşterinin geri bildirimine göre yapılanmayı sağlar. İletişim ve takım çalışması çok önemlidir. 3 temel prensip üzerine kurulmuştur;

-	***Şeffaflık;*** Projenin ilerleyişi, sorunlar, gelişmeler herkes tarafından görülebilir olmalıdır.
-	***Denetleme;*** Projenin ilerleyişi düzenli olarak kontrol edilir.
-	***Uyarlama;*** Proje, yapılabilecek değişikliklere uyum sağlayabilmelidir.

![image tooltip here](/assets/img/scrum.jpg)

***1)Product Backlog;*** Proje için gerekli olan gereksinimler listesidir. Proje sonunda “Ne üretilmek isteniyor?” sorusuna cevap aranır. Product owner tarafından müşteriden gereksinimler alınır, öncelik sırasına göre sıralanır.
***2)Product Backlog Item;*** Product backlog içindeki her bir gereksinime verilen isimdir.
***3)Sprint(Koşma);*** Proje sprint denilen küçük kısımlara ayrılır. Scrum içerisindeki tüm aktiviteler sprint içerisinde gerçekleşir.1–2 haftalık süreçlerdir.
***4)Sprint Backlog;*** Geliştirme takımı tarafından product backlog itemlar öncelik sırasına göre sprint içerisine alınırlar.
***5)Scrum board;*** Bir sprint içerisinde yapılacak olan maddeler burada yönetilir. Yapılacak olan tasklar “TO DO” bölümüne alınır. Takım üyesi bu işe başladığında “IN PROGRESS” bölümüne getirilir. Bir iş, test için hazırsa “TO VERIFY” durumuna getirilir. İş, kontrol edildikten sonra “DONE” bölümüne getirilir. Scrum toplantılarında bu maddeler durumlarına göre yerleri değiştirilir.
***6)Burndown Chart;*** Yatay ekseninde sprintin günlerini, dikey ekseninde sprintte kalan işi gösteren grafiktir. Scrum’un temel ilkelerinden olan şeffaflığı sağlar.
***Pig Roller;*** Scrum sürecine dahil olanlar yani projede asıl işi yapan kişilerdir. Bunlar Scrum Master, Product Owner, Geliştirme Takımı’dır.
***1) Product Owner;*** Geliştirme takımı ve müşteri arasındaki iletişimi sağlar. Projenin özelliklerini tanımlar.
***2) Scrum Master;*** Scrum kurallarını, teorilerini ve pratiklerini iyi bilir ve takımın bu kurallarını uygulamasından sorumlu kişidir.
***3) Geliştirme Takımı;*** Bir Sprint’e alınan bütün işleri tamamlayacak özelliklere sahip kişilerdir. sprint backlogu oluştururlar. Kendi kendini yönetir.


### Toplantılar
***1) Sprint Planning;*** Product backlog ile belirtilen gereksinimler, bu toplantı ile geliştirme takımı tarafından küçük görevlere (task) ayrılır.
***2) Daily Scrum;*** Her gün aynı yerde aynı saatte ayak üstü yapılan 15 dakikalık toplantılardır.
***3)Sprint Review;*** Her sprint sonunda yapılır. Yapılan sprint gözden geçirilir, ortaya çıkan ürün değerlendirilir.

