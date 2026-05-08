# Leukemia Classification from Gene Expression Data

##  Overview
This project focuses on classifying leukemia subtypes using high-dimensional gene expression data and machine learning techniques. The dataset contains thousands of gene activity measurements collected from leukemia patients diagnosed with Acute Lymphoblastic Leukemia (ALL) and Acute Myeloid Leukemia (AML).
The project explores dimensionality reduction using Principal Component Analysis (PCA), model comparison, and validation techniques to analyze how machine learning can identify disease patterns from genomic data.


## Features

 * Gene expression data preprocessing
 * High-dimensional data handling
 * 2D PCA visualization
 * Dimensionality reduction using PCA
 * Logistic Regression, Random Forest, and SVM models
 * Cross-validation for generalization analysis
 * Comparison between PCA and non-PCA workflows
 * Scientific visualization using Seaborn and Matplotlib

   
##  Tool Used
 * Python
 * NumPy
 * Pandas
 * Matplotlib
 * Seaborn
 * Scikit-learn


##  Machine Learning Workflow
 Gene Expression Data
        ↓
 Preprocessing
        ↓
  Scaling
        ↓
 PCA (Optional)
        ↓
 Model Training
        ↓
 Cross Validation
        ↓
 Performance Comparison


##  Models Used

 * Logistic Regression
 * Random Forest Classifier
 * Support Vector Machine (SVM)

---

##  Why PCA?
 Gene expression datasets are highly dimensional and often contain redundant or noisy features. PCA was used to reduce dimensionality while preserving most 
 of the important variance in the dataset.


## Results
The models achieved strong classification performance across multiple cross-validation folds. PCA significantly reduced feature dimensionality while maintaining similar predictive performance, suggesting that important biological patterns were preserved after dimensionality reduction.


## Dataset
Dataset link : http://hastie.su.domains/CASI_files/DATA/leukemia_big.csv

Classes:
  * ALL (Acute Lymphoblastic Leukemia)
  * AML (Acute Myeloid Leukemia)

---

## Visualization
 * 2D PCA visualization
 * Scatter plots for class separability
 * Cross-validation performance comparison

## Future Improvements
  * Feature selection and important gene analysis
  * Deep learning approaches
  * Biological interpretation of significant genes
  * Interactive dashboard deployment
  * Integration with additional genomic datasets

##  Project Goal
The goal of this project is to combine bioinformatics and machine learning techniques to explore disease classification from genomic data while gaining practical experience with high-dimensional biological datasets.

## Author

Md. Arif Hasnat
First-Year Undergraduate Student
Department of Bioinformatics Engineering,
Bangladesh Agricultural University,Bangladesh
