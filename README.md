## Laptop Price Prediction

This project focuses on predicting laptop prices based on various specifications using machine learning techniques. It involves data cleaning, preprocessing, exploratory data analysis, and building a predictive model.

### Dataset

[cite_start]The dataset used in this project is `Laptop-Price.csv`[cite: 1]. [cite_start]It contains 1146 rows and 18 columns, providing detailed information about various laptops[cite: 17].

**Columns:**
* [cite_start]**Company**: Manufacturer of the laptop[cite: 1].
* [cite_start]**Product**: Specific product name of the laptop[cite: 1].
* [cite_start]**TypeName**: Type of laptop (e.g., Notebook, Ultrabook, Gaming)[cite: 1].
* [cite_start]**Inches**: Screen size in inches[cite: 1].
* [cite_start]**ScreenResolution**: Resolution and features of the screen (e.g., Full HD, IPS Panel, Touchscreen)[cite: 1].
* [cite_start]**Ram**: RAM size (e.g., 8GB, 16GB)[cite: 1].
* [cite_start]**OpSys**: Operating System installed[cite: 1].
* [cite_start]**Cpu Brand**: Brand of the CPU (e.g., Intel, AMD)[cite: 1].
* [cite_start]**Cpu Model**: Specific CPU model[cite: 1].
* [cite_start]**Cpu Rate**: Clock rate of the CPU[cite: 1].
* [cite_start]**SSD**: SSD storage capacity (in GB)[cite: 1].
* [cite_start]**HDD**: HDD storage capacity (in GB)[cite: 1].
* [cite_start]**Flash Storage**: Flash storage capacity (in GB)[cite: 1].
* [cite_start]**Hybrid**: Hybrid drive storage capacity (in GB)[cite: 1].
* [cite_start]**Gpu Brand**: Brand of the GPU (e.g., Nvidia, AMD, Intel)[cite: 1].
* [cite_start]**Gpu Model**: Specific GPU model[cite: 1].
* [cite_start]**Unnamed: 16**: An empty column that will be dropped[cite: 1, 17].
* [cite_start]**Price_euros**: The target variable, representing the price of the laptop in Euros[cite: 1].

### Analysis and Methodology

[cite_start]The `Laptop_Prices.ipynb` notebook [cite: 17] outlines the following steps:

1.  **Environment Setup**:
    * [cite_start]Installation of necessary libraries: `matplotlib`, `pandas`, `numpy`, `seaborn`, and `scikit-learn`[cite: 17].
    * [cite_start]Importing key libraries for data manipulation, visualization, and machine learning[cite: 17].

2.  **Data Loading and Initial Inspection**:
    * [cite_start]The `Laptop-Price.csv` dataset is loaded into a pandas DataFrame[cite: 17].
    * Initial inspection includes:
        * [cite_start]Viewing the first few rows (`data.head()`)[cite: 17].
        * [cite_start]Checking data types and non-null counts (`data.info()`)[cite: 17].
        * [cite_start]Summarizing numerical columns (`data.describe()`)[cite: 17].
        * [cite_start]Identifying missing values (`data.isnull().sum()`)[cite: 17]. [cite_start]A fully null column named `Unnamed: 16` was identified, indicating it should be removed[cite: 17].

Further steps for data cleaning, preprocessing, feature engineering, model training, and evaluation would typically follow in the notebook.

### Dependencies

The project requires the following Python libraries:
* [cite_start]pandas [cite: 17]
* [cite_start]numpy [cite: 17]
* [cite_start]matplotlib [cite: 17]
* [cite_start]seaborn [cite: 17]
* [cite_start]scikit-learn [cite: 17]

---
