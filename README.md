# 🌸 iris-knn-classifier

A simple machine learning project that uses the **K-Nearest Neighbors (KNN)** algorithm to classify Iris flowers based on their features.  
Built using **scikit-learn**, this project demonstrates the basics of data loading, model training, prediction, and evaluation.

---

## 📌 Features

- ✅ Uses scikit-learn's built-in Iris dataset
- ✅ Implements KNN (k=3) classification
- ✅ Splits the dataset into training and testing sets
- ✅ Evaluates accuracy
- ✅ Makes predictions on sample data
- ✅ Saves and loads model using `joblib`

---

## 📊 Example Output

```
Feature Names: ['sepal length (cm)', 'sepal width (cm)', 'petal length (cm)', 'petal width (cm)']
Target Names: ['setosa' 'versicolor' 'virginica']

Training Shape: (105, 4)
Test Shape: (45, 4)
Accuracy: 0.955

Sample Predictions:
['virginica', 'versicolor']
```

---

## 💾 Save and Load Model

### Save the trained model:

```python
from joblib import dump
dump(knn, 'mlbrain.joblib')
```

### Load the saved model:

```python
from joblib import load
model = load('mlbrain.joblib')
model.predict(sample)
```

---

## 📚 Dependencies

Install the required packages using:

```bash
pip install scikit-learn numpy joblib
```

### Required Libraries:

- `scikit-learn`
- `numpy`
- `joblib`

---

## 🧠 Dataset Info

The [Iris Dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set) contains:

- 150 samples (rows)
- 4 features per sample:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- 3 target classes:
  - Setosa
  - Versicolor
  - Virginica

---

## 🗂️ Project Structure

```
iris-knn-classifier/
│
├── iris_knn_classifier.py     # Main script
├── mlbrain.joblib             # Saved model (after training)
└── README.md                  # Project documentation
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/iris-knn-classifier.git
   cd iris-knn-classifier
   ```

2. Run the classifier:
   ```bash
   python iris_knn_classifier.py
   ```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to submit a pull request.

---

## 👤 Author

**Hasan Berjawi**  
[GitHub](https://github.com/yourusername) • [LinkedIn](https://linkedin.com/in/yourprofile)
