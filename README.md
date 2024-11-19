# Digit Classification with SVM


This project focuses on classifying handwritten digits using Support Vector Machines (SVM). The dataset used consists of 8x8 pixel grayscale images of digits, which are flattened into feature vectors for model input. The goal is to achieve high accuracy in classifying the digits, using SVM with hyperparameter optimization via `GridSearchCV`. The model's performance is evaluated using accuracy, confusion matrix, and classification report.

### Key Features:
- Data preprocessing including resizing and flattening images.
- Hyperparameter optimization using `GridSearchCV`.
- Model evaluation with accuracy, confusion matrix, and classification report.
- Achieved a test accuracy of 98.12%.

### Requirements:
- Python 3.x
- `scikit-learn`
- `Pillow`
- `matplotlib`
- `seaborn`

---

Bu proje, el yazısı rakamlarının sınıflandırılmasına yönelik olarak Destek Vektör Makineleri (SVM) kullanmaktadır. Kullanılan veri kümesi, 8x8 piksel boyutlarında gri tonlamalı rakam görüntülerinden oluşmaktadır. Bu görüntüler, modelin giriş verisi olarak kullanılmak üzere özellik vektörlerine dönüştürülmüştür. Proje, SVM ile yüksek doğruluk elde etmeyi hedeflemekte olup, hiperparametre optimizasyonu için `GridSearchCV` kullanılmaktadır. Modelin performansı doğruluk, karmaşıklık matrisi ve sınıflandırma raporu ile değerlendirilmiştir.

### Ana Özellikler:
- Görüntü verisinin ön işlenmesi (yeniden boyutlandırma ve düzleştirme).
- `GridSearchCV` kullanılarak hiperparametre optimizasyonu.
- Doğruluk, karmaşıklık matrisi ve sınıflandırma raporu ile model değerlendirmesi.
- %98,12 test doğruluğu elde edilmiştir.

### Gereksinimler:
- Python 3.x
- `scikit-learn`
- `Pillow`
- `matplotlib`
- `seaborn`
