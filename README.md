# Final_Project_Liver_Diagnosis
##Title: 
<br>Analysis on Liver Disease Diagnosis and Prediction

#Background:
The liver is a vital visceral organ that plays a crucial role in various metabolic processes, including digestion, detoxification, regulation of blood sugar levels, and production of important proteins. Liver diseases can range from mild to life-threatening illnesses. 
Most of the common liver diseases are:
Fatty liver disease – associated with excessive alcohol, diabetes and obesity
Hepatitis : inflammation caused by viruses 
Cirrhosis : advanced scarring of the liver tissue caused by long-term damage, often due to chronic alcoholism, viral hepatitis, or other factors
Primary liver cancer (hepatocellular carcinoma) originates in the liver cells and is often associated with underlying liver disease.
#Problem Analysis and Motivation:
Problem: Accurate and early diagnosis of liver disease is critical for effective treatment and patient well-being.

Motivation: Improving diagnosis can lead to better healthcare outcomes, reduced medical costs, and enhanced patient care.

#Diagnosis:
Blood tests or Liver function tests which is the basis of this project in the major way of diagnosing liver disease measures enzymes, bilirubin, and proteins to assess how well the liver is functioning.

#Project goals & objectives:
Improving Healthcare service delivery -  Contribute to enhanced patient care, reduced medical costs, and improved healthcare outcomes through reliable diagnosis.

Early Detection - Identify features that contribute to early detection of liver disease, enabling timely medical interventions.

Accurate Diagnosis - Develop predictive models to accurately diagnose liver disease based on patient data.
#Approach:

#Observations:
Certain features exhibit direct relationships among themselves, such as:
Protein features  - Albumin and Total Proteins; Albumin and Albumin-to-Globulin Ratio.
Enzyme features  - Aspartate Aminotransferase and Alanine Aminotransferase also show a direct relationship.
Bilirubin features - Direct Bilirubin and Total Bilirubin

#Machine Learning Model Performance:

Evaluation: We tested multiple models on the dataset for predicting liver disease.
Top Performers: XGBoost and Extra Trees Classifier achieved the highest accuracy of approximately 83.2% in predicting liver disease.

#Model Comparison: See Table below.
Model Name	Test Accuracy
XGBoost	83.2%
Extra Trees Classifier	83.2%
Random Forest Classifier	80.8%
Ada Boost Classifier	79.6%
Cat Boost	79.6%
Gradient Boosting Classifier	79.0%
Stochastic Gradient Boosting	79.0%
Decision Tree Classifier	73.7%

#What Worked: 
Certain features, such as enzyme(Alkaline Phosphatase & Alanine Aminotransferase), Total Protein and Total Bilirubin levels, showed significant impact on liver disease prediction.
#What Didn't: 
Some models performed better than others; Decision Tree had comparatively lower accuracy.
#Benefit: 
Accurate prediction models can aid in timely diagnosis and treatment decisions, potentially improving patient outcomes.

#Conclusion:
Based on the analysis, healthcare providers should focus on certain features  that play a significant role in diagnosing liver disease for early diagnosis and treatment.

For accurate predictions, we recommend using machine learning models such as XGBoost or Extra Trees Classifier.

#Next Steps:

Deployment: Planned possible collaboration with diagnostic centers to deploy the best predictive model using their patient dataset.
