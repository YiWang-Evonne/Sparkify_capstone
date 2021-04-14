# Sparkify_capstone

This repo contains the code for my Sparkify capstone project. For more details and findings please refer to my [Blog](https://bigyi1989-93881.medium.com/sparkify-churn-rate-bdd4baae5021).


## Structure
 ```bash
├── Sparkify_Capstone.ipynb: main notebooks that contain all my code. This is directly download from EMR.
├── README.md
└── .gitignore
 ```
## Project Overview
Churn rate is a very intuitive concept. It measures the percentage of customers that leave over a given period. However, it also very important for almost every business. The longer we could keep a custom, the more revenue we could generate by providing the service. For this project, I am trying to build models to predict the Chun rate of the Sparkify service provided by Udacity.

## Data Overview
After data cleaning, the data has 22,227 users and 25,480,720 activity records, and the data covers the period from 2018/10 to 2018/12. Plots below show the Chun Rate by state, user type.
![plot](./fig/chun_rate_analysis.png)
In addition, the plot below shows the cancalling timing. It seems more people cancel after 1 to 2 months.
![plot](./fig/user_cancel_timing.png)

## Model Result 
I have tested logistic regression and random forecast model. The model performances are as below:

![plot](./fig/model_result.png)


![code base](https://github.com/YiWang-Evonne/Sparkify_capstone) 
