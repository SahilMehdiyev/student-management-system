# Student-Management-System
Brew Kurulumu:

# brew install python3
NOT: Eğer MacOS ilk defa kurduysanız ve hemen ardından python3 kurmak isterseniz hata alabilirsiniz. Çünkü kurulum sırasında Apple Command Line Tool’u kullanmak isteyecek. Bu sorunu python3 kurmadan önce mutlaka xcode açıp gerekli kurulumlarını yapmanız gerek. İlgili linke şurdan bakabilirsiniz.

Xcode 4.4 and later install Command Line Tools
How do I get the command line builds tools installed with Xcode 4.4 / Mac OS X v10.8 (Mountain Lion) or later? Unlike…
stackoverflow.com

“brew” ile python3 kurduğumuzdan dolayı içinde pip3, Setuptools ve pyvenv (≥python3.4 sonrasında ve virtualenv alternatifi) içinde kurulmuş şekilde gelir.

# pyvenv aktif etmek için:

pyvenv myenv
source myenv/bin/activate
virtualenv kurmak için yapılacak adımlar;

# pip3 install virtualenv
Sırada projemizi hangi dizinde açacağımıza karar vermek kalıyor. Ben “projects/django/” altında “testapp” olarak bir klasör açıyorum. ve terminalden bu dizine gidiyorum.

cd /projects/django/testapp
sanal ortamı aktif etmek için;

virtualenv venv(istediğiniz ismi verebilirsiniz.)
source venv/bin/activate
sanal ortamı kapatmak için;

deactivate
Birçok django paketi kuracağımızdan ayrı bir sanal ortamda hem sistemizi hemde projemizi daha sağlıklı hale getirecektir.

# Django Kurulumu
Kurulumu yapmadan önce çalışacağımız proje dizinine tekrar gidelim.

pip3 install django==1.10
“Successfully installed django-1.10" mesajını gördüyseniz sorunsuz şekilde django’yu sanal ortamıza kurmuş olduk.

Django proje yaratmak için şu komutu kullanıyoruz. “webservices” istediğiniz proje ismini verebilirsiniz. “ . ” ise bulunduğu dizine oluştur demek. Eklemez iseniz ayrı bir klasöre projeyi oluşturur.

django-admin startproject webservices .
Projeleri PyCharm , Sublime Text 3 veya TextEditor ile yazmanız mümkün.


<img width="1440" alt="Screen Shot 2023-07-11 at 02 56 06" src="https://github.com/SahilMehdiyev/student-management-system/assets/86464376/6b2d3150-a1cf-4564-9eb4-383c57bb2685">
