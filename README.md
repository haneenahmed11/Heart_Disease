# Heart Disease Classification Project

##  Objective
This project aims to **predict the presence of heart disease** using patient health data.  
Various **supervised and unsupervised machine learning models** are applied to analyze and classify the data.

##  Dataset
- Source: Kaggle – **Heart Disease Dataset**  
- File: `heart.csv`  
- Features include patient attributes like age, sex, chest pain type, blood pressure, cholesterol, etc.  
- Target variable: `target` (0 = No Disease, 1 = Disease)  

##  Tools & Libraries
- Python 3.x  
- Data analysis & visualization: `pandas`, `numpy`, `matplotlib`, `seaborn`  
- Machine learning: `scikit-learn`  
- Model saving: `joblib`  
- Warnings are ignored for cleaner outputs.

##  Project Steps
1. **Load and inspect the dataset** (`head()`, `info()`, `describe()`, missing values, etc.)  
2. **Visualize target distribution** and feature correlations using plots.  
3. **Handle missing values** and remove outliers using IQR method.  
4. **Convert categorical variables** into dummy variables.  
5. **Scale numerical features** using `StandardScaler`.  
6. **Split dataset** into training and testing sets (80% train, 20% test).  
7. **Train multiple supervised models**:  
   - Logistic Regression  
   - SVM (Linear & RBF)  
   - KNN  
   - Decision Tree  
   - Random Forest  
   - Gradient Boosting  
   - Naive Bayes  
8. **Evaluate models** using Accuracy, Precision, Recall, F1-score.  
9. **Visualize performance** using bar plots for comparison.  
10. **Train unsupervised models** (optional):  
    - KMeans Clustering  
11. **Save trained models** using `joblib` for future use.

##  Results
- Models are evaluated based on Accuracy, Precision, Recall, and F1-score.  
- Supervised models usually outperform unsupervised methods for classification.  
- Visual comparison of models helps in selecting the best performing algorithm.

##  Project Files
- `heart.csv` – Dataset  
- `Heart_Disease_Classification.ipynb` – Main notebook  
- `*.pkl` – Saved trained models for each algorithm  
- `README.md` – This file  

##  How to Use
1. Open the notebook or run the Python script.  
2. Ensure the dataset is in the correct directory.  
3. Run the code to train models or load pre-trained models.  
4. Use trained models to predict heart disease on new patient data.

##  Contributions
- Contributions are welcome for improving model performance, adding new algorithms, or enhancing visualization.  
- Please open an Issue or Pull Request on GitHub to share your updates.
