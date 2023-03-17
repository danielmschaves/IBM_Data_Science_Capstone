# IBM Data Science Capstone

## About this Course
This capstone project is a part of the IBM Data Science Professional Certificate offered on Coursera. The course aims to provide a practical experience in data science by simulating the real-life scenario of a Data Scientist working for a start-up that intends to compete with SpaceX. In this project, you will follow the Data Science methodology including data collection, data wrangling, exploratory data analysis, data visualization, model development, model evaluation, and reporting your results to stakeholders.


## Table of Contents
- Introduction
- Week 1: Data Collection and Wrangling
- Week 2: Exploratory Data Analysis (EDA)
- Week 3: Interactive Visual Analytics and Dashboard
- Week 4: Predictive Analysis (Classification)
- Week 5: Presenting Data-Driven Insights

## Introduction
The commercial space age is upon us, with companies making space travel accessible to everyone. Companies like Virgin Galactic, Rocket Lab, and Blue Origin are leading the way, but the most successful among them is SpaceX. SpaceX has achieved a lot, including sending spacecraft to the International Space Station, launching satellite internet constellations through Starlink, and sending manned missions to space. One of the reasons SpaceX has been able to do all this is because their rocket launches are relatively inexpensive compared to other providers. 

In this capstone, I took the the role of a Data Scientist working for a new rocket company, Space Y, that aims to compete with SpaceX. My job was to determine the price of each launch by gathering information about SpaceX and creating dashboards for my team. Additionally, I will determine if SpaceX will reuse the first stage of their rockets. I trained train a machine learning model using public information to predict if SpaceX will reuse the first stage.

## Week 1: Data Collection and Wrangling
In this week, I collected the data either through an API or web scraping and then clean and transform it into a usable format.

## Week 2: Exploratory Data Analysis (EDA)
In this week, I explored the data using SQL and Pandas and created visualizations with Matplotlib to gain insights into the data.

## Week 3: Interactive Visual Analytics and Dashboard
In this week, I created interactive visualizations using Folium and Plotly, and built a dashboard to present insights.

## Week 4: Predictive Analysis (Classification)
In this week, I used machine learning to predict if SpaceX will reuse the first stage of their rockets.

## Week 5: Presenting Data-Driven Insights
In this week, I presented insights to stakeholders.

## Conclusion
In this project, we aimed to perform exploratory data analysis, determine training labels, preprocess the data, and find the best hyperparameters for various classification algorithms. Our primary objective was to identify the most accurate method for our dataset among Logistic Regression, Support Vector Machines (SVM), Decision Trees, and K-Nearest Neighbors (KNN).

After standardizing the data and splitting it into training and test sets, we tuned hyperparameters for each model and compared their performance on the test dataset. The results are as follows:

- Logistic Regression: 83.33% accuracy
- Support Vector Machines (SVM): 83.33% accuracy
- Decision Trees: 88.89% accuracy
- K-Nearest Neighbors (KNN): 83.33% accuracy

Based on the test data accuracy, the Decision Tree classifier outperformed the other methods with an accuracy of 88.89%. Therefore, we can conclude that the Decision Tree is the most suitable model for this dataset among the tested algorithms.
