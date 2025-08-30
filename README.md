# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Project Overview
Credit card fraud is a major concern in financial systems, causing significant losses each year.  
This project aims to build a **fraud detection model** using **Logistic Regression** to classify transactions as either **fraudulent** or **genuine**.  

The dataset used in this project is the famous **Credit Card Fraud Detection dataset** (highly imbalanced, with only ~0.17% fraudulent transactions).  
The main focus is on **data preprocessing, analysis, and model building**.

---

## 🛠 Work Flow
![Workflow](https://github.com/shaikhmairaj/Credit_Card_Fraud_Detection_Using_ML/blob/main/project%20workflow.jpg)

1. **Credit Card Data**  
   - Load dataset (CSV file containing credit card transactions).
   
2. **Data Pre-processing**  
   - Handle missing values  
   - Feature scaling  
   - Handle imbalanced data (under-sampling / over-sampling if needed)

3. **Data Analysis**  
   - Exploratory Data Analysis (EDA)  
   - Check fraud vs. non-fraud distribution  
   - Correlation analysis & visualization  

4. **Train-Test Split**  
   - Split dataset into training and testing sets  

5. **Logistic Regression Model**  
   - Train a logistic regression classifier  
   - Predict fraudulent transactions  

6. **Evaluation**  
   - Evaluate model performance using:  
     - Accuracy  
     - Precision  
     - Recall  
     - F1 Score  
     - Confusion Matrix  

---

## 📂 Project Structure
Credit_Card_Fraud_Detection_Using_ML/
│-- data/ # Dataset folder (not uploaded due to size > 100MB)
│-- notebooks/ # Jupyter notebooks for EDA & model building
│-- src/ # Python source code files
│-- images/ # Workflow & output images
│-- README.md # Project documentation
│-- requirements.txt # Python dependencies


---

## 🚀 Installation & Usage

### 1. Clone the Repository
```bash
git clone https://github.com/shaikhmairaj/Credit_Card_Fraud_Detection_Using_ML
cd Credit_Card_Fraud_Detection_Using_ML

### 2. Create Virtual Environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # for Linux/Mac
venv\Scripts\activate      # for Windows
## 3. Install Dependencies
pip install -r requirements.txt
### 4. Run the Project

open jupyter notebook

📊 Results

Logistic Regression achieved:

High Recall (important in fraud detection)

Balanced Precision & Recall using evaluation metrics

🔮 Future Improvements

Try other ML models (Random Forest, XGBoost, SVM, Neural Networks)

Implement SMOTE or ADASYN for handling imbalanced dataset

Deploy model using Flask/Django + Streamlit/Gradio

Real-time fraud detection with Apache Kafka + Spark Streaming

🤝 Contributing

Contributions are welcome!
If you’d like to improve this project, feel free to fork the repo and create a pull request.

📜 License

This project is licensed under the MIT License.

👤 Author

Mairaj Shaikh
📧 Email: shaikhmairaj075@gmail.com
]
🔗 GitHub: https://github.com/shaikhmairaj
