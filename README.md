# 🌊 AquaMind

**AI-powered groundwater management and prediction system**  
Built with **Streamlit + Machine Learning**

---

## 🚩 Problem Statement
Water scarcity and poor groundwater management threaten agriculture and sustainability.  
Communities lack **predictive tools** and **decision support systems** to manage groundwater resources effectively.

---

## 💡 Our Solution
AquaMind provides **AI-driven insights** for groundwater sustainability:
- ✅ Predicts water quality from CSV/manual input  
- ✅ Visualizes trends (heatmap, histograms, 3D map)  
- ✅ Simulates recharge planning (check-dams, pits)  
- ✅ Suggests water-sharing between regions  
- ✅ Advises crops based on water budget  
- ✅ Early warning alerts for risks  
- ✅ Chatbot for quick Q&A  

---

## 🛠️ Tech Stack
- **Python, Streamlit** – frontend + backend  
- **Scikit-learn, Pandas, Numpy** – ML training & prediction  
- **Plotly, PyDeck, Matplotlib** – visualization  
- **Joblib** – model persistence  

---

## 📊 Dataset
We used groundwater quality datasets containing:
- `pH`
- `Turbidity`
- `Hardness`  
Preprocessed and trained using scikit-learn classifiers.

---

## 🤖 Machine Learning Model
- Algorithm: Random Forest (tested with Logistic Regression)  
- Features: pH, Turbidity, Hardness  
- Output: Water quality prediction (potable / non-potable, risk score)  
- Saved as: `model.pkl`  

---

