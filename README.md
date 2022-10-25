# Analytical-Research-For-a-Telecommunication-Company
This README describes work done on the telecommunication data as a project for Yandex Practicum Data Analyst courses.

# Technologies
The analysis takes the form of a single Jupyter notebook "Telecom".

## Resources used
Python 3.8 and associated packages Jupyter:
- pandas,
- numpy,
- matplotlib.pyplot,
- seaborn,
- scipy.stats,
- math,
- io.BytesIO,
- requests,
- statistics,
- datetime.

These packages all come as part of the Anaconda distribution of Python.

# Introduction

Telecom company Megaline was launched in the end of 2017. It offers two tariffs: Smat and Ultra. 
We have to make analysis according to the results of the year.

**The purpose of the analysis:**
1. It is necessary to analyze users behavior  and draw a conclusion - which tariff brings more revenue.

2. Also company managment asks to chek if the average user in Moscow generates more revenue than regional user.

**Data sets -** inner data based on a sample of 500 users:
- user information,
- call information,
- information about messages,
- information about internet sessions,
- information about tariffs.

**Tariff Description**

_Tariff "Smart":_
1. Monthly fee: 550 rubles
2. Included 500 minutes of talk, 50 messages and 15 GB of internet traffic
3. The cost of services above the tariff package:
    - minute of conversation: 3 rubles
    - message: 3 rubles
    - 1 GB of Internet traffic: 200 rubles

_Tariff "Ultra":_
1. Monthly fee: 1950 rubles
2. Included 3000 minutes of calls, 1000 messages and 30 GB of internet traffic
3. The cost of services above the tariff package:
    - minute of conversation: 1 ruble
    - message: 1 ruble
    - 1 GB of Internet traffic: 150 rubles
   
**Contents:**

1. Data overview and preprocessing
    - Calls dataset
    - Internet dataset
    - Message dataset
    - Tariffs dataset
2. Users dataset
    - Let's have a look at our clients
    - How many users do we have?
    - What ages are represented?
    - Where do our users live?
    - Calculations to explore our users behavior.
    - How our customers use their connection?
3. What is our income?
4. Let's check the hipotesis.
    - Does income between tariffs is different?
    - Does income between Moscow and other regions is different?
5. General conclusions
