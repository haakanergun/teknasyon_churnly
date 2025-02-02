# Müşteri Churn Tahmini (Basit Readme)

Bu proje, bir telekomünikasyon veri seti üzerinde **müşteri churn (müşteri kaybı)** durumunu tahmin etmeyi amaçlar.  
Veri seti, müşteri hesap geçmişi, kullanım verileri ve çeşitli etkileşim metriklerini içerir.

## Adımlar

1. **EDA (Exploratory Data Analysis)**  
   - Veri setinin genel incelemesi  
   - Eksik değer ve uç değer (outlier) tespiti  
   - Dağılım grafiklerinin ve korelasyonların incelenmesi  

2. **Özellik Mühendisliği**  
   - Log dönüşümleri (çarpık dağılımlar için)  
   - Yeni özelliklerin üretilmesi (ör. `spending_per_day`, `call_to_sms_ratio`)  

3. **Modelleme**  
   - Veri setinin eğitim ve test olarak ayrılması  
   - LightGBM, Random Forest, vb. gibi sınıflandırma modellerinin eğitimi  
   - Model performansını ölçmek için Accuracy, Recall, Precision, F1-Score, ROC-AUC gibi metrikler  

4. **Değerlendirme**  
   - Modelin tahmin doğruluğunu ve sınıf ayrımını değerlendirmek  
   - Özellik önem analizleri (ör. SHAP)  

## Kullanılan Teknolojiler
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- PyCaret (otomatik makine öğrenmesi)  

## Katkıda Bulunma
- Fork’ladıktan sonra kendi branch’inizde değişiklik yapabilir, ardından pull request gönderebilirsiniz.  

## Lisans
Bu proje, özel çalışma amaçlıdır ve ticari kullanım için uygun olmayabilir.
