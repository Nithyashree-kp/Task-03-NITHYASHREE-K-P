# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project implements the **K-Nearest Neighbors (KNN)** machine learning algorithm to classify Iris flowers into three different species using the famous **Iris Dataset** from Scikit-learn.

The project includes data preprocessing, feature scaling, model training, prediction, and performance evaluation using various classification metrics.

---

## 📌 Features

- Load the Iris dataset
- Split the dataset into training and testing sets
- Apply feature scaling using StandardScaler
- Train a K-Nearest Neighbors (KNN) model
- Predict flower species
- Calculate model accuracy
- Display Confusion Matrix
- Generate Classification Report
- Calculate Weighted F1 Score

---

## 🛠️ Technologies Used

- Python 3
- Pandas
- Scikit-learn

---

## 📂 Project Structure

```
Iris-Flower-Classification/
│── iris_knn.py
│── README.md
```

---

## 📦 Required Libraries

Install the required libraries:

```bash
pip install pandas scikit-learn
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Iris-Flower-Classification.git
```

2. Navigate to the project folder

```bash
cd Iris-Flower-Classification
```

3. Run the Python file

```bash
python iris_knn.py
```

---

## 📊 Dataset

The project uses the **Iris Dataset** available in **Scikit-learn**.

Dataset Information:

- 150 Samples
- 4 Features
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- 3 Classes
  - Setosa
  - Versicolor
  - Virginica

---

## 🤖 Machine Learning Model

Algorithm Used:

- K-Nearest Neighbors (KNN)

Parameters:

- Number of Neighbors (K): 5
- Feature Scaling: StandardScaler
- Train-Test Split: 80% Training, 20% Testing

---

## 📈 Evaluation Metrics

The model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Weighted F1 Score

Example Output:

```
Accuracy: 1.0

Confusion Matrix
[[10 0 0]
 [ 0 9 0]
 [ 0 0 11]]

Classification Report
              precision    recall    f1-score    support

setosa          1.00       1.00       1.00        10
versicolor      1.00       1.00       1.00         9
virginica       1.00       1.00       1.00        11

F1 Score: 1.0
```

---

## 🎯 Future Improvements

- Optimize the value of K using Cross Validation
- Compare KNN with Decision Tree, SVM, and Random Forest
- Visualize the dataset using Matplotlib and Seaborn
- Build a Streamlit web application
- Allow users to classify custom flower measurements

---

## 👩‍💻 Author

**Nithyashree KP**

GitHub: https://github.com/your-username

---

## 📄 License

This project is open-source and available under the MIT License.
