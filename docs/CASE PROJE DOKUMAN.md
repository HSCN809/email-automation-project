CASE DOKUMAN

**Proje Tanımı**

Bu projenin amacı:

1.  Excel tablosunda yer alan **email** adreslerini çekmek, çekilen
    emailleri farklı segmentlere ayırmak ve her bir segmentte yer alan
    kişilere belirli zaman aralıklarında üçer farklı içerikte **email**
    göndermektir.

2.  Gönderilen emaillerin içerisindeki butonlara tıklanması durumunda,
    bu etkileşimlerin ayrı bir **excel** tablosuna log olarak
    kaydedilmesini sağlamaktır.

Bu şekilde, temel bir otomasyon sistemi kurulması hedeflenmiştir.

Aşağıdaki görseller projeyi adım adım açıklamaktadır:

![](media/image1.png){width="6.3in" height="2.111111111111111in"}

![](media/image2.png){width="5.189172134733158in"
height="1.4843088363954506in"}

![](media/image3.png){width="6.3in" height="1.4076388888888889in"}

İlk görsel, otomatik olarak **email** gönderimini sağlayan iş akışını
göstermektedir. İkinci görsel ise, gönderilen emaillerin içinde yer alan
butonlara tıklanması durumunda, bu tıklamaların sistem tarafından
algılanarak butonun içindeki link sayesinde tıklayan kişinin bilgilerini
toplamasını ve bu bilgilerin ayrı bir **excel** tablosuna log olarak
kaydedilmesini sağlamaktadır.

Üçüncü görselde ise bu log tablosundaki verilerden oluşturulan iki
farklı tablo yer almaktadır:

- İlk tablo, her bir segmentteki belirli bir **email**'e kaç kez
  tıklanıldığını detaylı biçimde göstermektedir.

- İkinci tablo ise, kaçıncı email gönderildiği fark etmeksizin, doğrudan
  hangi segmente ait emaillere toplamda kaç kez tıklanıldığını
  özetlemektedir.

Bu iki tabloyu içeren rapor, sistem tarafından haftalık olarak bir
**email** ile gönderilmektedir.

Gönderilen raporun içeriği de aşağıdaki örnekte olduğu gibi
gösterilmiştir.

![](media/image4.png){width="3.7290332458442697in"
height="3.658333333333333in"}

![](media/image5.png){width="3.8106747594050745in"
height="3.26251312335958in"}

**Gözlemlenen Etkiler**

Hazırladığım projede hedeflediklerim:

1.  Email gönderim süresini en az yüzde 80 oranında azaltmak.

2.  Bütün bu sürecin (hem gerçekleşmesi hem de takip edilmesi açısından)
    tutarlılığını sağlamak

3.  Emaillere dönme bir başka deyişle emaillere tıklanma oranında yüzde
    15-20 artış potansiyeli.

**Deneme**:

10 farklı kişiye, her birine ikişer saniye arayla toplam üçer adet
e-posta gönderilmiştir. Yani toplamda 30 adet e-posta gönderme işlemi
**yaklaşık 32 saniyede**
tamamlanmıştır.![](media/image6.png){width="3.2848600174978126in"
height="2.9216633858267715in"}![](media/image7.png){width="2.988155074365704in"
height="2.9351246719160105in"}

Yukarıda iki farklı e-posta örneği yer almaktadır. Soldaki e-posta
otomasyon sistemiyle gönderilmişken, sağdaki e-posta ise manuel olarak
tarafımdan yazılıp gönderilmiştir.  
30 e-postayı 32 saniyede göndermek mümkün olmuşken, yalnızca 1 e-postayı
manuel olarak göndermem yaklaşık **2 dakika 30 saniyemi** almıştır. Bu
işlemi 30 e-posta için tekrar etmem gerekseydi, toplamda **75 dakika
(4500 saniye)** sürecekti.

Oysa otomasyon sistemi ile bu işlem sadece 32 saniyede tamamlandı.  
Bu durumda, 30 e-postanın gönderilme süresi yaklaşık **%99.29 oranında
azalmış** oldu.

🔹 **Sonuç olarak**, geliştirdiğim bu otomasyon sistemi zaman açısından
ciddi bir tasarruf sağlamakta ve süreci verimli hâle getirmektedir.

Ayrıca, bu sürecin tamamen otomasyona dayalı olarak yürütülmesi herhangi
bir tutarsızlığa yol açmamış; gönderilen e-postalar başarılı bir şekilde
ve biçimsel bozulma olmaksızın iletilmiştir.

Son olarak, **yapay zekâ destekli otomasyon sistemiyle** oluşturulan
e-postaların, manuel olarak hazırlanan e-postalara kıyasla **tasarımsal
açıdan daha profesyonel ve estetik** göründüğü de gözlemlenmiştir. Bu
da, müşterinin e-postaya dönüş yapma ihtimalini artıran önemli bir
faktör olarak değerlendirilebilir.

**Hangi Emailler Daha Etkili Oldu?**

Hazırlanacak geri dönüş raporuna geçmeden önce belirtmek isterim ki,
raporda yer alacak **veriler ve istatistikler sentetiktir**; yani sadece
sistemin işleyişini ve analiz mantığını göstermek amacıyla
oluşturulmuştur.

![](media/image8.png){width="3.0124026684164478in"
height="2.6574343832020997in"}![](media/image9.png){width="3.35175634295713in"
height="1.964494750656168in"}

📊 **Tablolara Göre Elde Edilen Bulgular**

1.  **Email Bazlı Değerlendirme**  
    İlk segmentte (Deneme Aldı Ama Satın Almadı) en fazla geri dönüşün
    **1. email**e yapıldığı görülmektedir.  
    İkinci segmentte (Form Doldurdu, Deneme Almadı) ise hem 1. hem 2.
    email\'e eşit sayıda tıklama yapılmıştır.  
    Üçüncü segmentte (Denemeye Katıldı, İlgi Gösterdi) ise özellikle
    **3. email** en fazla geri dönüşü almıştır.  
    Dördüncü segmentte (Hiç Etkileşim Yok) 1. ve 3. emaile birer kez
    tıklanmıştır.

Bu bulgular, her segmentin etkileşim zamanlamasının farklı olabileceğini
göstermektedir. Örneğin üçüncü email, sadece 3. segmentte etkili
olmuşken diğer segmentlerde ilk emailler daha etkili olmuştur.

2.  **Segment Bazlı Değerlendirme**  
    Toplam tıklama sayılarına bakıldığında en yüksek etkileşim,
    **"Denemeye Katıldı, İlgi Gösterdi"** segmentinden gelmiştir (toplam
    6 tıklama).  
    Bu grubu sırasıyla **"Form Doldurdu, Deneme Almadı" (5 tıklama)** ve
    **"Deneme Aldı Ama Satın Almadı" (4 tıklama)** segmentleri takip
    etmektedir.  
    En düşük etkileşim ise beklendiği gibi **"Hiç Etkileşim Yok"**
    segmentinde gözlemlenmiştir (2 tıklama).

Bu veriler, müşterinin daha önceki aksiyonları ile (örneğin form
doldurmak veya deneme almak gibi) sonradan yapılan email etkileşimleri
arasında doğrudan bir ilişki olduğunu ortaya koymaktadır.

Özellikle 3. segmentin (denemeye katılmış ve ilgi göstermiş) en yüksek
geri dönüşü sağlaması, email gönderim zamanlamasının bu tür segmentlerde
daha anlamlı olabileceğini göstermektedir.
