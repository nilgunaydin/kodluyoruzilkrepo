 ## jenkins
 *KURULUMU YAPAMAYAN ARKADAŞLAR İÇİN Adres: http://3.83.176.40:8080*
*Kullanıcı Adı: test*
*Password: Test2022?*

1- jenkins bize soruldugunda ne oldugunu bilmemiz birkac cumle ile anlatabilmemiz lazim.
2- it sektorunde genelde devOpslar kurar biz bana verilen server adresine verilen sifre ve kullanicu adi ile giris yaptim kullandim github'ima entegre ettim kodlarimi gonderdim ve testi run ettim diyicez (kurmayi biliyorum veya jenkins biliyorum demeyecegiz)
3- jenkinsten once ----- jenkinsten sonra
4-slayt'a da bakariz
"Jenkins, 
-Sürekli Entegrasyon (CI: Continuous Integration) ve 
-sürekli dağıtım (CD:Continous Delivery) 
yöntemi için kullanılan java ile yazılmış açık kaynak kodlu  bir otomasyon sunucusudur. 
Yazılım geliştirme süreçlerini otomatize etmemize yarar. 
Jenkins, belirli bir sunucuda ve portta çalışır (8080 portu kendimiz de ayarlayabiliriz), 
belirlenen kaynaktan projeye ulaşır ve istenen işlemleri gerçekleştirir. 
Sonuçlarını belirlenen kişilere iletir. 
Bu sayede projemiz sürekli test edildiği için hatalar hızlıca tespit edilir ve çalışır bir vaziyette tutulur. 
Jenkins, manuel olarak yapılan build, test ve deploy gibi işlemleri uygular ve bu süreçte yaşanabilecek tüm aksaklık ve iletişim eksikliğini en aza indirir"

5- “Pipeline” terimi bir projenin ilk geliştirme aşamalarından halka 
yayınlanmasına kadar olan süreci tanımlamak için kullanılır.

jenkins pipeline in 3 temel asamasi 
-Proje oluşturma (build), 
-projeyi test etme (test) ve 
-projeyi dağıtma (deploy)  
-----------------------------------------------------------------------------

# adimlar
- Eklentiler kismi

- System configurations
* port degisikligi yapilabilir
* admin epostasi tanimlama
* system saat formati tanimlama
* github server i tanimlama
* github api usage 
<!-- -- ama buralar bizle alakali degil tabi -->

- Global tool configuration <!-- asil kullanacagimiz yer>
* jdk tanimlama --> java_Home > path goster (where java)  
* git tanimlama --> path goster(where git)  
* maven tanimlama --> isim mvn > path goster (program files icinde)
apply and save 

- New item 
* free style > ok
* github project'i sectim> url paste
*https://github.com/MuratTANC/JenkinsDeneme.git* bu yalin cunku 
* kaynak kodu yonetimine de  git secip ayni kodu yapistir^
* branch Specifier da main master dikkat (githubda neyse o)
* yapilandirma> maven version tanimla -> mvn > hedefler-> clean install
* save (ekrandan cikar)
* simdi yapilandir test ciktisi verir
* hatali test yap ve control center a bak
* yapilandirma gecmisi - kisiler vs 
* manager users asagida kisi ekleme falan

