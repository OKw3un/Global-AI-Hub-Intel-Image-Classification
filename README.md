# Intel Image Classification with CNN

Bu repo, Global AI Hub bootcamplerinde template olarak kullanmanız amacıyla tasarlanmıştır. Bu proje kapsamında Intel Image Classification veri seti kullanılarak bir Convolutional Neural Network (CNN) modeli eğitilmiş ve test edilmiştir.

---

## Giriş

Bu projede, Intel Image Classification veri seti kullanılmıştır. Veri seti 6 sınıftan oluşmaktadır: **buildings, forest, glacier, mountain, sea, street**.  
Proje kapsamında aşağıdaki adımlar gerçekleştirilmiştir:

- Eğitim, doğrulama ve test veri setlerinin ön işlenmesi (normalizasyon, veri artırma)  
- 3 katmanlı CNN modeli oluşturulması  
- Modelin eğitim süreci ve doğruluk/ loss grafikleri  
- Test seti üzerinde modelin performans değerlendirilmesi  
- Confusion matrix ve classification report ile sonuçların detaylı analizi  
- Grad-CAM ile görsel açıklama yapılması (modelin hangi bölgelere dikkat ettiğinin görselleştirilmesi)

Teknik anlatım notebook içerisinde markdown hücreleriyle detaylandırılmıştır.

---

## Metrikler

Eğitim süreci 20 epoch boyunca yapılmıştır. Elde edilen sonuçlar:

- **Test Accuracy:** Yaklaşık olarak 0.80 (örnek)  
- **Accuracy & Loss Grafikleri:** Eğitim ve doğrulama setlerinde modelin performansı görselleştirilmiştir.  

Confusion matrix ve classification report sayesinde, modelin hangi sınıfları daha iyi veya kötü tahmin ettiğini görebilmekteyiz.  

Grad-CAM görselleştirmesi ile modelin karar verirken hangi bölgeleri kullandığı analiz edilmiştir.

---

## Ekler

Proje kapsamında ek olarak:

- **Grad-CAM** görselleştirmesi uygulanmıştır. Bu sayede modelin hangi görüntü bölgelerine odaklandığı anlaşılabilmektedir.  
- Notebook içerisinde eğitim, doğrulama, test ve görselleştirme adımları ayrı hücrelerde açıklanmıştır.

---

## Sonuç ve Gelecek Çalışmalar

Bu çalışmada, Intel Image Classification veri seti üzerinde başarılı bir CNN modeli geliştirilmiştir.  

Gelecekte yapılabilecek geliştirmeler:

- Daha derin veya farklı mimariler (ResNet, EfficientNet vb.) kullanarak doğruluk artırılabilir.  
- Daha fazla veri artırma ve regularization teknikleri eklenebilir.  
- Model bir web arayüzü üzerinden deploy edilerek gerçek zamanlı tahmin yapılabilir.  

---

## Linkler

- [Kaggle Veri Seti](https://www.kaggle.com/datasets/puneet6060/intel-image-classification)
- Notebook Kaggle üzerinde mevcuttur ve tüm preprocessing, model training ve görselleştirme adımlarını içermektedir.
