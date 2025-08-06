# akilli-musteri-analizi
Türkçe e-ticaret yorumları ile duygu analizi projesi
# Akıllı Müşteri Analizi: Türkçe E-Ticaret Yorumları için Duygu Sınıflandırma

## Proje Özeti

Bu proje, Türkçe e-ticaret mağazalarından alınan müşteri yorumlarını analiz ederek, yorumların **Olumlu** veya **Olumsuz** duygu taşıyıp taşımadığını otomatik olarak sınıflandıran bir yapay zeka modelini kapsamaktadır.

## Amaç

E-ticaret sitelerinde yer alan müşteri yorumları, işletmeler için altın değerindedir. Bu proje ile:
- Otomatik duygu analizi yapılabilir,
- Marka itibarı ölçülebilir,
- Müşteri memnuniyeti takip edilebilir,
- Potansiyel krizler erken tespit edilebilir.

## Kullanılan Yöntemler ve Teknolojiler

- **Programlama Dili**: Python
- **Kütüphaneler**: Pandas, Scikit-learn, Seaborn, Matplotlib, WordCloud
- **Veri Temizleme ve Görselleştirme**: Keşifsel Veri Analizi (EDA), kelime bulutları, yorum uzunluğu grafikleri
- **Vektörleştirme**: TF-IDF (Term Frequency-Inverse Document Frequency)
- **Modeller**: Logistic Regression, Naive Bayes, Random Forest

## Sonuçlar

En iyi sonuç, Logistic Regression modeli ile elde edilmiştir:

| Metik     | Olumlu | Olumsuz |
|-----------|--------|---------|
| Precision | %94    | %88     |
| Recall    | %87    | %94     |
| Accuracy  | **%90.4** |

## Veri Seti

Veri seti, Kaggle platformundan alınan `magaza_yorumlari.csv` dosyasından oluşmaktadır. Her satırda müşteri yorumu ve buna ait duygu etiketi (`Olumlu` / `Olumsuz`) yer almaktadır.

## Geliştirme Fırsatları

- Türkçe'ye özel BERT tabanlı modellerle doğruluğun artırılması
- Gelişmiş metin ön işleme yöntemlerinin uygulanması
- Kullanıcıların yorumlarını analiz edebileceği basit bir web uygulamasının geliştirilmesi (Streamlit ile)

## Proje Dosyası

Proje Jupyter Notebook (.ipynb) formatındadır. Tüm adımlar, kodlar ve grafiklerle birlikte belgelenmiştir.

> Bu proje, BTK Akademi, Google ve Girişimcilik Vakfı tarafından düzenlenen AI Hackathon yarışması için geliştirilmiştir.
