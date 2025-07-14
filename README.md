# Iris Flower Classification with Logistic Regression

This beginner machine learning project uses **Logistic Regression** to classify different species of Iris flowers based on their petal and sepal measurements.

---

## Dataset

The **Iris dataset** is a classic in machine learning and is included with `scikit-learn`. It contains:

- 150 rows
- 4 features:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)
- 3 target classes:
  - `setosa`
  - `versicolor`
  - `virginica`

---

## What This Project Covers

- Loading and exploring a dataset
- Data visualization with `matplotlib`
- Splitting data into training and test sets
- Training a Logistic Regression model
- Evaluating model accuracy using:
  - Confusion Matrix
  - Classification Report
- Predicting species for new data

---

## File Structure

```bash
iris-flower-classification/
├── Iris-Flower-Classification.ipynb   # Jupyter notebook with full code
├── README.md                        # Project documentation (this file)
````

---

## Example Output

```
Confusion Matrix:
[[10  0  0]
 [ 0  7  1]
 [ 0  0 12]]

Classification Report:
              precision    recall  f1-score   support

      setosa       1.00      1.00      1.00        10
  versicolor       1.00      0.88      0.93         8
   virginica       0.92      1.00      0.96        12

    accuracy                           0.97        30
```

---

## Predicting a New Flower

Example: Predicting for a flower with `[5.1, 3.5, 1.4, 0.2]`

```
Predicted Species: setosa
```

---

## Tech Stack

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib

---

## How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/iris-flower-classification.git
   cd iris-flower-classification
   ```

2. Open the notebook:

   ```bash
   jupyter notebook iris_logistic_regression.ipynb
   ```
