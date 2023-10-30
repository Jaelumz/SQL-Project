# Final-Project-Transforming-and-Analyzing-Data-with-SQL

## Project/Goals
The goal of this project is to analyze transactions made on a company's website by visitors from multiple countries and cities.
By doing this, we intend to build insights around the products making the best sales, highlighting the countries with the highest visitors on the sites as well as revenues made from those countries.

## Process
My first task was to understand the data set and define relationships between the tables.
I proceeded to establish these associations by implementing primary and foreign keys.
After completing this step, I carried out some exploratory data analysis, during which I data type discrepancies
I did some data cleansing by identifying duplicate rows and deleting unwanted rows.
Next stage entailed identifying the objective by highlighting the columns that will help in addressing the questions.
This led to additional cleaning efforts - updating the column data, filtering out null or missing data and modifying the data set to allow for more transformations.

## Results
Based on my data transformation, the data can be used to address the following:
-Countries/cities with the highest numbers of visitors on the site.
-Countries/cities with the visitors making the most purchaes on the site.
-Countries/cities with the visitors not making purchases on the site.
-Countries/cities where the company makes the most of its revenue.
-Most selling products categories based on countries/cities.
-Least selling products categories based on countries/cities.

## Challenges 
My primary challenge throughout this project was the absence of clear guidance while working with the dataset. The documented information was not enough to help me easily understand the within each columns and table. As such, assumptions were necessary to derive final insights.
A second challenge I encountered was with establishing relationship between the analytics and the all_sessions table. Those two tables held important information regarding products sold, revenue generated and information on the visitors such as their countries and cities. While both tables contained columns with common names (such as "fullvisitorid" and "visitid"), I could not find any distinct column in either table that would enable a straightforward relationship. This compelled me to employ a many-to-many relationship to join the two tables based on the "fullvisitorid" column.

## Future Goals
In the future, I would aspire to have access to more information explaining the type and nature of the data contained within the data set and the relationship between the tables.
