# HelloWorldDeneme1
YAPILANLAR;
  -Kendi makinama a LİNUX yüklenmesi(BOOT ayarlarından açılış USB yapıldı. USB den yüklendi)
  -Local Makinama virtual machine yüklemesi yapıldı (https://www.virtualbox.org/wiki/Downloads)
  -Virtual machine üzerine Ubuntu Server Kurulumu yapıldı .(https://wiki.ubuntu.com/TrustyTahr/ReleaseNotes?_ga=1.196309861.833388703.1457530291)
  -Local makinama 
     sudo apt-get update
     sudo apt-get install jdk-8-oracle
     sudo groupadd tomcat
     Devamı(https://www.digitalocean.com/community/tutorials/how-to-install-apache-tomcat-8-on-ubuntu-14-04)
     buradan yapılarak içinde tomcat ve java ekleri yüklendi.
     
  -Hem local makinaya hemde ubuntu servera 
    "sudo apt-get install maven"
    komutu ile maven kurulumu yapıldı.
    
  -hem local makinaya hemde ubuntu servera
   "sudo apt-get install git"(https://www.digitalocean.com/community/tutorials/how-to-install-git-on-ubuntu-14-04)
   komutu ve devamı linkteki gibi git kurulumu yapıldı.
   
   -VM de settings kısmından ssh baglantıları gerceklestirildi hem tomcat için hemde ssh için portlar ayarlandı(settings->network->Atached to:NAT->Port Forwarding den portlar ayarlandı).
   
   -Githup hesabı acıldı .(www.github.com)adresinden.
   -İntelij IDEA da hello world uygulaması yapıldı .
   -Bu uygulama maven uygulamasıhaline getirildi.
   -Intelij IDEA dan github hesabına giris yapıldı.
   -Intelij IDEA dan tomcat tanımlandı .
   -VCS->import into vertion Control ->share project on github diyerek gerekli alanlara isimler verilip projenın dosyalarını github hesabına HelloWorldDeneme1 diye gönderdik.
   
   maven porjects den package dosyasına asağıdakı kodu yazdıktan sonra tekrar derledik.
   
 <packaging>war</packaging>
  ve ıntelij IDEA da var dosyasını olusturdum.
