# Heart-Disease-Prediction
### Steps for running the project:
1. Download the files and extract them.
2. Open the terminal or anaconda prompt at the same location.
3. Type "streamlit run app.py" in that terminal.
4. A web page will open to enter details.
5. Enter the value of the specified parameters.
6. Click on the predict button to generate results.   

### The project for heart disease prediction is done by integrating with Streamlit.

The provided parameters are likely related to heart disease prediction. Let's break down each one:

1. cp - Chest pain type
    1. Typical angina
    2. Atypical angina
    3. Non-anginal pain
    4. Asymptomatic

2. trestbps - Resting blood pressure (mm Hg)

3. chol - Total cholesterol (mg/dl)

4. FBS - Fasting blood sugar (> 120 mg/dl) --> This parameter is not included 
   1. 1 for True
   2. 0 for False

5. restecg - Resting electrocardiographic results 
   1. 0 for Normal
   2. 1 for Having ST-T wave abnormality (indicating possible heart attack) or Hypertrophy of the left ventricle (enlarged heart)

6. thalach - Maximum heart rate achieved

7. exang - Exercise-induced angina
 1: Yes
 0: No

8. oldpeak - ST depression induced by exercise relative to rest

9. slope - ST segment slope at peak exercise
   1. Upsloping
   2. Flat
   3. Downsloping

10. ca - Number of coronary arteries with significant stenosis (blockage)

11. thal - Thalassemia
    1. Normal
    2. Fixed defect
    3. Reversible defect


These parameters are commonly used in machine learning models to predict the likelihood of heart disease. Analyzing these factors, a model can identify individuals at higher risk and recommend appropriate interventions.

Upvote this repo and follow for more.
