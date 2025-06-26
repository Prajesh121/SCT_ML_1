# Machine Cost Prediction using Linear Regression

**Internship Project Task 1 – Handpac India Pvt. Ltd.**

This project predicts the **purchase or maintenance cost of packaging machines** using machine specifications.  
It was completed as part of a machine learning internship.

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| `production_capacity_per_hour` | The machine's production throughput per hour |
| `num_heads_or_modules` | Number of operational modules or heads in the machine |
| `avg_operational_hours_per_day` | Average number of hours the machine operates per day |

**Target:** `machine_price` — estimated cost of the machine in INR

---

## 📁 Dataset

The dataset is a **repurposed Kaggle House Prices dataset**, where house-related features were mapped to machine specifications:

- [House Prices - Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  

**Note:** Column names have been renamed to reflect machine-related attributes.

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- Scikit-Learn  
- Matplotlib  
- Jupyter Notebook  

---

## 📈 Output

- **Linear Regression Model**  
- **Evaluation Metrics:** Mean Squared Error (MSE) and R² Score  
- **Visualization:** Scatter plot showing Actual vs Predicted Machine Costs

---

## 🔍 How to Run

1. Clone the repository:  
```bash
git clone https://github.com/Prajesh121/<repo_name>.git
