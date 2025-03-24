# Car Price Prediction

## 📌 Project Overview
This project aims to analyze key factors influencing car prices in the US market and develop predictive models using machine learning techniques. The insights from this model can help manufacturers and businesses set competitive prices for their vehicles.

## 🚀 Objective
- Identify significant variables affecting car prices.
- Build and compare multiple machine learning models.
- Tune hyperparameters to enhance model performance.
- Recommend the best model for car price prediction.

## 📊 Dataset Information
The dataset consists of various car attributes, including:
- **Car specifications** (fuel type, engine size, horsepower, etc.)
- **Performance metrics** (mileage, curb weight, drive type, etc.)
- **Price** (Target variable for prediction)

## 🛠️ Tech Stack
- **Programming Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, XGBoost, LightGBM

## 🔍 Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Handling missing values and categorical encoding
- Feature selection and correlation analysis
- Data visualization for insights

## 🏆 Models Implemented
- **Linear Regression**
- **Decision Tree Regression**
- **Random Forest Regression** ✅ (Best Model after Hyperparameter Tuning)
- **Gradient Boosting (XGBoost, LightGBM)**
- **Support Vector Regression (SVR)**
- **Neural Networks (MLP Regressor)**

## 🎯 Model Performance & Results
The **Random Forest Regression (after tuning)** provided the best results in terms of accuracy and error metrics, making it the recommended model for production.

## 🔧 Hyperparameter Tuning
Performed on the best model using GridSearchCV, improving its performance by optimizing parameters like:
- Number of estimators
- Maximum depth
- Minimum samples split

## 📜 Reports Included
- **Model Comparison Report**: Performance analysis of all models.
- **Challenges & Solutions**: Issues faced in data processing and modeling, along with solutions.

## 📂 Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Car-Price-Prediction.git
   cd Car-Price-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis and models.

## 📬 Contact
For any queries, feel free to reach out!

---
📌 **Contributions are welcome!** 🚀
