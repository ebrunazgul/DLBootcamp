# DLBootcamp
Akbank Derin Öğrenme Kampı

Derin Öğrenme Görüntü Sınıflandırma Projesi

Bu proje, büyük bir görüntü veri seti kullanarak derin öğrenme modeli geliştirmeyi amaçlamaktadır. Hedef, görüntüleri doğru bir şekilde sınıflandırabilen bir model oluşturmak ve model performansını izlemek için veri ön işleme, model optimizasyonu ve değerlendirme tekniklerinden faydalanmaktır.

Ana Adımlar:
Veri Yükleme ve Ön İşleme:

Veri setinden görüntüler yüklendi ve işlendi.
Belirli dosya türleri (örneğin .png dosyaları) filtrelendi ve 'GT' gibi bazı dizinler hariç tutuldu.
Model Eğitimi:

Model, veri seti üzerinde eğitim alarak sınıflandırmayı öğrendi.
Modelin optimizasyonu için öğrenme hızı, katman sayısı, düğüm sayısı ve kayıp fonksiyonu gibi hiperparametreler ayarlandı.
Kayıp Grafiğinin İzlenmesi:

Eğitim sırasında kayıp değerleri izlendi ve eğitim sürecindeki hataları minimize etmek için grafikler kullanıldı.
Aşırı uyum (overfitting) ve yetersiz uyum (underfitting) durumlarını önlemek amacıyla veri normalizasyonu ve düzenli öğrenme teknikleri uygulandı.
Model Performansının Değerlendirilmesi:

Modelin doğruluk, kayıp fonksiyonu, karmaşıklık matrisi gibi metriklerle performansı değerlendirildi.
Eğitim ve doğrulama kayıplarının zaman içindeki değişimi görselleştirildi.
Bu proje, görüntü sınıflandırma problemlerine yönelik derin öğrenme modellerinin nasıl inşa edildiği ve optimize edildiği konusunda önemli adımlar sunmaktadır.

Bu proje Dilruba Aydın ile birlikte hazırlanmıştır.
