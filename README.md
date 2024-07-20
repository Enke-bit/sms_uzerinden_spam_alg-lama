# SMS Spam Algılama Projesi
Bu proje, kısa mesajların (SMS) spam olup olmadığını sınıflandırmak için bir makine öğrenimi modelinin nasıl geliştirileceğini ve değerlendirileceğini göstermektedir. Projede, Naive Bayes algoritması kullanılarak spam ve non-spam SMS'lerini ayırt eden bir model oluşturulmuştur.

## Proje Özeti
Bu projede, SMS'lerin spam olup olmadığını belirlemek için MultinomialNB (Naive Bayes) sınıflandırıcı modeli kullanılmıştır. Modelin performansı, doğruluk ve sınıflandırma raporu gibi metriklerle değerlendirilmiştir.

## Kullanılan Veri Seti
Proje için kullanılan veri seti spam.csv dosyasından alınmıştır. Veri seti, iki ana sütundan oluşmaktadır:

- label: SMS'nin spam (1) veya non-spam (0) olduğunu belirten etiket.
- message: SMS içeriği.
# Proje Adımları
## Veri Yükleme ve Ön İşleme:

- Veri seti CSV formatında yüklenmiştir.
- Veriler, Naive Bayes modeline uygun şekilde işlenmiştir.
- Metin verisi sayısal özelliklere dönüştürülmüştür (TF-IDF kullanılarak).
## Model Eğitim ve Test:

- Eğitim ve test setlerine veri bölünmüştür.
- Naive Bayes sınıflandırıcı modeli eğitilmiştir.
- Test verisi üzerinde tahminlerde bulunulmuştur.
## Performans Değerlendirmesi:

- Modelin doğruluğu hesaplanmıştır.
- Sınıflandırma raporu oluşturulmuş ve görselleştirilmiştir.
   # Kullanım
Aşağıdaki adımları takip ederek projeyi çalıştırabilirsiniz:

## Gereksinimler:

- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- NLTK

  ## Sonuçlar
- Modelin doğruluk oranı ve diğer performans metrikleri görselleştirilmiştir.
- Spam ve non-spam SMS'lerinin doğru bir şekilde sınıflandırılması sağlanmıştır.
## Katkıda Bulunanlar
İbrahim Püsküllü - Proje geliştirici
## Lisans
Bu proje MIT Lisansı altında lisanslanmıştır.

