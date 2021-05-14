# Dataset Description - Assignment 1

The original data is from [HealthData: Hospital Inpatient Discharges (SPARCS De-Identified)](https://healthdata.gov). The data provided is based on this, with some modifications.

The Statewide Planning and Research Cooperative System (SPARCS) Inpatient De-identified File contains discharge level detail on patient characteristics, diagnoses, treatments, services, and charges.

### Licence agreement: 

The dataset can only be used for the purpose of this assignment. Sharing or distributing this data or using this data for any other commercial or non-commercial purposes is prohibited.


### Data Fields

| Column   Name                | Attribute/Target | Description                                                                                                                                                                                                  |
|------------------------------|------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ID                           | N/A              | Unique number to represent patient ID                                                                                                                                                                        |
| HealthServiceArea            | N/A              | A description of the Health Service Area (HSA) in which the hospital is located. Capital/Adirondack, Central NY, Finger   Lakes, Hudson Valley, Long Island, New York City, Southern Tier, Western NY.       |
| Gender                       | Attribute 1      | Patient gender:   (M) Male, (F) Female, (U) Unknown.                                                                                                                                                         |
| Race                         | Attribute 2      | Patient race. Black/African American, Multi, Other Race, Unknown, White. Other Race   includes Native Americans and Asian/Pacific Islander.                                                                  |
| TypeOfAdmission              | Attribute 3      | A description of   the manner in which the patient was admitted to the health care facility:   Elective, Emergency, Newborn, Not Available, Trauma, Urgent.                                                  |
| CCSProcedureCode             | Attribute 4      | AHRQ Clinical Classification Software (CCS) ICD-9 Procedure Category Code                                                                                                                                    |
| APRSeverityOfIllnessCode     | Attribute 5      | All Patient  Refined Severity of Illness (APR SOI) Description: Minor (1), Moderate (2),   Major (3), Extreme (4)                                                                                            |
| PaymentTypology              | Attribute 6      | A description of the type of payment for this occurrence.                                                                                                                                                    |
| BirthWeight                  | Attribute 7      | The neonate birth weight in grams; rounded to nearest 100g.                                                                                                                                                  |
| EmergencyDepartmentIndicator | Attribute 8      | Emergency Department Indicator is set based on the submitted revenue codes. If the   record contained an Emergency Department revenue code of 045X, the indicator   is set to "Y", otherwise it will be “N”. |
| AverageCostInCounty          | Attribute 9      | Average hospitalization Cost In County of the patient                                                                                                                                                        |
| AverageChargesInCounty       | Attribute 10     | Average medical Charges In County of the patient                                                                                                                                                             |
| AverageCostInFacility        | Attribute 11     | Average Cost In Facility                                                                                                                                                                                     |
| AverageChargesInFacility     | Attribute 12     | Average Charges In Facility                                                                                                                                                                                  |
| AverageIncomeInZipCode       | Attribute 13     | Average Income In Zip Code                                                                                                                                                                                   |
| LengthOfStay                 | target           | The total number  of patient days at an acute level and/or other than acute care level. Need to be transformed to match the task class 0 id LengthOfStay < 4 and class 1 otherwise                           |

