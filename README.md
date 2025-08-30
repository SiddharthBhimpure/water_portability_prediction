#  Water Potability Prediction  

A machine learning project that predicts whether water is **safe for drinking (potable)** or **not potable**, based on physicochemical attributes such as pH, hardness, solids, sulfate, conductivity, organic carbon, and turbidity.  

The model leverages **XGBoost Classifier** and is evaluated using accuracy and confusion matrix visualization.  

---

## 🚀 Features
- ✅ Predicts **water potability** using physicochemical indicators  
- ✅ Implements **XGBoost Classifier** with tuned hyperparameters  
- ✅ Data preprocessing, cleaning, and feature engineering included  
- ✅ Provides **accuracy scores on training & test sets**  
- ✅ Visualizes performance with a **confusion matrix heatmap**  

---

## 📂 Dataset
- **Dataset used:** `water_potability.csv`  
- Contains physicochemical properties of water samples along with labels (potable or not).  
- Target Variable: **Potability** (1 = drinkable, 0 = not drinkable)  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- **XGBoost** (classification model)  
- **scikit-learn** (metrics, preprocessing)  
- **matplotlib, seaborn** (visualizations)  
- **pandas, numpy** (data handling)  

---

## ⚙️ Setup Instructions

### 1. Clone the repository

git clone https://github.com/your-username/water_potability_prediction.git
cd water_potability_prediction

### 2. Create a virtual environment
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

### 3. Install dependencies
pip install -r requirements.txt

### 4. Run the notebook
Open prediction.ipynb in Jupyter Notebook / Jupyter Lab and run the cells step by step.



## 👤 Author
**Siddharth Bhimpure**  
- 🎓 B.Tech in AI & Data Science  
