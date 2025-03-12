# Healthcare-Analytics-Transforming-Data-into-Actionable-Insights
## Project Overview  
This project focuses on transforming raw healthcare data into actionable insights to optimize financial performance, improve patient care, and enhance operational efficiency. By leveraging **Python**, **Power Query**, and **Power BI**, we cleaned, analyzed, and visualized data to uncover trends and provide data-driven recommendations.  

---

## Key Features  
- **Data Cleaning & Transformation**: Handled missing values and inconsistencies using Python and Power Query.  
- **Regression Imputation**: Applied linear regression to impute missing insurance coverage values.  
- **Interactive Dashboards**: Built Power BI dashboards for financial, operational, and demographic insights.  
- **DAX Measures**: Created advanced calculations for revenue, coverage shortfalls, and patient satisfaction.  

---

## Tools & Technologies  
- **Python**: For data cleaning, regression imputation, and analysis.  
- **Power Query**: For ETL (Extract, Transform, Load) processes.  
- **Power BI**: For creating interactive dashboards and visualizations.  
- **DAX**: For advanced calculations and measures.  

---

## ETL Process  
1. **Extraction**: Data was extracted from PDF reports and CSV files.  
2. **Transformation**:  
   - Standardized provider names and corrected date formats using Power Query.  
   - Merged tables to create a unified dataset.  
3. **Imputation**: Used Python's `scikit-learn` library to impute missing insurance coverage values with linear regression.  
4. **Loading**: Loaded the cleaned data into Power BI for visualization.  

---

## Dashboards & Insights  
### 1. Healthcare Financial Overview  
- Analyzed revenue, treatment costs, and unpaid bills.  
- Identified a **38% unpaid bill rate**, risking cash flow.  

### 2. Patient Visit Analysis  
- Visualized visit trends, service types, and diagnosis frequency.  
- Found **Hypertension** as the most common diagnosis.  

### 3. Insurance Provider Performance  
- Highlighted coverage shortfalls by provider and department.  
- **Cardiology** and **Orthopedics** had the highest shortfalls.  

### 4. Patient Demographics  
- Analyzed patient age, gender, and race trends.  
- Identified disparities in emergency visits and treatment costs.  

### 5. Diagnosis & Procedure Efficiency  
- Tracked costly procedures (e.g., CT Scans, MRIs) and follow-up rates.  
- Found low follow-up rates for chronic conditions like **Migraines**.  

---

## Recommendations  
1. **Reduce Financial Leakage**: Renegotiate insurance contracts and automate payment reminders.  
2. **Optimize Operations**: Train staff on billing best practices and promote telehealth for follow-ups.  
3. **Enhance Patient Care**: Launch preventive care programs and improve cost transparency.  
4. **Control Procedure Costs**: Substitute costly procedures with cost-effective alternatives where possible.  
