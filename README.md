# 📦 E-Commerce Orders Data Cleaning & Exploratory Analysis

A data wrangling and exploratory data analysis project focusing on handling messy, real-world e-commerce order records, cleaning inconsistent data formats, and identifying consumer purchasing patterns.

---

## 📌 Project Overview

In real-world data pipelines, raw transactional data rarely arrives in clean, analysis-ready formats. Datasets often suffer from missing values, inconsistent string cases, corrupt date formats, and erroneous price inputs. This project demonstrates end-to-end data cleaning, standardization, and exploratory analysis on an e-commerce order dataset (`messy_orders_550.csv`).

---

## 📊 Dataset & Wrangling Challenges

The dataset reflects typical real-world transactional noise:

* **Inconsistent Categorization:** Discrepant product naming, mixed casing, and typographical variations across categories.
* **Format Standardization:** Unifying date-time formats, stripping unwanted currency artifacts, and casting columns to proper datatypes.
* **Missing Value Imputation:** Handling missing delivery dates, prices, and customer locations.
* **Outlier & Duplicate Detection:** Identifying redundant transaction logs and anomalously high order counts.

---

## 🔍 Key Findings & Workflow Highlights

1. **Systematic Data Cleaning Pipeline:**
   * Step-by-step resolution of null values, duplicate entries, and inconsistent string casing.
   * Correct casting of numeric order amounts and proper datetime indexing for temporal tracking.

2. **Order Volume by Geography:**
   * Categorical count plots illustrate customer concentration across key metropolitan cities, highlighting regional demand hubs.

3. **Product Line Performance:**
   * Examination of top-selling categories (Electronics, Mobile accessories, Lifestyle) identifies volume vs. margin leaders.

---

## 📈 Visualizations in the Notebook

* **Data Quality Audits:** Pre- and post-cleaning summary tables and missingness checks.
* **Geographical Distribution:** Count plots tracking order frequency by customer city.
* **Category Breakdown:** Bar charts ranking order volumes across merchandise lines.
* **Order Value Trends:** Distribution plots examining typical basket sizes.

---

## 🛠️ Tech Stack

* **Language:** Python 3.x
* **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
* **Dataset:** `messy_orders_550.csv`

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Zelarq/ecommerce-orders-cleaning-analysis.git
cd ecommerce-orders-cleaning-analysis
```

### 2. Set Up Virtual Environment
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook
```bash
jupyter notebook project1.ipynb
```

---

## 👤 Author

* **Sayanth N K**
* GitHub: [@Zelarq](https://github.com/Zelarq)
* Email: [sayanthnk32@gmail.com](mailto:sayanthnk32@gmail.com)
