# Using Machine Learning to Predict Stroke

Objective:
The objective of this project is to explore stroke data such that a prediction model can be created. Factors which highly correlate to having a stroke will be detected to conclude which factors to most be aware of for stroke prediction. 


This GitHub repository contains:
 - The file titled "Using_Machine_Learning_To_Predict_Stroke.ipynb" is a Jupyter Notebook using Python code. This contains all code used to upload the data, clean the data, eploratory data analysis, create and evaluate models. Additionally, there are interactive features within the code, allowing for users to click buttons to display different charts or information. 

 - The file titled "healthcare-dataset-stroke-data.csv" contains all the Stroke data used during this project. This dataset was provided by Kaggle by Fedesoriano. 

 - The file titled "requirements.txt" lists all the required Python packages necessary to run the Jupyter Notebook file. 

These files together allow for MyBinder to create a publiclly accessable, interactive website which only shows the output of the code: https://mybinder.org/v2/gh/tbentley2016/Project/HEAD?urlpath=%2Fvoila%2Frender%2FUsing_Machine_Learning_To_Predict_Stroke.ipynb  

Conclusion:
- Age is the main factor which can predict stroke and the developer recommends special care to prevent stroke, especially for those who are more at risk (such as also having heart disease or high average glucose level) while growing older. 
- Though age is the factor which correlates the highest with stroke, this may mean that those who are younger, but have other factors which increase their risk, just haven't had a stroke yet. For this reason, those with risk factors who are younger should be aware of their increased risk of stroke in order to take preventative action.
- The best performing model for predicting stroke was GBM with a 94% accuracy rate and with better false negative and positive rates than the other models considered.
