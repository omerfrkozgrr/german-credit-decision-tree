# German Credit Risk Classification with Decision Tree

## Proje Hakkında
Bu projede, Kaggle üzerinde yer alan Alman Kredi Veri Seti kullanılarak bireylerin
kredi risk durumları (İyi Kredi / Kötü Kredi) tahmin edilmiştir.
Problem, denetimli makine öğrenmesi kapsamında bir sınıflandırma problemi olarak ele alınmıştır.

## Kullanılan Veri Seti
- German Credit Dataset (Kaggle)

## Kullanılan Yöntem
- Decision Tree Classifier (Karar Ağaçları)

## Veri Ön İşleme
- Kategorik değişkenler One-Hot Encoding yöntemi ile dönüştürülmüştür
- Eğitim ve test verisi ayrımı yapılmıştır

## Model Değerlendirme
Model performansı aşağıdaki metrikler ile değerlendirilmiştir:
- Accuracy
- Confusion Matrix
- Precision, Recall, F1-score

## Sonuç
Kurulan karar ağacı modeli kredi risk tahmininde orta seviyede başarı sağlamış
ve yorumlanabilir yapısı sayesinde karar destek sistemleri için uygun bir çözüm sunmuştur.

## Kullanılan Kütüphaneler
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
