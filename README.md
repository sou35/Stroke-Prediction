# Stroke-Prediction
According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.
Dataset can be downloaded from the [Kaggle](https://www.kaggle.com/fedesoriano/stroke-prediction-dataset).

![stroke prediction](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.kaggle.com%2Ffedesoriano%2Fstroke-prediction-dataset%2Fcode&psig=AOvVaw32ovYkfQMouWZp1ZYFg86B&ust=1634392060194000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCND9_oTHzPMCFQAAAAAdAAAAABAD)

Attribute Information
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"*
12) stroke: 1 if the patient had a stroke or 0 if not

Run app.py using below command to start Flask API:
```
python app.py
```
By default, flask will run

Navigate to URL http://127.0.0.1:7384/

You should be able to view the homepage as below : alt text

Enter valid numerical values in all  input boxes and hit Submit.

If everything goes well, you should be able to see the predcited the patient had a stroke or not on the HTML page! 
