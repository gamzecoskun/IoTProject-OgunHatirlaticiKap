# IoTProject-OgunHatirlaticiKap

<b>KOCAELI ÜNIVERSITESI TEKNOLOJI FAKÜLTESI BILISIM SISTEMLERI MÜHENDISLIGI 3. SINIF NESNELERIN INTERNETI DERSİ PORJESİDİR.</b>

<b>PROJE ADI:</b> ÖĞÜN HATIRLATICI KAP 

<b>HAZIRLAYANLAR:</b> Gamze COSKUN(151307020), Hazal EROGLU(151307002), Magbula DEGER(151307066), Rümeysa Mumcu(151307041)

<b>ÖGRETIM GÖREVLISI:</b> Ugur YILDIZ

<b>Amaç:</b> Agirlik sensörlü kap projesiyle, diyet yapanlara, yemegini belirli bir zamanda yemesi gerekenlere belirli saatler geçtikten sonra eger kap doluysa, mesaj yoluyla hatirlatma yaparak düzenlerini saglamayi amaçladik. 

<b>Kullanilan Malzemeler: </b> Raspberry Pi 3, HX711 Çift Kanal Tarti Sensörü Modülü, Uzun Load Agirlik Sensörü (0-5 KG), Jumper Kablo

<b>1)Raspbian Isletim Sistemi Indirme; </b>

Ilk olarak Raspbian’i https://www.raspberrypi.org/downloads/raspbian/ adresinden “Download ZIP” seçeneginden direkt olarak indirdik.

<b>2)Isletim Sistemi Raspbian’i Micro-SD Kart’a Yazdirma;</b>

Indirdigimiz dosyayi .zip içerisinden çikartarak, indirdigimiz program yardimiyla SD kartimiza yazdik.

<b>3)Baglantilar ve Çalistirma</b>

Isletim sistemini SD karta yazma islemini bitirdikten sonra SD kartimizi Raspberry Pi 3’e taktik.
Agirlik sensörümüz ve Raspberry Pi arasindaki baglantiyi HX711 Çift Kanal Tarti Sensörü Modülü yardimiyla board üzerinden yaptik.
Baglantilari gerçeklestirdikten ve kodlari yazdiktan sonra agirlik sensörümüzden deger almaya basladik. Fakat çözemedigimiz bir sebepten dolayi negatif veri almaya basladik. Calibration yapabilmemiz için agirlik sensörünün bostaki degerini 0’a indirmemiz gerekiyordu. Bu degeri 0’a indiremedigimiz için calibrationi yapamadik. Ve bu asamayi atlayamadigimiz için verileri buluta aktarma islemini gerçeklestiremedik. 

KAYNAKÇA :	 

1) www.maker.robotistan.com 

2) https://github.com/tatobari/hx711py 

3) www.raspberrypi.org/
