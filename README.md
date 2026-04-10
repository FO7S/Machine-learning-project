# 🧠 Machine Learning Project  
# 🦠 Predict the Age of a Trilobite Fossil  

<p align="center">
  <img src="images/trilobites.jpg" width="700">
</p>

This project explores the use of machine learning to estimate the geological age of trilobite fossils. By leveraging biological taxonomy, geographical information, and paleo-environmental features, we aim to build predictive models that classify fossils into their correct geological time periods.

---

## 🐚 What Were Trilobites?


::contentReference[oaicite:0]{index=0}


Trilobites were ancient marine arthropods, related to modern-day insects and crustaceans. They are among the earliest and most successful life forms in Earth's history.

- 🕰 **First Appearance:** ~521 million years ago (Cambrian Period)  
- 💀 **Extinction:** ~251 million years ago (End-Permian mass extinction)  
- 🌊 **Habitat:** Marine environments  
- 🍽 **Diet:** Predators, scavengers, and filter feeders  

---

## 🔍 Physical Structure

Trilobites had a unique segmented body divided into three main parts:

- 🧠 **Cephalon (Head):** Contains eyes and sensory organs  
- 🧩 **Thorax (Body):** Multiple flexible segments  
- 🔚 **Pygidium (Tail):** Rear part of the body  

---

## 🪨 What is a Trilobite Fossil?


::contentReference[oaicite:1]{index=1}


A trilobite fossil is the preserved remains or impression of a trilobite in rock.

### Common fossilization processes:
- 🟤 **Compression:** The organism is flattened in sediment  
- 🟡 **Mineral Replacement:** Original material replaced by minerals  
- ⚫ **Mold & Cast:** Shape preserved in surrounding rock  

These fossils help scientists understand ancient ecosystems and evolutionary changes.

---

## 📊 Dataset Overview

The dataset contains **29,039 fossil records** collected from different geological periods and global locations.

### 🔑 Key Feature Categories:

- 🧬 **Taxonomy:**  
  *order, family, genus, species*

- 🌍 **Geography:**  
  *country, state, latitude, longitude*

- 🪨 **Geology:**  
  *formation, lithology, stratigraphy_scale*

- 🌊 **Ecology & Biology:**  
  *environment, diet, vision, life_habit*

- ⏳ **Time Information:**  
  *time_period (target variable)*  

---

## 🚀 Project Objectives

We applied machine learning techniques to solve multiple tasks:

- 🌍 **Country Classification**  
- ⏳ **Time Period Classification**  
- 🌊 **Environment Clustering**  
- 📈 **Age Prediction (Regression)**  

---

## 🧠 Machine Learning Models

For the **Time Period Classification** task:

- 🌳 **Baseline Model:** Decision Tree  
- 🌲 **Advanced Model:** Random Forest  

📊 The Random Forest model achieved higher accuracy due to its ability to reduce overfitting and capture complex patterns.

---

## 📈 Key Insights

- Trilobite characteristics strongly relate to geological time periods  
- Biological features such as *order* and *family* are highly informative  
- Environmental and geological data help improve classification accuracy  
- Some features initially caused overly high accuracy and were removed to avoid data leakage  

---

## 🎯 Project Goal

The goal of this project is to:

> Understand how biological, environmental, and geological features influence fossil age and classification, and build accurate predictive models based on these relationships.

---

## 🏁 Conclusion

This project demonstrates how machine learning can be applied to paleontology data to uncover patterns in ancient life and improve our understanding of Earth's history.
## 🚀 Project Objectives

This project applies both supervised and unsupervised machine learning techniques to analyze trilobite fossil data and extract meaningful insights:

- **Country Classification** 
- **Time Period Classification** 
- **Environment Clustering** 
- **Age Prediction (Regression)**

## Dataset: 
https://www.kaggle.com/datasets/kayleefranklin/predict-the-age-of-a-trilobite
