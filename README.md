# Obje Dedektörü Android Uygulaması
Bu uygulama Yolo V3 (Tiny) kullanılarak geliştirilmiştir. Uygulama gerçek zamanlı obje taraması yapar ve taramada yakalanamayan objeleri ivme verisini kullanarak takip eder. 
# Ayarlamalar
"Videoyu Kaydet" seçeneği gerçek zamanlı oynatılan videoyu /sdcard/DCIM klasörüne .avi formatında kaydeder.<br>
"Önizleme için FPS'i Uygulamaya Zorla" seçeneği uygulamanın her pozu en az 1000/FPS ms göstermesini sağlar. Zaman kaymasını azaltmaya yardımcı olur.<br>
"3 saniye işledikten sonra göster" seçeneği daha akıcı bir önizleme sağlamak amacı ile en az 5 saniyelik görüntü işledikten sonra önizleme sunar.<br>
"OpenCV FPS Metreyi AÇ" seçeneği görüntünün kaç FPS olduğunu gerçek zamanlı yansıtan FPS Metreyi arayüze ekler.<br>
"İvme test modunu etkinleştir" seçeneği obje taramasını askıya alır ve başlatıldığında ekranın ortasında beliren bir kutucuğu ivme verileri ile izler.<br>
"Alfa Değeri" bölümü uygulamanın kullanacağı alfa değerinin belirlenmesini sağlar<br>
"Saniyede işlenecek kare" seçeneği bir saniyede kaç video karesi işleneceğini belirtir.<br>
"Aranacak nesne" bölümü obje taramasındaki nesneleri filtrelemeyi sağlar. <br>Not: Uygulama ilk kurulumunda bir nesne seçmediğiniz taktirde tüm objeler filtrelenecektir.<br>
<br>

Bu uygulama [SensorCamera](https://github.com/yusufhanoglu/SensorCamera) projesinin Android'e uyarlamasıdır.<br>

