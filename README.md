# Classifying Pumpkin Seeds

This project focuses on classifying pumpkin seeds into two different varieties (`Çerçevelik` and `Ürgüp Sivrisi`) using a variety of seed morphological features. It uses machine learning techniques to analyze and predict the type of seed based on attributes such as area, perimeter, major/minor axis length, eccentricity, and others.

## Dataset

The dataset used comes from the [UCI Machine Learning Repository - Pumpkin Seeds Dataset](https://archive.ics.uci.edu/ml/datasets/Pumpkin+Seeds). It contains 1600 samples and 12 features, including:

- Area
- Perimeter
- MajorAxisLength
- MinorAxisLength
- Eccentricity
- ConvexArea
- EquivDiameter
- Extent
- Solidity
- Roundness
- AspectRation
- Compactness
- Class Label (target variable)

## Project Structure
<pre> 
Classifying-Pumpkin-Seeds/
├── notebook/
│ └──  pumpkin_seed_classification.ipynb # Main notebook for analysis
├── data/
│ └── Pumpkin_Seeds_Dataset.csv # Dataset file
├── README.md # Project description and usage
 </pre>

## Approach

1. **Data Preprocessing**  
   - Checked for missing values
   - Normalized/standardized features
   - Converted categorical labels into numerical format

2. **Exploratory Data Analysis (EDA)**  
   - Visualized class distribution and feature relationships
   - Performed correlation analysis

3. **Modeling**  
   - Trained and evaluated several classifiers:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - LDA, QDA, and naive Bayes' models
     - PCA
     - Support Vector Machine (SVM)
     - Gradient Boosting
     - Random Forest
     - XGBoost
     - Used cross-validation for evaluation

4. **Performance Metrics**  
   - Accuracy

## Results

The best-performing model, random forest, achieved an accuracy of approximately 0.868 on the test set (update based on your actual result). The model effectively distinguished between the two pumpkin seed varieties based on morphological features.
