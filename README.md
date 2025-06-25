# 🤖 Warehouse Automation and Robotics Integration Project

## 📌 Overview

This project analyzes the impact of robotics integration—such as Amazon’s touch-sensing robot “Vulcan”—on warehouse operational efficiency and workforce dynamics. Using real-world-inspired data, we assess how robotics affects cost savings, productivity, safety, and human-to-robot collaboration within fulfillment centers.

Business Analysts play a key role in identifying underperforming warehouses and recommending data-driven strategies for optimization.

---

## 🎯 Objectives

- Quantify the operational impact of robotics installation in warehouses.
- Predict cost savings based on robotics and workforce metrics.
- Identify underperforming fulfillment centers.
- Provide actionable insights to maximize ROI and minimize inefficiencies.

---

## 📂 Dataset

The dataset (`warehouse_robotics_data.csv`) includes information about robotic deployment, workforce distribution, and performance indicators.

### Key Columns:

- `Center_ID`
- `Robotics_Installed` (1 = Yes, 0 = No)
- `Robots_Count`
- `Operational_Hours`
- `Human_Workforce_Count`
- `Incidents_Reported`
- `Processing_Volume_Units`
- `Avg_Pick_Time_sec`
- `Cost_Saving_USD`

---

## 🧠 Tech Stack

- **Python**: Core programming
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn**: Visualization
- **Scikit-learn**: Modeling and evaluation
- **Joblib**: Model serialization

---

## 📊 Exploratory Data Analysis (EDA)

- Created metrics such as `Robot_Density`, `Volume_per_Hour`, and `Human_to_Robot_Ratio`.
- Compared cost savings in warehouses with and without robotics using box plots.
- Evaluated correlations between features using heatmaps.

---

## 🔍 Modeling

- Used **Random Forest Regressor** to predict `Cost_Saving_USD`.
- Achieved model evaluation using:
  - **RMSE (Root Mean Squared Error)**
  - **R² Score**

---

## 📈 Output Files

- `optimized_robotics_data.csv`: Post-processed dataset with engineered features.
- `robotics_optimization_suggestions.csv`: List of underperforming centers with suggestions.
- `robotics_efficiency_model.pkl`: Trained predictive model.

---

## ✅ Recommendations Engine

A custom function identifies centers with lower-than-average cost savings and recommends potential robotic scaling strategies based on performance.

---

## 🚀 How to Run This Project

```bash
# Clone the repo
git clone https://github.com/yourusername/warehouse-robotics-analytics.git

# Install required libraries
pip install -r requirements.txt

# Run the Python script or Jupyter Notebook
python Warehouse_robotics_analysis.py    '
 ```

---

## 📜 License
This project is licensed under the MIT License.


## 👨‍💻 Author
    Harsh Sonkar


---




