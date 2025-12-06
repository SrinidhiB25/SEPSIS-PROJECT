**SEPSIS_PROJECT OVERVIEW
Sepsis remains a major global public health challenge. In the United States, nearly 1.7 million people develop sepsis each year, and approximately 270,000 die from it. More than one-third of all in-hospital deaths are associated with sepsis. Globally, an estimated 30 million people develop sepsis annually, resulting in 6 million deaths.
In the U.S., sepsis management costs exceed $24 billion per year—about 13% of total hospital expenditures—with most costs driven by cases that develop during hospitalization. In low- and middle-income countries, the financial burden is compounded by limited resources and a higher risk of adverse outcomes.
Despite its prevalence, early and reliable identification of sepsis remains difficult due to its broad and syndromic presentation, often leading to delays in diagnosis and treatment. Overall, sepsis contributes significantly to morbidity, mortality, and healthcare spending worldwide.

OBJECTIVE :  To identify, predict, and reduce the progression of sepsis by analyzing patient data, detecting early warning signs, and improving clinical outcomes through timely intervention.
ABOUT DATA :  The Sepsis project involved the analysis of a large-scale dataset containing over 1.5 million data points from more than 40,000 ICU patients. The dataset included hourly clinical records, demographic details, and a sepsis label indicating the exact hour of diagnosis. In addition, the project incorporated bloodwork results for 34 critical biomarkers associated with sepsis, enabling a comprehensive evaluation of physiological patterns leading up to sepsis onset.
DEMOGRAPHIC ANALYSIS :  Utilized Calculated Fields, Level of Details Expressions(LOD) with the "FIXED" keyword to accurately classify patients into sepsis, non-sepsis





Dashboard displays patient distribution: 92.73% without sepsis and 7.27% with sepsis.
The primary goal is swift diagnosis and treatment for the non-sepsis patients to prevent sepsis development.
These patients were primarily admitted due to infections or SIRS.
Demographic analysis factors in age and gender, revealing a heightened sepsis risk in the 60-80 age group, with males at higher risk than females.
Impact Of Biomarker :  Sprint3_ImpactofbiomarkerFinal | Tableau Public 
Biomarker trends show clear differentiation between patient groups, highlighting potential predictive value for clinical outcomes. Correlation analysis indicates strong associations between biomarker levels and key maternal health indicators, supporting their role in early risk stratification.
Outlier detection reveals a small subset of patients with extreme biomarker values, suggesting the need for closer clinical monitoring or data validation.
Dashboard visualization confirms usability for stakeholders, offering an accessible format to track biomarker impact and guide decision-making in maternal health programs.


SIRS (Systemic inflammatory response syndrome) Analysis
SIRS_ANALYSIS | Tableau Public 

We understand that 22% of total patients in this data set got admitted with SIRS symptoms. It is hard to find the time of trigger since many patients may not keep track of the time when they start showing each symptom.
Over 55% of patients exhibit high heart rates and increased metabolic stress (RR). Around 2% of patients are admitted with Acute-phase Reactions (high temp & high WBC), which can be fatal. Within the first hour of admission, many patients show more than 2 SIRS symptoms, requiring immediate medical attention.
The percentage of new SIRS patients drops below 3% after 10 hours of admission, and it continues to decrease over time.










Utilized calculated fields, Level of Details Expressions(LOD) with the "FIXED" keyword to specifically target and identify the SIRS trigger hour for patients.
Implemented dummy axes technique and formatted cell colors to effectively highlight abnormal test results, enabling quick identification and analysis.
Added URL actions to implement email alerts, ensuring the prompt notification of responsible hospital staff when patients meet the pre-alert criteria, facilitating timely attention and response.
Septic Shock Analysis
SepticShockAnalysis | Tableau Public 

Septic shock is a severe, life-threatening condition with a low survival rate. It depends on your health, age, treatment, and organ failure. Without treatment, most don't survive. With it, about 30-40% can make it.
Criteria: SBP<90 mm Hg, MAP<60 mm Hg , Resp ≥ 22 breaths/mins,Lactate>2 mmol/L.
There were 473 cases of septic shock, and it was more common among individuals aged 71 to 80. This risk was particularly notable in both men and women aged 61 to 70.
Data Driven impact.....
This project demonstrates the significant impact of data analysis on patient care. By identifying crucial risk factors and sepsis-related patterns, we empower doctors to detect and treat this severe condition proactively, potentially saving lives and reducing hospital stays. This not only improves patient outcomes but also enhances ICU operational efficiency by up to 30%.





