# Ravi_DataHack


#Workflow for Hackathon Submission

#Data Wrangling and Cleaning  

> For most of the first columns, i have used the mode() value to fillin empty values.
> Then i have exploited map() function to replace object/string values to replace them with numericals.
> I used OneHotEncoding encoding to seperate columns having multiple distinct values and converted them into binary.
> I ignored the columns having too high of null values( ~50% ).
> #Please Note that i used the same code to clean training and then testing dataframe, so the notebook will contain code with later only.

#Data Preprocessing and Modeling
> I used multiple feature engineering combinations, to try and improve the ultimate model for prediction.
> I further used feature selection to improve method selection for second target label.
> With preprocessing, i prepraed the data for modeling. I used GridSearchCV to tune the hyperparameters.
> Ultimately, average roc_acu_score was achieved to be of 0.722.
>Testing set is then subjected to same transformations and the resultant probability 1 for each element is stored within csv file.
 
