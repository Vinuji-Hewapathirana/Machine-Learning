## 📌 Project Overview  
This project aims to predict whether a client will subscribe to a **term deposit** based on the **Bank Marketing Dataset** from the **UCI Machine Learning Repository**.  
The classification problem is approached using two **machine learning models**:  
1. **Random Forest Classification**  
2. **Neural Network Model**  

## 📁 Folder Structure  

- **models_tried/**: Contains the machine learning models experimented with for the **Random Forest Model**.  
- **models_tried_neuralnetwork/**: Contains the machine learning models experimented with for the **Neural Network Model**.  

## 🚀 Final Models  

The final models were selected based on accuracy and performance metrics, ensuring optimal evaluation.  

- **ML_RFC_Final.ipynb**:  
  - Final **Random Forest Classification Model** with **SMOTE** and **feature reduction**.  
- **ML_NN_Final.ipynb**:  
  - Final **Neural Network Model** with **class weights** applied.  

## 📊 Dataset Information  

The dataset contains information related to **bank marketing campaigns**, including attributes such as:  
- **Demographics** (Age, Job, Marital Status, etc.)  
- **Financial Information** (Balance, Loan Status, etc.)  
- **Campaign Interaction** (Last Contact Duration, Number of Contacts, etc.)  
- **External Factors** (Economic Indicators)  

The target variable is **"y"**, which indicates whether the client subscribed to a term deposit (`yes` or `no`).  

## ⚙️ Implementation Steps  

1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Apply feature scaling  
   - Address class imbalance using **SMOTE** and **class weights**
2. **Model Training & Tuning**  
   - Experiment with different **hyperparameters**  
   - Optimize **Random Forest & Neural Network** models  
3. **Model Evaluation & Comparison**  
   - Use optimal evaluation metrics (**accuracy, precision, recall, F1-score, ROC-AUC**)  
   - Compare experimental results for both models  

## 📈 Performance Metrics  

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC 

## 🔧 Tools & Libraries  

- **Python**  
- **Scikit-Learn**  
- **TensorFlow/Keras**  
- **Pandas, NumPy, Matplotlib, Seaborn**  
- **Imbalanced-learn (for SMOTE and class weights)**  

## 🎯 Conclusion  

This project successfully applied **Random Forest Classification** and **Neural Networks** to predict term deposit subscriptions. The models were optimized using **feature selection, data balancing, and hyperparameter tuning**, ensuring robust performance.  
