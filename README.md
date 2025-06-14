![image](https://github.com/user-attachments/assets/b06087ac-06f9-4d95-b91d-33627adc4ea0)

Staffelter Hof Winery is Germany's oldest business, established in 862 under the Carolingian dynasty. It has continued to serve customers through dramatic changes in Europe, such as the Holy Roman Empire, the Ottoman Empire, and both world wars. What characteristics enable a business to stand the test of time?

To help answer this question, BusinessFinancing.co.uk researched the oldest company still in business in **almost** every country and compiled the results into several CSV files. This dataset has been cleaned.

Having useful information in different files is a common problem. While it's better to keep different types of data separate for data storage, you'll want all the data in one place for analysis. You'll use joining and data manipulation to work with this data and better understand the world's oldest businesses.

## The Data
`data/businesses.csv` and `data/new_businesses.csv`
|Column|Description|
|------|-----------|
|`business`|Name of the business (varchar)|
|`year_founded`|Year the business was founded (int)|
|`category_code`|Code for the business category (varchar)|
|`country_code`|ISO 3166-1 three-letter country code (char)|

`data/countries.csv`
|Column|Description|
|------|-----------|
|`country_code`|ISO 3166-1 three-letter country code (varchar)|
|`country`|Name of the country (varchar)|
|`continent`|Name of the continent the country exists in (varchar)|

`data/categories.csv`
|Column|Description|
|------|-----------|
|`category_code`|Code for the business category (varchar)|
|`category`|Description of the business category (varchar)|

## What is the oldest business on each continent? Save your answer as a DataFrame called oldest_business_continent with four columns: continent, country, business, and year_founded in any order.
![image](https://github.com/user-attachments/assets/158a919c-2412-4003-b4e7-f36aecb46ddc)

## How many countries per continent lack data on the oldest businesses? Does including new_businesses change this? Count the number of countries per continent missing business data, including new_businesses, and store the results in a DataFrame named count_missing with columns for the continent and the count.

![image](https://github.com/user-attachments/assets/939fd648-0c01-4245-809e-36a605d5a52c)

## Which business categories are best suited to last many years, and on what continent are they? Create a DataFrame called oldest_by_continent_category that stores the oldest founding year for each continent and category combination. It should contain three columns: continent, category, and year_founded, in that order.
![image](https://github.com/user-attachments/assets/77943b61-7b50-4795-aa26-c561a31cf95b)


