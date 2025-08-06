# Cancer Gene Expression Analysis Using Machine Learning
Machine learning classification of cancer types (ALL vs AML) using gene expression data with ensemble methods achieving 100% accuracy.   

### Overview  
This project classifies Acute Lymphoblastic Leukemia (ALL) and Acute Myeloid Leukemia (AML) using gene expression patterns. Through dimensionality reduction and ensemble learning, we achieve perfect classification on test data.  

### Dataset  

Features: 7,129 genes  
Samples: 72 total (38 training, 34 testing)  
Classes: ALL vs AML (binary classification)  

### Tech Stack  

ML Libraries: scikit-learn, TensorFlow/Keras  
Data Processing: pandas, numpy  
Visualization: matplotlib, seaborn, plotly    

### Key Features

**Dimensionality Reduction:** PCA reduced 7,129 features to 32 (95% variance retained)  
**Ensemble Learning:** Weighted voting classifier with dynamic F1-score weighting  
**Feature Importance:** Identified key genes (X95735_at, M55150_at, M27891_at, M31166_at)  
**Comprehensive Evaluation:** Multiple ML algorithms with hyperparameter tuning  

### Methodology

**Data Preprocessing:** Standardization, label encoding, feature selection  
**Dimensionality Reduction:** PCA for efficient feature reduction  
**Model Training:** 5 different algorithms with hyperparameter optimization (*Logistic Regression, KNN, Random Forest, Naive Bayes, and Ensemble Model*)  
**Ensemble Creation:** Weighted voting based on individual model performance  

### Result  

99.7% Accuracy is Leukemia Classification using Ensemble Model. The genes X95735_at, M55150_at, M27891_at, and M31166_at exhibit high feature importance, indicating their significant role in
distinguishing between ALL and AML cancer types in the analysis.
