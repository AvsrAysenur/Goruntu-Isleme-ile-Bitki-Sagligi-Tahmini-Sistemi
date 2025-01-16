# Goruntu-Isleme-ile-Bitki-Sagligi-Tahmini-Sistemi

Bu proje, derin öğrenme tabanlı bir Konvolüsyonel Sinir Ağı (CNN) kullanarak bitki hastalıklarını tespit etmeyi amaçlamaktadır. RGB görüntüleri analiz ederek bitkileri 38 farklı hastalık sınıfına ayırır. Proje, TensorFlow ve Keras kütüphanelerini kullanarak model oluşturma, eğitim ve değerlendirme süreçlerini içerir.

Proje Hakkında
Bitki Hastalığı Tespit Sistemi, çiftçilere ve tarım uzmanlarına hastalık teşhisinde yardımcı olmayı amaçlayan bir uygulamadır. Bu sistem, hastalık teşhis sürecini kolaylaştırır ve ürün kaybını önlemek için önleyici tedbirler alınmasını sağlar.

Veriseti
Kaynak: PlantVillage Veriseti
Boyut: 87.000 RGB görüntü
Sınıflar: 38 farklı bitki hastalığı kategorisi
Görüntü Çözünürlüğü: 128x128 piksel
veriseti linki:https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset

<img width="187" alt="Ekran görüntüsü 2024-12-26 175419" src="https://github.com/user-attachments/assets/f8d4b466-23e1-4c52-a121-7eb26e5f1e5b" />

Model Eğitimi

<img width="756" alt="Ekran görüntüsü 2024-12-26 211529" src="https://github.com/user-attachments/assets/3bb3e254-25fe-4a91-b3f3-ab61e78857d1" />

<img width="438" alt="Ekran görüntüsü 2025-01-15 005454" src="https://github.com/user-attachments/assets/981dfa74-1c67-4632-808e-f2afe4db72b9" />



![image](https://github.com/user-attachments/assets/6284850e-6003-4da6-9240-714cb585438a)

Sonuçların Değerlendirilmesi
Eğitim ve doğrulama setleri üzerinden modelin performansı ölçülmüştür:
Eğitim doğruluğu: %99.07
Doğrulama doğruluğu: %96.87
Performans değerlendirmesi için karışıklık matrisi, hassasiyet (precision), geri çağırma (recall) ve F1 skoru gibi metrikler kullanılmıştır.


![image](https://github.com/user-attachments/assets/fde9344f-3b6b-4cb4-8ce4-ae4d50ac0295)

![image](https://github.com/user-attachments/assets/16959d5e-8e1c-49cf-a419-90a243c5ab50)

TEST SONUÇLARIM

<img width="395" alt="image" src="https://github.com/user-attachments/assets/397b8337-b5f8-4284-87cb-d36ce57a5b7b" />
<img width="368" alt="image" src="https://github.com/user-attachments/assets/62a9b6f3-0390-44be-aa07-d24feba6dea2" />






