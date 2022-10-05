# Urban-Sound-8K- Global AI HUB Deep Learning Bootcamp Final Assignment

## İÇERİK VE KAPSAM <br/>
Global AI HUB Deep Learning Bootcamp kapsamında gerçekleştirdiğimiz final projesinde “The Urban Sound 8K” veri setini, derin öğrenme algoritmalarıyla oluşturduğumuz model marifetiyle analiz ettik. Şehir seslerinin bulunduğu veri setinde 4 saniyeden küçük ya da eşit ses dosyaları bulunmakta ve bu sesler 10 sınıfa ayrılmaktadır. Söz konusu sınıflar:  Air Conditioner, Car Horn, Children Playing, Dog bark, Drilling Engine, Idling Gun Shot, Jackhammer, Siren, Street Music. 
Projenin temel amacı, şehir seslerini sınıflandırmak ve bunları kullanarak bir yapay zeka modeli hazırlamaktı.
Bu doğrultuda projeyi 3 temel aşamada ele aldık:

## 1)	Ses dosyalarını librosa kütüphanesini kullanarak spectrogramlara çevirmek ve söz konusu spectrogramları ait oldukları sınıflara kaydetmek. 


## 2)	Elde ettiğimiz görüntüleri (spectrogram) önişleme (preprocessing) uygulamalarıyla düzenlemek. 

Bu aşamada spectrogramları okuyarak  grayscale dönüşümü, resizing ve normalizasyon süreçlerini gerçekleştirdik. Görüntüleri [görüntü, etiket] formatında bir listeye kaydettikten sonra X_train, y_train, X_val, y_val, X_test ve y_test veri setlerine ayırdık.

## 3)	CNN modeli oluşturmak ve modeli hazırladığımız veriyle eğitmek.
Bu aşamada modeli eğittikten sonra performans ölçümlerini, accuracy ve loss grafiklerini ekrana yazdırdık ve hiperparametre optimizasyonu gerçekleştirdik.

## SONUÇ
Deep learning alanına giriş seviyesinde gerçekleştirdiğimiz bu projede temel hedefimiz yüksek performanslı bir model oluşturmaktan ziyade alanla ilgili temel bilgileri öğrenmekti. Bu doğrultuda modelimizin performansını arttırmak için epoch sayısını, katman sayısını, dropout miktarını değiştirmeyi denedik. Nihayetinde her ne kadar modelin performansı overfitting (aşırı öğrenme) sebebiyle düşük olsa da elde ettiğimiz bilgi ve beceriler alana dair merakımızı arttırdı. 
Bize böyle bir eğitimi ve imkânı sağlayan Global AI HUB ekibine teşekkür ederiz.

