# HEALTHCARE ANALYTICS DASHBOARD

Dashboard:

![Image](https://github.com/quafiya-rahim/Healthcare-Analytics-Dashboard/blob/main/healthcare_dashboard.PNG)



## 1. Data Overview

 This project analyzes patient data for individuals suffering from various kidney diseases across.The 
 analysis focuses on patients undergoing dialysis, with detailed insights into healthcare facilities, chain organizations, and dialysis stations. Additionally, 
 the project examines payment modes to identify any discounts or payment reductions and analyzes their impact.
 The dataset used for analysis contains several columns related to patient's information as stated below:

* Patient_ID :Unique ID of each patient.
* Facility_Name : Hospital name.
* Chain_Organization : Organisation that owns the facility.
* Dialysis_Station_ID : Station where dialysis is done.
* Disease_Type : Types of kidney disease.
* Payment_Mode : Payment methods
* Total_Cost : Original treatment cost.
* Discount_Applied : Discount amount given.
* Final_Amount : Final amount after discount.
* Visit_Date : Date of visit.
* Has_Discount : Indicates whether patient received any discount or not.
                 True -> Discount was applied
                 False -> No discount was applied


The primary objective is to derive data-driven insights by calculating critical metrics such as:

* Total revenue
* Total patients
* Revenue lost due to discount
* Average discount amount
* Patients per facility
* Monthly Revenue
* No.of facilities belong to each chain oraganisation
* Most used dialysis stations
* Underutilised dialysis stations
* Patients payment methods
  


## 2. Data Cleaning & Pre-Processing (Python – Pandas)

![Image](https://github.com/quafiya-rahim/Healthcare-Analytics-Dashboard/blob/main/data_cleaning_pandas.PNG)

* Converted columns to appropriate data types to ensure consistency and accuracy.

* Handled missing values .

* Identified and removed duplicate records to maintain data integrity.


## 2. Data Transformation (Power BI – Power Query)

![Image](https://github.com/quafiya-rahim/Healthcare-Analytics-Dashboard/blob/main/data_cleaning.PNG)

* Removed irrelevant and unnecessary columns to reduce data noise.

* Standardized text formats by converting lowercase to uppercase and vice versa where required.

* Prepared refined datasets for efficient visualization and analysis in Power BI.



# 3. EDA - Exploratory data analysis Key Insights
1️ Patients per facility(Hospitals)
* CityCare Hospital has the highest patient count (22), indicating higher patient inflow and utilization.
* MediLife Center, Wellness Clinic, and Unknown facilities each account for 11 patients, showing relatively balanced 
  distribution among secondary facilities.
* Suggests that patient preference or referral patterns may be stronger for CityCare Hospital.
![Image](https://github.com/user-attachments/assets/8ae72886-178f-450b-81a6-03de4785efc0)

2️ Monthly Revenue
* Revenue remains relatively stable between 19K–25K throughout most of 2024.
* Peak revenue observed in July (25K), indicating possible seasonal or operational efficiency improvements.
* A sharp decline to 10K in January 2025 suggests seasonal slowdown, reporting cut-off, or reduced patient visits.
* Overall trend reflects consistent revenue generation with occasional fluctuations.
![Image](https://github.com/user-attachments/assets/5f1cc09c-0d02-44e3-aa13-7be0185eda0d)

3️ Most utilised and underutilised dialysis stations
* Station_4 has the highest usage (18 sessions), indicating higher demand or better operational efficiency.
* Station_2 and Station_5 show lower utilization, suggesting scope for workload redistribution or optimization.
![Image](https://github.com/user-attachments/assets/f57ad014-1863-4520-a8f5-2c1eef7f9932)

4 Patients payment methods
* Insurance dominates payments (40%), highlighting dependency on insured patients.
* Cash, Government Aid, and Unknown modes each contribute ~20%, indicating diversified payment sources.
![Image](https://github.com/user-attachments/assets/31bcffe3-a1b2-4beb-b12b-a11ccc2a7af7)

6 No.of facilities belong to each chain oraganisations
* HealthPlus chain has the highest facility presence, contributing significantly to patient volume.
* MediLife Group and Independent facilities show moderate participation.
* Presence of Unknown facilities indicates possible data gaps or unclassified entities.
![Image](https://github.com/user-attachments/assets/1d240856-dbd4-4a50-a177-e5794df5526f)



## 4.Insights and Report


* Patient Distribution: CityCare Hospital records the highest patient volume, indicating strong patient
  preference or better service availability compared to other facilities.
* Revenue Stability: Monthly revenue remains consistent throughout most of 2024, reflecting steady patient
  inflow and operational efficiency.Peak revenue observed mid-year (June–July), while a noticeable decline in early 2025 indicates seasonal or reduced patient visits.
* Payment Dependency: Insurance is the most dominant payment mode,highlighting dependency on third-party payers for 
  revenue generation.Cash and government aid contribute moderately.
* Operational Imbalance: Dialysis station usage is uneven,certain dialysis stations show higher usage, while others remain underutilized, pointing to 
  operational inefficiencies.
* Revenue Leakage: Discounts contribute to measurable revenue loss, affecting overall financial efficiency.
* Facility Chain Impact: HealthPlus facilities contribute the most to patient and service volume, emphasizing the importance 
  of strong healthcare networks.


# Overall Conclusion 

  This healthcare analytics project transformed raw patient and operational data into actionable insights supporting both 
  clinical and financial decision-making. The analysis identified key patterns in patient distribution, facility performance,
  dialysis utilization, and revenue flow, helping uncover operational inefficiencies and revenue leakages.
  Through interactive visualizations, the dashboard enables stakeholders to monitor performance, optimize resources, and 
  improve revenue efficiency. Overall, the project demonstrates the practical use of data analytics to support informed 
  decision-making in healthcare operations.


# Final Recommendations:
✅ Optimize Facility Utilization-
Redistribute patient load across facilities through improved scheduling and referral mechanisms to prevent overcrowding at high-volume hospitals.

✅ Enhance Dialysis Station Efficiency-
Balance dialysis station workloads by reallocating patients and staff to underutilized stations, improving overall operational throughput.

✅ Strengthen Insurance Collaboration –
Work closely with insurance providers and simplify claim processes to receive payments faster and maintain steady cash flow.

✅ Control Revenue Leakage-
Review discount policies and introduce approval thresholds to minimize unnecessary revenue loss without impacting patient affordability.

✅ Diversify Payment Channels-
Encourage transparent cash and government-aided payment options to reduce over-reliance on insurance-based revenue streams.

