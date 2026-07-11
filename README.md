<h1 align="center">Regresyon Modeli Seçimi</h1>

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🔍 Projeye Bakış

Bu depo, **tek bir veri seti** (`Data.csv`) üzerinde farklı regresyon algoritmalarını uygulayarak en iyi tahmin performansını veren modeli bulmayı amaçlar.

- 🎯 Aynı veriyi birden fazla modelle eğit ve karşılaştır
- 📊 $R^2$ skorlarına göre en uygun modeli seç
- 🧩 Doğrusal ve doğrusal olmayan yaklaşımları yan yana değerlendir

---

## 🤖 Kullanılan Modeller

| # | Model | Dosya | Yapı |
|---|-------|-------|------|
| 1️⃣ | Çoklu Doğrusal Regresyon | `multiple_linear_regression.ipynb` | Doğrusal |
| 2️⃣ | Polinom Regresyon | `polynomial_regression.ipynb` | Doğrusal Olmayan |
| 3️⃣ | Destek Vektör Regresyonu (SVR) | `support_vector_regression.ipynb` | Doğrusal Olmayan |
| 4️⃣ | Karar Ağacı Regresyonu | `decision_tree_regression.ipynb` | Doğrusal Olmayan |
| 5️⃣ | Rastgele Orman Regresyonu | `random_forest_regression.ipynb` | Topluluk (Ensemble) |


---

## 🏆 Kazanımlar ve Sonuçlar

- ✅ **Model karşılaştırması:** Farklı algoritmaların aynı veri üzerindeki davranışını gözlemleme
- ✅ **Doğrusal olmayan veri:** Hangi modelin karmaşık ilişkileri daha iyi yakaladığını anlama
- ✅ **$R^2$ metriği:** Skorlar üzerinden en optimal modeli objektif olarak seçme
- ✅ **Aşırı öğrenme (overfitting):** Karar Ağacı ve Rastgele Orman arasındaki denge farkını kavrama

---

## 🚀 Nasıl Kullanılır

```bash
# 1. Depoyu klonlayın
git clone <repo-url>

# 2. Gerekli kütüphaneleri kurun
pip install numpy pandas matplotlib scikit-learn
```

---

<p align="center">⭐ Faydalı bulduysanız yıldız vermeyi unutmayın!</p>
