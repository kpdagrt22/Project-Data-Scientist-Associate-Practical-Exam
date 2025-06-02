Practical Exam: House sales
RealAgents is a real estate company that focuses on selling houses.

RealAgents sells a variety of types of house in one metropolitan area.

Some houses sell slowly and sometimes require lowering the price in order to find a buyer.

In order to stay competitive, RealAgents would like to optimize the listing prices of the houses it is trying to sell.

They want to do this by predicting the sale price of a house given its characteristics.

If they can predict the sale price in advance, they can decrease the time to sale.

Data
The dataset contains records of previous houses sold in the area.

Column Name	Criteria
house_id	Nominal.
Unique identifier for houses.
Missing values not possible.
city	Nominal.
The city in which the house is located. One of 'Silvertown', 'Riverford', 'Teasdale' and 'Poppleton'.
Replace missing values with "Unknown".
sale_price	Discrete.
The sale price of the house in whole dollars. Values can be any positive number greater than or equal to zero.
Remove missing entries.
sale_date	Discrete.
The date of the last sale of the house.
Replace missing values with 2023-01-01.
months_listed	Continuous.
The number of months the house was listed on the market prior to its last sale, rounded to one decimal place.
Replace missing values with mean number of months listed, to one decimal place.
bedrooms	Discrete.
The number of bedrooms in the house. Any positive values greater than or equal to zero.
Replace missing values with the mean number of bedrooms, rounded to the nearest integer.
house_type	Ordinal.
One of "Terraced" (two shared walls), "Semi-detached" (one shared wall), or "Detached" (no shared walls).
Replace missing values with the most common house type.
area	Continuous.
The area of the house in square meters, rounded to one decimal place.
Replace missing values with the mean, to one decimal place.
