# Patika.dev OOP

# Ödev - Üniversite Yönetim Sistemi

1 - Üniversiteye ait sınıflıklar, çalışma ofisleri ve departmanlar vardır.

2 - Departmanlara ait ofisler vardır.

3 - Üniversiteye ait çalışanlar vardır. Bu çalışanlar profesör veya memur olabilir.

4 - Her çalışan bir ofiste çalışır.

Bu sistemi tasvir eden Class (Sınıf) diyagramını çiziniz.

Not : Sınıflara ait nitelik ve davranışların belirtilmesine gerek yoktur.


![Untitled](https://user-images.githubusercontent.com/48656439/223553510-2be7956c-aef7-4f62-a541-46c9d289dbc6.png)


*******************************************************************


# Ödev - Hayvanat Bahçesi Yönetimi

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

Hayvanlar:
1 - Atlar (atlar, zebralar, eşekler vb.),

2 - Kedigiller (kaplanlar, aslanlar vb.),

3 - Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.

4 - Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır. tür adı, ağırlığı, yaşı vb.

5 - Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()

6 - Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()

7 - Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

![Untitled Diagram drawio](https://user-images.githubusercontent.com/48656439/224138124-21014748-aa81-4f51-95c5-8973bdcfc239.png)


*******************************************************************


# Ödev - Uçuş Yönetim Sistemi

Uçuşların ve pilotların yönetimi için bir sistem tasarlayın.

1 - Hava yolu şirketleri uçuşları gerçekleştirir. Her hava yolunun bir kimliği vardır.

2 - Hava yolu şirketi, farklı tipteki uçaklara sahiptir.

3 - Uçaklar çalışır veya onarım durumunda olabilir.

4 - Her uçuşun benzersiz kimliği, kalkacağı ve ineceği havaalanı, kalkış ve iniş saatleri vardır.

5 - Her uçuşun bir pilotu ve yardımcı pilotu vardır ve uçağı kullanırlar.

6 - Havaalanlarının benzersiz kimlikleri ve isimleri vardır.

7 - Hava yolu şirketlerinin pilotları vardır ve her pilotun bir deneyim seviyesi mevcuttur.

8 - Bir uçak tipi, belirli sayıda pilota ihtiyaç duyabilir.

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.

![air](https://user-images.githubusercontent.com/48656439/224179636-53153fc1-31f1-4eef-8629-fbbc555f1b7d.png)


*******************************************************************


# Ödev - Online Film Sistemi

Online film satan veya kiralayan uygulamanın sistemini tasarlayın.

1 - Uygulamada filmler listelenebilir, sıralanabilir ve kullanıcılar uygulamaya abone olabilir.

2 - Kullanıcılar abonelik için sistem üzerinden kredi satın alır.

3 - Sadece abone olan kullanıcılar, kredileri ile film kiralayabilir ve kiraladığı filmin kredi bedeli kadar hesabından düşülür.

4 - Normal kullanıcılar ve aboneler film satın alabilirler.

5 - Eğer film mevcut değil ise talep edilebilir.

Bu sistemi tasvir eden Class(Sınıf) diyagramını çiziniz.
