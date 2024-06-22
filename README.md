# PYTHON İLE CIFAR10 VERİ SETİ KULLANILARAK RESİM SINIFLANDIRMA
## PROJENİN AMACI

CIFAR10 veri seti üzerinden CNN ağı ile nesne sınıflandırma yapılması amaçlanmıştır. Bu veri setinde bulunan uçak , otomobil,kuş , kedi , geyik , köpek , kurbağa ,at , gemi ve tır
nesnelerinin görselleri kullanılmıştır.

İlk olarak verilerin boyutları incelenip gerekli verileri tek boyutluya çevirme işlemi yapılmıştır. Sonrasında verilere normalizasyon işlemi yapılıp verile eğitime hazırlanmıştır.


CNN modeli tasarlanırken 2 adet Conv2D  ve Maxpooling2D katmanları kullanılmıştır. Overfittingi önlemek için Droput kulllanılmıştır. Ayrıca eğitimde öğrenmenin tekrarlanmaya başladığı
zamanlarda eğitimin devam etmesini önlemek için EarylStopping özelliği kullanılmıştır.

![image](https://github.com/MehmetCantemir/image_classification/assets/74190655/fbfeacbb-f522-4b29-9166-dede2be2c9e3)

Eğitim sonucunda %76 doğruluk oranı yakalanmıştır. Accuracy ve loss değerleri validation değerleri ile karşılaştırılıp performans doğruluğu ölçülmüştür.

Python dili ile gerçekleştirdiğim proje basit bir nesne tanımlama projesidir.
