# 🍽️ Zomato Data Analysis | End-to-End Data Analytics Project

## 📌 Project Overview

This project demonstrates a complete **Data Analytics workflow** using the Zomato Restaurant Dataset. Starting with raw restaurant data, the project performs data cleaning, exploratory data analysis (EDA), feature engineering, and concludes with an interactive **Power BI dashboard** that provides meaningful business insights.

The objective is to identify restaurant trends, customer preferences, pricing patterns, and factors influencing restaurant ratings.

---

## 🎯 Project Objectives

- Clean and preprocess raw restaurant data
- Perform Exploratory Data Analysis (EDA)
- Engineer meaningful features for better analysis
- Build an interactive Power BI dashboard
- Generate actionable business insights

---

## 📂 Project Structure

```
zomato-analysis/
│
├── data/
│   ├── raw/
│   │   └── zomato.csv
│   │
│   └── processed/
│       └── cleaned_zomato.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_feature_engineering.ipynb
│
├── dashboard/
│   └── zomato_dashboard.pbix
│
├── reports/
│   └── insights_summary.md
│
├── images/
│   └── dashboard_preview.png
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Dataset

The dataset contains restaurant information such as:

- Restaurant Name
- Location
- City
- Cuisines
- Average Cost for Two
- Ratings
- Votes
- Online Order Availability
- Table Booking Availability
- Restaurant Type

---

# 🧹 Data Cleaning

The dataset contained several inconsistencies which were resolved during preprocessing.

### Cleaning Steps

- Removed duplicate records
- Dropped unnecessary columns
- Handled missing values
- Converted ratings into numeric format
- Removed "NEW" and "-" values from ratings
- Standardized cost values
- Removed currency symbols and commas
- Converted categorical columns into appropriate data types
- Cleaned inconsistent cuisine names

---

# 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Rating Distribution
- Restaurant Distribution by City
- Most Popular Cuisine Types
- Cost Distribution
- Rating vs Cost Analysis
- Online Order vs Ratings
- Table Booking vs Ratings
- Restaurant Votes Analysis
- Outlier Detection

Libraries Used:

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# ⚙️ Feature Engineering

Additional features were created to improve analysis.

### Features Created

- Cost Bucket
  - Budget
  - Mid Range
  - Premium

- Primary Cuisine

- Popularity Score

```
Popularity Score = Rating × Votes
```

---

# 📊 Power BI Dashboard

The dashboard provides interactive insights using filters and slicers.

### Dashboard Features

✅ KPI Cards

- Total Restaurants
- Average Rating
- Average Cost
- Total Votes

✅ Interactive Filters

- City
- Locality
- Cuisine
- Restaurant Type
- Cost Bucket

✅ Visualizations

- Rating Distribution
- Restaurants by Cuisine
- Restaurants by City
- Online Order Analysis
- Table Booking Analysis
- Cost Analysis
- Top Rated Restaurants
- Restaurant Map

---

# 📌 Business Insights

Some key findings from the analysis include:

- Popular cuisines dominate restaurant listings across major cities.
- Mid-range restaurants receive the highest customer engagement.
- Restaurants offering online ordering generally receive more customer votes.
- Higher-rated restaurants tend to attract significantly more customer reviews.
- Table booking is more common among premium restaurants.
- Restaurant ratings do not always increase with higher pricing.

---

# 💻 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Analysis Environment |
| Power BI | Dashboard Development |
| Git & GitHub | Version Control |

---

# 🚀 How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/zomato-analysis.git
```

### Move into Project Folder

```bash
cd zomato-analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Run notebooks in the following order:

1. 01_data_cleaning.ipynb
2. 02_eda.ipynb
3. 03_feature_engineering.ipynb

Finally, open the **Power BI Dashboard (.pbix)** to explore the visualizations.

---

# 📷 Dashboard Preview

> Add a screenshot of your Power BI dashboard here.

Example:

```
images/dashboard_preview.png
```

```markdown
![Dashboard Preview](images/dashboard_preview.png)
```

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Feature Engineering
- Data Visualization
- Business Intelligence
- Dashboard Design
- Power BI
- Python
- SQL Concepts
- Business Insights Generation

---

# 📈 Future Improvements

- Sentiment Analysis using Restaurant Reviews
- Predict Restaurant Ratings using Machine Learning
- Deploy Interactive Dashboard Online
- Build Streamlit Web Application
- Add Real-Time Restaurant Data

---

# 👩‍💻 Author

**Chainika Rathore**

🎓 Final Year B.Tech (Computer Science Engineering)

💼 Aspiring Data Analyst

### Connect with Me

- LinkedIn: linkedin.com/in/chainika-rathore-8a942b24a
- Gmail: chainikarathore7976@gmail.com
