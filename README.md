# **Lung Cancer Analysis Project**

- Lung cancer remains one of the leading causes of cancer-related deaths worldwide, with late diagnosis significantly reducing survival rates. Key risk factors such as smoking, passive smoking, air pollution, and genetic predisposition contribute to its prevalence. Early identification of high-risk individuals and understanding survival patterns are essential for improving patient outcomes.

- This project leverages **SQL and Power BI** for data analysis and visualization, utilizing patient records to uncover insights into risk factors, diagnosis trends, survival rates, and treatment effectiveness. The goal is to identify key patterns, assess the impact of different factors on lung cancer progression, and provide data-driven insights to aid early detection and treatment planning.

---

## **Project Objectives**

- **Patient Data Segmentation:** Categorize patient records based on lung cancer diagnosis, smoking status, age, gender, and geography.
- **Risk Factor Analysis:** Assess the impact of smoking, passive smoking, and air pollution on lung cancer prevalence.
- **Cancer Progression Insights:** Identify unique cancer stages and analyze survival years based on disease progression.
- **Mortality Rate Evaluation:** Determine death rates based on early detection and treatment effectiveness.
- **Global Prevalence Ranking:** Identify countries with the highest lung cancer rates and mortality statistics.
- **Environmental & Occupational Risk Assessment:** Establish correlations between air pollution, occupational exposure, and lung cancer risk.
- **Treatment Effectiveness Analysis:** Assess the impact of treatment types and early detection on survival rates.
- **Gender-Based Analysis:** Compare lung cancer prevalence across men and women in different regions.

---

## **Dataset Overview**

- **Demographic Information:** ID, Country, Population Size, Age, Gender
- **Lifestyle & Environmental Factors:** Smoker, Years of Smoking, Cigarettes per Day, Passive Smoker, Air Pollution Exposure, Occupational Exposure, Indoor Pollution
- **Medical History & Diagnosis:** Family History, Lung Cancer Diagnosis, Cancer Stage, Adenocarcinoma Type
- **Healthcare & Treatment:** Healthcare Access, Early Detection, Treatment Type
- **Patient Outcomes & Statistics:** Survival Years, Developed or Developing Country, Annual Lung Cancer Deaths, Lung Cancer Prevalence Rate, Mortality Rate
- **Dataset Size:** 23 Columns, 2,206,332 Records

---

## Tools Utilized in this Project

- Microsoft SQL SERVER & SQL Server Management Studio 

- Power BI Destop

- Published in Power BI Service

## **Data Cleaning & Preprocessing**

 **Data Validation & Standardization** – Used **SQL** queries to identify and correct inconsistencies in data types, column formats, and categorical values to ensure uniformity.
 **Handling Missing & Duplicate Values** – Checked for null entries and duplicate records, applying appropriate cleaning techniques like imputation or removal to maintain data integrity.
 **Ensuring Data Consistency** – Standardized naming conventions, date formats, and categorical labels to create a structured and reliable dataset for analysis.

---
## Project Files

- Pbix Files : <a href = "Lung Cancer Analysis Project.pbix"> Power BI File</a>

- Dataset file: <a href = "\lung_cancer_Dataset.csv"> Lung Cancer Dataset</a>

- PPT created in this Project: <a href = "Lung Cancer Analysis  Project.pdf"> Presentation </a>

###

### **Key Insights & Findings**
![Screenshot 2025-02-24 154613](https://github.com/user-attachments/assets/3b0148d5-4203-4e2b-89cf-f7dfc1504ea7)
![Screenshot 2025-02-24 154537](https://github.com/user-attachments/assets/b6e17faf-b143-43ba-98cc-8c139012c24f)
![Screenshot 2025-02-24 154613](https://github.com/user-attachments/assets/1562ba96-5a76-4c1b-9b21-ba306dd14c5a)

### **High-Level Observations on Lung Cancer:**

- **Total Lung Cancer Cases:** 8,961 – Highlights the disease’s prevalence.
- **Average Age of Patients:** 52.66 years – Most cases occur in middle-aged or older individuals.
- **Smokers with Lung Cancer:** 7.07% – Indicates other factors (environmental, genetic) also play a role.
- **Average Mortality Rate:** 75.09% – High mortality underscores the need for early detection.

### **Geographic Distribution:**

- High cases in **North America, Europe, and Asia**, likely due to industrialization, air pollution, and smoking.

### **Age-Wise Distribution:**

- Cases remain consistent from ages **20–79 (1,300–1,400 per group)**.
- Steep decline in cases (836) at **80–85 age group**, likely due to mortality before reaching this age.
- **Cigarette consumption is constant (~33K) until it declines sharply in the 80+ age group (20.2K).**

### **Air Pollution & Mortality Impact:**

- **Mortality Rate by Air Pollution Levels:**
    - **High:** 75.23%
    - **Medium:** 75.08%
    - **Low:** 74.79%
- **Insight:** Pollution worsens outcomes, but **smoking and late detection** play a bigger role.

### **Smoking & Lung Cancer Risk:**

- **Total Smokers:** 88,341 – Indicates a large high-risk population.
- **Early Detection Rate:** 28.37% – Over 70% of lung cancer cases are detected late, reducing survival rates.
- **Passive Smoking Impact:**
    - 1 in 3 lung cancer cases (30.06%) occur in passive smokers.
    - Non-smokers (69.74%) also develop lung cancer, proving other risk factors matter.

### **Air Pollution vs. Smoking Risk:**

- Highest lung cancer cases occur in **medium & high pollution exposure** areas.
- Even in **low pollution areas, smokers still have a high risk**, proving smoking is a dominant risk factor.

### **Gender-Based Analysis:**

- **Men (5,332 cases, 59.5%)** are more affected than **women (3,629 cases, 40.5%)**.
- **Smoker’s Lung Cancer Cases:**
    - **Males:** 4,309 cases (68.96%)
    - **Females:** 1,940 cases (31.04%)
- **Insight:** Smoking has a stronger impact on men, likely due to **historical smoking trends, occupational hazards, and lifestyle.**

---

### **Recommendations**

- **Age-Based Screening:** Since cases remain consistent across ages **20–79**, **early detection should start in the 20s or 30s**, not just for people aged 50+.
- **Air Pollution Awareness & Policies:** Although mortality is high across all pollution levels, **air pollution control should be prioritized** to reduce compounding risks.
- **Targeted Male-Focused Anti-Smoking Campaigns:** 68.96% of male lung cancer cases are smoking-related → **Anti-smoking efforts should be specifically aggressive toward men.**
- **Stricter Passive Smoking Regulations:** 30.06% of passive smokers develop lung cancer → **Public smoking bans, stricter home & office rules needed to reduce second-hand smoke exposure.**
- **Stronger Early Detection Strategies:** Only **28.37% of lung cancer cases are detected early**, meaning **routine screenings (CT scans) should be mandatory for high-risk groups** (smokers, passive smokers, and pollution-exposed individuals).
- **Occupational Risk Prevention:** Males are disproportionately affected, likely due to **workplace exposure (factories, mining, construction).**
- **Stronger safety measures, improved ventilation, and regular health checkups** should be implemented in high-risk jobs.
- **Pollution & Smoking Control Together:** Air pollution **increases cancer risk for both smokers & non-smokers** → Governments should **control industrial emissions, promote clean energy, and plant more green spaces.**
