# Deloitte-Australia-Data-Analytics-Virtual-Internship-

## 📌 Task 1 – Telemetry Data Analysis (Tableau)

**Requirement:**  
Analyze one month of telemetry data collected from 4 factories (Tokyo, Osaka, Berlin, Shenzhen) and 9 machine types to identify machine downtime.

**What I did:**  
- Imported JSON telemetry data into Tableau.  
- Created a calculated field **“Unhealthy”** (10 mins for each unhealthy status).  
- Built a bar chart showing **downtime per factory**.  
- Built another bar chart showing **downtime per device type**.  
- Combined both into a dashboard with interactive filtering.  

**Key Insights:**  
- Identified the **factory with the highest downtime**.  
- Pinpointed the **device types that failed most often** in that factory.  

## 📌 Task 2 – Equality Score Classification (Excel)

**Requirement:**  
Classify the provided Equality Score (range -100 to +100) into three categories:  
- **Fair** (score between -10 and +10 inclusive)  
- **Unfair** (score between -20 and -11 OR 11 and 20)  
- **Highly Discriminative** (score ≤ -21 or ≥ 21)

**What I did:**  
- Loaded the `Equality Table.xlsx` and created a new column **Equality Class** using Excel logical formulas (IFS + AND/OR).  
- Validated classification across factories and job roles to identify areas with most severe inequality.

**Outcome:**  
- Produced a clean classification file ready for further analysis and visualization.  
- Supported Deloitte’s forensic team by highlighting job roles and factories requiring deeper review.




