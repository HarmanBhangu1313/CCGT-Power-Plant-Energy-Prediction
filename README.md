#  CCGT Power Plant Energy Prediction

This project analyzes data from a **Combined Cycle Gas Turbine (CCGT) power plant**.  
The goal is to predict the **net hourly electrical energy output (PE)** of the plant using various regression models and compare their performance with **R² values**.

---

##  Project Structure
├── Data.csv                                     # Dataset (CCGT power plant data)
├── CCGT_Power_Plant_Energy_Prediction           # Jupyter Notebook with model training
├── requirements.txt                             # Python dependencies
└── README.md                                    # Project documentation

---
+----------------------------+-----------------+-----------------------+-------------------+-----------------+
| Multiple Linear Regression | Polynomial Reg. | Decision Tree Reg.    | Random Forest Reg | SVR             |
+----------------------------+-----------------+-----------------------+-------------------+-----------------+
|           R²               |       R²        |          R²           |        R²         |       R²        |
+----------------------------+-----------------+-----------------------+-------------------+-----------------+
|    0.9325315554761303      | 0.945951500578  |  0.922905874177941    |  0.96159083343638 | 0.948369330431  |
+----------------------------+-----------------+-----------------------+-------------------+-----------------+



---
##  Requirements

Install the dependencies with:

```bash
pip install -r requirements.txt

