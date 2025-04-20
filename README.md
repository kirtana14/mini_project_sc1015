### SC1015 Mini project 
Kirtana Nair - U2431861D

Aadya Gupta - U2431801E

## Problem definition based on a dataset
We defined our objective clearly: to predict the likelihood of a stroke based on individual health attributes. This problem is framed within a real-world context — early detection of stroke risk can empower healthcare systems to take preventive measures, reduce emergency admissions, and enhance quality of life.

To justify the relevance of this task, we identified that:

1) Stroke is one of the leading causes of death and disability worldwide.
2) Clinical and lifestyle data is often already collected in hospitals and check-ups, making predictive analytics feasible and scalable.

With the help of data science, we aim to transform this raw health data into insightful, decision-support tools.


## Data preparation and cleaning
1) Handled missing values and null values by dropping irrelevnt variables.
2) Converted categorical variables (e.g., gender, work type) to numeric formats for modeling through encoding, this allowed us to factor in all vaiables whwen prediciting stroke. 
3) Ensured data consistency and proper formatting for model inputs.

## Exploratory data analysis/visualization 
We understood that single variables as well as a combination fo different varibales can have an effect on possibility of stroke. Hence we performed various analysis to identify trends and variables to focus in on. 

1) Performed univariate and bivariate analysis to examine stroke distribution across features.
2) Used visualizations like histograms and bar plots to highlight patterns (e.g., age, heart disease, glucose levels).
   
Through this EDA we were able to derive insights like:
1) Higher stroke rates are found amongst people with heart disease and hypertension.
2) Former smokers have higher stroke rates than those who havent smoked previously.
3) Glucose levels and age are strong indicators.

## Use of machine learning techniques 
In order to apply our findings from our EDA, we used several machine learning modles to help us predict the possibility of stroke due to different variables
Applied and compared multiple models: Logistic Regression, Decision Trees, and more.
Evaluated models using metrics like accuracy, recall (TPR), FPR, and FNR.
Prioritized models that performed well on recall — due to the importance of detecting true stroke cases.
Learned new methods like feature importance interpretation and confusion matrix analysis.

## Data-driven insights and the recommendations
Generated clear, actionable insights based on EDA and model outputs.
Gave practical recommendations, such as:
Prioritizing screening for those with heart disease/hypertension.
Encouraging glucose control and long-term follow-up for former smokers.
Designing risk calculators that go beyond age thresholds.
Linked technical findings to real-world healthcare applications.


## Learning something new and doing something beyond this course
Explored medical context and connected technical results with health policies.
Compared multiple models and discussed trade-offs (e.g., recall vs. false positives).
Added thoughtful feature engineering and new perspectives in the recommendations.
