# 🧠 Akbank Derin Öğrenme Bootcamp: Yeni Nesil Proje Kampı

## 🎯 Projenin Amacı
Bu projede, **CNN (Convolutional Neural Network)** mimarisi kullanılarak beyin MRI görüntülerinden **tümör sınıflandırması** yapılmaktadır.  
Proje, katılımcılara derin öğrenme alanında **görüntü sınıflandırması, veri analizi, model geliştirme, değerlendirme ve yorumlama** konularında pratik deneyim kazandırmayı hedefler.

---

## 📊 Veri Seti
Kullanılan veri seti toplamda **7023 MRI görüntüsünden** oluşmaktadır. Görüntüler dört sınıfa ayrılmıştır:

- **Glioma:** Glial hücrelerde oluşan kanserli tümörler  
- **Meningioma:** Meninkslerden kaynaklanan iyi huylu tümörler  
- **Pituitary:** Hipofiz bezini etkileyen tümörler  
- **No Tumor:** Tümör bulunmayan normal beyin görüntüleri  

Kaynak: *Kaggle - Brain Tumor MRI Dataset*

---

## 🔬 Kullanılan Yöntemler
- **Veri Önişleme & Data Augmentation**  
  - Yeniden ölçekleme, döndürme, kaydırma, yakınlaştırma, parlaklık değiştirme, yatay/dikey çevirme  
- **CNN Tabanlı Model**  
  - Birden fazla Conv2D + MaxPooling blokları  
  - Batch Normalization ve Dropout katmanları  
  - Global Average Pooling + Dense katmanlar  
- **Hiperparametre Optimizasyonu (Keras Tuner)**  
  - Filtre sayısı, kernel boyutu, dense katman büyüklüğü, dropout oranı, öğrenme oranı  
- **Eğitim Stratejileri**  
  - EarlyStopping  
  - ReduceLROnPlateau (öğrenme oranını otomatik azaltma)  
- **Değerlendirme**  
  - Accuracy / Loss eğrileri  
  - Confusion Matrix & Classification Report  
  - Grad-CAM görselleştirmesi ile modelin odaklandığı bölgeler  

---
# 🧠 Akbank Derin Öğrenme Bootcamp: Yeni Nesil Proje Kampı

## 🎯 Projenin Amacı
Bu projede, **CNN (Convolutional Neural Network)** mimarisi kullanılarak beyin MRI görüntülerinden **tümör sınıflandırması** yapılmaktadır.  
Proje, katılımcılara derin öğrenme alanında **görüntü sınıflandırması, veri analizi, model geliştirme, değerlendirme ve yorumlama** konularında pratik deneyim kazandırmayı hedefler.

---

## 📊 Veri Seti
Kullanılan veri seti toplamda **7023 MRI görüntüsünden** oluşmaktadır. Görüntüler dört sınıfa ayrılmıştır:

- **Glioma:** Glial hücrelerde oluşan kanserli tümörler  
- **Meningioma:** Meninkslerden kaynaklanan iyi huylu tümörler  
- **Pituitary:** Hipofiz bezini etkileyen tümörler  
- **No Tumor:** Tümör bulunmayan normal beyin görüntüleri  

Kaynak: *Kaggle - Brain Tumor MRI Dataset*

---

## 🔬 Kullanılan Yöntemler
- **Veri Önişleme & Data Augmentation**  
  - Yeniden ölçekleme, döndürme, kaydırma, yakınlaştırma, parlaklık değiştirme, yatay/dikey çevirme  
- **CNN Tabanlı Model**  
  - Birden fazla Conv2D + MaxPooling blokları  
  - Batch Normalization ve Dropout katmanları  
  - Global Average Pooling + Dense katmanlar  
- **Hiperparametre Optimizasyonu (Keras Tuner)**  
  - Filtre sayısı, kernel boyutu, dense katman büyüklüğü, dropout oranı, öğrenme oranı  
- **Eğitim Stratejileri**  
  - EarlyStopping  
  - ReduceLROnPlateau (öğrenme oranını otomatik azaltma)  
- **Değerlendirme**  
  - Accuracy / Loss eğrileri  
  - Confusion Matrix & Classification Report  
  - Grad-CAM görselleştirmesi ile modelin odaklandığı bölgeler
 
## Kaggle Notebook Linki:https://www.kaggle.com/code/melikedemirtas/akbank-derin-renme-bootcamp
