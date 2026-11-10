# Iris Flower Classification

**Oasis Infobyte Internship · Python Track · Task 1**

## Objective
Train machine learning classifiers that identify the species of an iris flower (Setosa, Versicolor or Virginica) from its sepal and petal measurements.

## Dataset
The classic Iris dataset (150 samples, 4 numeric features, 3 balanced classes), loaded directly from `sklearn.datasets.load_iris()`.

## Approach
1. Exploratory data analysis: shape, dtypes, null check, descriptive statistics, class balance
2. Visualisations: pairplot, box plots, correlation heatmap
3. Feature discussion: petal length and petal width are the most discriminative
4. Stratified 80/20 train/test split
5. Models trained: Logistic Regression, K-Nearest Neighbours, Decision Tree, Random Forest
6. Evaluation: accuracy, confusion matrix, classification report, plus 5-fold cross-validation
7. Best model declared with justification

## Results
| Model | Test Accuracy | CV Mean Accuracy |
|-------|---------------|------------------|
| Logistic Regression | 0.9333 | 0.9600 |
| K-Nearest Neighbours | 0.9333 | 0.9600 |
| Decision Tree | 0.9333 | 0.9533 |
| Random Forest | 0.9000 | 0.9667 |

**Best model:** Random Forest (highest 5-fold cross-validated accuracy, 0.9667)

## Tech Stack
Python, pandas, NumPy, scikit-learn, matplotlib, seaborn, Jupyter Notebook

## How to Run
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook Iris_Flower_Classification.ipynb
```



