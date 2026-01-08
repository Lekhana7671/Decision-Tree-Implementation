# Decision-Tree-Implementation

*Company*: Codtech IT Solutions Private Limited

*Name*: Yarnakula Lekhana

*Intern ID*: CTIS1133

*Domain*: Machine Learning

*Duration*: 12 Weeks

*Mentor*: Neela Santosh

# 🌳 Decision Tree Implementation Using Scikit-Learn

## 📌 Overview
This project demonstrates the implementation, visualization, and analysis of a **Decision Tree machine learning model** using the **Scikit-learn** library in Python. The task is designed to provide hands-on experience with one of the most interpretable and widely used supervised learning algorithms.

The entire workflow is implemented in a **Jupyter Notebook (Google Colab compatible)** and includes dataset loading, model training, evaluation, visualization, and result analysis. The final deliverable is a notebook that clearly documents each step of the process.

---

## 🎯 Objectives
The main objectives of this task are:

- To understand the working principles of Decision Tree algorithms  
- To build a Decision Tree classifier using Scikit-learn  
- To train and test the model on a real dataset  
- To evaluate the model using standard performance metrics  
- To visualize the Decision Tree for interpretability  
- To analyze and document observations clearly  

---

## 📊 Dataset Description
The project uses the **Iris dataset**, a built-in dataset provided by Scikit-learn. This dataset is commonly used for classification tasks and is well-suited for understanding machine learning fundamentals.

### Dataset Features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Since the dataset is built into Scikit-learn, no external dataset download is required.

---

## 🛠️ Methodology

### 1. Data Loading
The Iris dataset is loaded using Scikit-learn’s dataset loader. The feature matrix (X) and target vector (y) are extracted for further processing.

### 2. Data Splitting
The dataset is split into training and testing sets using the train-test split method. This helps in evaluating the model’s performance on unseen data.

### 3. Model Building
A **Decision Tree Classifier** is created using the Gini Index as the splitting criterion. To avoid overfitting and to improve interpretability, the maximum depth of the tree is limited.

### 4. Model Training
The model is trained using the training dataset. During this phase, the Decision Tree learns decision rules based on feature values.

### 5. Prediction and Evaluation
Predictions are made on the test dataset. The model is evaluated using:
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

These metrics provide insights into the model’s classification performance.

### 6. Model Visualization
The trained Decision Tree is visualized using Scikit-learn’s plotting utilities. The visualization displays feature splits, decision rules, and class distributions at each node, making the model easy to interpret.

---

## 📈 Analysis and Observations
The Decision Tree model achieves high accuracy on the Iris dataset, indicating effective classification performance. Visualization reveals that features such as **petal length** and **petal width** play a crucial role in determining flower species. Limiting the depth of the tree helps reduce complexity and prevents overfitting while maintaining good performance.

---

## ✅ Conclusion
This project successfully demonstrates an end-to-end implementation of a Decision Tree classifier using Scikit-learn. The task enhances understanding of machine learning workflows, model evaluation techniques, and the importance of interpretability in decision-making models. The final notebook serves as a reproducible and well-documented deliverable suitable for academic and professional evaluation.

---

## 💻 Tools & Technologies Used
- Python  
- Scikit-learn  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab / Jupyter Notebook  

---

## 📁 Deliverable
- `Decision_Tree_Implementation.ipynb` – Jupyter Notebook containing code, outputs, visualizations, and analysis.

---

## 🙌 Acknowledgment
This task was completed as part of a learning exercise to understand Decision Tree algorithms and their practical implementation using Scikit-learn.

# Output

<img width="1636" height="836" alt="Image" src="https://github.com/user-attachments/assets/59bd18a6-0e60-4570-b0e0-4a6509292933" />
