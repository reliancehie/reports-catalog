![](pictures/reliance_logo.png)

# Reliance Insight Report Catalog

### Click on a report name below for a detailed description 

## [A. OHA CCO Incentive and Performance Reports](#oha-cco-incentive-and-performance-reports)

| Report Name    | Description               |
| -------------  |-------------              |
| [Diabetes: HbA1c Poor Control](#diabetes-hba1c-poor-control)        | Percentage of patients 18-75 years of age with diabetes who had hemoglobin A1c > 9.0% during the measurement period.         |
| [Controlling Hypertension](#controlling-hypertension)  | Percentage of patients 18-85 years of age who had a diagnosis of hypertension and whose blood pressure was adequately controlled (<140/90mmHg) during the measurement period.        |
| [Disparity Measure: Emergency Department Utilization for Individuals Experiencing Mental Illness ]()  | Rate of visits to an emergency department among adult members experiencing mental illness.        |
| [Childhood Immunization Status]()  | Percentage of children 2 years of age who had four diphtheria, tetanus and acellular pertussis (DTaP); three polio (IPV), one measles, mumps and rubella (MMR); three H influenza type B (HiB); three hepatitis B (Hep B); one chicken pox (VZV); four pneumococcal conjugate (PCV); one hepatitis A (Hep A); two or three rotavirus (RV); and two influenza (flu) vaccines by their second birthday       |
| [Effective Contraceptive Use]()        | Percentage of women (ages 15-50) with evidence of one of the most effective or moderately effective contraceptive methods during the measurement year: IUD, implant, contraception injection, contraceptive pills, sterilization, patch, ring, or diaphragm.         |

## [B. QCDR Reports](#qcdr-reports)
| Report Name    | Description               |
| -------------  |-------------              |
| [Diabetes: Hemoglobin A1c (HbA1c) Poor Control (>9%)]()        | Percentage of patients 18-75 years of age with diabetes who had hemoglobin A1c > 9.0% during the measurement period.         |
| [Breast Cancer Screening]() | Percentage of women 50-74 years of age who had a mammogram to screen for breast cancer. |
| [Colorectal Cancer Screening]() | Percentage of adults 50-75 years of age who had appropriate screening for colorectal cancer. |
| [Preventive Care and Screening: Body Mass Index (BMI) Screening and Follow-Up Plan]() | Percentage of patients aged 18 years and older with a BMI documented during the current encounter or during the previous six months AND with a BMI outside of normal parameters, a follow-up plan is documented during the encounter or during the previous six months of the current encounter.  Normal Parameters: Age 18 years and older BMI => 18.5 and < 25 kg/m2 |
| [Ischemic Vascular Disease (IVD): Use of Aspirin or Another Antiplatelet]() | Percentage of patients 18 years of age and older who were diagnosed with acute myocardial infarction (AMI), coronary artery bypass graft (CABG) or percutaneous coronary interventions (PCI) in the 12 months prior to the measurement period, or who had an active diagnosis of ischemic vascular disease (IVD) during the measurement period, and who had documentation of use of aspirin or another antiplatelet during the measurement period. |
| [Preventive Care and Screening: Tobacco Use: Screening and Cessation Intervention]() | Percentage of patients aged 18 years and older who were screened for tobacco use one or more times within 24 months AND who received cessation counseling intervention if identified as a tobacco user. |
| [Controlling High Blood Pressure]() | Percentage of patients 18-85 years of age who had a diagnosis of hypertension and whose blood pressure was adequately controlled (<140/90mmHg) during the measurement period. |
| [Cervical Cancer Screening]() | Percentage of women 21-64 years of age who were screened for cervical cancer using either of the following criteria: * Women age 21-64 who had cervical cytology performed every 3 years * Women age 30-64 who had cervical cytology/human papillomavirus (HPV) co-testing performed every 5 years |

## [C. Custom Reports](#custom-reports)
| Report Name    | Description               |
| -------------  |-------------              |
| [HepC Dx and Hepatic Labs]() | All patients with HepC, their diagnosis labs and liver function labs |
| [Diabetes by Type]() | Based on CCO incentive measure report but splits out Type 1 vs Type 2 | 
| [Positive Pregnancy]() | Real time identification of pregnant population |  

## [D. Appendix](#appendix)
[Consolidated Patient Chart](#consolidated-patient-chart)  
[Glossary](#glossary)


## OHA CCO Incentive and Performance Reports  
The Oregon Health Authority (OHA) uses quality health metrics to show how well Coordinated Care Organizations (CCOs) are improving care, making quality care accessible, eliminating health disparities, and curbing the rising cost of health care. These outcome and quality measures are developed by the OHA Metrics and Scoring Committee and can be found here:   
<http://www.oregon.gov/OHA/HPA/ANALYTICS/Pages/CCO-Baseline-Data.aspx>  
Many of these reports are based off of the CMS 2017 Performance Period EP/EC eCQMs: <https://ecqi.healthit.gov/eligible-professional-eligible-clinician-ecqms/2017-performance-period-epec-ecqms>   
The default measurement period for the following reports is Calendar Year 2017, but the user can choose a measurement period of their choice.

### Diabetes: HbA1c Poor Control
**Measure Description**  
Percentage of patients 18-75 years of age with diabetes who had hemoglobin A1c > 9.0% during the measurement period.   
OHA 2017 Benchmark Measure Ratio (total numerator hits/total denominator hits) is 19%.  
**Denominator**  
Patients 18-75 years of age who had a diagnosis of diabetes during or any time prior to the measurement period and who received a qualifying outpatient service during the measurement period.  
**Numerator**  
Patients whose most recent HbA1c level (performed during the measurement period) is >9.0%.  
**Data Sources**  
ADTs, CCDs, LABs, and Encounters   
**Input Parameters**   
Start Date, End Date, and Records to Display Below  
**Output**  
Total denominator hits, total numerator hits, measure ratio (total numerator hits/total denominator hits), stacked bar chart of measure ratio, distribution plot of HbA1c values in denominator population, list of patients that meet denominator and numerator requirements.  
OHA Format CSV Download and All Data CSV Download (contains all column headings below)  
**Example Output**  
![](pictures/diabetes_chart.png)  
**Column headings**  
![](pictures/diabetes_fields.png)  
or in Markdown style:  

| | | | | 
|:-:|:-:|:-:|:-:|
|mpid_CPC|patient_date_of_birth|sex|patient_medicaid_id|sending_facility|
date_of_service_denom|sending_facility_num|date_of_service_num|HbA1c|provider_name|
ordering_provider|meets_denominator|meets_numerator|measurement_period_begin|measurement_period_end|


**Link to Measure Specifications**  
<http://www.oregon.gov/oha/HPA/ANALYTICS/CCOData/Diabetes%20HbA1c%20Poor%20Control%20-%202017%20%28revised%20Feb%202017%29.pdf>

### Controlling Hypertension

## QCDR Reports

## Custom Reports

## Appendix

### Consolidated Patient Chart  
The Consolidated Patient Chart (CPC) is a tool that allows users to more easily access patient records. CPC consists of three main sections: Summary, a quick overview of the patient; History, a timeline and charts of the patient's measurements; and Details, an in-depth analysis of the records.  

### Glossary 