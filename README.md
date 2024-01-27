# Shaurya Nanda  - Data-Analytics-Portfolio

## About

Hi, I am Shaurya. I am an aspiring data analyst on a journey to explore stupendous world of data and analytics.

📊 Data Enthusiast: Passionate about turning raw data into meaningful insights, I thrive on the thrill of discovering patterns, trends, and stories hidden within the numbers.


Resume: in [pdf]

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.


## Table of Contents

- [About](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#about)

- [Portfolio Projects](https://github.com/shauryananda/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)

   - Exploratory Data Analysis and Visualization - Python Libraries
     
     - [Content Analysis on a Video Streaming Platform](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Content%20Analysis%20on%20a%20Video%20Streaming%20Platform.ipynb)
       
     - [Housing Market Analysis](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Housing%20Market%20Analysis.ipynb)


   - SQL
     
      - [Operational Analysis for a Retailer in the United States](https://github.com/shauryananda/Portfolio-Projects/blob/main/SQL/Target%20-%20Business%20Case.pdf)


- [Education](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#education)

- [Certifications]
  
- [Contact](https://github.com/shauryananda/Data-Analytics-Portfolio/blob/main/README.md#contact)

## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

## Data Exploration and Data Visualization

### Content Analysis on a Video Streaming Platform
**Code:** [`Content Analysis on a Video Streaming Platform`](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/Content%20Analysis%20on%20a%20Video%20Streaming%20Platform.ipynb)

**Introduction:**  One of the most popular media and video streaming platforms. They have over 10000 movies or tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. The dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

**Business Problem:** Analyze the data and generate insights that could help the streaming platfrom decide which type of shows/movies to produce and how they can grow the business in different countries

**Dataset:** [netflix.csv](https://github.com/shauryananda/Portfolio-Projects/blob/main/Data%20Exploration%20and%20Visualisation/netflix.csv)

**Skills:** Data Cleaning, Data Analysis with Numpy and Pandas, Data Visualization.

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

**Datasets:** 

The data is available in 8 csv files:

customers.csv
sellers.csv
order_items.csv
geolocation.csv
payments.csv
reviews.csv
orders.csv
products.csv
___________________________________________________________________________________________________________

The column description for these csv files is given below.

The customers.csv contain following features:

Features                         Description

customer_id                      ID of the consumer who made the purchase

customer_unique_id               Unique ID of the consumer

customer_zip_code_prefix         Zip Code of consumer’s location

customer_city                    Name of the City from where order is made

customer_state                   State Code from where order is made (Eg. são paulo - SP)


The sellers.csv contains following features:

Features                          Description

seller_id                         Unique ID of the seller registered

seller_zip_code_prefix            Zip Code of the seller’s location

seller_city                       Name of the City of the seller

seller_state                      State Code (Eg. são paulo - SP)


The order_items.csv contain following features:

Features                          Description

order_id                          A Unique ID of order made by the consumers

order_item_id                     A Unique ID given to each item ordered in the order

product_id                        A Unique ID given to each product available on the site

seller_id                         Unique ID of the seller registered in Target

shipping_limit_date               The date before which the ordered product must be shipped

price                             Actual price of the products ordered

freight_value                     Price rate at which a product is delivered from one point to another



The geolocations.csv contain following features:

Features                           Description

geolocation_zip_code_prefix        First 5 digits of Zip Code

geolocation_lat                    Latitude

geolocation_lng                    Longitude

geolocation_city                   City

geolocation_state                  State


The payments.csv contain following features:

Features                           Description

order_id                           A Unique ID of order made by the consumers

payment_sequential                 Sequences of the payments made in case of EMI

payment_type                       Mode of payment used (Eg. Credit Card)

payment_installments               Number of installments in case of EMI purchase

payment_value                      Total amount paid for the purchase order


The orders.csv contain following features:

Features                           Description

order_id                           A Unique ID of order made by the consumers

customer_id                        ID of the consumer who made the purchase

order_status                       Status of the order made i.e. delivered, shipped, etc.

order_purchase_timestamp           Timestamp of the purchase

order_delivered_carrier_date       Delivery date at which carrier made the delivery

order_delivered_customer_date      Date at which customer got the product

order_estimated_delivery_date      Estimated delivery date of the products


The reviews.csv contain following features:

Features                           Description

review_id                          ID of the review given on the product ordered by the order id

order_id                           A Unique ID of order made by the consumers

review_score                       Review score given by the customer for each order on a scale of 1-5

review_comment_title               Title of the review

review_comment_message             Review comments posted by the consumer for each order

review_creation_date               Timestamp of the review when it is created

review_answer_timestamp            Timestamp of the review answered


The products.csv contain following features:

Features                           Description

product_id                         A Unique identifier for the proposed project.

product_category_name              Name of the product category

product_name_lenght                Length of the string which specifies the name given to the products ordered

product_description_length         Length of the description written for each product ordered on the site

product_photos_qty                 Number of photos of each product ordered available on the shopping portal

product_weight_g                   Weight of the products ordered in grams

product_length_cm                  Length of the products ordered in centimeters

product_height_cm                  Height of the products ordered in centimeters

product_width_cm                   Width of the product ordered in centimeters

## Education

Goa Institute of Management: Master of Business Administration - MBA, Big Data Analytics, 2019 - 2021

Guru Gobind Singh Indraprastha University: Bachelor's degree, Information Technology, 2012 - 2016


## Certifications


## Contact

LinkedIn: [Shaurya Nanda](https://www.linkedin.com/in/shaurya-nanda/)

Email: shauryananda10@gmail.com
