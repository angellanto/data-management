# Ethical Data Usage in Consumer Behavior Analytics
## Dataset Source: https://archive.ics.uci.edu/dataset/352/online+retail
## Youtube Explainer Video: https://youtu.be/Z45F-Q-WqoQ
### Data Management | Individual Assignment Grade: 77/100 
### Professor Comment: 
Your ERD was well-structured, with appropriate tables and clear visualisations, complemented by optimised and well-executed SQL queries. You provided a thorough analysis of both ethical and unethical data use, incorporating real-world examples. Moreover, the attached video was particularly insightful, showcasing your in-depth understanding of SQL.

However, there are areas for improvement, including:

For Query 7, the joins are not necessary, as you can access all the required data through the Invoice table.
The same applies to Queries 3 and 4—review the joins used.
Ensure you include ethical/unethical data practices for each query, as required by the assignment.
To enhance your work further, consider the following tip and best practice:

Carefully read the assignment requirements to ensure ethical/unethical data practices are addressed in each query.

### Assignment Instructions:
E-Commerce dataset: Ethical Data Usage in Consumer Behavior Analytics

 (A) Assignment Overview:

Objective: In this assignment, you will explore how companies are managing data in the context of e-commerce. You will analyze a dataset related to customer transactions from a UK-based online retailer and assess how ethical data usage principles such as privacy, transparency, and informed consent are either adhered to or violated. The focus is on identifying key insights and potential ethical conflicts in customer data usage, suggesting ways to improve data practices to ensure ethical and responsible treatment of consumer information. 
 
 (B) Dataset Example:

E-Commerce Data: Link to Dataset on Kaggle - https://www.kaggle.com/datasets/carrie1/ecommerce-data/dataLinks to an external site.)
Description: This dataset contains transactional records from an e-commerce company, including details such as: 
InvoiceNo: A unique identifier for each transaction or invoice
StockCode: A unique code assigned to each product or item in the inventory
Description: A brief description of the product or item sold
Quantity: The number of units of the product that were sold in the transaction
InvoiceDate: The date and time when the invoice was generated
UnitPrice: The price of a single unit of the product at the time of the transaction
CustomerID: A unique identifier for the customer who made the purchase
Country: The country where the customer is located

 (C) Assignment Details:

Dataset Exploration: Carry out the steps to import the dataset into DBeaver. Analyze customer interaction data, such as purchasing behavior or website navigation patterns
SQL Queries: Write queries that could be used for customer behavior analysis, such as identifying popular products, or tracking frequent site visitors (highlighted below). Discuss how the data could be used both ethically and unethically.
For example: Segment customers into groups based on their spending to tailor market strategies: (a) Ethically, this data can be used to offer personalized discounts, reward loyalty, or provide tailored marketing content that meets the needs of specific segments (e.g., high spenders receiving VIP treatment). (b)  Unethically, companies might use this data to disproportionately target high spenders with aggressive upselling tactics or manipulate lower spenders into feeling pressured to increase their spending.

Questions to answer for the assignment, but feel free to explore further if you find more insights related to ethical or unethical data management:

Identify which customers have made the most and least transactions

Understand which customers are buying specific products and in what quantity

Identify customers with the lowest number of transactions

Identify customers with the highest number of transactions

Identify products that are trending based on purchase frequency

Identify which countries are making the most purchases

Identify customers who make frequent purchases

Track product purchasing trends over time to identify seasonal or emerging trends

Segment customers based on total spending

Proposal for improvements: Based on your analysis, propose improvements to ensure ethical data usage.

(D) Report

Screenshot of the normalized table in DBeaver (example screen)
normalized-table.png

SQL queries and their results (e.g., most purchased products, customer segmentation etc.)
Discuss how the data could be used both ethically and unethically
Recommendations for improving data ethics in customer analytics
Visualizations of insights within DBeaver (e.g., which products have been purchased the most) 
Screenshot 2024-09-11 at 12.50.50.png

Prepare a summary of your findings and proposals for more responsible data usage
Video explaining the SQL queries (e.g., how you mapped the question to a query etc.), visualizations and challenges dealing with the provided dataset, what did you learn...
