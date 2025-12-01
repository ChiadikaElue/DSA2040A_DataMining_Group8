# DSA2040A_DataMining_Group8
 DSA 2040A Project: Online Retail Customer Analytics

##  Project by: 
Chiadika Elue 

Keyshia Mideva

Nelisa Wacera

##  Executive Summary
This project implements a complete data mining pipeline on the Online Retail II dataset, uncovering customer behavior patterns, product associations, and sales trends to drive business decisions.

##  Key Insights Discovered
1. **Customer Segments:** Identified 4 distinct customer groups (Champions, Loyal, At-Risk, Lost)
2. **Product Associations:** Found 15+ significant product pairs for cross-selling
3. **Sales Trends:** Clear seasonal patterns with peak in Q4
4. **Revenue Drivers:** Top 10% customers generate 45% of revenue

##  Technical Implementation
- **ETL:** Automated data cleaning and feature engineering
- **EDA:** Comprehensive statistical and visual analysis
- **Mining:** RFM clustering, association rules, time series forecasting
- **Dashboard:** Interactive Plotly Dash application

##  Mining Techniques Applied
1. **Clustering:** K-Means for customer segmentation (RFM analysis)
2. **Association Rules:** Apriori algorithm for market basket analysis
3. **Time Series:** Prophet for sales forecasting
4. **Statistical Analysis:** Correlation analysis, outlier detection

##  How to Run in VS Code

# Clone repository
git clone https://github.com/your-username/DSA2040A_DataMining_SoloProject.git
cd DSA2040A_DataMining_SoloProject

# Install dependencies
pip install -r requirements.txt

# Open in VS Code and run notebooks in order:
 1. 1_extract_transform.ipynb
 2. 2_exploratory_analysis.ipynb
 3. 3_data_mining.ipynb
 4. 4_insights_dashboard.ipynb

##  Team Members & Contributions

### Detailed Contributions

#### **Chiadika** - ETL Lead & Dashboard Developer
**Notebook 1: Data Extraction & Transformation**
- Designed and implemented complete ETL pipeline
- Performed data quality assessment and cleaning procedures
- Engineered RFM features for customer segmentation
- Handled missing values, outliers, and data standardization
- Created scalable data transformation workflows

**Notebook 4: Insights Dashboard & Storytelling**
- Developed interactive visualizations and business intelligence dashboards
- Created comprehensive executive summary and actionable insights
- Built customer segmentation visualizations and product performance charts
- Designed association rules network graphs and geographical analysis
- Compiled final business recommendations and strategic roadmap

#### **Keyshia** - Data Analyst & EDA Specialist
**Notebook 2: Exploratory Data Analysis**
- Conducted comprehensive statistical analysis and descriptive analytics
- Performed temporal analysis including seasonal trends and daily patterns
- Executed customer behavior analysis and RFM metric distributions
- Identified correlation patterns and outlier detection
- Created geographical revenue analysis and product performance insights
- Developed key findings summary with data-driven insights

#### **Nelisa** - Data Mining Engineer
**Notebook 3: Data Mining & Advanced Analytics**
- Implemented K-Means clustering for customer segmentation
- Performed cluster optimization using elbow method and silhouette scores
- Developed RFM-based customer profiling and segment characterization
- Executed market basket analysis using Apriori algorithm
- Generated association rules with confidence and lift metrics
- Prepared time series data for forecasting and trend analysis
- Validated mining results and created segment naming conventions
