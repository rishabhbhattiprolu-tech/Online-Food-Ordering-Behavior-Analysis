# 🍽️ Online Food Ordering Behavior Analysis

This project explores what drives people to order food online, using demographic, economic, and behavioral data. Through exploratory analysis and predictive modeling, the project identifies key factors influencing customer decisions and overall satisfaction with online food delivery platforms.

---

## 📊 Dataset

The dataset includes:
- **Age, Gender, Marital Status**
- **Occupation & Monthly Income**
- **Education level**
- **Family size**
- **Location data (latitude, longitude, pin code)**
- **Output** – whether the individual orders food online  
- **Feedback** – customer sentiment toward online ordering

This combination enables a comprehensive view of customer habits and preferences.

---

## 🚀 Workflow

**Data Preprocessing**  
- Handling missing values  
- Encoding categorical variables  
- Cleaning geographic & demographic fields  

**Exploratory Data Analysis (EDA)**  
- Distribution of age, income, occupation  
- Heatmaps to explore correlations  
- Analysis of factors linked to “Output: Yes”  
- Feedback sentiment patterns  

**Modeling**  
- Classification models (Logistic Regression, Random Forest, XGBoost)  
- Target variable: `Output` (Yes/No)  
- Evaluation metrics: Accuracy, Precision, Recall, F1-score  

**Insights**  
- Income, age, and occupation strongly influence online ordering  
- Students and young adults show high adoption  
- Positive feedback correlates with higher engagement  

---

## 🛠️ Installation

Clone the project and install requirements:
git clone https://github.com/yourusername/online-food-analysis.git
cd online-food-analysis
pip install -r requirements.txt
Run the notebook: jupyter notebook online_food.ipynb

🤝 Contributing: Pull requests and suggestions are welcome!
