
# 🏡 Real Estate Market Dashboard

**Author:** Karim Elsayed  
**Tools:** Python, Pandas, Seaborn, Scikit-learn, Tableau

---

## 📌 Project Overview

This project analyzes housing data to explore how various factors affect 
**real estate prices**. Using a combination of Python for data processing and Tableau for dashboard design, 
we uncover key patterns in property prices, distance to MRT stations, and convenience store availability.
- 📁 **Dataset**: Real estate data with price per unit area
- 📊 **Goal**: Predict prices and segment neighborhoods using clustering
- 🧠 **Methods**:
  - Exploratory Data Analysis (EDA)
  - Regression Modeling (Linear Regression)
  - Clustering (KMeans)
  - Tableau Dashboard Design
---

## 📊 Dashboard Preview

![Real Estate Market Dashboard](output/final_dashboard_image.png)

The dashboard visualizes:

- 🏷️ **Unit Price** based on location and amenities  
- 🚉 **Distance to MRT Station** vs 💰 Price  
- 🏪 **Nearby Convenience Stores** vs 💸 Price

👉 Tooltip shows detailed insights with color-coded values for quick interpretation.

---

## 🧪 Analysis Pipeline

### ✅ Step 1: Data Cleaning & Preprocessing  
- Removed missing values  
- Renamed confusing column headers  
- Scaled features using `StandardScaler` for ML

### ✅ Step 2: Exploratory Data Analysis  
- Created correlation heatmap  
- Found strong positive correlation with:
  - `convenience_stores`, `latitude`, and `longitude`  
  - Negative correlation with `distance_to_mrt`

### ✅ Step 3: Clustering  
- Used K-Means to group similar properties  
- Optimal clusters determined by the Elbow Method  
- Visualized using scatter plots

### ✅ Step 4: Machine Learning  
- Trained a Linear Regression model  
- Performance:
  - MAE = 5.35
  - RMSE = 7.39
  - R² Score = 0.67

---

## 📈 Tableau Dashboard

📌 **Title:** *Real Estate Market Dashboard*  
📌 **Tooltips:** Custom rich text (emoji + color + HTML)  
📌 **Design:**  
- Log scale for better separation  
- Interactions through filters  
- Modern layout with titles and icons  

🖼️ Screenshot: `output/final_dashboard_image.png`

---

## 📸 Dashboard Preview

![Tableau Dashboard Preview](output/final_dashboard_image.png)

> This Tableau dashboard shows predicted vs. actual prices, clusters of housing segments, and GDP vs. life expectancy impact.

---

## 📂 Project Structure

```
real-estate-dashboard/
│
├── data/
│   └── Real estate.csv
├── output/
│   └── final_dashboard_image.png
├── notebooks/
│   └── real_estate_analysis.ipynb
├── README.md
└── .gitignore
```

---

## 🚀 Future Improvements

- Add Random Forest & XGBoost regressors  
- Deploy dashboard using Tableau Public  
- Integrate time series trends  
- Interactive web app with Streamlit
- Add more real-world features (crime rate, schools)
- Integrate geospatial maps in Tableau

---

## 📬 Contact

📧 info.karimelsayed@gmail.com  
🔗 [GitHub](https://github.com/InfoKarim)  
🌐 Portfolio: [Coming Soon]

---

> _“Data reveals what intuition hides.”_
