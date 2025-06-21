# 🛒 Market Price Prediction - YZTA Datathon 2025

## English

This project was developed as part of the **Google AI & Technology Academy (YZTA) Datathon 2025** competition. The objective of the task is to **predict market product prices** based on temporal and categorical features using machine learning models. The evaluation metric used is **Root Mean Square Error (RMSE)**.

### 🔍 Problem Description
The dataset contains daily product prices, and we aim to predict the price of various items using historical data. The target variable is the `price`.

### 📁 Dataset
- `train.csv`: Contains historical product prices and associated features.
- `testFeatures.csv`: Features used for predicting prices in the test set.

### 🧠 Models Used
- Decision Tree Regressor
- Random Forest Regressor
- MLP Regressor (Neural Network)
- LightGBM Regressor

### ⚙️ Features Engineered
- Date decomposition: `year`, `month`, `day`, `day_of_week`
- Encoding categorical variables (Label Encoding)
- Scaling numerical data (Standard Scaler)

### 📊 Evaluation Metric
- **RMSE (Root Mean Square Error)**
- `r2_score` also used for comparison purposes.

### 📦 Libraries Used
- `pandas`, `numpy`
- `scikit-learn`
- `lightgbm`
- `matplotlib`, `seaborn` 

---

## Türkçe

Bu proje, **Google Yapay Zeka ve Teknoloji Akademisi (YZTA) 2025 Datathonu** kapsamında geliştirilmiştir. Amacımız, tarihsel ve kategorik verilere dayanarak **market ürün fiyatlarını tahmin etmektir**. Kullanılan değerlendirme metriği **RMSE (Root Mean Square Error)**’dir.

### 🔍 Problem Tanımı
Veri setinde günlük ürün fiyatları bulunmaktadır. Hedef, geçmiş verilere dayanarak belirli ürünlerin fiyatlarını tahmin etmektir. Hedef değişken `price` sütunudur.

### 📁 Veri Seti
- `train.csv`: Geçmiş ürün fiyatları ve açıklayıcı değişkenler.
- `testFeatures.csv`: Test kümesinde kullanılacak özellikler.

### 🧠 Kullanılan Modeller
- Decision Tree Regressor
- Random Forest Regressor
- MLP Regressor (Yapay Sinir Ağı)
- LightGBM Regressor

### ⚙️ Özellik Mühendisliği
- Tarih parçalama: `yıl`, `ay`, `gün`, `haftanın günü`
- Kategorik verilerin kodlanması (Label Encoding)
- Sayısal verilerin ölçeklenmesi (Standard Scaler)

### 📊 Değerlendirme Metrikleri
- **RMSE (Karekök Ortalama Hata)**
- `r2_score` karşılaştırma amacıyla da kullanıldı.

### 📦 Kullanılan Kütüphaneler
- `pandas`, `numpy`
- `scikit-learn`
- `lightgbm`
- `matplotlib`, `seaborn` 
