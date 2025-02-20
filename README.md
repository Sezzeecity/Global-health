# 🌍 Global Health Insights

## 📌 Project Overview
**Global Health Insights** is a Power BI project that provides an in-depth analysis of global healthcare trends, disease demographics, and the effectiveness of healthcare systems. The dashboard visualizes key indicators such as:
- Disease prevalence rates
- Healthcare accessibility
- Treatment costs and recovery rates
- Population impact by age, gender, and region

## 🏥 Key Insights

### **1️⃣ Socioeconomic & Environmental Impact**
- A strong correlation between **per capita income** and **healthcare access** was observed.
- Higher education levels contribute to better healthcare accessibility.
- Urbanization influences recovery rates in different regions.

![{7C484B2D-20B4-46EA-8093-43AA98BA8DE9} png](https://github.com/user-attachments/assets/fe7e6804-48db-421c-b4b3-ea8779de44a7)

### **2️⃣ Disease Demographics & Population Impact**
- Some diseases disproportionately affect certain **age groups and genders**.
- Mortality rates vary significantly by country and disease type.
- Yearly trends indicate fluctuations in **population-affected rates**.

![{998067AB-3B0B-4459-A56B-22BCED2D88EA} png](https://github.com/user-attachments/assets/2b0a0701-47e0-454c-a284-34c7ba85e240)

### **3️⃣ Healthcare System Effectiveness**
- **Doctors per 1000 people, hospital beds availability, and recovery rates** vary across countries.
- **Surgery and therapy treatments** yield better recovery outcomes.
- Disability-Adjusted Life Years (**DALYs**) show the long-term impact of diseases.

![{57E13453-E5A9-4D61-8A09-17E81045105F} png](https://github.com/user-attachments/assets/e85db6fb-2b37-40a8-9bf7-811e758e8d52)

### **4️⃣ Global Disease Overview**
- The **total cost of treatment** is in billions, reflecting the healthcare financial burden.
- Recovery rates are improving in some areas but declining in others.
- **Mortality rates** reveal disparities in healthcare infrastructure globally.

![{A1F8A579-5EEF-4A18-81E8-2C1867593480} png](https://github.com/user-attachments/assets/5f6c4f84-6d81-4366-9d3f-150e971da18f)

## 🛠️ Data Cleaning Process
To ensure data accuracy and consistency, the following data cleaning steps were performed:

1. **Handling Missing and Inconsistent Data**
   - Missing values in **age, income, and treatment cost** were replaced with the **median** to maintain data integrity.
   - Health condition data with blank entries were labeled as `"Unknown"` for consistency.
   - Negative or invalid values in **treatment cost and mortality rates** were corrected.

2. **Standardization of Formats**
   - All date columns were converted to **ISO format (YYYY-MM-DD)** for uniformity.
   - Name inconsistencies (e.g., `"uSa"`, `"usa"`) were standardized to `"USA"`.
   - Disease names with variations (e.g., `"COVID-19"`, `"Covid 19"`) were unified.

3. **Data Type Corrections**
   - **Age, income, and treatment cost** were converted to **numeric** formats.
   - **Date columns** were converted into proper date formats for time-series analysis.
   - **Categorical values** (e.g., `"Yes"`, `"No"`, `"Unknown"`) were standardized.

4. **Duplicate Removal**
   - Duplicate records were identified and removed based on **unique patient IDs**.
   - Only the most recent record per patient was retained.

5. **Handling Outliers**
   - Extreme values in **healthcare access and treatment costs** were analyzed.
   - Values significantly deviating from the mean were adjusted or flagged for review.

## 🔍 Recommendations
Based on the analysis, the following recommendations were made:

### **1️⃣ Improve Healthcare Access in Low-Income Regions**
- Countries with **low per capita income** and **low recovery rates** should receive targeted healthcare funding.
- Investments in **public healthcare infrastructure** will improve accessibility.

### **2️⃣ Increase Awareness & Early Diagnosis**
- Regions with **high mortality rates** should focus on **early disease detection programs**.
- Government and healthcare providers should run **educational campaigns** on disease prevention.

### **3️⃣ Optimize Treatment Costs & Efficiency**
- Countries with **high treatment costs** but **low recovery rates** need policy interventions.
- Implementing **cost-effective healthcare solutions** can reduce financial burdens.

### **4️⃣ Enhance Medical Workforce & Infrastructure**
- Countries with **low doctor-to-patient ratios** should invest in **medical training programs**.
- Increasing **hospital bed availability** can improve recovery rates in overburdened regions.





