# 📊 Veri Analizi Projeleri

Bu repoda iki farklı veri analizi projesi bulunmaktadır:

1. **UK Trafik Kazaları Analizi (2000–2016)**
2. **COVID-19 Bilimsel Literatür Analizi (CORD-19)**

Her iki proje, veri ön işleme, keşifsel veri analizi (EDA), görselleştirme ve tahminleme tekniklerini kapsamaktadır.

---

## 🚗 1. Trafik Kazaları Analizi – UK (2000–2016)

### 🔍 Amaç:
2000–2016 yılları arasında İngiltere, İskoçya ve Galler’de gerçekleşen 1.6 milyonun üzerinde trafik kazasının analiz edilmesi. Ana sorular:

- Trafik akışı değişimi kazaları nasıl etkiler?
- Kaza oranlarını hangi faktörler artırır?
- Zaman içinde kaza oranları tahmin edilebilir mi?
- Kırsal ve kentsel bölgeler arasında nasıl farklar vardır?

### 📁 Kullanılan Veri Seti:
[Kaggle - 2000-16 Traffic Flow Dataset](https://www.kaggle.com/datasets/daveianhickey/2000-16-traffic-flow-england-scotland-wales)

### 🧪 Yapılan Analizler:
- Eksik veri analizi ve temizlik
- Kazaya karışan araç sayısı, yaralı sayısı, kaza şiddeti incelemeleri
- Kentsel/kırsal alanlara göre karşılaştırmalar
- Zaman serisi ile Prophet kullanarak gelecek tahminleri

---

## 🦠 2. COVID-19 Literatür Analizi (CORD-19)

### 🔍 Amaç:
CORD-19 veri seti, COVID-19 ile ilgili 200.000’den fazla bilimsel yayını içermektedir. Bu proje, doğal dil işleme (NLP) teknikleriyle bilimsel literatürdeki eğilimleri keşfetmeyi amaçlar.

### 📁 Kullanılan Veri Seti:
[Kaggle - CORD-19 Research Challenge](https://www.kaggle.com/datasets/allen-institute-for-ai/CORD-19-research-challenge)

### 🧪 Yapılan Analizler:
- Veri ön işleme (abstract, title vb. sütunlar)
- Metin temizliği ve tokenizasyon
- Sık kullanılan kelimelerin analizi (wordcloud, frequency)
- Anahtar konuların çıkarımı (TF-IDF, topic modeling)

---

## 🛠 Kullanılan Teknolojiler

- Python (Pandas, Matplotlib, Seaborn, Prophet, NLTK, Scikit-learn)
- Google Colab
- Jupyter Notebook
- Kaggle API

---

