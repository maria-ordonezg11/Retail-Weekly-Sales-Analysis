# 📊 Retail Weekly Sales Analysis: Exploratory Data Analysis and Statistical Insights

## 🧩 Introduction

Retail companies constantly face challenges related to demand forecasting, inventory planning, promotional effectiveness, and resource allocation.

Several key business questions need to be addressed:

- What factors have the strongest influence on weekly sales?
- Do holidays significantly impact sales performance?
- Are promotional markdowns generating measurable revenue growth?
- How does sales behavior differ across regions?
- Can future sales be accurately forecasted using historical operational data?

To answer these questions, weekly sales data, store information, and operational features were analyzed using Exploratory Data Analysis (EDA), statistical testing, feature engineering, and machine learning techniques.

The goal of this project is to transform historical sales data into actionable insights that support retail planning, forecasting, and business decision-making.

---

## 🎯 Project Objective

Throughout this project, the following business questions are addressed:

- Can we trust the data?
- What sales patterns can be identified?
- Which factors most strongly influence weekly sales?
- Do holidays significantly increase sales performance?
- Are markdown promotions effective?
- How predictable are future sales?
- How can insights be communicated effectively to decision-makers?

---

## 🔄 Analysis Workflow

Each phase builds upon the previous one and answers a different business question.

| Step | Business Question                              | Expected Outcome         |
| ---- | ---------------------------------------------- | ------------------------ |
| 1    | Can we trust the data?                         | Clean dataset            |
| 2    | What patterns exist in sales performance?      | Exploratory insights     |
| 3    | Which factors influence sales?                 | Statistical evidence     |
| 4    | Can additional features improve understanding? | Enhanced dataset         |
| 5    | Can future sales be predicted?                 | Forecasting models       |
| 6    | How do we communicate findings?                | Business recommendations |

## 🔹 Step 1: Data Preparation and Quality Assessment

🎯 Objective
- Evaluate data quality
- Identify missing values and inconsistencies
- Prepare data for analysis
- Generate reliable datasets
 
📦 Deliverable

Clean and structured dataset ready for analysis

📂 Project Datasets

The analysis begins with three primary data sources:

- 📄 sales.csv

Contains historical weekly sales for multiple retail stores and departments.

- 📄 features.csv

Contains operational variables such as temperature, fuel price, CPI, unemployment rate, and markdown activities.

- 📄 stores.csv

Contains store characteristics including store type and size.

## 🔹 Step 2: Exploratory Data Analysis (EDA)

🎯 Objective
- Understand weekly sales behavior
- Identify seasonal trends
- Explore sales distributions
- Evaluate regional and store-level differences
  
📦 Deliverable
- Business-oriented exploratory insights
  
Key Business Questions Investigated
- How do weekly sales evolve over time?
- Are there clear seasonal patterns?
- Which stores consistently outperform others?
- How do promotional activities affect sales?

## 🔹 Step 3: Statistical Analysis

🎯 Objective
- Validate business assumptions
- Measure the impact of holidays
- Quantify relationships between variables
- Identify significant sales drivers

### Statistical Tests Performed

### Holiday Impact Analysis
Evaluated whether holiday weeks generate significantly higher sales than non-holiday periods.

### Regional Sales Comparison
Analyzed whether meaningful differences exist between regions and store groups.

### Correlation Analysis
Measured relationships between sales and operational variables.

📦 Deliverable
Statistical evidence supporting business conclusions

## 🔹 Step 4: Feature Engineering

🎯 Objective

Create additional variables that improve analytical depth and forecasting performance.

### Features Created
Time Features
- Year
- Month
- Week
- Quarter

### Business Features
- Holiday indicators
- Regional classifications
- Promotional intensity variables

### Growth Metrics
- Sales Growth Rate

### Historical Sales Features
- Lag Sales
- Rolling Sales Average

📦 Deliverable
Enhanced dataset optimized for analysis and predictive modeling

## 🔹 Step 5: Predictive Modeling

🎯 Objective
- Forecast future sales performance
- Compare model performance
- Identify the strongest sales 

### Models Implemented

### Linear Regression
Used as a baseline forecasting model to evaluate relationships between variables and weekly sales.

### Random Forest Regressor
Used to capture more complex patterns and evaluate feature importance.

### Model Evaluation Metrics
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

📦 Deliverable
- Forecasting models
- Performance comparison
- Feature importance analysis

## 🔹 Step 6: Business Insights and Communication

🎯 Objective
- Transform findings into actionable recommendations
- Communicate insights through visualizations
- Support business decision-making
  
📦 Deliverable
- Executive-ready visualizations
- Business recommendations
- Data storytelling outputs

## 📈 Key Business Insights

### 1. Strong Seasonal Sales Patterns
Weekly sales exhibit significant seasonal fluctuations, with demand peaking during specific periods of the year.

### 2. Holidays Drive Higher Sales
Holiday weeks consistently outperform regular periods, confirming the positive impact of seasonal events on retail performance.

### 3. Regional Differences Matter
Statistical analysis revealed meaningful differences in sales behavior across regions, emphasizing the importance of localized strategies.

### 4. Promotions Support Revenue Growth
Markdown activities demonstrated a positive relationship with sales performance, indicating that promotional campaigns contribute to increased demand.

### 5. Historical Sales are Powerful Predictors
Lagged sales and rolling averages emerged as the strongest indicators of future sales performance.

### 6. Reliable Forecasting is Possible
Predictive models successfully explained a substantial portion of sales variability, demonstrating the value of data-driven forecasting.

## 🚀 Expected Business Outcomes

By the end of this project, the analysis provides:

- Reliable and structured sales data
- Understanding of seasonal demand patterns
- Evidence of holiday and promotional impacts
- Identification of key sales drivers
- Predictive forecasting capabilities
- Actionable business recommendations

## 💼 Business Impact

This project demonstrates how data analytics can support strategic retail decision-making by:

- Improving sales forecasting accuracy
- Supporting inventory planning
- Optimizing promotional strategies
- Identifying regional performance opportunities
- Enhancing resource allocation decisions
- Reducing uncertainty through data-driven insights

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Statistical Hypothesis Testing
- Feature Engineering
- Machine Learning
- Data Visualization

## 📌 Project Skills Demonstrated

 ✅ Data Cleaning & Preparation
 ✅ Exploratory Data Analysis (EDA)
 ✅ Statistical Analysis
 ✅ Feature Engineering
 ✅ Predictive Modeling
 ✅ Business Analytics
 ✅ Data Storytelling
 ✅ Retail Analytics
 ✅ Sales Forecasting
 ✅ Business Recommendation Development

 
