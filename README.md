# Shaurya Nanda  - Data-Analytics-Portfolio

## About

Hi, I am Shaurya. I am an aspiring data analyst on a journey to explore an intriguing world of data and analytics.

📊 Data Enthusiast: Passionate about turning raw data into meaningful insights, I thrive on the thrill of discovering patterns, trends, and stories hidden within the numbers.


Resume: 

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.


## Table of Contents

- [About](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#about)

- [Portfolio Projects](https://github.com/shauryananda/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)

   - Exploratory Data Analysis and Visualization - Python Libraries
     
     - [Content Analysis on a Video Streaming Platform](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Content%20Analysis%20on%20a%20Video%20Streaming%20Platform.ipynb)
       
     - [Housing Market Analysis](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Housing%20Market%20Analysis.ipynb)


   - SQL
     
      - [Operational Analysis for a Retailer in the United States](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Target%20-%20Business%20Case.pdf)
        
      - [Instagram User Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Instagram%20User%20Analytics.pdf)

      - [Operations & Metric Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Operations%20And%20Metric%20Analytics.pdf)


- [Education](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#education)

- [Certifications](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#certifications)
  
- [Contact](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#contact)


## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

## Data Exploration and Data Visualization

### Content Analysis on a Video Streaming Platform
**Code:** [`Content Analysis on a Video Streaming Platform`](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Content%20Analysis%20on%20a%20Video%20Streaming%20Platform.ipynb)

**Introduction:**  One of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. The dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

**Business Problem:** Analyze the data and generate insights that could help the streaming platfrom decide which type of shows/movies to produce and how they can grow the business in different countries

**Dataset:** [netflix.csv](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/netflix.csv)

**Skills:** Data Cleaning, Data Analysis with Numpy and Pandas, Data Visualization with Matplotlib and Seaborn

### Housing Market Analysis
**Code:** [Housing Market Analysis](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Housing%20Market%20Analysis.ipynb)

**Introduction:** Exploratory Data Analysis on the Housing Market of London in the years between 1995 and 2020.

**Business Problem:** Perform exploratory data analysis with the goal of discovering new information and answering the following questions:

How has the housing market (average house price and number of houses sold) changed over the years in different boroughs of London? 
How does it compare to England?
What factors affected it the most?

**Datasets:** [housing_in_london_monthly_variables](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/housing_in_london_monthly_variables.csv)

[housing_in_london_yearly_variables](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/housing_in_london_yearly_variables.csv)

**Skills:** Exploratory Data Analysis, Data Cleaning, Data Visualization.

## SQL

### Operational Analysis for a Retailer in the United States

**Introduction**: [Operational Analysis for a Retailer in the United States](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Target%20-%20Business%20Case.pdf)

**Business Problem:** Perform Analysis on the Sales and Operations for a Retailer in the United States:

A globally renowned brand and a prominent retailer in the United States. Target makes itself a preferred shopping destination by offering outstanding value, inspiration, innovation and an exceptional guest experience that no other retailer can deliver.

This particular business case focuses on the operations of a retailer in Brazil and provides insightful information about 100,000 orders placed between 2016 and 2018. The dataset offers a comprehensive view of various dimensions including the order status, price, payment and freight performance, customer location, product attributes, and customer reviews.

By analyzing this extensive dataset, it becomes possible to gain valuable insights into the retailer's operations in Brazil. The information can shed light on various aspects of the business, such as order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction levels.

**Datasets:** https://shorturl.at/dnotw

**Skills:** SQL

### Instagram User Analytics

**Introduction**:

**Business Problem:** [Instagram User Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Instagram%20User%20Analytics.pdf)

You're a data analyst working with the product team at Instagram. Your role involves analyzing user interactions and engagement with the Instagram app to provide valuable insights that can help the business grow.

User analysis involves tracking how users engage with a digital product, such as a software application or a mobile app. The insights derived from this analysis can be used by various teams within the business. For example, the marketing team might use these insights to launch a new campaign, the product team might use them to decide on new features to build, and the development team might use them to improve the overall user experience.

In this project, I have used SQL and MySQL Workbench as your tool to analyze Instagram user data and answer questions posed by the management team. Your insights will help the product manager and the rest of the team make informed decisions about the future direction of the Instagram app.

**SQL Queries:** [Instagram User Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Instagram_User_Analytics_Queries.sql)

**SQL Tasks** :

**A) Marketing Analysis:**

**Loyal User Reward:** The marketing team wants to reward the most loyal users, i.e., those who have been using the platform for the longest time.

Task: Identify the five oldest users on Instagram from the provided database.

**Inactive User Engagement:** The team wants to encourage inactive users to start posting by sending them promotional emails.

Task: Identify users who have never posted a single photo on Instagram.

**Contest Winner Declaration:** The team has organized a contest where the user with the most likes on a single photo wins.

Task: Determine the winner of the contest and provide their details to the team.

**Hashtag Research:** A partner brand wants to know the most popular hashtags to use in their posts to reach the most people.

Task: Identify and suggest the top five most commonly used hashtags on the platform.

**Ad Campaign Launch:** The team wants to know the best day of the week to launch ads.

Task: Determine the day of the week when most users register on Instagram. Provide insights on when to schedule an ad campaign.

**B) Investor Metrics:**

**User Engagement:** Investors want to know if users are still active and posting on Instagram or if they are making fewer posts.

Task: Calculate the average number of posts per user on Instagram. Also, provide the total number of photos on Instagram divided by the total number of users.

**Bots & Fake Accounts:** Investors want to know if the platform is crowded with fake and dummy accounts.

Task: Identify users (potential bots) who have liked every single photo on the site, as this is not typically possible for a normal user.

**Dataset:** https://docs.google.com/document/d/1-WhNRX1iYJIz7e5l28DMPWgsPklpE_w6/edit

**Skill:** SQL

### Operations & Metric Analytics

**Introduction**:

**Business Problem:** [Operations & Metric Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Operations%20And%20Metric%20Analytics.pdf)

Operational Analytics is a crucial process that involves analyzing a company's end-to-end operations. This analysis helps identify areas for improvement within the company. As a Data Analyst, you'll work closely with various teams, such as operations, support, and marketing, helping them derive valuable insights from the data they collect.

One of the key aspects of Operational Analytics is investigating metric spikes. This involves understanding and explaining sudden changes in key metrics, such as a dip in daily user engagement or a drop in sales. As a Data Analyst, you'll need to answer these questions daily, making it crucial to understand how to investigate these metric spikes.

In this project, my goal is to use advanced SQL skills to analyze the data and provide valuable insights that can help improve the company's operations and understand sudden changes in key metrics.

**SQL Queries:** 

[Operations Analytics](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Operation_Analytics_Queries.sql)

[Investigating Metric Spikes]

## Education

Goa Institute of Management: Master of Business Administration - MBA, Big Data Analytics, 2019 - 2021

Guru Gobind Singh Indraprastha University: Bachelor's degree, Information Technology, 2012 - 2016


## Certifications

[Google Data Analytics Professional - Coursera (March 2024)](https://www.coursera.org/account/accomplishments/professional-cert/Z45XUGNDEFLY)

[IBM Data Analyst Professional - Coursera (January 2024)](https://www.coursera.org/account/accomplishments/professional-cert/E5T42S45A7HP)

[Lean Six Sigma Green Belt Certification - KPMG (November 2020)](https://media.licdn.com/dms/document/media/C561FAQGDSFwjn6m7eA/feedshare-document-pdf-analyzed/0/1621064447068?e=1710374400&v=beta&t=SFklb4EkTg0KtYtpYasGFfViotEBdmTGdaoq1leqm_U)

## Contact

LinkedIn: [Shaurya Nanda](https://www.linkedin.com/in/shaurya-nanda/)

Email: shauryananda10@gmail.com
