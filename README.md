# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Objective
Build a machine learning model using the K-Nearest Neighbors algorithm to classify iris flowers into one of three species:
- Setosa
- Versicolor
- Virginica

The classification is based on four input features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

---

## 📚 Dataset
We use the built-in Iris dataset from `sklearn.datasets`. It contains 150 samples, 4 features, and 3 classes of iris flowers.

---

## 🛠️ Tools & Libraries
- Python
- pandas
- seaborn
- matplotlib
- scikit-learn

---

## 🔁 Project Workflow

1. **Load and Explore the Dataset**  
   Display basic info, visualize relationships using pairplots, and understand patterns.

2. **Preprocess the Data**  
   Split the dataset into features (X) and target (y), then divide into training and testing sets.

3. **Train KNN Model (k=3)**  
   Use scikit-learn’s KNeighborsClassifier to train on the dataset.

4. **Make Predictions & Evaluate**  
   Use accuracy score and confusion matrix to evaluate model performance.

5. **Visualize Results**  
   Plot a heatmap of the confusion matrix for easy interpretation.

6. **Predict on New Samples**  
   Test the model on new unseen flower measurements.

---

## 📈 Results
The model achieves high accuracy and performs well on test data. You can experiment with different `k` values to see how accuracy changes.

---

## 💻 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook  
2. Run all cells step-by-step  
3. Add your own sample inputs and test the predictions

---
