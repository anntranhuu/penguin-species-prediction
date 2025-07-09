# 🐧 Penguin Species Prediction

## 📊 Project Overview

This project uses the Palmer Penguins dataset to predict penguin species based on features like **bill length**, **flipper length**, **island**, and **sex**. I applied the machine learning models **Decision Tree**, **Random Forest**, and **K-Nearest Neighbors (KNN)**, and evaluated their performance using classification metrics and visualisations. This project was completed as part of my MSc Applied Data Science at the University of Essex.

---

## 🎯 Objectives

- Classify penguin species using both numerical and categorical variables  
- Apply, compare, and evaluate different classification models  
- Create clear, reproducible visualisations and insights

---

## 📁 Dataset

- **Source**: [Palmer Penguins Dataset](https://www.kaggle.com/datasets/parulpandey/palmer-archipelago-antarctica-penguin-data)  
- **Observations**: 344 penguins  
- **Features**: Island, species, bill length/depth, flipper length, body mass, sex

---

## 🛠️ Tools & Technologies

- **Language**: Python  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `sklearn`, `math`
- **Techniques**:
  - Data cleaning & exploratory analysis  
  - Feature encoding  
  - Model training & evaluation
  - Confusion matrix, accuracy, precision, recall, F1-score  

---

## 🔍 Models Used

| Model           | Accuracy | 
|----------------|----------|
| **Random Classifier** |    37.7%    | 
| **Decision Tree** | 96.5%   | 
| **Random Forest**  | 98.2%   | 
| **KNN**      |  96%    | 

✅ Random Forest performed best, with strong generalisation and clear decision boundaries.

---

## 📈 Key Insights

- Island, culmen length, culmen depth, body mass, and flipper length can all be used to determine the species
- Random forest performed the best in terms of accuracy and robustness, but the most suitable model depends on the resources available of the prospective users
- If a simpler, less expensive model is required and the accuracy is not as important, then the decision tree may be best, as this still had a high accuracy and performed just as well as KNN, which would be more expensive to use.

---

## 📍 Visual Highlights

- Decision tree visualisation
- Line graph of accuracy vs max depth for decision tree
- Bar charts, pie charts, scattergraphs of different features

---

## 🧠 What I Learned

- Importance of feature selection and preprocessing for model performance
- How to deal with unbalanced data
- How to evaluate model performance
- Comparing model performance fairly with train/test splits

---

## 📁 Project Structure

📦 penguin-species-prediction/  
┣ 📄 penguin_species_prediction.html ← Full report with outputs and visuals  
┣ 📄 README.md ← This file  
┗ 📄 penguin_species_prediction.ipynb ← ipynb file for EDA & modeling  

---

## 🚀 How to Run

1. Upload the notebook (`.ipynb`) to [Google Colab](https://colab.research.google.com)
2. Run all cells to view data, visuals, and model predictions  

## 📚 References

Palmer Penguins Dataset
scikit-learn documentation
University of Essex – MSc Applied Data Science coursework (2024)
