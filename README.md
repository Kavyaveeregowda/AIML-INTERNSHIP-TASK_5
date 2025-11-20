# Task 5 – Decision Tree & Random Forest (AI/ML Internship)

## 1. Objective
The goal of this task is to:
- Train and evaluate **Decision Tree** and **Random Forest** models.
- Understand **overfitting**, **max depth**, and **feature importance**.
- Compare a single tree with an ensemble method.
- Save tree visualizations and submit the GitHub repo.

## 2. Dataset
- File used: **heart.csv**
- Total rows: **1025**
- Target column: **target**
- No missing values.

## 3. Steps Performed
1. Loaded and explored the dataset.
2. Performed train-test split.
3. Trained default Decision Tree.
4. Visualized the decision tree.
5. Checked `max_depth` effect on accuracy.
6. Tr Trained tuned Decision Tree.
7. Trained Random Forest model.
8. Extracted feature importance.
9. Performed cross-validation.
10. Saved all plots into `images/` folder.

## 4. Results

### Decision Tree (Default)
- Accuracy: **98.53%**

### Decision Tree (Depth = 4)
- Accuracy: **83.90%**

### Random Forest
- Accuracy: **100%**
- CV Accuracy: **99.71%**

### Important Features (Top 5)
1. cp
2. thalach
3. ca
4. oldpeak
5. thal

## 5. Conclusion
- Shallow trees underfit.
- Full-depth trees perform well but may overfit.


