# Drug_BaseScorePrediction:
Problem Statement

A new pharmaceutical startup is recently acquired by one of the world's largest MNCs. For the acquisition process, the startup is required to tabulate all drugs that they have sold and account for each drug's effectiveness. A dedicated team has been assigned the task to analyze all the data. This data has been collected over the years and it contains data points such as the drug's name, reviews by customers, popularity and use cases of the drug, and so on. Members of this team are by the noise present in the data.


Data description:
The data consists of the following two .csv files:
• train.csv - (32165x 7)
• test.csv - (10760x6)

The dataset has the following columns:
patient_id : ID of patients
name_of_drug:  Name of the drug prescribed
use_case_for_drug: Purpose of the drug
review_by_patient: Review by patient
drug_approved_by_UIC: Date of approval of the drug by UIC
number_of_times_prescribed:  Number of times the drug is prescribed
effectiveness_rating:  Effectiveness of drug
base_score:  Generated score (Target Variable)



Approach:
In this project we are going to predict the drug base_score based on the features provided in the csv file.

It is NLP based Regression Problem. We have trained the different regression models using train.csv and made the predictions for test.csv.
We have used Label Encoding for text column to convert them into numerical values.
Among different algorithms, Random Forest(RF) and Decision Tree(DT) are performing well. We have predicted the results using both the algorithms and saved the results in results_RF.csv and results_DT.csv respctively.

Tools used
•	Python
•	Seaborn
•	Numpy
•	Pandas
•	Sci-kit Learn

