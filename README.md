# Customer-Purchase-Review-Data-Cleaning-Project
This project focuses on end to end cleaning and preparation of a customer purchase and review dataset. The goal was to transform raw, inconsistent data into a fully usable, analysis ready dataset by applying practical data cleaning techniques used in real analytics workflows.

### Tools Used
- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Workflow

### 1. Data Import
- Loaded CSV file using pd.read_csv()
- Checked shape, missing values, and column details
- Identified and removed irrelevant columns

### 2. Handling Missing Values
- Filled Family size missing values → *mean*
- Filled Age missing values → *median*

### 3. Outlier Detection & Treatment
- Used boxplots to identify outliers  
- Applied IQR method to clip extreme Age values

### 4. Categorical Cleaning
- Trimmed whitespace in text columns
- Applied one hot encoding for:
  - Gender  
  - Marital Status  
  - Employment Status  

### 5. Category → Numeric Mapping
- Reviews: Positive → 1, Negative → 0  
- Monthly Income: ordinal scale (1–5)  
- Education: ordinal scale (1–5)  
- Order status: Yes → 1, No → 0  

### 6. Final Output
- Fully cleaned dataset  
- No missing values  
- Outliers treated  
- Encoded & mapped categories  
- Ready for dashboards, EDA, or ML models

## Results
- Cleaned and transformed a 389 row customer purchase & review dataset into an analysis ready format.
- Achieved a fully imputed, outlier treated and consistently encoded dataset suitable for EDA, dashboards and machine learning models.

---

## Author

 LinkedIn: in/abhaypandey18
