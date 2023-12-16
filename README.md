# Object Detector Android Application
This application is developed using YOLOv3 (Tiny). The application performs real-time object detection and tracks objects that are not detected during the detection by utilizing accelerometer data.

## Settings
- The "Record Video" option saves the real-time played video to the /sdcard/DCIM directory in .avi format.
- The "Force FPS for Preview in the Application" option ensures that each frame of the application is displayed at least every 1000/FPS ms, helping to reduce time deviation.
- The "Show after Processing for 3 Seconds" option provides a preview after processing at least 5 seconds of footage to achieve smoother previewing.
- The "Enable OpenCV FPS Meter" option adds an FPS Meter to the interface, displaying the FPS of the image in real-time.
- The "Enable Accelerometer Test Mode" option suspends object detection and tracks a box that appears in the center of the screen using accelerometer data.
- The "Alpha Value" section allows setting the alpha value used by the application.
- The "Frames to Process per Second" option specifies how many video frames will be processed in one second.
- The "Object to be Searched" section filters the objects in object detection.
Note: If no object is selected upon the initial installation of the application, all objects will be filtered.

This application is an adaptation of the [SensorCamera](https://github.com/yusufhanoglu/SensorCamera) project for Android.


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

