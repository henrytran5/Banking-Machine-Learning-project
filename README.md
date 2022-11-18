# Banking-Machine-Learning-project
Banking dataset:

Content and purpose:

Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing.\
\
Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.\

Apply statistical models:
\
The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit (variable y).\
Dataset includes 17 columns and 45,211 rows with customer’s attributes such as:
\
1 - age (numeric)\
2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
"blue-collar","self-employed","retired","technician","services")\
3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)\
4 - education (categorical: "unknown","secondary","primary","tertiary")\
5 - default: has credit in default? (binary: "yes","no")\
6 - balance: average yearly balance, in euros (numeric)\
7 - housing: has housing loan? (binary: "yes","no")\
8 - loan: has personal loan? (binary: "yes","no")\
# related with the last contact of the current campaign:\
9 - contact: contact communication type (categorical: "unknown","telephone","cellular")\
10 - day: last contact day of the month (numeric)\
11 - month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec")\
12 - duration: last contact duration, in seconds (numeric)\

# Other attributes:\

13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)\
14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)\
15 - previous: number of contacts performed before this campaign and for this client (numeric)\
16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")\
Output variable (desired target):
17 – variable y (outcome target) - has the client subscribed a term deposit? (binary: "yes","no")\

Data Analytics process:
Using Data Analytics for analyzing in Tableau, Power BI, R, and Python language as summary on attributes, find outliers with Anomaly Detection, correlations, missing values, removing duplicate values, find histogram, line charts between attributes to compare, evaluate, and understand customer ‘s purposes and background, use Machine Learning and Statistical models predicting on Dataset for outcome target to make decisions to customers for marketing, advertising by call phone.\

          -  Collecting, Combining, Storing, Cleaning, ELT process, Understanding, Analyzing and Predicting \
Collecting, Combining, Storing: from many source complex initial dataset, we will collect, combine and store dataset completely to prepare analytics process\
Cleaning: Use software to clean dataset as waiver missing values, duplicate data, wrong data, add more values necessary, the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset, etc.\
ELT process: Extract- Load-Transform dataset.\
Extract: After collect raw dataset from many source locations, we will extract data as dataset can consist of many data types and come from virtually any structured or unstructured source\
Load: the transformed data is moved from the staging area into a data storage area, or between many storing software\
Transform: data is to change values to new values for the purport of analytics process.\
•	Filtering, cleansing, de-duplicating, validating and authenticating the data.
•	Performing calculations, translations, data analysis or summaries based on the raw data. 
•	Removing, encrypting, hiding, or otherwise protecting data.
•	Formatting the data into tables or joined tables based on the schema deployed
          -  Find outliers, anomaly detection, missing values, duplicate values, histogram, bar charts, line charts of attributes.
         -  Find accuracies, AUC values, ROC curves based on the target attribute to making decisions.

          - Building, developing, and maintaining statistical models for whole dataset in R, Python language
Apply Statistical model and Machine Learning:
          - Using statistical models as Linear Regression, Decision Tree, Random Forest, SVM, KNN, Neural Net, Logistics, Bayes Net, K Means, Hierarchical cluster based on 16 attributes and 1 target attribute with the classification goal is to predict if the client will subscribe to a term deposit (outcome target, variable y).
If modeling results have given high AUC values based on the target over 80% then we can make a decision that customer will subscribe to a term deposit
●Design and Implementation of Analytics System of Big Data Analytics project with Machine Learning and Statistical models results that uses Big and Real Life datasets from The New York Police Department (NYPD)’s Stop, Question and Frisk database by Python, R programming and Rattle.
Content and purpose:
These data were originally collected by New York Police Department officers and record information gathered as a result of stop question and frisk (SQF) encounters between 2003 and 2018. These data were used in a study carried out, under contract to the New York City Police Foundation, by the Rand Corporation's Center on Quality Policing. This data collection contains information on the officer's reasons for initiating a stop, whether the stop led to a summons or arrest, demographic information for the person stopped, and the suspected criminal behavior. We need to analyze dataset and use statistical to predict on the SQF target to understand that when we can use SQF process to a person or we can use modeling algorithm to review SQF process by police since we may know that wrong action of SQF from police.
Data Analytics process:

       -  Collecting, Combining, Storing, Cleansing, Understanding, Analyzing and Predicting on the Big Dataset around four million rows such as find outliers, missing values, duplicate values, histogram, bar charts, line charts to analyze on the attributes, find relationship on the related as race, age, height, weight, reason of stop, reason of frisked, using weapons, check and analyze criminal problems.
       -  Find Predictor Importance attributes impact directly to the Frisked target.
       - Building, developing, and maintaining statistical models for whole dataset as Linear Regression, Decision Tree, Random Forest.
       -  Analyzing on 120 attributes and 4,000,000 rows of Criminal problems, Sex, Race, Age, Haircolor, City, Eyecolor Stop, Frisked, Height, Weapons, ect and predicting to Frisked target for the Stop, Question, and Frisked problem by police.

Apply Statistical model and Machine Learning:

      -  Find accuracies, AUC values, ROC curves and using statistical models as Linear Regression, Decision Tree, Random Forest, SVM based on the Frisked target attribute to making decisions for Stop, Question, and Frisked process by police.
If modeling results have given high AUC values based on the target over 80% then we can make a decision that person will be stop, question or frisked by police 

