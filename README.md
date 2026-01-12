# Sport_Data_Analysis


⚽ Spor Veri Analizi ve Maç Sonucu Tahmini
Bu proje, Veri Analizi dersi kapsamında; ham veri setinin işlenmesi, gelişmiş normalizasyon tekniklerinin uygulanması ve Makine Öğrenmesi modelleri (Random Forest & Decision Tree) ile maç sonuçlarının tahmin edilmesini içermektedir.

📝 Proje Özeti
Proje, futbol takımlarının güç puanları (Elo) ve form durumlarını baz alarak, bir maçın sonucunu (Ev Sahibi, Beraberlik, Deplasman) tahmin etmeye odaklanır. 500 satırlık sentetik bir veri seti üzerinde çalışılmıştır.

🛠️ Uygulanan Veri Ön İşleme Teknikleri
Modelin başarısını artırmak için aşağıdaki 13 farklı ölçeklendirme ve dönüşüm tekniği uygulanmıştır:

Normalizasyon & Ölçeklendirme:

Max Normalization (Max Scaling)

Min-Max Normalization

Mean Normalization

Z-Score Normalization (Standardization)

Robust Scaling

Norm Ölçeklendirmeleri:

L1, L2 ve L∞ (L-sonsuz) Norm Ölçeklendirme

Dönüşümler (Transformations):

Log Dönüşümü

Güç Dönüşümleri (Box-Cox & Yeo-Johnson)

Quantile Transformation (Uniform & Gaussian)

🤖 Kullanılan Modeller ve Başarım
Projede iki farklı algoritma karşılaştırmalı olarak kullanılmıştır:

Karar Ağacı (Decision Tree): Verinin mantıksal kırılımlarını belirlemek için kullanıldı.

Random Forest: Topluluk öğrenmesi (Ensemble Learning) yöntemiyle daha yüksek doğruluk oranı elde edildi.

Model Sonuçları:

Random Forest Accuracy: %86 (Kendi sonucunu buraya yaz)

Decision Tree Accuracy: %72 (Kendi sonucunu buraya yaz)