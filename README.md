# Enhanced-Heart-disease-prediction-with-Dragonfly-algorithm
## Overview  
This project focuses on enhancing heart disease prediction by implementing advanced optimization techniques for feature selection and hyperparameter tuning. The Dragonfly Algorithm, along with its variations (Binary Dragonfly Algorithm (BDA), Sinusoidal Binary Dragonfly Algorithm (SBDA)), Ant Lion Optimizer, Moth Flame Optimization, and Sand V models, were utilized to improve model accuracy and efficiency. Logistic Regression was used as the final classifier to predict the presence of heart disease ('yes' or 'no').

---

## Objectives  
- To develop a robust predictive model for heart disease classification.  
- To improve feature selection and hyperparameter optimization using the Dragonfly Algorithm and its variations.  
- To compare the performance of BDA, SBDA, and other optimization models for effective feature selection.  

---

## Methodology  
1. **Dataset**:  
   The project uses the `heart_disease_uci.csv` dataset, which includes 14 attributes like age, sex, chest pain type, cholesterol levels, etc., to predict heart disease.

2. **Optimization Techniques**:  
   - **Binary Dragonfly Algorithm (BDA)**: For feature selection aimed at improving the prediction process.  
   - **Sinusoidal Binary Dragonfly Algorithm (SBDA)**: For selecting the best features among the dataset attributes.  
   - **Ant Lion Optimizer (ALO)**: For exploring alternative optimization methods.  
   - **Moth Flame Optimization (MFO)**: For comparing different optimization strategies.  
   - **Sand V Model**: To add diversity to feature selection analysis.

3. **Classifier**:  
   - Logistic Regression was employed as the final classifier to predict outcomes (`yes` for heart disease, `no` for no heart disease).  

---

## Results  
The project demonstrates a significant improvement in heart disease prediction accuracy by comparing the feature selection outcomes of BDA and SBDA, along with a thorough analysis of other optimization techniques (ALO, MFO, Sand V).  
- **BDA**: Selected all relevant features but lacked diversity in some iterations.  
- **SBDA**: Achieved optimized and varied feature selection, highlighting critical attributes.  
- **Logistic Regression**: Final classifier to predict heart disease with improved accuracy.

---

## Challenges  
- Implementing the Dragonfly Algorithm required manual coding due to module-related issues.  
- Addressed issues like:  
  - Selection of all features with a fitness value of 1.0.  
  - Index errors in iteration loops.  
  - Type errors with velocity addition.  
