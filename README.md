# WordPress-on-Azure

WordPress on Azure
Herkese merhabalar ben Halil Furkan Damar. Bugün sizlere Microsoft Azure üzerinden WordPress sitesi nasıl oluşturulur bundan bahsedeceğim.

Öncelikle Azure hesabınızın olduğunu varsayarak ilerleyeceğim. Eğer hesabınız yoksa <link> üzerinden kolyalıkla oluşturabilirsiniz. Ben öğrenci mailimle hesap oluşturduğum için Azure for Students aboneliğine sahibim. Bunu belirtmemin sebebini ilerleyen cümlelerde açıklayacağım.


Azure Portal’da arama çubuğuna “App Service” yazarak App Service sayfasına geldikten sonra sol üstte yer alan “Create” butonuna tıklayalım. Açılan seçeneklerden “WordPress on Azure” seçeneğine tıklayalım. Artık oluşturmaya başlayabiliriz.

İlk olarak “Basic” sekmesinden başlıyoruz. “Project details” başlığında subscription ve resource group seçmemiz isteniyor. Var olan resource grouplarınızdan birini seçebilirsiniz ya da yeni bir resource group oluşturabilirsiniz.


“Hosting details” başlığında sunucunun region’ını ve sitenizin ismini belirlemeniz isteniyor. Burda dikkat edilmesi gereken konu öğrenci hesaplarında kullanılabilen region sayısı sadece 5. Bunlar Germany West Central, France Central, Poland Central, Sweden Central ve Switzerland North regionları.


“Hosting plans” başlığında uygulamamızın hangi planı kullanacağını seçiyoruz. Hosting planınız, App Service Planınızı, Veritabanı SKU’nuzu ve diğer kullanılabilir özellikleri belirler. Öğrenci aboneliği sadece Free ve Basic planı destekliyor. Siz kullanım durumunuza göre ikisinden birini seçebilirsiniz.


“WordPress setup” başlığında WordPress’e girişte kullanacağınız bilgileri doldurmanız gerekiyor.


Bundan sonra next butonuna tıklayarak “Add-ins” sekmesine geçiyoruz. Burdaki özellikleri inceleyebilirsiniz ancak kurulum için şart olmadığından boş bırakarak “Networking” sekmesine geçiyoruz. Eğer hosting planınızı free olarak seçtiyseniz burda virtual network seçtirmiyor zaten. Basic olarak seçtiyseniz var olan virtual networklerinizden birini seçerek ya da yeni bir virtual network oluşturarak devam ediyoruz.

“Deployment” ve “Tag” sekmelerini de zorunluluk içermediği için geçerek “Review + Create” aşamasına geliyoruz. Create diyerek artık süreci tamamlıyoruz. Deployment işlemi biraz vakit alabilir merak etmeyin 🙂

“Your deployment is complete” yazısını gördükten sonra ekrandaki “Go to resource” butonuna tıklayarak portaldaki Web App sayfasına yönlendiriliyoruz.


Bu sayfadaki “Browse” butonuna basarak veya default domaini kopyalayıp tarayıcıda açarak WordPress sayfamıza ulaşabiliriz. Ancak önce installing yapmasını beklemeliyiz.


Sonrasında sayfa karşınıza çıkacak. Site içeriğinde düzenleme yapmak için admin sayfasına gitmemiz gerekli. Bu yüzden site urlsinin sonuna “/wp-admin” ekleyerek admin sayfasına gidiyoruz.


Karşınıza çıkan ekranda oluşturma sürecindeki “WordPress setup” başlığında belirlediğimiz kullanıcı adı ve parolayı girerek admin sayfasına ulaşıyoruz.


Evet artık burdan sonrasında sitenizi istediğiniz içeriklerle doldurabilirsiniz ve belirlediğiniz domain ile ulaşabilirsiniz.

Yazımı bitirirken vurgulamakta fayda gördüğüm bir kısım var. Bu yazının amacı Azure Portal üzerinden WordPress sitesi nasıl oluşturulur ve konfigüre edilir onu göstermektir. Oluşturma sürecindeki bilmediğiniz kavramlar ya da atladığımız adımlar doğrudan yazının amacına hizmet etmediği için detaylandırma yapılmamıştır. Bunu gözeterek değerlendirmenizi rica ediyorum.

Okuduğunuz için çok teşekkür ederim umarım faydalı olmuştur.
