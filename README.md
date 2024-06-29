

![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/ea3b127d-9b02-4dcb-883d-913896f2e987)


# About Dataset
This dataset contains comprehensive health data for 1,879 patients, uniquely identified with IDs ranging from 6000 to 7878. The data includes demographic details, lifestyle factors, medical history, clinical measurements, medication usage, symptoms, quality of life scores, environmental exposures, and health behaviors. Each patient is associated with a confidential doctor in charge, ensuring privacy and confidentiality. This dataset is ideal for researchers and data scientists looking to explore factors associated with diabetes, develop predictive models, and conduct statistical analyses.

- **Patient Information**
    - **PatientID**: Unique identifier (6000 to 7878).
- **Demographic Details**
    - **Age**: 20 to 90 years.
    - **Gender**: 0 (Male), 1 (Female).
    - **Ethnicity**: 0 (Caucasian), 1 (African American), 2 (Asian), 3 (Other).
    - **SocioeconomicStatus**: 0 (Low), 1 (Middle), 2 (High).
    - **EducationLevel**: 0 (None), 1 (High School), 2 (Bachelor's), 3 (Higher).
- **Lifestyle Factors**
    - **BMI**: 15 to 40.
    - **Smoking**: 0 (No), 1 (Yes).
    - **AlcoholConsumption**: 0 to 20 units per week.
    - **PhysicalActivity**: 0 to 10 hours per week.
    - **DietQuality**: 0 to 10.
    - **SleepQuality**: 4 to 10.
- **Medical History**
    - **FamilyHistoryDiabetes**: 0 (No), 1 (Yes).
    - **GestationalDiabetes**: 0 (No), 1 (Yes).
    - **PolycysticOvarySyndrome**: 0 (No), 1 (Yes).
    - **PreviousPreDiabetes**: 0 (No), 1 (Yes).
    - **Hypertension**: 0 (No), 1 (Yes).
- **Clinical Measurements**
    - **SystolicBP**: 90 to 180 mmHg.
    - **FastingBloodSugar**: 70 to 200 mg/dL.
    - **HbA1c**: 4.0% to 10.0%.
    - **BUNLevels**: 5 to 50 mg/dL.
- **Medications**
    - **AntihypertensiveMedications**: 0 (No), 1 (Yes).
    - **Statins**: 0 (No), 1 (Yes).
    - **AntidiabeticMedications**: 0 (No), 1 (Yes).
- **Symptoms and Quality of Life**
    - **FrequentUrination**: 0 (No), 1 (Yes).
    - **ExcessiveThirst**: 0 (No), 1 (Yes).
    - **UnexplainedWeightLoss**: 0 (No), 1 (Yes).
    - **FatigueLevels**: 0 to 10.
    - **BlurredVision**: 0 (No), 1 (Yes).
    - **SlowHealingSores**: 0 (No), 1 (Yes).
    - **TinglingHandsFeet**: 0 (No), 1 (Yes).
    - **QualityOfLifeScore**: 0 to 100.
- **Environmental and Occupational Exposures**
    - **WaterQuality**: 0 (Good), 1 (Poor).
- **Health Behaviors**
    - **MedicalCheckupsFrequency**: 0 to 4 per year.
    - **MedicationAdherence**: 0 to 10.
    - **HealthLiteracy**: 0 to 10.
- **Diagnosis Information**
    - **Diagnosis**: 0 (No diabetes), 1 (Diabetes).
# EXPLORATORY DATA ANALYSIS (EDA)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/d27832ab-fd76-405d-bb3a-4bae375756dc)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/d27489d9-1ddf-4c56-b0dc-2008fce260ea)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/f37f14dc-59d2-4f64-9602-0bcc4a132416)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/c93d784e-1c7a-42e0-9aca-66159c704edc)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/4b781fb8-ebf8-4201-ad0e-b98e413921b2)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/57fa355e-9163-4618-987a-0072548f8c84)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/f3e2120b-7d94-423a-941f-f72f75c9d0fd)
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/b329bef4-fdfa-4159-b954-0f73c77c0974)

# MODELS PREDICTIONS
## Classification - SVM models
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/585210b4-f41c-4479-b230-b184e3b528e5)
## Classification - Logistic Regression
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/e9838fb1-77e7-493f-99e0-647f6aedc403)
## Classification - Random forest
![image](https://github.com/vsynguyen/Diabetes-Analysis/assets/162006821/f76fc647-0aa2-4d02-9cad-229e07e99ebc)

