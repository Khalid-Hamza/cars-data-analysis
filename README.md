#  Data Analyst Project – Cars Data (432 rows, 15 columns)

## Project Objective
This project analyzes a dataset of 432 cars (15 features) with the goal of:

- Understanding the key factors that influence car prices (MSRP).  
- Studying fuel consumption and vehicle performance.  
- Comparing brands, types, and origins (Asia, Europe, USA).  
- Identifying the cars that provide the best balance between **price – horsepower – fuel efficiency**.  

---

##  Phase 1: Data Cleaning & Preparation

- **Q1: Missing values**  
  Find all null values in the dataset.  
  If a column has missing values, replace them with the mean of that column.  

- **Q2: Category counts**  
  What are the different car makes available in the dataset?  
  What is the frequency (number of models) of each make?  

- **Q3: Filtering**  
  Show all records where the car origin is *Asia* or *Europe*.  

- **Q4: Removing unwanted records**  
  Remove all rows where the car weight is above 4000.  

- **Q5: Column transformation**  
  Increase all values of the column `MPG_City` by **+3**.  

---

##  Phase 2: Exploratory Data Analysis (EDA)

- **Q6: Average price by groups**  
  What is the average MSRP by car make, type, and origin?  

- **Q7: MSRP vs Invoice**  
  What is the average difference between MSRP and Invoice?  
  Does this difference vary by brand?  

- **Q8: Correlations**  
  What is the correlation between MSRP and:  
  - EngineSize  
  - Cylinders  
  - Horsepower  

- **Q9: Weight and fuel efficiency**  
  Do heavier cars (Weight) consume more fuel in city (MPG_City) and highway (MPG_Highway)?  

---

##  Phase 3: Visualization & KPIs

- **Q10: Price distribution**  
  What is the distribution of MSRP prices?  
  Are there outliers?  

- **Q11: Price by origin and type**  
  How do prices vary by origin (Asia, Europe, USA)?  
  How do prices vary by car type (SUV, Sedan, etc.)?  

- **Q12: Fuel consumption comparison**  
  What is the difference between city (MPG_City) and highway (MPG_Highway) consumption?  
  Do cars from different origins have similar consumption patterns?  

- **Q13: Top brands**  
  Which are the top 10 most represented brands in the dataset?  
  Are these brands oriented toward economy cars or premium cars?  

- **Q14: Best value for money**  
  Which cars provide the best compromise between:  
  - Affordable price (low MSRP)  
  - High horsepower  
  - High fuel efficiency (MPG)  
