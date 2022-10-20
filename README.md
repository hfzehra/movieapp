# Movie App

Movie app projesi geliştirilebilir bir film sitesi projesidir. Python (django) diliyle yazılmıştır. SQL Lite veritabanı projede kullanılmıştır. 

 ###### Uygulama **2** kısımdan oluşur:
 - Yönetici paneli
 - Film paneli

 Film panelide kendi içersinde kategorilere ve sayfalara ayrılır:

 1. Account pages
    - Login
    - Register
    - Profile
    - Change Password


 2. Movies Pages
    - index (Anasayfa)
    - Movies (Filmler)
    - Movies_detail (Film Detayları Sayfası)


https://user-images.githubusercontent.com/64837576/196894374-7daa4b85-b571-4ed9-a080-c6d7af7b8416.mp4


## Uygulamayı çalışırmak için :

Öncelikle uygulamanın olduğu ![image](https://user-images.githubusercontent.com/64837576/196895472-b4ba0ec2-812c-4049-8928-e5fff6483730.png)
kısmından ;

![image](https://user-images.githubusercontent.com/64837576/196895597-0c75d0cd-5a00-4e17-a1b1-27973b91a2ce.png)

clone kısmını kopyalayın . Daha sonra VS code IDE'sinde projeyi açabilirsiniz.

Terminalden kendinize python için sanal makine oluşturun :


>python -m ven myenv

myenv kısmını istediğiniz gibi adlandırabilirsiniz .

<hr>

#### Sanal makinaya girme (windows için) : 
>myenv\Scripts\activate.bat

#### Sanal makinaya girme (linux için) : 
>source tutoriol-env/bin/activate

Projenin çalışması için projeyle alakalı paketlerin sanal makine içersine yüklemesi gereklidir. Sanal makine dizine girdikten sonra projenin içersinde bulunan requriment.txt dosyası projeye entegre edilmelidir. Aşağıda verilen kod ile bu işlem yapılır .

>pip install -r requirements.txt

Kodunuzu aşağıdaki kod ile çalıştırabilirsiniz:
> python manage.py runserver



