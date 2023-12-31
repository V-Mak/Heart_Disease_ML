# Heart_Disease_ML

This database contains 76 attributes, but all published experiments refer to using a subset of 14 of them.  In particular, the Cleveland database is the only one that has been used by ML researchers to this date.  The "goal" field refers to the presence of heart disease in the patient.  It is integer valued from 0 (no presence) to 4. Experiments with the Cleveland database have concentrated on simply attempting to distinguish presence (values 1,2,3,4) from absence (value 0).

Additional Information

* Only 14 attributes used:
  
      1. age       
      2. sex       
      3. cp        
      4. trestbps  
      5. chol      
      6. fbs       
      7. restecg   
      8. thalach   
      9. exang     
      10. oldpeak   
      11. slope    
      12. ca       
      13. thal
      14. num     (the predicted attribute)


*Complete attribute documentation:

      1. age: age in years
      2. sex: sex (1 = male; 0 = female)
      3. cp: chest pain type
        -- Value 1: typical angina
        -- Value 2: atypical angina
        -- Value 3: non-anginal pain
        -- Value 4: asymptomatic
     4. trestbps: resting blood pressure (in mm Hg on admission to the hospital)
     5. chol: serum cholestoral in mg/dl
     6. fbs: (fasting blood sugar > 120 mg/dl)  (1 = true; 0 = false)
     7. restecg: resting electrocardiographic results
        -- Value 0: normal
        -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
        -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
     8. thalach: maximum heart rate achieved
     9. exang: exercise induced angina (1 = yes; 0 = no)
     10. oldpeak = ST depression induced by exercise relative to rest
     11. slope: the slope of the peak exercise ST segment
        -- Value 1: upsloping
        -- Value 2: flat
        -- Value 3: downsloping
     12. ca: number of major vessels (0-3) colored by flourosopy
     13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
     14. num: diagnosis of heart disease (angiographic disease status)
        -- Value 0: < 50% diameter narrowing
        -- Value 1: > 50% diameter narrowing
        (in any major vessel: attributes 59 through 68 are vessels)
