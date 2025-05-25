# AutoPredict-Auction-Purchase-Risk-Analyzer


# 🚗 Smart Auction Risk Analyzer

A machine learning project that predicts whether a car purchased at auction is a **good buy** or a **potential risk (kick)** — helping dealerships make smarter, data-driven decisions.

---

## 📌 Introduction

Purchasing used vehicles from auctions is a common practice among dealerships, but it comes with the **risk of "kicked" cars** — vehicles that turn out to be problematic and unsellable due to issues like:

- Tampered odometers 🕒  
- Mechanical defects 🔧  
- Missing or problematic vehicle titles 📄  
- Other hidden risks 🚫  

These vehicles can lead to **financial losses**, including repair costs, transportation fees, and poor resale value.

**🎯 Objective:**  
To build a predictive model using real-world auction data that classifies purchases as either a **Good Buy ✅** or a **Kick ❌**, helping auto dealers **minimize risk and maximize value**.

---

## 📊 Dataset

- 📦 **Source:** Real-world auction data with over **150,000 vehicle entries**
- 🔢 **Features:** Make, Model, Year, Odometer Reading, Auction details, etc.
- 🏷️ **Target:** `IsBadBuy` (1 = Kick, 0 = Good Buy)

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing** 🧹  
2. **Exploratory Data Analysis (EDA)** 📈  
3. **Feature Engineering** 🏗️  
4. **Model Building** 🤖  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
5. **Evaluation** ✅  
   - Accuracy, Precision, Recall, F1 Score  
6. **Visualization & Insights** 🌈

---

## 📷 Visualizations

Here are some key insights from the dataset:

- Distribution of car makes at auction 🏷️  
- Kick rate by vehicle age ⏳  
- Model performance comparison 📊  


---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/akshata130504/AutoPredict-Auction-Purchase-Risk-Analyzer.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python script:
   ```bash
   jupyter notebook main.ipynb
   ```

---

## 📦 Tech Stack

- Python 🐍  
- Pandas & NumPy 🔢  
- Matplotlib & Seaborn 📊  
- Scikit-learn 🤖  
- XGBoost ⚡  
- Jupyter Notebook 📓

---

## ✅ Results

✅ Achieved 89% accuracy using the Random Forest model after hyperparameter tuning.

⚙️ Effectively handled imbalanced data and performed comprehensive preprocessing.

🔍 Identified key risk factors influencing bad purchases, enhancing decision-making for dealerships.

---

## 🌟 Future Work

- Add deep learning model with LSTM or DNN  
- Deploy as a web app using Streamlit or Flask  
- Integrate real-time auction data via API  
