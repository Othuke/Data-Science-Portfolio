# My Data Science Portfolio

## About Me
I am a Data Enthusiast who is naturally curious and analytical, keen to turn data into insights. I am a graduate of Electrical/Electronics Engineering and one who is always ready to learn and take on new challenges, a problem solver. You can find my academic journey and work experience on [My Resume](https://drive.google.com/file/d/1ddCk72hgMtE0vB9slfj6jc-cWR3-1e4c/view?usp=share_link)

Feel free to contact me on [my LinkedIn page](https://linkedin.com/in/othuke-ajaye) if you are looking t hire a data scientist or analyst or for a chat.

## Projects
This repository contains a list of projects that I have worked on or currently working on. All datasets are gotten from Kaggle and other publicly available websites.

[1. Customer Churn](https://github.com/Othuke/Customer-Churn-Case-Study)

![Customer Churn](images/customer_churn.png)

The goal of this project was to build a model that would predict behavior to retain customers, analyze all relevant customer data and develop focused customer retention programs.

The major insights gotten from this project include:
* The target variable had an imbalanced ratio of about 74% to 26%. For the purpose of this project, this was balanced using the SMOTE technique (which has proven not to be the best especially in industry related problems).
* Customers who churned spend much less time with company than customers who did not churn. They are also charged a bit higher.
* The rate of churn amongst the senior citizens are relatively higher although they constitute only a small part of the dataset.
* Customers with patners and dependents have lower churn rates than those without partners and dependents.
* Customers whose contracts are on an annual or a two-year basis seem to have significantly lower churn rate than their counterpart
* Customers who use the electronic method of payment have a much higher churn rate than others

The full notebook can be accessed [here](https://github.com/Othuke/Customer-Churn-Case-Study/blob/main/Customer%20churn.ipynb)

The model was also tracked using comet_ml. Click [here](https://www.comet.com/othuke/customer-churn/view/new/experiments) to access the experiments
