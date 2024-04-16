# coffee_sales

Introduction
The file provides an analysis of coffee bag sales from 2019 to 2022, facilitating insights into sales patterns, customer behaviour, and market trends.

Data Preparation and Cleaning
The initial dataset was found to be messy and incomplete, necessitating a thorough cleaning process which included the following steps:

Initial Review: The data, housed in the first tab, consisted of 'Order ID', 'Order Date', 'Customer ID', 'Product ID', and 'Quantity'. This setup provided a fundamental framework to structure the subsequent cleaning and analysis.

Data Enrichment: Information was augmented using the XLOOKUP function to pull relevant customer details from the 'Customers' tab, ensuring a richer and more accurate dataset for analysis.

Refining Product Information: The 'Coffee Type' data was standardised using a combination of INDEX, MATCH for cell contents, and MATCH for row positioning, which streamlined the categorisation and analysis process.

Pivot Table Creation: With clean and structured data, a pivot table was constructed to summarise and visualise the data effectively. Additional components such as a timeline, various filters, and charts were integrated to enhance interactive analysis and ease of use.


Dashboard Features

Dynamic Filters: Users can filter data by roast type, package size, and loyalty card membership.

Sales Trends Analysis: Insights into sales trends over the period from 2019 to 2022.

Top Buyer Insights: Identification of top purchasing countries and key customers, aiding targeted marketing strategies.
