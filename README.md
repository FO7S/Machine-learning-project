# 🧠 Machine Learning Project  
# 🦠 Predict the Age of a Trilobite Fossil  

<p align="center">
  <img src="images/trilobites.jpg" width="850">
</p>

<p align="center">
  <b>Using Machine Learning to Decode Earth's Ancient Life 🌍</b>
</p>

---

## 🚀 Overview

This project explores how machine learning can be applied to paleontological data to understand and predict the geological age of trilobite fossils.

By analyzing biological, environmental, and geological features, we build models capable of classifying fossils into their correct **geological time periods**.

---

## 🐚 What Were Trilobites?

Trilobites were ancient marine arthropods that lived hundreds of millions of years ago.

- 🕰 **First Appearance:** ~521 million years ago (Cambrian)  
- 💀 **Extinction:** ~251 million years ago (Permian extinction)  
- 🌊 **Habitat:** Marine environments  
- 🍽 **Diet:** Predators, scavengers, filter feeders  

---

## 🔬 Fossil Formation

Trilobites are known today through fossils formed via:

- 🟤 Compression  
- 🟡 Mineral Replacement  
- ⚫ Mold & Cast  

These fossils preserve key biological and environmental information.

---

## 📊 Dataset Overview

- 📁 **Total Records:** 29,039  
- 🌍 **Global Coverage:** Multiple countries and geological formations  
- 🧬 **Rich Features:** Taxonomy, environment, geology, and location  

### 🔑 Key Features:

| Category | Examples |
|--------|--------|
| 🧬 Taxonomy | order, family, genus |
| 🌍 Geography | country, latitude, longitude |
| 🌊 Ecology | environment, diet, vision |
| 🪨 Geology | lithology, formation |
| ⏳ Time | time_period (target) |

---

## 🎯 Project Tasks

We applied multiple ML tasks:

- 🌍 Country Classification  
- ⏳ **Time Period Classification (Main Focus)**  
- 🌊 Environment Clustering  
- 📈 Age Prediction (Regression)  

---

## 🤖 Machine Learning Models

For **Time Period Classification**:

| Model | Type | Purpose |
|------|------|--------|
| 🌳 Decision Tree | Baseline | Fast & interpretable |
| 🌲 Random Forest | Advanced | Higher accuracy & stability |

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| 🌳 Decision Tree | 97.7% |
| 🌲 Random Forest | 98.4% |

✔ Random Forest outperformed the baseline by reducing overfitting and capturing complex patterns.

---

## 🧠 Key Insights

- Trilobite biological features strongly correlate with geological time periods  
- Environmental and geological conditions help determine fossil age  
- Removing time-related features prevented data leakage and improved model reliability  
- Class imbalance affected minority classes such as Permian  

---

## ⚠️ Data Challenges

- 📉 Imbalanced classes (e.g., Permian has fewer samples)  
- 🔍 Potential data leakage from geological features  
- 🧩 High-dimensional data after encoding  

---

## 🏁 Conclusion

This project demonstrates how machine learning can uncover hidden patterns in ancient fossil data and contribute to understanding Earth's evolutionary history.

---

## 💡 Future Work

- Improve performance using feature selection  
- Handle class imbalance using resampling techniques  
- Build interactive dashboard (Streamlit)  
- Deploy model for real-world predictions  

---

## ⭐ Project Highlights

✔ Clean Data Preprocessing  
✔ Data Leakage Handling  
✔ Model Comparison  
✔ Real-world scientific dataset  

---

<p align="center">
  💙 Built with passion for AI & Data Science
</p>
## 🚀 Project Objectives

This project applies both supervised and unsupervised machine learning techniques to analyze trilobite fossil data and extract meaningful insights:

- **Country Classification** 
- **Time Period Classification** 
- **Environment Clustering** 
- **Age Prediction (Regression)**

## Dataset: 
https://www.kaggle.com/datasets/kayleefranklin/predict-the-age-of-a-trilobite
