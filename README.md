# ✈️ AeroReach Insights – Personalizing Customer Interaction through Social Media Insights  

## 📌 Project Overview  
Airlines often struggle to deliver **personalized offers** that resonate with individual travelers.  
This project, **AeroReach Insights**, leverages **demographic data** and **social media engagement** to:  
- Segment users into meaningful groups.  
- Predict whether a user will **take a product/offer**.  
- Provide insights for airlines to create **hyper-personalized digital marketing campaigns**.  

---

## 📂 Dataset  
- **File:** `AeroReach Insights.csv`  
- **Target Column:** `Taken_product` (`Yes`/`No`)  
- **Features include:**  
  - Travel page views, likes & comments  
  - Outstation check-ins  
  - Family size  
  - Preferred device & location type  
  - Daily average time on travel pages  
  - Employment & age flag  

---

## 🛠️ Methodology  
1. **Data Cleaning & Preprocessing**  
   - Missing value handling  
   - Outlier detection & treatment  
   - Encoding categorical variables  
   - SMOTE for class imbalance  

2. **Exploratory Data Analysis (EDA)**  
   - Univariate & bivariate analysis  
   - Outlier detection via boxplots  
   - Correlation heatmap  

3. **Model Building**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

4. **Evaluation Metrics**  
   - Accuracy  
   - Precision, Recall, F1-score  
   - Confusion Matrix  

---

## 📊 Results  

| Model               | Accuracy | Precision (Class 1) | Recall (Class 1) | F1-score (Class 1) |
|---------------------|----------|---------------------|------------------|--------------------|
| Logistic Regression | 84%      | 0.00                | 0.00             | 0.00               |
| Random Forest       | ~92%     | 0.89                | 0.70             | 0.78               |
| **XGBoost**         | **96%**  | **0.98**            | **0.77**         | **0.86**           |

✅ **XGBoost performed the best** and is recommended for deployment.  

---

## 🚀 Business Impact  
- Helps airlines avoid spamming uninterested users (**high precision**).  
- Captures majority of likely buyers (**good recall**).  
- Enables personalized offers:  
  - Discounts on favorite destinations  
  - Family travel packages  
  - Device-based targeted ads  

---

## 💻 Tech Stack  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn, Imbalanced-learn, XGBoost  
- Jupyter Notebook  

---

## 📌 How to Run  

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/AeroReach-Insights.git
   cd AeroReach-Insights
##install dependencies
pip install -r requirements.txt


📈 Future Enhancements
Deploy as a Flask/Django web app
Connect with real-time social media APIs
Try deep learning for improved personalization

Author - 
Sarayu Polepalli
MBA in DataScience and Analytics
