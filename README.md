Hi, I'm Ilham Brilliandi. I'm a fresh graduate student majoring at mathematics in Brawijaya University. I have a heavy passionate towards data science since college. Here's a simple tour on projects i've done since 2023.


## [Project 1: Data Analysis - E-Commerce](https://github.com/ilhambrilliandi/da_e-commerce)
This project is end-to-end analysis, including data preprocessing and visualization, providing actionable insights into sales trends, top products, and seller performance from 3 years dataset of a store.

Overview:
- Top product categories differ across 3 years, health beauty is the most bought category based on sum of 3 years.
- Average busiest transactions occurred on Monday, at the afternoon (around 4PM).

Recommendation:
- Give promotions and bonuses to most bought products to enhance sell performance.
- Also give a discount to busiest transaction time such as promoting free delivery fee.
- Give promotions to first buyer on least and most bought product to get them engage.
- Give bonuses and rewards to the loyal customers.


## [Project 2: Data Analysis - Employee Promotion](https://github.com/ilhambrilliandi/da_predictemployeepromotions)
This is a project of end-to-end analysis, including data preprocessing, visualization and predicting using several methods. Providing insights about what takes the biggest role on promotions, and find the best department based on promotion rates in a year.

Overview:
- Overfitting occured on LogR and SVM models because of imbalanced data.
- Tested on 6 models, lightgbm is the fittest.
- 429 people (3.3%) of all employees predicted will get promoted in 2024.
- Education level and department have important role in determining promotion.
- Based on promotion, the most accomplished departments are Sales & Marketing, Operations, and Procurement.
- Bachelors got the most promoted employees by number, and Masters & Above by percentage. Note that no Below Secondary employees got promoted.
- Recruitment Channel has important role in determining promotion. Other is the most by number, and Referred by percentage (4.55%).
- Promotion distribution by gender relatively even.

Recommendation:
- Use hyperparameter tuning or other resampling method.
- Employees' performance can be improved by conducting training, Below Secondary employees need to be the focus.


## [Project 3: Machine Learning - Identifying Rock, Paper, Scissors](https://github.com/ilhambrilliandi/ml_cv_classificationrps)
In this project i implemented machine learning using Tensorflow to identifying images of hand gesture, achieving the accuracy of 92%.


## [Project 4: Web Scraping - Automation Clicker Game](https://github.com/ilhambrilliandi/ws_automationcoockieclicker)
This code runs an automation for web-based game "[Cookie Clicker](https://orteil.dashnet.org/cookieclicker/)" by automatically clicking and upgrading items using selenium.


## [Project 5: Web Scraping - Extract Website Information](https://github.com/ilhambrilliandi/ws_extractwebsiteinformation)
In this project i'm trying to scrape the information from [this website](https://www.anwb.nl/auto/private-lease/anwb-private-lease/aanbod) using selenium, then store them in csv file.


## [Project 6: Sentiment Analysis: Social Media Posts](https://github.com/ilhambrilliandi/sa_socialmediaposts)
In this project i try to analyze the sentiment from 3 social media platforms (Facebook, Instagram, Twitter) using BERT method. This method categorize the text into 5 different levels:
- 1 = negative
- 2 = somewhat negative
- 3 = neutral
- 4 = somewhat positive
- 5 = positive

here's the required specific libraries for this project:
- transformers
- torch
- re

Overview:
- Each platform has different user's behaviour. While Twitter's users' traffic mostly occured in last days of the month, Facebook and Instagram relatively spread across the entire month.
- The users' traffic suddenly peaked at 2023 on all platforms.
- The model finds that across all platforms, most of the posts' sentiment is positive, followed by negative. Shows that posts are rarely neutral.
- Need to take a note that this model doesn't accurately spot the ambiguous sentences such as sarcasms.
