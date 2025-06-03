
# 🧠 Tumor Detection using Machine Learning

This project aims to classify tumors as **Malignant (M)** or **Benign (B)** based on their characteristics using a supervised machine learning approach. The dataset contains diagnostic measurements of breast cancer tumors, and the goal is to build an accurate and interpretable classification model.

---

## 📁 Dataset

The dataset used is `Tumor_Detection.csv`, which includes features such as:

- Radius, Texture, Perimeter, Area, Smoothness, etc.  
- Each feature has mean, worst, and standard error statistics.  
- The target variable is `diagnosis`:  
  - **M** = Malignant  
  - **B** = Benign  

---

## 📌 Project Steps

1. **Data Cleaning**  
   - Removed irrelevant columns like `id` and unnamed fields.  
   - Checked and confirmed absence of missing values.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized class distribution of tumor types.  
   - Created a correlation heatmap to explore relationships between features.

3. **Preprocessing**  
   - Converted categorical diagnosis labels (`M`/`B`) into numerical format (1/0).  
   - Standardized feature values using `StandardScaler`.

4. **Model Building**  
   - Used a **Random Forest Classifier** to train the model.  
   - Split data into 80% training and 20% testing.

5. **Evaluation**  
   - Achieved an accuracy of **96.49%** on the test set.  
   - Visualized performance with a confusion matrix.  
   - Generated a detailed classification report (precision, recall, F1-score).

---

## 🎯 Final Accuracy

```
Model: Random Forest Classifier
Accuracy: 96.49%
```

---

## 📊 Key Visuals

- **Class Distribution Plot**  
- **Correlation Heatmap**  
- **Confusion Matrix**  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn (RandomForest, train_test_split, metrics)

---

## 📎 How to Run

1. Clone the repository  
2. Install required packages (`pip install -r requirements.txt`)  
3. Run the Jupyter notebook: `Tumor_Detection.ipynb`
