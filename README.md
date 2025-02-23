# Breast_Cancer_Classification
"This project predicts breast cancer diagnosis (Malignant/Benign) using machine learning models based on the Breast Cancer Wisconsin (Diagnostic) Dataset."
# 🔬 Breast Cancer Prediction Using Machine Learning

📌 This project conducts Exploratory Data Analysis (EDA) and develops various Machine Learning models to predict breast cancer using the **Breast Cancer Wisconsin (Diagnostic) Dataset**.

---

## 📑 Project Workflow
- **Step 1:** 📂 Load the Dataset  
- **Step 2:** 📊 Perform Exploratory Data Analysis (EDA)  
- **Step 3:** ⚙️ Data Preprocessing  
- **Step 4:** 🤖 Train Machine Learning Models  
- **Step 5:** 📊 Model Evaluation  
- **Step 6:** 📈 Compare Model Accuracies  
- **Step 7:** 💾 Save and Deploy the Best Model  
- **Step 8:** 📂 Upload Test Dataset & Predict Outcomes  

---

## 📌 Steps in Detail

### 📂 Step 1: Load the Dataset  
**📌 Description:**  
- Load the Breast Cancer Wisconsin Dataset from `sklearn.datasets`.  
- Convert it into a **Pandas DataFrame** for analysis.  
- Display the first few rows of the dataset.  

✅ **Expected Outcome:**  
✔️ A structured dataset ready for Exploratory Data Analysis (EDA).  

---

### 📊 Step 2: Perform Exploratory Data Analysis (EDA)  

EDA helps understand the dataset, detect patterns, and identify potential issues before training the model.

#### 🔹 Step 2.1: 📁 Examine Dataset Structure  
✔️ Display dataset shape, column names, data types, and check for missing values.

#### 🔹 Step 2.2: 🚫 Handle Missing Values  
✔️ Verify if the dataset contains missing values and apply necessary handling techniques.

#### 🔹 Step 2.3: 📉 Analyze Target Distribution  
✔️ Plot a countplot to visualize the distribution of **Malignant vs. Benign** cases.

✅ **Expected Outcome:**  
✔️ The dataset exhibits imbalance (with a higher proportion of benign cases).  

#### 🔹 Step 2.4: 🔗 Feature Correlation Analysis  
✔️ Generate a **correlation heatmap** to identify highly correlated features.  

✅ **Expected Outcome:**  
✔️ Features with strong correlation may be removed later to reduce redundancy.  

#### 🔹 Step 2.5: 📊 Visualize Key Features  
✔️ **Histogram:** Analyze feature distributions.  
✔️ **Pairplot:** Observe relationships between features.  
✔️ **Boxplot:** Detect outliers that may impact model performance.  

✅ **Expected Outcome:**  
✔️ Histograms provide insights into feature distribution and skewness.  
✔️ Pairplots illustrate relationships between different features.  
✔️ Boxplots highlight potential outliers.  

---

### ⚙️ Step 3: Data Preprocessing  
**📌 Description:**  
- Standardize features to enhance model performance.  
- Address class imbalance, if necessary.  
- Split the dataset into training and test sets (**e.g., 80% train, 20% test**).  

✅ **Expected Outcome:**  
✔️ Preprocessed and cleaned data ready for model training.  

---

### 🤖 Step 4: Train Machine Learning Models  
**📌 Description:**  
Train multiple **supervised learning algorithms** for comparison, including:  

✔️ **Logistic Regression**  
✔️ **Support Vector Machine (SVM)**  
✔️ **Random Forest Classifier**  
✔️ **K-Nearest Neighbors (KNN)**  
✔️ **Gradient Boosting Models** (e.g., XGBoost, LightGBM, etc.)  

✅ **Expected Outcome:**  
✔️ Multiple trained models for breast cancer prediction.  

---

### 📊 Step 5: Model Evaluation  
**📌 Description:**  
- Assess model performance using **accuracy, precision, recall, F1-score, and the ROC-AUC curve**.  
- Present results using **classification reports and confusion matrices**.  

✅ **Expected Outcome:**  
✔️ A detailed performance comparison of all trained models.  

---

### 📈 Step 6: Compare Model Accuracies  
**📌 Description:**  
- Compare the **accuracy of all models** using a bar chart.  
- Select the **best-performing model** based on accuracy and evaluation metrics.  

✅ **Expected Outcome:**  
✔️ Identification of the **most effective model** for breast cancer prediction.  

---

### 💾 Step 7: Save and Deploy the Best Model  
**📌 Description:**  
- Save the **best-performing model** using `joblib` or `pickle`.  
- Deploy the model via **Flask** or **Streamlit** for real-time predictions.  

✅ **Expected Outcome:**  
✔️ A fully deployed **breast cancer prediction model** accessible for real-world applications.  

---

## 📂 Step 8: Upload Test Dataset & Predict Outcomes  
**📌 Description:**  
- **Upload a CSV file** containing **test patient data**.  
- The **best-trained model** will automatically make predictions.  
- The **predictions** will be saved in a CSV file alongside the **Patient ID**.  
- Users can **download the results** for further analysis.  

### 🛠️ How It Works:  
1️⃣ **Upload** the test dataset (CSV format).  
2️⃣ The model **processes the data** and predicts the outcome.  
3️⃣ Results are **saved** in a new CSV file with two columns:  
   - **Patient ID**  
   - **Prediction**  
4️⃣ Users can **download the results** for further evaluation.  

✅ **Expected Outcome:**  
✔️ A CSV file containing **patient IDs and predictions** ready for clinical evaluation.  

---

## 📌 Summary  
✅ **EDA** provides insights into the dataset.  
✅ **Data Preprocessing** ensures a clean and structured input.  
✅ **Multiple Machine Learning models** are trained and evaluated.  
✅ The **best model** is saved and ready for deployment.  
✅ Users can **upload a test dataset**, apply predictions, and download results.  

🚀 **This project delivers a comprehensive Machine Learning pipeline for Breast Cancer Prediction!**  

---

## 📞 Contact  
If you have any questions or suggestions, feel free to reach out:  

📧 **Email:** hadeerkhaledali2023@gmail.com  
🔗 **LinkedIn:** [Hadeer Khaled](https://www.linkedin.com/in/hadeer-khaled-b18050210)  

---

## 📂 Project Structure  
```bash
Breast_Cancer_Classification/
│── datasets/                 # Contains raw and processed data
│   ├── breast_cancer_data.csv  # Full dataset
│   ├── train.csv               # Training dataset
│   ├── test.csv                # Testing dataset
│   ├── test_results.csv        # Test predictions (Patient ID + Diagnosis)
│
│── models/                   # Contains ML model training files
│   ├── breast_cancer_model.ipynb  # Jupyter Notebook for model training
│   ├── trained_model.pkl          # Saved trained model (optional)
│
│── results/                  # Stores evaluation results, charts, and reports
│   ├── model_performance.png      # Accuracy & loss graphs
│   ├── classification_report.txt   # Precision, recall, F1-score
│
│── README.md                 # Project documentation
│── requirements.txt          # Python dependencies

🚀 **This project delivers a comprehensive Machine Learning pipeline for Breast Cancer Prediction!**  
