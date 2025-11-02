# MSCS_634_ProjectDeliverable_1

---

## Dataset Overview
**Dataset Name:** Customer Experience Dataset for AI-Driven Optimization  
**Source:** Simulated dataset (synthetic data)  
**Records:** 1,000  
**Features:** 10+ attributes including:
- **Customer Demographics:** Age, Gender, Location
- **Interaction Data:** Number of Interactions, Feedback Score, Products Purchased
- **Behavioral Data:** Products Viewed, Time Spent on Website
- **Satisfaction & Retention:** Satisfaction Score, Retention Status

**Why this dataset?**
- Simulates real-world customer behavior
- Large enough for regression, classification, clustering, and association rule mining
- Provides actionable insights for customer experience optimization

---

## Data Cleaning & Preparation
- **Missing Values:** Checked and imputed numerical features with median, categorical features with mode
- **Duplicates:** Removed duplicates to maintain data integrity
- **Outliers:** Detected via boxplots and histograms; handled by capping/removal
- **Feature Engineering (planned for next deliverable):**
  - Engagement Rate = Time_Spent_on_Site / (Num_Interactions + 1)
  - Purchase-to-View Ratio = Products_Purchased / (Products_Viewed + 1)
- **Categorical Encoding:** One-hot encoding applied for `Gender` and `Location`

---

## Exploratory Data Analysis (EDA)
- **Distribution Plots:** To examine feature distributions
- **Boxplots:** To identify outliers
- **Correlation Heatmap:** To observe relationships between features
- **Pairplots:** To explore feature interactions

**Insights:**
- Higher engagement correlates with higher retention and satisfaction
- Age and location may influence customer behavior
- Interaction metrics strongly correlate with purchases
- These insights guide feature selection and modeling in subsequent deliverables

---

## Challenges & Solutions
- **Missing Data:** Used median/mode imputation
- **Outliers:** Applied visual and statistical thresholds to avoid data skew
- **Categorical Features:** One-hot encoding while avoiding multicollinearity

---

