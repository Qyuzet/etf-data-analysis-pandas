# ETF Data Analysis with Pandas

**Author:** Riki Awal Syahputra

A comprehensive data science project analyzing Exchange-Traded Funds (ETFs) using Python and pandas. This project demonstrates essential data analysis skills including data loading, cleaning, merging, grouping, aggregation, missing value handling, and advanced operations like regex text processing and JSON parsing.

---

## 📊 Project Overview

This project analyzes real-world ETF market data to demonstrate:
- Data loading and inspection
- DataFrame manipulation and transformation
- Data merging and concatenation
- Grouping and aggregation operations
- Missing value handling strategies
- Advanced pandas operations
- Regex text cleaning
- JSON data parsing

---

## 📁 Dataset

The project uses two main datasets:

### **1. ETFs.csv** - Details about 2,310 ETFs
- Fund symbols, names, categories
- Fund families and management details
- Fees and expense ratios
- 142 columns of ETF characteristics
- **Size:** ~17 MB

### **2. ETF prices.csv** - Daily price history
- 3.8M+ price records
- Date, open, high, low, close prices
- Trading volume
- Adjusted prices
- Historical performance data
- **Size:** ~188 MB

---

## 📥 How to Get the Dataset

**The CSV files are NOT included in this repository due to their size.**

### **Download from GitHub Releases:**

1. Go to the [Releases page](https://github.com/Qyuzet/etf-data-analysis-pandas/releases)
2. Download the latest release (v1.0)
3. Extract the CSV files:
   - `ETFs.csv`
   - `ETF prices.csv`
4. Place them in the `finance_data/` folder in your local clone

**Direct download link:** [Download Dataset (v1.0)](https://github.com/Qyuzet/etf-data-analysis-pandas/releases/tag/v1.0)

---

## 🚀 Quick Start

### **1. Clone the repository:**
```bash
git clone https://github.com/Qyuzet/etf-data-analysis-pandas.git
cd etf-data-analysis-pandas
```

### **2. Download the dataset:**
- Download CSV files from [Releases](https://github.com/Qyuzet/etf-data-analysis-pandas/releases)
- Place them in `finance_data/` folder

### **3. Install dependencies:**
```bash
pip install pandas numpy scikit-learn jupyter
```

### **4. Launch Jupyter Notebook:**
```bash
jupyter notebook etfs-comparators.ipynb
```

### **5. Run the analysis:**
- In Jupyter: `Cell → Run All`
- Or run cells sequentially with `Shift + Enter`

---

## 📂 Project Structure

```
etf-data-analysis-pandas/
├── etfs-comparators.ipynb    # Main Jupyter notebook
├── finance_data/              # Data directory
│   ├── ETFs.csv              # Download from Releases
│   └── ETF prices.csv        # Download from Releases
├── README.md                  # This file
└── .gitignore                 # Git ignore file
```

---

## 🛠️ Requirements

```bash
pip install pandas numpy scikit-learn jupyter
```

**Versions used:**
- Python 3.8+
- pandas 1.3.0+
- numpy 1.21.0+
- scikit-learn 1.0.0+
- jupyter

---

## 📚 What's Inside

### **Core Analysis (Steps 1-16)**

1. **Data Loading** - Import CSV files with pandas
2. **Data Inspection** - head(), tail(), info(), describe()
3. **Missing Values** - Identify and quantify missing data
4. **Data Merging** - Combine ETF details with price history
5. **Grouping & Aggregation** - Calculate statistics by fund
6. **Handling Missing Values** - dropna() strategies
7. **Filling Missing Values** - fillna() with different methods
8. **Display Options** - Customize pandas output
9. **Column Renaming** - Rename and modify column names
10. **Index Manipulation** - set_index(), reset_index()
11. **Data Reshaping** - melt() and pivot() operations
12. **Concatenation** - Combine DataFrames vertically/horizontally
13. **Function Application** - apply(), applymap(), map()
14. **Data Querying** - Filter with query() method
15. **Advanced Missing Values** - Multiple imputation strategies
16. **sklearn SimpleImputer** - Professional imputation techniques

### **Extra Miles (Steps 17-18)**

17. **Regex Text Cleaning** - Pattern matching and text processing
18. **Movies Metadata** - Parse nested JSON in CSV files

---

## 💡 Skills Demonstrated

### **Technical Skills**
- Python programming
- Pandas data manipulation
- NumPy numerical operations
- Regular expressions (regex)
- JSON parsing
- Data type conversion
- Error handling
- Feature engineering

### **Data Science Skills**
- Exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Missing value imputation
- Data transformation
- Data quality assessment
- Statistical analysis
- Creating derived metrics

---

## 🎯 Key Features

- ✅ Comprehensive data cleaning pipeline
- ✅ Real-world financial data analysis
- ✅ Advanced pandas operations
- ✅ Professional missing value handling
- ✅ Text processing with regex
- ✅ Nested JSON data parsing
- ✅ Well-documented code
- ✅ Reproducible analysis

---

## 📊 Results & Insights

The analysis provides insights into:
- ETF performance patterns
- Trading volume trends
- Fund family comparisons
- Category-based analysis
- Price movement statistics

---

## 🔮 Future Enhancements

- [ ] Add data visualization with matplotlib/seaborn
- [ ] Implement time series analysis
- [ ] Build predictive models
- [ ] Create interactive dashboards
- [ ] Add more ETF metrics and indicators

---

## 🤝 Contributing

This is an educational project. Suggestions and improvements are welcome!

---

## 📄 License

This project is for educational purposes.

---

## 📧 Contact

**Riki Awal Syahputra**
- GitHub: [@Qyuzet](https://github.com/Qyuzet)
- Project Link: [https://github.com/Qyuzet/etf-data-analysis-pandas](https://github.com/Qyuzet/etf-data-analysis-pandas)

---

## 🙏 Acknowledgments

- Data Science Fundamentals Course
- Pandas documentation and community
- ETF market data providers

---

**⭐ If you find this project helpful, please give it a star!**

