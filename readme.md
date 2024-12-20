# **Eczane-Yönetim-Sistemi**<br>

**Proje nasıl yürütülür:**<br>
1. Bu repoyu kullanarak klonlayın 
   - "git clone<br> https://github.com/Kaan-Kutlu/Eczane-Yonetim-Sistemi.git"<br>
2. Apache NetBeans veya seçtiğiniz herhangi bir IDE'yi yükleyin.<br>
3. WAMP veya XAMPP'yi veya seçtiğiniz herhangi bir sunucuyu kullanın.<br>
4. Öncelikle repodaki sql dosyasını kullanarak XAMPP sunucusunda MySql veritabanını oluşturun.<br>
5. Daha sonra projeyi IDE'den derleyin ve çalıştırın. <br>

**Giriş Bilgileri** <br>
 ```
 ID :1
 Şifre: admin
 ```
 not: Oturum açma bilgileri MySQL kurulumu sırasında veya daha sonra kullanıcı arayüzü aracılığıyla değiştirilebilir<br>
 
# GİRİŞ: <br>
Projenin ana amacı eczane mağazasının veri tabanının yönetimidir. Bu proje, Eczane Yönetim Sisteminin tasarımı ve uygulanmasına ilişkin bir fikirdir. Bu, mağazadaki mevcut ilaçların bir veri tabanı oluşturularak yapılır. Eczane yönetim sisteminin temel amacı, eczanelerde doğruluğu ve güvenliği ve verimliliği artırmaktır. Bu projenin amacı bir ecza deposunun etkin yönetimi için yazılım geliştirmektir. Bu yazılımı, stoktaki ilaçların istatistiklerini sağlayarak etkin Yönetim sağlamak amacıyla geliştirdik. 

**Projeyle ilgili açıklama:** <br>
Bu program, bakımı gereken bir veritabanına sahip olan tüm eczanelerde kullanılabilir. Kullanılan yazılım kullanıcının gereksinimlerine göre raporlar üretebilmektedir. Yazılım fatura, makbuz vb. yazdırabilir. Ayrıca tedarikçi tarafından gönderilen malzemelerin kaydını da tutabilir. Burada organizasyonu yöneten yönetici, çalışanın kayıtlarını yönetmekten sorumlu olacaktır. Her çalışana ayrı bir kullanıcı adı ve şifre verilecektir.

**Sorun Tanımı:**<br>
Projenin amacı, eczacının ilaçların kayıtlarını tutmasına, kullanıcı bilgilerini yönetmesine, fatura oluşturmasına, geçerliliğini kontrol edip yenilemesine ve dahili mesajlaşma sistemini kullanarak kullanıcılar arasında bir iletişim kapsamı sağlamasına yardımcı olacak etkili bir yazılım oluşturmaktır. Eczane yönetim sistemi eczane birimindeki ilaç ve sarf malzemelerinin bakımıyla ilgilenir. Bu eczane yönetim sistemi kullanıcı dostudur.


**Hedefler**<br>
-> **Birincil hedef**<br>
•Gerçek dünya problemlerine dayalı bir yazılımı modelleyerek pratik deneyim kazanmak. <br>
• Sunucu (xampp) kullanarak Ön Uç (Java) ve Arka Uç (MySQL) üzerinde nasıl çalışılacağını anlamak.

-> **İkincil hedef** <br>
• Herhangi bir eczanenin günlük ihtiyaçlarını karşılayan bir uygulama geliştirmek.<br>
•İlaçların (ilaçların) kolay yönetimini geliştirmek. <br>
•Satış ayrıntıları, satın alma ayrıntıları ve stokun sona ermesi ve miktarı gibi stok ayrıntılarını yönetmek.<br>
•Eczaneye rekabet avantajı sağlamak.<br>
•Stok hakkında gerekli ayrıntılar hakkında ayrıntılı bilgi sağlamak ve mağazada kolayca bulunmasına yardımcı olmak. <br>
•Stokları yönetilebilir hale getirmek ve eczanede stok kullanımını basitleştirmek.<br>

**Donanım ve yazılım araçları:**<br>
Sistem hizmetleri ve hedefleri, sistem kullanıcısı ile istişarede bulunularak belirlenir. Daha sonra ayrıntılı olarak tanımlanırlar ve sistem spesifikasyonu olarak hizmet ederler. Sistem gereksinimleri, sistemin üzerinde çalıştığı gereksinimlerdir.<br><br>

⚙️ **Donanım Gereksinimleri:**<br>
o Intel veya AMD işlemcili bilgisayar.<br>
o 1 GB+ DDR RAM<br>
o 40GB sabit disk sürücüsü<br>


💻 **Yazılım Gereksinimleri:**<br>
o Windows/ MacOS/ Linux işletim sistemi.<br>
o JRE ve JDK.<br>
o MySQL sunucusu (WAMP veya XAMPP veya herhangi biri)<br>
# Bölüm 2 - TASARIM<br>
Veritabanı Tasarımı, kurumsal veri yönetimi sistemlerinin tasarlanmasını, geliştirilmesini, uygulanmasını ve bakımını kolaylaştıran süreçlerin bir toplamıdır.<br>
Veritabanı sistemleri oluşturmaya yardımcı olur:<br>
o Kullanıcıların gereksinimlerini karşılayan<br>
o Yüksek performansa sahip olun.<br><br>

**Mimari Tanımı** <br>
Bir DBMS'nin tasarımı mimarisine bağlıdır. Merkezi, merkezi olmayan veya hiyerarşik olabilir. Bir DBMS'nin mimarisi, tek katmanlı veya çok katmanlı olarak görülebilir.<br><br>

# Bölüm 3 - UYGULAMA <br>
**Uygulama Açıklaması**<br>
Bu uygulamanın amacı ilaçları ve eczanenin çeşitli fonksiyonlarını yönetmektir. <br><br>
**Modüllerin listesi:**<br>
o Giriş sayfası<br>
o Ana sayfa<br>
o İlaç Şirketi<br>
o Satın Al<br>
o İlaçlar<br>
o Satış<br>
o Kullanıcı/Ayarlar<br>
o Mesajlaşma<br><br>

**Proje Görüntüleri**

![image1.png](Ekran_Goruntuleri/image1.png)

![image2.png](Ekran_Goruntuleri/image2.png)

![image12.png](Ekran_Goruntuleri/image12.png)

# Bölüm 4 - Sonuç ve Tartışma<br>
Bu web sitesi Eczane yönetimi, MySQL komutlarını ve veritabanını kullanarak, ilaç satış detayları ve sahiplerinin elde ettiği karlar da dahil olmak üzere kullanıcılardan alınan tüm verileri bu veri tabanında saklama eğilimindedir. Bu web sitesi, kullanıcının satışlar için fatura oluşturmasına, ilaçların son kullanma tarihini ve kalan miktarını kontrol etmesine olanak tanır. Ayrıca kullanıcıya geçerliliği yenileme ve mağazaya daha fazla ilaç ekleme ve veritabanını buna göre güncelleme seçenekleri sunar. Xampp sunucusu kullanılarak bu veritabanı komutları veritabanına kolayca başlatılır ve ilişkisel şema diyagramlarına sahip ER diyagramı, veritabanının yapısını daha hızlı hale getirmemize yardımcı olur ve web sitesinin ihtiyaçlarını anlamaları daha kolay olur.<br>


# SONUÇLAR VE GELECEK KAPSAM
o Detaylı bilgi toplama yapılmalıdır. Bu olmadan, yazılımı kullanma amacınız tam olarak karşılanamayacaktır.<br>
o Ancak uzun vadede iyi karlar sağlayabilir.<br>
o Yazılımın uygulanması iş uygulamalarında değişiklik yapılmasını gerektirir.<br>
o Analiz şirketi tüm bilgilerin verimli bir şekilde organize edilmesini sağlar ve analize kolay erişim ve bilgiye erişim mümkündür.<br>
o Bu projeye, barkod okuyucu kullanarak, son kullanma tarihini ve ilgili ilaçlarla ilgili diğer bilgileri tespit edecek BAR KOD özelliğini de dahil edebiliriz.<br>
o Bu yazılımı kullanan firma her zaman geleceğe yönelik plan yapabilecek ve piyasadaki mali durumunun her zaman farkında olabilecektir. <br>
o İş süreçlerinin işleyişinde kolaylık sağlar.<br>
o Biyometrik doğrulama dahil edilerek proje daha sağlam hale getirilebilir.<br>
o Bulut vb. gibi daha yeni teknolojilerin uygulanmasıyla genişletilebilecek bir kapsam da vardır. <br>
 
 
