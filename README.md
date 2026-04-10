# Predict the Age of a Trilobite Fossil (Machine Learning Project)

<p align="center">
  <img src="images/trilobites.jpg" width="850">
</p>

<p align="center">
  <b>Using Machine Learning to Decode Earth's Ancient Life</b>
</p>

---

## Overview

This project explores how machine learning can be applied to paleontological data to analyze trilobite fossils and uncover patterns related to their age, distribution, and environment.

Multiple models were developed to solve different tasks using the same dataset.

---

## What Were Trilobites?

Trilobites were ancient marine arthropods that lived hundreds of millions of years ago.

- First Appearance: ~521 million years ago (Cambrian)  
- Extinction: ~251 million years ago (Permian extinction)  
- Habitat: Marine environments  
- Diet: Predators, scavengers, filter feeders  

---

## Dataset Overview

- Total Records: 29,039  
- Global Coverage: Multiple countries and geological formations  

### Key Features:

| Category   | Examples                         |
|-----------|---------------------------------|
| Taxonomy  | order, family, genus            |
| Geography | country, latitude, longitude    |
| Ecology   | environment, diet, vision       |
| Geology   | lithology, formation            |
| Time      | time_period                     |

---

## Machine Learning Tasks

The project includes four main tasks:

### 1. Time Period Classification (Main Task)

**Goal:**  
Classify fossils into their correct geological time period (e.g., Cambrian, Ordovician).

**Models Used:**
- Decision Tree (Baseline)
- Random Forest (Advanced)

**Results:**
- Decision Tree: 97.7%  
- Random Forest: 98.4%  

---

### Model Comparison (Latest Update)

To better understand the impact of features, two versions of the model were built:

#### Model A (With Taxonomy Features)
Includes all features such as genus, family, and order.

- Decision Tree: 97.7%  
- Random Forest: 98.5%  

#### Model B (Without Taxonomy Features)
Removes genus, family, and order.

- Decision Tree: 96.5%  
- Random Forest: 97.4%  

**Insight:**
Taxonomic features significantly improve model performance. However, even without these features, the model still achieves strong accuracy, indicating that environmental and geographical features also contribute to prediction.

---

### 2. Country Prediction

**Goal:**  
Predict the country where the fossil was found.

**Approach:**  
Supervised classification using taxonomy and environmental features.

---

### 3. Age Prediction (Regression)

**Goal:**  
Predict the fossil age in millions of years.

**Approach:**  
Regression models using geological and environmental data.

---

### 4. Clustering

**Goal:**  
Group trilobites based on similarity.

**Approach:**  
K-Means clustering.

---

## Key Insights

- Biological features are strongly correlated with geological time periods  
- Environmental factors help explain fossil distribution  
- Removing time-related features prevented data leakage  
- The dataset contains class imbalance (e.g., fewer Permian samples)  

---

## Challenges

- Imbalanced dataset  
- Potential data leakage  

---

## Conclusion

This project demonstrates how machine learning can be used to analyze fossil data and uncover patterns about ancient life on Earth.

---

## Future Work

- Improve performance using feature selection  
- Handle class imbalance  
- Build an interactive dashboard  
- Deploy models  

---

## Project Highlights

- Multiple machine learning tasks  
- Real scientific dataset  
- Data preprocessing and leakage handling  
- Model comparison and evaluation  

---

## Dataset

https://www.kaggle.com/datasets/kayleefranklin/predict-the-trilobite-fossil-age

---

<p align="center">
  Built with a focus on data analysis and machine learning
</p>
