# Global Life Expectancy & Health Metrics Analysis

## About the Project
This project explores life expectancy trends, mortality rates, and health expenditures across various countries. Using **Power BI**, the analysis provides insights into how economic and healthcare factors influence life expectancy worldwide.  

The dataset used in this project is sourced from **Google Sheets**, offering a comprehensive look at multiple health and economic indicators.

---

## **Objectives**
- Analyze global life expectancy trends over time.  
- Examine the relationship between health expenditures and mortality rates.  
- Identify economic and healthcare factors affecting life expectancy and global diphtheria cases.  
- Provide interactive visualizations for better understanding and exploration.

---

## **Dataset Used**
The dataset consists of key metrics related to health, economy, and mortality.  

📄 **[Life Expectancy Dataset](https://docs.google.com/spreadsheets/d/e/2PACX-1vTJ38xWbXCqHfm1m7ny-27nKHlrsZhPldkfRf2dWy-Nv2jJLcrYQMpGbhuBcr1dCkbsacrPs0SDojW4/pubhtml)**  

### **Key Data Columns**
- **Country** – Name of the country.  
- **Year** – The year of the record.  
- **Status** – Whether the country is developed or developing.  
- **Life Expectancy** – Average life expectancy in years.  
- **Adult Mortality** – Probability of dying between ages 15 and 60 per 1,000 population.  
- **Infant Deaths** – Number of infant deaths per 1,000 live births.  
- **Alcohol** – Alcohol consumption per capita.  
- **Health Expenditure (%)** – Percentage of GDP spent on healthcare.  
- **Hepatitis B & Measles (%)** – Vaccination coverage rates.  
- **BMI** – Average body mass index.  
- **Under-Five Deaths** – Mortality rate of children under five.  
- **Polio & Diphtheria (%)** – Vaccination rates.  
- **HIV/AIDS (%)** – HIV/AIDS prevalence rate.  
- **GDP** – Gross domestic product per capita.  
- **Population** – Total country population.  
- **Income Composition** – Income index measuring access to essential resources.  
- **Schooling** – Average years of schooling per person.  

---

## **Questions**
- How do life expectancy trends differ across countries?  
- Does higher health expenditure correlate with lower mortality rates?  
- What role do economic factors play in longevity?  
- Which countries experience the highest child and adult mortality rates?  
- How do GDP, education, and healthcare spending influence life expectancy?  

---

## **Visualizations**
### **Proposed Power BI Charts**
📌 **Trend Analysis:**  
✔ Line charts for **life expectancy over time**.  
✔ Heat maps for **mortality distribution by region**.  
✔ Scatter plots for **GDP vs. life expectancy correlations**.  

📌 **Comparative Insights:**  
✔ Bar charts comparing **developed vs. developing countries**.  
✔ Geographic maps for **health and economic disparities**.  
✔ Interactive filters for **country and year selection**.

---
## Dashboard

### Preview of Dashboards
📊 This project includes the following Power BI dashboards:  

### **1️⃣ Mortality Rates and Health Expenditure**  
- Examines the relationship between **health spending and mortality rates.  
- Analyzes trends in adult and infant mortality across different regions.
    
![Mortality Rates & Health Expenditure](https://github.com/ludreinsalvador/life-expectancy_data_analysis_dashboards/blob/main/mortality-rates_health-expenditures.png)  

### **2️⃣ Global Life Expectancy and Economic Metrics**  
- Explores how GDP, income composition, and education levels affect life expectancy.  
- Compares developed vs. developing countries in terms of longevity.
   
![Global Life Expectancy Analysis](https://github.com/ludreinsalvador/life-expectancy_data_analysis_dashboards/blob/main/global-life-expectancy.png)  

### **3️⃣ Global Diphtheria and Mortality Analysis**  
- Investigates the impact of diphtheria vaccination rates on mortality trends.  
- Highlights patterns in childhood mortality and vaccine-preventable diseases.
  
![Diphtheria Cases & Mortality Analysis](https://github.com/ludreinsalvador/life-expectancy_data_analysis_dashboards/blob/main/diptheria-cases_analysis.png)  

---

## **Data Processing**
### **Data Cleaning**
- **Filled missing values** with appropriate estimates to avoid gaps.  
- **Converted categorical values** (e.g., "Developed" vs. "Developing") for analysis.  
- **Normalized numerical data** for trend comparisons.  

### **Data Transformation**
- Merged economic and healthcare data for comprehensive insights.  
- Created **calculated columns** such as:
  - Combined expenditure
  - Under-Five mortality rate
  - Diphtheria cases per year
  - Diphtheria cases to adult mortality ratio

- Created **calculated measures** such as:
- Average life expectancy
- Sum expenditure
- Average diphtheria cases
- Total diphtheria cases
- Total no. of countries with diphtheria

---

## **Conclusion**
This project provides valuable insights into **global health trends, mortality rates, and economic impacts on life expectancy**. By leveraging **Power BI visualizations**, it enables policymakers and researchers to identify **key health patterns** and areas needing intervention.  
