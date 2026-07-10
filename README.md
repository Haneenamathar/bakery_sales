
# Project - Bread Basket Analysis



## Project Overview

This project analyses customer purchasing behaviour using the Bread Basket dataset. The project follows an ETL (Extract, Transform, Load) process to clean and prepare the data before performing Exploratory Data Analysis (EDA).

The aim is to identify customer purchasing patterns, understand product popularity, and generate business insights that can support inventory planning and operational decision-making.

## Business Requirements

Understanding customer purchasing behaviour is important for any retail business. By analysing transaction data, businesses can identify popular products, recognise purchasing trends, and improve inventory planning.

This project explores bakery transaction data to answer these business questions and provide data-driven insights.




## Hypotheses

*H1:* Some bakery products are purchased more frequently than others.

*H2:* Customer purchasing behaviour changes depending on the time of day, day of the week, and month.

*H3:* Many customer transactions contain more than one bakery product, indicating opportunities for product bundling and cross-selling.

*H4:* Customer purchasing patterns can provide insights to improve inventory planning, product availability, and business decision-making 

## Project Plan

 Dataset

The project uses the *Bread Basket* dataset from Kaggle.

The dataset contains bakery transaction records, including:

- Transaction ID
- Item purchased
- Date and time of purchase

During the ETL process, additional features were created to support the analysis, including:

- Hour
- Day of the week
- Month
- Period of day
- Weekday/Weekend



## Project Objectives

- Analyse customer purchasing behaviour using the cleaned Bread Basket dataset.
- Identify the most frequently purchased bakery products.
- Analyse purchasing trends by hour, day of the week, and month.
- Analyse multiple-product purchasing behaviour.
- Evaluate the project hypotheses using data analysis and visualisations.
- Generate insights to support inventory planning and business decision-making


## Rationale for Mapping Business Requirements to Data Visualisations

The charts were created to answer the project objectives and hypotheses.

| Business Requirement | Chart Used | Reason |
|----------------------|------------|--------|
| Find the most popular bakery products | Top 10 Products Bar Chart | To show which products customers buy the most. |
| Understand when customers buy products | Purchases by Hour | To identify the busiest hours of the day. |
| Find the busiest days | Purchases by Day of the Week | To compare customer purchases across the week. |
| Compare purchases by month | Purchases by Month | To see how customer purchases change over time. |
| Compare weekdays and weekends | Weekday vs Weekend Chart | To see whether customers buy more on weekdays or weekends. |
| Compare different times of the day | Period of Day Chart | To find out which part of the day is busiest. |
| Understand how many products customers buy | Items per Transaction Chart | To see if customers usually buy one item or multiple items. | 


## Analysis Techniques Used

The project used Exploratory Data Analysis (EDA) to understand customer purchasing behaviour and identify trends within the Bread Basket dataset.

The following techniques were used:

- Data cleaning and transformation (ETL)
- Descriptive statistics
- Grouping and aggregation using Pandas
- Frequency analysis
- Data visualisation using Matplotlib
- Simple comparisons across different time periods



## Development Roadmap

### Challenges Faced

During this project, I faced a few challenges while cleaning the dataset and deciding how to analyse the data. I also found it challenging to choose the right charts to answer my project objectives and hypotheses.

These challenges were overcome by testing different approaches, reviewing the dataset carefully, and improving the analysis step by step until the results were clear and easy to understand.

### Skills to Develop

After completing this project, I would like to learn:

- More advanced data visualisation techniques.
- Market basket analysis to better understand products purchased together.
- Predictive analysis using machine learning.
- Power BI and Tableau for creating interactive dashboards.

## Deployment

This project was completed using Jupyter Notebook in Visual Studio Code and uploaded to GitHub as part of the Code Institute AI Bootcamp Unit 1 assessment.

The repository contains the notebook, cleaned dataset, README, and supporting project files


## Main Data Analysis Libraries

The following Python libraries were used in this project:

- *Pandas* – Used to load, clean, organise, and analyse the dataset.
- *NumPy* – Used for basic numerical operations.
- *Matplotlib* – Used to create charts and visualisations.
- *Seaborn* – Used to improve the appearance of the charts.

## Credits

### Dataset

- Bread Basket dataset from Kaggle:
  https://www.kaggle.com/datasets/mittalvasu95/the-bread-basket

### Learning Resources

- Code Institute AI Bootcamp course materials.
- Pandas documentation:
  https://pandas.pydata.org/

- Matplotlib documentation:
  https://matplotlib.org/

- Seaborn documentation:
  https://seaborn.pydata.org/

### AI Assistance

-Copilot/ChatGPT was used as a learning tool to help explain Python code, improve project documentation, and support the ETL and EDA process.



## Acknowledgements

*I would like to express my sincere gratitude to Mr. Vasi, my course facilitator, and to my classmates for their support and encouragement throughout this project.

I am also grateful to the Code Institute for providing high‑quality learning materials, guidance, and a structured framework that helped me complete this assignment successfully.

Finally, I would like to acknowledge the assistance of Microsoft Copilot and OpenAI’s ChatGPT, which supported my learning by helping me understand Python concepts, data analysis techniques, and project documentation during the development of this project.