# PYTHON İLE CIFAR10 VERİ SETİ KULLANILARAK RESİM SINIFLANDIRMA [TR]
## PROJENİN AMACI

CIFAR10 veri seti üzerinden CNN ağı ile nesne sınıflandırma yapılması amaçlanmıştır. Bu veri setinde bulunan uçak , otomobil,kuş , kedi , geyik , köpek , kurbağa ,at , gemi ve tır nesnelerinin görselleri kullanılmıştır.

İlk olarak verilerin boyutları incelenip gerekli verileri tek boyutluya çevirme işlemi yapılmıştır. Sonrasında verilere normalizasyon işlemi yapılıp verile eğitime hazırlanmıştır.

CNN modeli tasarlanırken 2 adet Conv2D  ve Maxpooling2D katmanları kullanılmıştır. Overfittingi önlemek için Droput kulllanılmıştır. Ayrıca eğitimde öğrenmenin tekrarlanmaya başladığı zamanlarda eğitimin devam etmesini önlemek için EarylStopping özelliği kullanılmıştır.

![image](https://github.com/MehmetCantemir/image_classification/assets/74190655/fbfeacbb-f522-4b29-9166-dede2be2c9e3)

Eğitim sonucunda %76 doğruluk oranı yakalanmıştır. Accuracy ve loss değerleri validation değerleri ile karşılaştırılıp performans doğruluğu ölçülmüştür.

Python dili ile gerçekleştirdiğim proje basit bir nesne tanımlama projesidir.

# IMAGE CLASSIFICATION USING CIFAR10 DATASET WITH PYTHON [ENG]
## PURPOSE OF THE PROJECT

The aim is to perform object classification using the CNN network on the CIFAR10 dataset. Images of airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships and trucks were used in this dataset

First, the dimensions of the data were examined and the necessary data was converted to one-dimensional. Then, the data was normalized and prepared for training.

While designing the CNN model, 2 Conv2D and Maxpooling2D layers were used. Droput was used to prevent overfitting. In addition, the EarylStopping feature was used to prevent training from continuing when learning started to be repeated.

As a result of the training, 76% accuracy rate was achieved. Accuracy and loss values ​​were compared with validation values ​​and performance accuracy was measured.
The project I carried out with the Python language is a simple object definition project.
