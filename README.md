# Predict the Age of a Trilobite Fossil  (Machine Learning Project)

<p align="center">
  <img src="images/trilobites.jpg" width="850">
</p>

<p align="center">
  <b>Using Machine Learning to Decode Earth's Ancient Life 🌍</b>
</p>

---

## 🚀 Overview

This project explores how machine learning can be applied to paleontological data to analyze trilobite fossils and uncover patterns related to their age, distribution, and environment.

We built multiple models to solve different real-world tasks using the same dataset.

---

## 🐚 What Were Trilobites?

Trilobites were ancient marine arthropods that lived hundreds of millions of years ago.

- 🕰 **First Appearance:** ~521 million years ago (Cambrian)  
- 💀 **Extinction:** ~251 million years ago (Permian extinction)  
- 🌊 **Habitat:** Marine environments  
- 🍽 **Diet:** Predators, scavengers, filter feeders  

---

## 📊 Dataset Overview

- 📁 **Total Records:** 29,039  
-  **Global Coverage:** Multiple countries and geological formations  

### 🔑 Key Features:

| Category | Examples |
|--------|--------|
|  Taxonomy | order, family, genus |
|  Geography | country, latitude, longitude |
|  Ecology | environment, diet, vision |
|  Geology | lithology, formation |
|  Time | time_period |

---

#  Machine Learning Tasks

We implemented four different machine learning models:

---

## ⏳ 1. Time Period Classification (Main Task)

**Goal:**  
Classify fossils into their correct geological time period (e.g., Cambrian, Ordovician).

**Models Used:**
- 🌳 Decision Tree (Baseline)
- 🌲 Random Forest (Advanced)

**Results:**
- Decision Tree: **97.7%**
- Random Forest: **98.4%**

---

## 🌍 2. Country Prediction

**Goal:**  
Predict the country where the fossil was found based on its characteristics.

**Approach:**
- Supervised classification using features like taxonomy and environment

**Insight:**
- Fossil distribution is influenced by geological and environmental conditions

---

## 📈 3. Age Prediction (Regression)

**Goal:**  
Predict the numerical age of the fossil (in millions of years).

**Approach:**
- Regression models using geological and environmental features

**Output:**
- Continuous value (e.g., 450 MYA)

---

## 🌊 4. Clustering (Unsupervised Learning)

**Goal:**  
Group trilobites into clusters based on similarity.

**Approach:**
- K-Means clustering

**Insight:**
- Identifies natural groupings based on ecological and biological traits

---

## 📈 Key Insights

- Biological features strongly correlate with geological time periods  
- Environmental factors help explain fossil distribution  
- Removing time-related features prevented data leakage  
- Dataset contains class imbalance (e.g., fewer Permian samples)  

---

## ⚠️ Challenges

-  Imbalanced dataset  
-  Potential data leakage   

---

##  Conclusion

This project demonstrates how machine learning can be used to analyze fossil data and reveal patterns about ancient life on Earth.

---

##  Future Work

- Improve models using feature selection  
- Handle class imbalance  
- Build interactive dashboard  
- Deploy models  

---

## ⭐ Project Highlights

✔ Multiple ML Tasks  
✔ Real Scientific Dataset  
✔ Data Cleaning & Leakage Handling  
✔ Model Comparison  

---

<p align="center">
  💙 Built with passion for AI & Data Science
</p>
## 🚀 Project Objectives


## Dataset: 
https://www.kaggle.com/datasets/kayleefranklin/predict-the-age-of-a-trilobite
