# Heart Failure Analysis

## Brief Summary of dataset
This analysis is on a dataset with hospital admission data for 299 patients. All of these patients were admitted for heart failure. Some of these patients recovered and were discharged, while others passed away. This analysis will go through data cleaning, data exploration, and modeling to decipher whether or not a patient will die during their hospital admission.   


## Summary of variables
The columns in the data are as follows:
-  patient_identifier - Unique patient identifier
- age - Patient age in years
- anemia - Whether or not the patient had anemia upon admission
- creatinine_phosphokinase - Level of the CPK enzyme in the blood (mcg/L)
- diabetes - Whether or not the patient has diabetes
- ejection_fraction - Percentage of blood leaving the heart at each contraction (percentage)
- high_blood_pressure - Whether or not the patient had high blood pressure upon admission
- platelets - Platelets in the blood (kiloplatelets/mL)
- serum_creatinine - Level of serum creatinine in the blood (mg/dL)
- serum_sodium - Level of serum sodium in the blood (mEq/L)
- sex - Sex of the patient
- current_smoker - Whether or not the patient is a current smoker
- room_number -  Patient's room number during hospital admission
- hospital -  The hospital that admitted the patient
- DEATH_EVENT - Target variable. 0 = patient survived, 1 = patient died
