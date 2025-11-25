SİBERTİM - Ultimate Pentest & IT Toolkit
SİBERTİM toolkit, IT yöneticileri, siber güvenlik öğrencileri ve pentesterlar için geliştirilmiş; sistem yönetimi, ağ analizi ve güvenlik testlerini tek bir modern arayüzde toplayan Python tabanlı bir araç setidir.

Sürekli komut satırına yazılan karmaşık komutları ve farklı araçları tek bir merkezden yönetmenizi sağlar.


Özellikler
Bu araç kiti, günlük operasyonlarda ihtiyaç duyulan 4 ana kategoride çözümler sunar:


Ağ ve Sistem Analizi
Whois Sorgulama: Alan adı sahiplik bilgilerini detaylı görüntüler.

IP/Konum Tespiti: IP adresi üzerinden coğrafi konum analizi.

DNS & Traceroute: DNS kayıtlarını sorgulama ve ağ yolu izleme.

IP Çözümleyici: Alan adından IP'ye veya IP'den alan adına dönüşüm.


Siber Güvenlik Araçları
Port Tarayıcı: Hedef sistemdeki açık portları tespit eder.

Nmap Entegrasyonu: Hızlı Nmap taramaları başlatır.

Scapy ARP Scan: Yerel ağdaki cihazları (IP ve MAC adresleri) keşfeder.

Web Spider & Subdomain: Web sitelerindeki linkleri ve alt alan adlarını tarar.

Güvenlik Başlığı Kontrolü: Web sitelerinin HTTP güvenlik başlıklarını (Security Headers) analiz eder.


Sistem Yönetimi
Hızlı Erişim: Denetim Masası, Görev Yöneticisi, Regedit, Hizmetler gibi Windows araçlarına tek tıkla ulaşım.

Sistem Onarım: SFC Scannow, Disk Yönetimi ve Güvenlik Duvarı kontrolleri.

Kriptografi ve Yardımcı Araçlar
Hash Hesaplayıcı: Dosya ve metinler için MD5, SHA1, SHA256 değerlerini hesaplar.

Kodlayıcılar: Base64, URL Encode/Decode ve ROT13 işlemleri.

Parola Oluşturucu: Özelleştirilebilir güçlü parolalar üretir.

Kurulum ve Kullanım (EXE Sürümü)
Python veya herhangi bir kütüphane kurmanıza gerek yoktur.

Releases kısmından en son sürümü (.zip) indirin.

Dosyayı klasöre çıkartın.

main.exe dosyasını Yönetici Olarak Çalıştırın.


Not: Ağ tarama ve sistem onarım araçlarının (Scapy, SFC vb.) düzgün çalışabilmesi için yönetici yetkisi gereklidir.


"Windows Kişisel Bilgisayarınızı Korudu" Hatası
Program dijital olarak imzalanmadığı (açık kaynaklı ve bireysel geliştirildiği) için ilk açılışta Windows SmartScreen uyarısı alabilirsiniz. Bu tamamen normaldir.

Çözüm:

Çıkan mavi ekranda "Ek bilgi" (More info) yazısına tıklayın.

Altta çıkan "Yine de çalıştır" (Run anyway) butonuna basın.


Geliştirici Kurulumu (Kaynak Kod)
Projeyi geliştirmek veya kaynak koddan çalıştırmak isterseniz:


# Projeyi klonlayın
git clone https://github.com/memx13/toolkit

# Klasöre gidin
cd SiberTim

# Gerekli kütüphaneleri yükleyin
pip install -r requirements.txt

# Uygulamayı başlatın
python main.py


Yasal Uyarı (Disclaimer)
Bu yazılım eğitim ve test amaçlı geliştirilmiştir. Araçların izinsiz sistemlerde saldırı amaçlı kullanılması yasa dışıdır ve tüm sorumluluk kullanıcıya aittir. Geliştirici, bu aracın yanlış kullanımından doğacak sonuçlardan sorumlu tutulamaz.

Geri Bildirim ve İletişim
Projeyi kullandıktan sonra görüşlerinizi, önerilerinizi veya bulduğunuz hataları Issues kısmından bildirebilirsiniz.

Beğendiyseniz projeyi yıldızlamayı unutmayın!


Developed by Mehmet Emin MAĞNİSALIOĞLU
