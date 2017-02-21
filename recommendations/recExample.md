[recIndex] (https://github.com/johnnybender/adastandards2016/blob/master/index/recIndex.md)

### **Test for undiagnosed type 2 diabetes at the first prenatal visit in those with risk factors, using standard diagnostic criteria.**
* Recommendation 27
* Evidence: B
* Category: Classification and Diagnosis of Diabetes: Gestational Diabetes Mellitus

#### ICD-9 Codes:

Description | Codes
----------- | -----
Type 2 Diabetes | 250.0, 250.00, 250.02, 250.1, 250.10, 250.12, 250.2, 250.20, 250.22, 250.3, 250.30, 250.32, 250.4, 250.40, 250.42, 250.5, 250.50, 250.52, 250.6, 250.60, 250.62, 250.7, 250.70, 250.72, 250.8, 250.80, 250.82, 250.9, 250.90, 250.92
Pre-natal visit | V65.11
Supervision of normal first pregnancy | V22.0
Example | E11.610	E11.44	E11.36	E11.22	E11.52	E11.43	E11.37X3	E11.37X2	E11.37X1	E11.37X9	E11.41	E11.620	E11.42	E11.40	E11.51	E11.621	E11.65	E11.01	E11.00	E11.641	E11.649	E11.21	E11.321	E11.3213	E11.3212	E11.3211	E11.3219	E11.329	E11.3293	E11.3292	E11.3291	E11.3299	E11.331	E11.3313	E11.3312	E11.3311	E11.3319	E11.339	E11.3393	E11.3392	E11.3391	E11.3399	E11.59	E11.618	E11.49	E11.39	E11.638	E11.628	E11.622	E11.69	E11.630	E11.3543	E11.3542	E11.3541	E11.3549	E11.351	E11.3513	E11.3512	E11.3511	E11.3519	E11.3523	E11.3522	E11.3521	E11.3529	E11.3533	E11.3532	E11.3531	E11.3539	E11.359	E11.3593	E11.3592	E11.3591	E11.3599	E11.29	E11.341	E11.3413	E11.3412	E11.3411	E11.3419	E11.349	E11.3493	E11.3492	E11.3491	E11.3499	E11.3553	E11.3552	E11.3551	E11.3559	E11.8	E11.311	E11.319	E11.9

#### ICD-10 Codes:

Description | Codes
----------- | -----
Type 2 Diabetes | E11.*
First prenatal visit | Z34.*

#### LOINC Codes:

Description | Codes
----------- | -----
HbA1C | 4548-4

#### HCPCS Codes:

Description | Codes
----------- | -----
HbA1c Test | 496
FPG Test | 483

#### CPT Codes:

Description | Codes
----------- | -----
HbA1c Test | 83036
FPG Test | 82947

#### SNOMED Codes:

Description | Codes
----------- | -----
HbA1c | 43396009

#### Tables Referenced:

Description | Codes
----------- | -----
Poss. Risk Factors | Table 2.2

#### Modules:

Module |
------ |
[Template] (https://github.com/johnnybender/adastandards2017/blob/master/modules/Template) |
Age >= 18 YO |
Table 2.2: ID8: Overweight/Obese |
Table 2.2: ID8: ICD10: Overweight/Obese |
Table 2.2: ID8: LOINC: 39156-5 |
ID17: Table 2.2: ICD9: Cardisease |
ID17: Table 2.2: ICD10: Cardisease |

#### Implementation:
((Template) OR (Age >= 18 YO) OR (Table 2.2: ID8: Overweight/Obese)) AND ((ID17: Table 2.2: ICD9: Cardisease) OR (ID17: Table 2.2: ICD10: Cardisease))
