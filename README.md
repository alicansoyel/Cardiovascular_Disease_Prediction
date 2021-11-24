# Cardiovascular Disease Prediction(Kardiyovasküler Hastalık Tahmini) Uygulaması

Bu proje, gerçek insanların verilerinden oluşan bir veri setinin, makine öğrenmesi yöntemleri kullanılarak kişinin hastalık tahminine olanak tanımaktadır.

>**Proje Klasör İçeriği**

-Proje, makine öğrenmesi yöntemleri kullanılarak kodlanmıştır. Projenin makine öğrenmesi ile gerçekleştirilen işlemleri 'Cardiovascular_Disease_Prediction.ipynb' içerisinde bulunmaktadır

-Projede kullanılan veri seti 'cardio_diease.csv' adıyla mevcuttur. Veri seti [kaggle](https://www.kaggle.com/) platformu üzerinden indirilmiştir. Makine öğrenmesi kısmında verinin hazırlanması işlemleri sonucunda elde edilen yeni veri seti ise 'new_cardio_disease_dataset.csv' formatında kaydedilmiştir.

-Eğitim ve test sonucunda en iyi sonucu veren makine öğrenmesi algoritması olarak 'GradientBoostingClassifier' seçilmiştir. Bu algoritmanın daha sonrasında test edilebilmesi adına 'model' klasörünün içerisine 'gbc_model.pkl' adıyla kaydedilmiştir.

-Kaydedilen model, proje içerisine yüklenerek rastgele verilerle 2 farklı liste kullanılarak test edilmiştir.
