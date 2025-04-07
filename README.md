# HW2_2200357818_DogaDeryaBucan 
# Banknote Authentication with Decision Tree
This project implements a Decision Tree classifier to predict whether a banknote is fake or authentic using the [UCI Banknote Authentication Dataset](https://archive.ics.uci.edu/ml/datasets/banknote+authentication).

##  Files

- `decision_tree.ipynb`
- `README.md`

## Dataset

The dataset contains 1372 instances and 4 numerical features extracted from images of banknotes:

- Variance of wavelet transformed image
- Skewness of wavelet transformed image
- Kurtosis of wavelet transformed image
- Entropy of image
- **Class (Target)**: 0 = Fake, 1 = Authentic

## Libraries Used

- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn

## Key Steps

1. Loaded and visualized the dataset.
2. Explored the meaning of features (variance, skewness, kurtosis, entropy).
3. Split the dataset (80% train, 20% test).
4. Trained a Decision Tree classifier with different hyperparameters.
5. Evaluated model using classification report and confusion matrix.
6. Visualized the decision tree and feature importance.

## Results

- High accuracy and F1-score achieved.
- "Variance" and "Skewness" were the most important features.
- Decision Tree was interpretable and effective for this task.

## How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Run the code.
3. You can change hyperparameters in `DecisionTreeClassifier()` to experiment further.

## GitHub
 GitHub repo link here:  
https://github.com/DogaDeryaBucan/HW2_2200357818_DogaDeryaBucan

