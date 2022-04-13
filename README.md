# TR_NOTES
My Cyber Security Notes

# 07.03.2022

# 14.03.2022


- ### CTF için -> <a href="https://overthewire.org/wargames/bandit/">Over The Wire - Bandit</a> <a href="https://medium.com/@denizparlak_/overthewire-bandit-ctf-%C3%A7%C3%B6z%C3%BCmleri-a14ac8c148f1">Note</a>
- ### Shell Built-in nedir ?

Shell builtin(yerleşik kabuk) kavramı, işletim sistemi servislerine erişmek için kernel üzerinde calisan shell içerisinde tanımlı bir komut ya da fonksiyon olarak adlandırılır. Harici bir program komutu shell üzerinde yorumlanarak yüklenir ve çalıştırılır.

- ### Nat Mode Nedir?

NAT bir ağda bulunan bilgisayarın, kendi ağı dışında başka bir ağa veya İnternete çıkarken farklı bir IP adresi kullanabilmesi için geliştirilmiş bir İnternet protokolüdür. Yani NAT bilgisayarın sahip olduğu IP adresini istenilen başka bir adrese dönüştürür.

- ### Bridged Mode Nedir?

Bridged Köprüleme ile, sanal makine dışardaki Ethernet ağına doğrudan erişime sahiptir. Sanal makine, ana ağdaki DHCP Sunucusu'ndan İP Adresi alır (Bu bir Firewall yada Router olabilir)

- ### <a href="https://www.vulnhub.com/">Vulnhub</a> Nedir?

Vulnhub farkı makinaları site üzerinden deploy etmek yerine kendi bilgisayarınıza sanal makina olarak kurup sızmaya çalışıyorsunuz. Makinaları kurup sızma testi gerçekleştirebilirsiniz. (Wakanda,Mr-Robot vb)

- ### Ssh ve Telnet arasındaki fark nedir?

Telnet'in güvenlik kısmı olmadığı için ilk olarak onun yedeği olarak ortaya çıkmıştır. Şuanda da uzak makine bağlantılarında en çok kullanılan protokoldür. Telnet'in aksine SSH güvenlik konusuna önem vermiş olup iletişimin şifreli olarak iletilmesini sağlamıştır.


- ### Kernel ve Shell arasındaki fark nedir?

Kernel, bir linux işletim sisteminin ana bileşenidir ve bir bilgisayarın donanımı ile ilgili süreçleri yönetir. Shell, bir kullanıcı ile bir işletim sistemi çekirdeği arasında bir arayüz sağlayan bir programdır.Kernel temel işlemleri yapıyor.(Dosya işlemleri vs)

- ### SSL nedir?

SL (Secure Sockets Layer) sertifikaları, site adreslerinin doğruluğunu kontrol eden, iki nokta arasındaki veri iletişimini şifreli kanal üzerinden yaparak güvenli bir şekilde iletilmesini sağlayan bir üründür. SSL sertifikaları, hiç bir zaman yazdığınız kodun veya web sitenizin güvenliğini sağlamaz.


- ### HSTS (HTTP Strict Transport Security) nedir?

User-Agentlara ve web tarayıcılarına en baştan ve tarayıcıya geri gönderilen bir yanıt başlığı üzerinden bağlantılarını nasıl kullanacaklarını bildiren bir web sunucusu yönergesidir. Kısaca HSTS, web sunucunuz veya web barındırma hizmetiniz için güvenlik ayarları ile ilgili tam güvenliği sağlayabilecek yoldur.


- ### IP Spoofing nedir?

IP spoofing veya IP sahteciliği, sahte kaynak IP adresi ile Internet Protokolü paketlerinin oluşturulmasıdır.

> ### OverTheWire

Her Level için şifreyi not almayı unutma.

- ### Level 0 

![image](https://user-images.githubusercontent.com/61595808/158646693-5049e7d8-2a8d-40eb-9bfb-eb9f1cb7a47c.png)


![image](https://user-images.githubusercontent.com/61595808/158648659-9f44fd20-4800-4525-8705-27903f2c7f89.png)

![image](https://user-images.githubusercontent.com/61595808/158648993-3065f96f-0bea-4484-b470-f755e35eb9a0.png)

- ### Level 0 → Level 1

>
### SSH NEDİR?

SSH (Secure Shell), ağ üzerinde bulunan bir sunucuya bağlanmaya ve bağlanılan sunucu üzerinde komut çalıştırma, dosya transferi gibi işlemleri gerçekleştirmeye olanak sağlayan bir uzak sunucu bağlantı protokolüdür.



Wakanda


# 21.03.2022

1.Virtual Box
2.Kali Linux
3.Wakanda CTF yapılacak.

- Makineye bağlanmak için ilk önce port taraması, aynı Nat'ta olmalı,ip adresibi aramalıyız.
- Port taraması nmap ile yapılıyor.
- ssh portu 22 nolu porttur.
- dirbis,dirbuster,nikto/OWASP/burpsuite
- wakanda seçiliyken ayarlardan usb'yi seçiliyi kaldırmalısın.
- port scanning araştır
- Kali de wakandayı kurduktan sonra yazman gerekenler
           *sudo su
           *nmap -r 10.0.2.0/24
           *nmap -sS -sv -A -p- 10.0.2.4
           *setxbmap tr ->klavyeyi ingilizceye çevirmek için  
 

- https://aysenurilhan98.medium.com/wakanda-1-hack-ctf-c13acd532181 buradaki yazıyı oku.           




![image](https://user-images.githubusercontent.com/61595808/163189791-0d2e90f4-c542-4998-9358-5084dadc0f2a.png)





![image](https://user-images.githubusercontent.com/61595808/163191654-51f9fe87-3daa-4201-92b0-90677e2e01cd.png)





![image](https://user-images.githubusercontent.com/61595808/163196902-d9de77e4-3018-45ab-828d-d621d593ed89.png)



![image](https://user-images.githubusercontent.com/61595808/163200092-91bfcebb-5433-45a9-872a-e47921d56749.png)
