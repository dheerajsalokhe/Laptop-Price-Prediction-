# 💻 Laptop Price Prediction using Machine Learning

This project builds a predictive model to estimate laptop prices based on their specifications using machine learning techniques. It involves data cleaning, exploratory data analysis, feature engineering, and regression modeling.

---

## 📁 Dataset

- **Source**: `Laptop-Price.csv`  
- **Records**: 1,146 laptops  
- **Target Variable**: `Price_euros` (price in Euros)

### 📌 Key Features:
| Feature            | Description                                      |
|--------------------|--------------------------------------------------|
| `Company`          | Laptop manufacturer (e.g., Dell, HP, Apple)     |
| `Product`          | Model name                                       |
| `TypeName`         | Type (Notebook, Ultrabook, Gaming, etc.)        |
| `Inches`           | Screen size in inches                           |
| `ScreenResolution` | Resolution and display features (e.g., Full HD) |
| `Ram`              | RAM size (e.g., 8GB, 16GB)                       |
| `OpSys`            | Operating system (e.g., Windows 10, macOS)       |
| `Cpu Brand`        | Brand of the CPU (Intel, AMD)                    |
| `Cpu Model`        | Model of the CPU                                 |
| `Cpu Rate`         | Clock speed of the CPU                           |
| `SSD`, `HDD`, `Flash Storage`, `Hybrid` | Storage capacities (in GB) |
| `Gpu Brand`, `Gpu Model` | Graphics card info                         |
| `Price_euros`      | **Target** - Laptop price in Euros               |

---

## 🔎 Project Workflow

### 1. 🧹 Data Cleaning
- Dropped irrelevant or fully null columns (e.g., `Unnamed: 16`)
- Parsed RAM and storage fields into numeric GB
- Handled categorical variables (e.g., label encoding)

### 2. 📊 Exploratory Data Analysis (EDA)
- Distribution of laptop prices
- Price comparison across:
  - Brands
  - CPU types
  - GPU types
  - Operating systems

### 3. 🏗️ Feature Engineering
- Extracted CPU brands from `Cpu Model`
- Normalized units (e.g., GB, GHz) for numeric processing

### 4. 🤖 Model Building
- **Train-Test Split**: 80% training / 20% testing
- **Algorithms Tried**:
  - Linear Regression
  - Decision Tree Regressor
  - Random Forest Regressor
  - Gradient Boosting Regressor (optional)
- **Evaluation Metric**: R² Score and RMSE

---

## 📈 Results

| Model               | R² Score |
|---------------------|----------|
| Linear Regression   | ~0.70    |
| Random Forest       | ~0.87    |
| Decision Tree       | ~0.82    |

> Random Forest gave the most accurate predictions on the test set.

---

## 🧪 Dependencies

Install all required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


## Requirements.txt
-pandas
-numpy
-matplotlib
-seaborn
-scikit-learn


🚀 How to Run
1. Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/laptop-price-prediction.git
cd laptop-price-prediction

2. Run the notebook:

bash
Copy
Edit
jupyter notebook Laptop_Prices.ipynb

3. Ensure the dataset Laptop-Price.csv is placed in the same directory.

📬 Contact
Author: Dheeraj Atul Salokhe
📧 djsalokhe@gmail.com


