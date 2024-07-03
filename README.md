# heart-failure-prediction
Predictive model repository in Python. The dataset used contains the medical records of 5000 patients who had heart failure, collected during their follow-up period, where each patient profile has 13 clinical features.

Dataset link: https://www.kaggle.com/datasets/aadarshvelu/heart-failure-prediction-clinical-records 

Now, here I share some of the important graphs from the analysis and model creation.

**Histogram of the age distribution of the patients.**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/83b6793a-efd0-4c57-8ee6-489b0afb8935)

**Distribution of Clinical Variables**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/7d9f7d62-336c-477f-bc6d-45c0ba2d798f)

**Correlation Analysis HeatMap**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/33febb23-7fac-404e-b4d9-ee252b6aac06)

**Variable Importance**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/38a44ab2-b253-4033-9258-8711b13e7941)

**Confusion Matrix**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/9e3fcd83-09f3-4ba1-94c0-089324d85c72)

**ROC Curve**

![image](https://github.com/Alvaromonterobec/heart-failure-prediction/assets/166189832/39e9ae09-dcd6-4355-be81-a9b1bce015db)

**General conclusion of the analysis:**

High performance: The high number of true negatives and true positives, along with the low values of false positives and false negatives, indicate that your model has overall high performance.

Low error rate: With only 10 false positives and 7 false negatives, your model makes very few errors, which is excellent for medical applications where accuracy is critical.

Balanced performance: The metrics of precision and sensitivity are very high, suggesting that the model is good at both identifying positive cases and avoiding false alarms.
