# 🌸 Practice ML Projects

This repository contains beginner-friendly machine learning practice projects. These are small experiments I worked on while learning how to use **scikit-learn**, **pandas**, and **matplotlib**. The goal is to build foundational understanding by applying basic ML workflows on real datasets.

---

## 📁 Current Project: Iris Flower Classification

This project uses the famous **Iris dataset** to train and evaluate different classification algorithms. It follows a typical machine learning workflow:

### 🔍 Dataset Info

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)
- **Features**:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- **Target**: Iris flower species (`setosa`, `versicolor`, `virginica`)

### 🧪 Steps Followed

1. **Import Libraries**:
   - `pandas`, `matplotlib`, `scikit-learn`

2. **Load Dataset**:
   - Loaded CSV from an online URL using `pandas.read_csv()`

3. **Explore the Data**:
   - Dataset shape, summary statistics, class distribution (commented out)

4. **Visualize the Data** *(commented)*:
   - Box plots, histograms, scatter matrix

5. **Split the Dataset**:
   - 80% training / 20% testing using `train_test_split`

6. **Build Models** *(commented)*:
   - Logistic Regression
   - Linear Discriminant Analysis
   - K-Nearest Neighbors
   - Decision Tree Classifier
   - Gaussian Naive Bayes
   - Support Vector Machines (SVM)
   - Evaluation with 10-fold cross-validation

7. **Final Model**:
   - Trained an **SVM** model on training data
   - Made predictions on the test set

8. **Evaluate Model**:
   - Used accuracy score, confusion matrix, and classification report

---

## ✅ What I Learned

- How to load and explore datasets using pandas
- How to visualize features and relationships
- How to split datasets and validate models
- How to evaluate models with scikit-learn
- How to compare multiple classifiers

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/ms-siam/Practice-ML-Projects.git
   cd Practice-ML-Projects
   ```

2. Install dependencies (if not already installed):
   ```bash
   pip install pandas matplotlib scikit-learn
   ```

3. Run the Python file:
   ```bash
   python iris_classification.py
   ```

---

## 📌 Note

- Parts of the code are commented out for learning and testing purposes. You can uncomment them to explore data visualization and model comparison.

---

## 🙌 Final Thoughts

This project was an early step in my machine learning journey. It helped me understand basic ML concepts and practice using scikit-learn tools effectively.

More small projects will be added here as I learn!
