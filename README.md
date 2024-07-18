# Forage Quantium Data Analytics Virtual Experience Program.

Project Overview and Task Insights

This virtual experience program involves analyzing chip purchases at supermarkets. The aim of this project was to evaluate different customers' purchasing behaviours to provide insights of customer preferences to the client.

Language: Python 3.8

Packages: pandas, matplotlib, mlxtend, datetime, scipy, re.


Data preparation and customer analytics:

Data cleaning: Changed the date from integer format to datetime, removed Salsas from the products and removed outliers, and unnecessary characters and spaces.
Merged both DataFrames into one for the analysis.
Analyzed purchase behaviours of different customers by using statistical methodologies such as A/B tests and Affinity Analysis:
Customers segments are grouped by:
* LIFESTAGE: Customer attribute that identifies whether a customer has a family or not and what point in life they are at e.g. are their children in pre-school/primary/secondary school.

* PREMIUM_CUSTOMER: Customer segmentation used to differentiate shoppers by the price point of products they buy and the types of products they buy. It is used to identify whether customers may spend more for quality or brand or whether they will purchase the cheapest options.


Insights:

* A significant majority of customers, 90%, tend to purchase multiple packs of chips in a single transaction, indicating a strong preference for bulk buying.
* Seasonal trends show an increase in transactions during December, likely linked to Christmas celebrations, with peak sales reaching $6410.9.
* The 175g chip pack size emerges as the most popular choice among consumers, accounting for 27% of total sales and over 120,000 units sold.
* "Kettle Mozzarella Basil Pesto 175g" leads product sales with 6381 units sold, closely followed by "Kettle’s Tortilla Chips Honey Jalapeño Chili 150g" at 6309 units sold.
* Kettle dominates the market, being the preferred brand across most customer segments. However, exceptions exist for Budget-OLDER FAMILIES and Mainstream-RETIREES, which tend to buy products from the brand Smiths.
* Despite Kettle and Smiths being the preferred brands, Dorito Corn Chip Supreme 380g is the top-selling product, generating $39052 in revenue, which is 13% higher than Kettle's best-selling product.
* Sales are driven by three customer segments: Budget Older-Families, Mainstream Young-Singles/Couples, and Retirees. The Budget Older-Families segment shows a higher quantity of purchases per transaction, setting it apart from the other segments. For Mainstream Young-Singles/Couples and Retirees, sales correspond to the customer count within those segments.
