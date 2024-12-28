# Film_Classification_Project

# Film Fragmanı Sınıflandırma Projesi (18+)

Bu proje, bir filmin fragmanını değerlendirerek, içeriğinin 18 yaş üstü izleyiciler için uygun olup olmadığını sınıflandırmayı amaçlamaktadır. Makine öğrenmesi teknikleri kullanılarak, bir fragmanın görsel unsurları analiz edilip, sınıflandırma yapılacaktır.

## Proje Hakkında

Filmlerin fragmanları, genellikle film hakkında bilgi veren önemli unsurlardır. Ancak, fragmanlar bazen içerik açısından şiddet, küfürlü dil, cinsel içerik ve diğer olumsuz temalar içerebilir. Bu proje, film fragmanlarından elde edilen verileri kullanarak, fragmanların 18 yaş ve üzeri izleyiciler için uygun olup olmadığını sınıflandırmayı amaçlamaktadır.

### Amaç

- **Veri Toplama ve Hazırlık**: Film fragmanlarının verilerini toplamak ve uygun formatta işlemek.
- **Özellik Çıkartma**: Görsel verileri analiz ederek özellikler çıkartmak.
- **Model Eğitimi**: Bu verilerle makine öğrenmesi modelleri eğitmek ve sınıflandırma yapmak.
- **Sonuçları Yorumlama**: Modelin performansını değerlendirip sonuçları analiz etmek.

## Kullanılan Teknolojiler

- **Python**: Programlama dili olarak kullanılmıştır.
- **Scikit-learn**: Makine öğrenmesi modellerinin eğitimi için kullanılmıştır.
- **TensorFlow / Keras**: Derin öğrenme modelleri için kullanılmıştır.
- **OpenCV**: Görsel verilerin işlenmesi için kullanılmıştır.
- **pandas ve numpy**: Veri işleme ve manipülasyon için kullanılmıştır.

## Veri Kümesi

Proje, çeşitli film fragmanlarından elde edilen veri kümesi üzerinde çalışmaktadır. Veriler, video dosyaları, ses dosyaları, altyazılar ve açıklamalar gibi farklı formatlarda mevcuttur.

- **Video Verisi**: Fragmanlardan alınan görsel unsurların analiz edilmesi için kullanılır.


Veri kümesi, kamuya açık kaynaklardan veya film dağıtımcılarından alınabilir ve etiketlenmiş fragmanlardan oluşur.

## Kullanım

1. **Proje Kurulumu**:
   - Python 3.9 veya daha yeni bir sürümünün kurulu olması gerekir.
   - Gerekli kütüphanelerin yüklenmesi için aşağıdaki komutu kullanabilirsiniz:

   ```bash
   pip install -r requirements.txt
   ```

2. **Veri Seti Yükleme**:
   - Veri kümesini [bu bağlantıdan](#) indirebilirsiniz.

3. **Modeli Eğitme**:
   - Modeli eğitmek için aşağıdaki komutları çalıştırabilirsiniz:

   ```bash
   python train_model.py
   ```

4. **Modeli Test Etme**:
   - Eğitilen modeli test etmek için aşağıdaki komutu kullanabilirsiniz:

   ```bash
   python test_model.py
   ```

5. **Sonuçları Görüntüleme**:
   - Modelin tahmin sonuçlarını görüntülemek için:

   ```bash
   python results.py
   ```

## Model Yapısı

Projede kullanılan makine öğrenmesi modelinin yapısı aşağıdaki gibidir:

- **Model**: Model, bir dizi özellik ile eğitilir. Bu özellikler, fragmanın içeriği hakkında kararlar almak için kullanılır.
  - Görsel analiz için **Konvolüsyonel Sinir Ağları (CNN)** kullanılır.

## Sonuçlar



## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, lütfen bir pull request gönderin veya mevcut açık sorunları çözün. Katkılarınız için teşekkür ederiz!

## Lisans

Bu proje, MIT Lisansı altında lisanslanmıştır.

---

Bu README dosyasının içeriği, projeyi açıkça tanımlayacak, nasıl kurulup çalıştırılacağına dair bilgiler verecek ve hangi teknolojilerin kullanıldığını detaylandıracaktır.
