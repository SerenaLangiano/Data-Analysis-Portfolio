# Serena Langiano - Data Analyst Portfolio
This is a repository that I have created to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## About
Hi, I'm Serena! I have an academic background in Electrical Engineering and currently I am working as Data Analyst in the renewable energy field. In my 4+ years of working experience I've developed a passion for using data to uncover meaningful insights. I am excited to bring my technical and analytical skills to the field of Data Analytics, where I can contribute to solving challenging problems and making data-driven decisions that have a tangible impact. 

Throughout my career, I honed my ability to work with complex datasets and developed strong visualization skills. I am proficient in Python, Excel and SQL, whiche I've utilized to query large relational databases.

In my free time, I enjoy exploring new data analysis tools and techniques, and I am always looking for opportunities to expand my knowledge and skills. Whether working on a team or independently, I am driven by the thrill of discovering new insights and the satisfaction of using data to solve complex problems.

My CV in [pdf](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/Serena%20Langiano_CV.pdf).

This is a repository to showcase skills, share projects and track my progress in Data Analytics related topics.

## Table of Contents
- [About](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)
  - Python
    - [Data analysis on Climate Change - Italy](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#Data-analysis-on-Climate-Change---Italy)
    - [Marketing campaigns Analysis - Computer software Company](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#Marketing-campaigns-Analysis---Computer-software-Company)
  - SQL
    - [Ecommerce Analysis with MySQL](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#Ecommerce-Analysis-with-MySql)
    - [Healthcare Data Analysis](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#Healthcare-Data-Analysis)
  - Power BI
    - [Executive summary](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#Executive-Summary-Adventure-Works)
- [Experience](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#experience)
- [Education](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#education)  
- [Certificates](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#certificates)
- [Contact](https://github.com/SerenaLangiano/Data-Analysis-Portfolio/blob/main/README.md#contacts)


## Portfolio Projects
In this section I will list Data Analytics projects briefly describing the technology stack used to solve cases.

### Data analysis on Climate Change - Italy
**Code:** [`Data-analysis-on-Climate-Change-Italy.ipynb`](https://github.com/SerenaLangiano/Portfolio-Projects/blob/main/Data-analysis-on-Climate-Change-Italy/Data-analysis-on-Climate-Change-Italy.ipynb)

**Goal:** Analyzing temperature evolution in Italy from 1970 to 2022.

**Description:** The project focuses on analyzing a dataset of temperature measurements at 2 meters height in Italy. The project involves loading the data, cleaning and preprocessing it, performing exploratory data analysis (EDA), analyzing the trend of the average temperature in Italy and estimating the annual variation.

**Skills:** data extraction, data cleaning, data analysis, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, SciPy, Xarray, Geopandas, Shapely.

**Results:** The analysis reveals a clear trend in the temperature, which increases throughout the years. The average increase stands at 0.04ºC for the whole country. Northern Italy witnesses the highest increase (0.048ºC/year), followed by Central Italy (0.038ºC/year) and Southern Italy (0.035ºC).

### Marketing campaigns Analysis - Computer software company
**Code:** [`Marketing-Campaigns-analysis.ipynb`](https://github.com/SerenaLangiano/Portfolio-Projects/blob/main/Marketing%20campaign%20analysis/Marketing-Campaigns-analysis.ipynb)

**Goal:** Analyzing the performance of four marketing campaigns.

**Description:** The project focuses on analyzing a dataset containing metrics collected during four marketing campaigns. The project involves cleaning and preprocessing the data, implementing a machine learning classifier, analyzing the performance the marketing campaigns.

**Skills:** data cleaning, feature engineering, machine learning, data analysis, data visualization.

**Technology:** Python, Pandas, NumPy, Seaborn, Matplotlib, Sci-kit learn.

**Results:** The analysis provides clear and immediate insights on the campaigns, including leads breakdown, leads breakdown per source and per status, and which professional domains collected quality leads.

### Ecommerce Analysis
**Code:** [`Ecommerce-Analysis-with-MySql`](https://github.com/SerenaLangiano/Portfolio-Projects/blob/d38e6faa28e558cc0d43426235560371dd34f2ac/Ecommerce-Analysis/Readme.md)

**Goal:** Analysing an eCommerce dataset to gain insights on the data.

**Description:** The project focuses on the analysis of an eCommerce dataset to gain insights on revenues, customer behaviour, products and more. The data is stored in two different databases:

- 'ecommerce' which contains two tables: customers and products;
- 'shipping' containing two tables: orders and oder_items.

**Skills:** database, SQL, queries.

**Technology:** SQL

**Results:** Using SQL queries we want to answer to the following questions:
1.	What is the total revenue for each category?
2.	Which customer has the most orders?
3.	What is the average order value for each customer?	
4.	What is the total revenue for each month?
5.	Which products have been ordered the most and how many times?
6.	Which customers have ordered a particular product and how many times?
7.	What is the average order value for each month? 
8.	What is the average quantity ordered for each product?
9.	Which category has the highest revenue per customer on average?
10.	What is the total revenue for each status and month combination?

### Healthcare Data Analysis
**Code:** [`Healthcare Data Analysis with SQL`](https://github.com/SerenaLangiano/Portfolio-Projects/blob/7979ae96478289526bc7625df83a7b4ccf8662da/Healthcare%20Data%20Analysis/readme.md)

**Goal:** The goal of this project is to analyse patient demographics by postcode and gender to determine the distribution of patients across different areas. This analysis is aimed at identifying the most suitable areas with a balanced gender distribution for a research study. Additionally, for the top two postcode areas with the largest patient populations identified, patients are filtered based on specific clinical criteria (such as asthma diagnosis, medication history, smoking status, weight, COPD diagnosis, and opt-out preferences), allowing for generating a list of eligible patients for the study.

**Description:** The data is stored in four .csv files: medication, observation, patient and clinical_codes.

**Skills:** database, SQL, queries.

**Technology:** SQL

**Results:** The goal of the first part of the project is identifying the number of patients for each postcode, and their gender. LS99 9ZZ is the postcode with the highest number of patients. This is the starting point for the second part of the project.

The goal of the second part of the project is identifying the most suitable patients for the research study within the top 2 postcodes. Patients shall meet the following criteria:

1) belong to the most suitable postcode areas in terms of patient count;
2) have asthma and are currently treating it;
3) have been prescribed either Formoterol Fumarate, Salmeterol Xinafoate, Vilanterol, Indacaterol, Olodaterol (or meds containing these ingredients) in the past 30 years;
4) are not currently smoking;
5) weight more than 40kg;
6) do not have a COPD diagnosis;
7) have not opted out of taking part in research or sharing their medical record.

### Executive Summary Adventure Works
**Code:** [`Executive summary`](https://github.com/SerenaLangiano/Portfolio-Projects/blob/98cf9a25fff4c9263d23c7ef1c4ac6e18d304a67/Executive%20Summary/Adventure%20Works%20Executive%20Summary.pdf)

**Goal:** To analyse sales and customers data for Adventure Works, a company which specialises in bikes.

**Description:** The Power BI report showcases a variety of visualisations, including a table, column chart, line chart, and Key Performance Indicators (KPIs), to represent complex sales and customer data in a digestible format. It also incorporates a Q&A visual, enabling the executive team to query the data directly and receive timely insights.

**Skills:** data visualisation.

**Technology:** Power BI Desktop.

## Experience
Data Analyst - EDP
Data Analyst and Project Manager in EU funded projects.
2020 - Present

My achievements include:

- Data Analytics to drive informed decisions in the planning and execution of Operation&Maintenance of PV and offshore wind parks. Key metrics derived from the analysis: energy production, plant availability, weather windows and fault occurrence.
- Statistical analysis on faults in different components of a PV park to assess system health and performance.
- Data cleaning (including the IQR method) to preprocess data and remove outliers.
- Implementation of a GIS-based algorithm (Python) to compute the Levelized Cost of Energy for various renewable energy technologies.
- Data visualization (Python, Excel, PowerBI) to present data analysis findings to relevant stakeholders.

My current responsibilities also cover: Project Management, Budgeting, and Writing projects' Deliverables and Milestones.

## Education
University of Cassino and Southern Lazio, Italy: 
Master's degree, Electrical Engineering
2016 - 2018

University of Cassino and Southern Lazio, Italy:
Bachelor's degree, Industrial Engineering,
2012 - 2015

## Certificates
The best way to showcase skills is by doing and sharing your job done but sometimes certificates appear to be as an indirect result. Here's a list of the ones I have (in reverse-chronological order, with the date of completion in brackets):
- [Microsoft Power BI Data Analyst Professional Certificate](https://www.coursera.org/account/accomplishments/verify/KASUZADXLYUNutm_source=link&utm_medium=certificate&utm_content=cert_image&utm_campaign=sharing_cta&utm_product=course) (May 2024) (Microsoft)
- [Microsoft Certified: Azure Data Fundamentals](https://learn.microsoft.com/en-gb/users/serenalangiano-9408/credentials/19061c06d53518be) (Aug 2023) (Microsoft)
- [Unsupervised Learning, Recommenders, Reinforcement Learning](https://www.coursera.org/account/accomplishments/certificate/B3SJUWY47QR9) (Aug 2022) (Coursera - DeepLearning.AI, Stanford Online)
- [Advanced Learning Algorithms](https://www.coursera.org/account/accomplishments/certificate/UCSRF6P7DT4D) (Jul 2022) (Coursera - DeepLearning.AI, Stanford Online)
- [Supervised Machine Learning: Regression and Classification](https://www.coursera.org/account/accomplishments/certificate/24ESLA4LGB7R) (Jun 2022) (Coursera - DeepLearning.AI, Stanford Online)

## Contacts
- LinkedIn: [@serenalangiano](https://www.linkedin.com/in/serena-langiano-89a814170/)
- Email: serenalangiano@gmail.com
