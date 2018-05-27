# IoTProject-OgunHatirlaticiKap

KOCAELI ÜNIVERSITESI TEKNOLOJI FAKÜLTESI BILISIM SISTEMLERI MÜHENDISLIGI 3. SINIF NESNELERIN INTERNETI DERSİ PORJESİDİR.

PROJE ADI: ÖĞÜN HATIRLATICI KAP 

HAZIRLAYANLAR : Gamze COSKUN(151307020), Hazal EROGLU(151307002), Magbula DEGER(151307066), Rümeysa Mumcu(151307041)

ÖGRETIM GÖREVLISI : Ugur YILDIZ

Agirlik sensörlü kap projesiyle, diyet yapanlara, yemegini belirli bir zamanda yemesi gerekenlere belirli saatler geçtikten sonra eger kap doluysa, mesaj yoluyla hatirlatma yaparak düzenlerini saglamayi amaçladik. 

Kullanilan Malzemeler : Raspberry Pi 3, HX711 Çift Kanal Tarti Sensörü Modülü, Uzun Load Agirlik Sensörü (0-5 KG), Jumper Kablo

1)Raspbian Isletim Sistemi Indirme;
Ilk olarak Raspbian’i https://www.raspberrypi.org/downloads/raspbian/ adresinden “Download ZIP” seçeneginden direkt olarak indirdik.

2)Isletim Sistemi Raspbian’i Micro-SD Kart’a Yazdirma
Indirdigimiz dosyayi .zip içerisinden çikartarak, indirdigimiz programi yardimiyla SD kartimiza yazdik.

3)Baglantilar ve Çalistirma
Isletim sistemini SD karta yazma islemini bitirdikten sonra SD kartimizi Raspberry Pi 3’e taktik.
Agirlik sensörümüz ve Raspberry Pi arasindaki baglantiyi HX711 Çift Kanal Tarti Sensörü Modülü yardimiyla board üzerinden yaptik.
Baglantilari gerçeklestirdikten ve kodlari yazdiktan sonra agirlik sensörümüzden deger almaya basladik. Fakat çözemedigimiz biz sebepten dolayi negatif veri almaya basladik. Calibration yapabilmemiz için agirlik sensörünün bostaki degerini 0’a indirmemiz gerekiyordu. Bu degeri 0’a indiremedigimiz için calibration’i yapamadik. Ve bu asamayi atlayamadigimiz için verileri buluta aktarma islemini gerçeklestiremedik. 

KAYNAKÇA :	 1) www.maker.robotistan.com 2) https://github.com/tatobari/hx711py 3) www.raspberrypi.org/
