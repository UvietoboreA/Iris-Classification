# 🌺 **Iris Species Classification Using Decision Tree Classifier**  

## **1. Introduction**  
The **Iris dataset** is one of the most well-known datasets in machine learning, used for **classification tasks**. This project builds a **Decision Tree Classifier** to classify **Iris species** based on flower measurements.  

✅ **Performs Exploratory Data Analysis (EDA) on the Iris dataset.**  
✅ **Trains a Decision Tree Classifier** to predict the species of an Iris flower.  
✅ **Evaluates classification accuracy** using a confusion matrix and classification report.  

This project provides insights into **feature importance** and helps **visualize decision boundaries** for species classification.  

---

## **2. Background**  
The **Iris dataset** consists of three flower species: **Setosa, Versicolor, and Virginica**, classified based on:  

🔹 **Sepal Length & Width** – Outer part of the flower.  
🔹 **Petal Length & Width** – Inner part, useful for species differentiation.  

The challenge is to **accurately classify species** using **decision tree algorithms** while understanding which flower features contribute most to classification.  

This project addresses this challenge by:  

✅ **Applying Decision Tree classification** for accurate species prediction.  
✅ **Visualizing relationships** between flower dimensions and species labels.  
✅ **Evaluating model accuracy** with confusion matrix and feature correlations.  

---

## **3. Data Collection and Processing**  
### **📂 Dataset**  
The dataset **Iris.csv** contains **150 samples of flowers** with four key attributes.  

| Feature | Description |
|---------|------------|
| `SepalLengthCm` | Sepal length of the flower (cm) |
| `SepalWidthCm` | Sepal width of the flower (cm) |
| `PetalLengthCm` | Petal length of the flower (cm) |
| `PetalWidthCm` | Petal width of the flower (cm) |
| `Species` | Target variable – Iris Setosa, Versicolor, or Virginica |

### **🛠️ Data Preprocessing Steps**  
✅ **Dropped unnecessary columns** (e.g., `Id`).  
✅ **Checked for missing values** and handled inconsistencies.  
✅ **Encoded categorical labels** (converted `Species` into numerical values).  

---

## **4. Exploratory Data Analysis (EDA)**  
📊 **Feature Correlation Analysis**  
- **Heatmaps** revealed relationships between sepal/petal measurements and species classification.  

📈 **Species Distribution**  
- **Pair plots** visualized how different features separated flower species.  

📉 **Feature Impact on Classification**  
- **Box plots** analyzed the variation of petal and sepal dimensions across species.  

---

## **5. Model Development**  
### **📌 Machine Learning Model Used**  
- **Decision Tree Classifier** 🌳 – Selected for its **interpretable, rule-based classification approach**.  

### **🛠 Model Training Process**  
✅ **Split dataset into training (75%) and testing (25%) sets**.  
✅ **Trained Decision Tree Classifier on training data**.  
✅ **Optimized hyperparameters** to enhance classification accuracy.  

---

## **6. Model Evaluation & Results**  
📊 **Performance Metrics:**  
✅ **Accuracy Score** – Measures overall classification performance.  
✅ **Confusion Matrix** – Evaluates true vs. predicted classifications.  
✅ **Classification Report** – Displays precision, recall, and F1-score per class.  

📉 **Key Findings:**  
- **Petal length and width were the most significant features** for species differentiation.  
- **Decision Tree achieved high classification accuracy**, correctly predicting most species.  

---

## **7. Visualizing the Results**  
📊 **Decision Tree Visualization**  
- **Displayed the decision-making process** of the trained classifier.  

📈 **Confusion Matrix Heatmap**  
- **Highlighted correct and incorrect classifications** in a visual format.  

📉 **Feature Importance Analysis**  
- **Bar plots** showcased which flower features contributed most to classification.  

---

## **8. Future Work**  
+ 🔹 Test additional classification models (Random Forest, SVM) for comparison.  
+ 🔹 Implement **hyperparameter tuning** to optimize tree depth and splits.  
+ 🔹 Deploy the model as a **simple web app for real-time flower classification**.  
+ 🔹 Expand the dataset with **more flower species** for broader classification tasks.  

---

## **9. Technologies Used**  
+ 🔹 Programming: Python  
+ 🔹 Machine Learning: Scikit-learn, Decision Tree Classifier  
+ 🔹 Data Processing: Pandas, NumPy  
+ 🔹 Data Visualization: Seaborn, Matplotlib  
+ 🔹 Model Evaluation: Accuracy, Confusion Matrix, Feature Importance  

---

## **10. Connect With Me**  
💼 **LinkedIn:** [Uvietobore Joshua Adjugah](https://www.linkedin.com/in/uvietobore-joshua-adjugah-2b548621a)  
📧 **Email:** uviejosh@gmail.com  

🚀 **Star this repo if you find it useful!
