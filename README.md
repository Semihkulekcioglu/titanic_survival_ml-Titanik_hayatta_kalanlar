# 🚢 Titanic Hayatta Kalma Tahmini | Titanic Survival Prediction

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-green.svg)](https://scikit-learn.org/)

**🇹🇷 Türkçe | [🇬🇧 English](README_EN.md)**

---

## 📋 Proje Hakkında

Bu proje, 1912 yılında batan RMS Titanic gemisindeki yolcuların hayatta kalma durumunu **Logistic Regression** ve **K-Nearest Neighbors (kNN)** algoritmaları ile tahmin etmektedir.

<img width="416" height="416" alt="D" src="https://github.com/user-attachments/assets/d74bf9cc-21a4-4d0a-91bc-101eb9122e18" />

### Öğrenilen Konular

- ✅ Veri Gözden Geçirme & Train-Test Split
- ✅ Outlier (Aykırı Değer) Tespiti ve Eleme
- ✅ Feature Scaling (Özellik Ölçekleme)
- ✅ Logistic Regression Sınıflandırma
- ✅ kNN Sınıflandırma
- ✅ Model Karşılaştırma ve Değerlendirme

## 🛠 Kullanılan Teknolojiler

- Python, NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## 🚀 Kurulum

```bash
# Repoyu klonla
git clone https://github.com/Semihkulekcioglu/titanic_survival_ml-Titanik_hayatta_kalanlar.git
cd titanic_survival_ml-Titanik_hayatta_kalanlar

# Bağımlılıkları yükle
pip install -r requirements.txt

# Notebook'u çalıştır
jupyter notebook Titanic_Hayatta_Kalma_Tahmini.ipynb
```

## 📊 Sonuçlar

| Model | Accuracy |
|-------|----------|
| Logistic Regression | ~80% |
| kNN | ~78% |

### Temel Bulgular

- **Cinsiyet** en önemli faktör (Kadınların hayatta kalma oranı daha yüksek)
- **Bilet sınıfı** belirleyici (1. sınıf > 3. sınıf)
- **Yaş** etkili (Çocuklar ve gençler daha yüksek şans)

---

## 📝 License

MIT License - See [LICENSE](LICENSE) for details.

---

<div align="center">

⭐ **Star this repo if you found it helpful!** ⭐

</div>
