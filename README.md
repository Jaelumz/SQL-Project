# Final-Project-Transforming-and-Analyzing-Data-with-SQL

## Project/Goals
Project goal is to analyze transactions made on a company's website by visitors from multiple countries and cities.
By doing this, we intend to build insights around the products making the best sales, highlighting the countries with the highest visitors on the sites as well as revenues made from those countries.

## Process
The initial step involved comprehending the dataset and delineating relationships between the tables. This entailed formalizing these connections through the implementation of primary and foreign keys. Next steps was for exploratory data anaalysis, addressing data type inconsistencies and performing data cleaning by detecting and removing duplicate rows to address specific questions. This further led to additional data transformations steps to further clean the data to filter out null or missing data, update column data and modifying the dataset.

## Results
Based on data transformation, the following can be addressed by the data:
-Countries/cities with the highest numbers of visitors on the site.
-Countries/cities with the visitors making the most purchaes on the site.
-Countries/cities with the visitors not making purchases on the site.
-Countries/cities where the company makes the most of its revenue.
-Most selling products categories based on countries/cities.
-Least selling products categories based on countries/cities.

## Challenges 
A significant challenge from lack of explicit guidance when working with the dataset. Documented information to easily comprehend the content within each column and table was not sufficiently and assumptions had to be applied to derive conclusive insights.
Furthermore, during the process of modelling relationship between the analytics and all_sessions tables. Both tables held information concerning 'products sold', 'revenue generated', and 'visitor details' such as countries and cities. Despite having columns with common names (e.g., "fullvisitorid" and "visitid"), a distinct column in either table could not be identified for direct relationship. This led to adoption of a many-to-many relationship, utilizing the "fullvisitorid" column for joining the two tables.

## Future Goals
Gain access to information explaining the data type contained within the dataset and relationships between tables.
