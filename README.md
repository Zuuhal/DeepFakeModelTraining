# Model Training & Architecture Repository

Bu repo, proje kapsamında kullanılan ses ve görsel modelleme süreçlerine ait eğitim kodlarını, model mimarilerini ve deney sonuçlarını barındırmaktadır.

## 📂 İçerik Yapısı

- **audioTraining/**: Ses verileri üzerinde gerçekleştirilen özellik çıkarma, gürültü temizleme ve işitsel model eğitim süreçlerini içeren veri ön işleme ve eğitim kodları.
- **visualModelTraining/**: Görsel veriler üzerinde uygulanan kare çıkarma, normalizasyon gibi ön işleme adımları ile hiperparametre optimizasyonlarını içeren eğitim scriptleri.
- **visualModelArch/**: Projede kullanılan model mimarilerinin (backbone yapıları) tanımlandığı, katman yapıları ve model konfigürasyon dosyalarının bulunduğu bölümdür.

## 🛠️ Teknik Notlar
- **Veri Ön İşleme:** Her bir eğitim klasörü, ham verinin model tarafından işlenebilir formata getirilmesi için özelleşmiş `preprocessing` adımlarını içermektedir.
- Eğitim süreçleri PyTorch framework'ü ile yönetilmektedir.
- Görsel modeller için kullanılan her bir eğitim bloğu `visualModelArch` altındaki mimari yapılarla bağlantılıdır.

---
*Not: Bu repo, DeepFake-Detection---Web-UI- projesinin model geliştirme aşaması için özel olarak oluşturulmuştur.*
