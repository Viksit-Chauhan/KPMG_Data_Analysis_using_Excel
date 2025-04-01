Project Title: KPMG Data Analysis using Excel <br>
Project Overview: <br>
This project aims to analyze customer demographics, transactions and new customer data to provide insights into business performance and customer behavior. The project consists of six tasks that involve data cleaning, data analysis and visualization using Excel. <br>
Dataset:KPMG Project Dataset <br>
Dataset Description: <br>
1. Customer Address Dataset <br>
Description: Contains information about customers' addresses and property valuation. <br>
Columns: <br>
 ● customer_id: Unique identifier for each customer. <br>
 ● address: The street address of the customer. <br>
 ● postcode: Postal code for the customer’s address. <br>
 ● state: The state in which the customer resides (e.g., New South Wales, QLD). <br>
 ● country: The country of residence, which is Australia for all entries. <br>
 ● property_valuation: An integer value representing the valuation of the property where the customer
 resides. <br>
2. Customer Demographic Dataset <br>
Description: Contains demographic information about customers, including their personal details, job information, and purchase behavior. <br>
Columns: <br>
 ● customer_id: Unique identifier for each customer. <br>
 ● first_name: Customer’s first name. <br>
 ● last_name: Customer’s last name. <br>
 ● gender: Customer’s gender. <br>
 ● past_3_years_bike_related_purchases: Number of bike-related purchases made by the customer in the past
 three years. <br>
 ● DOB:Date of birth of the customer. <br>
 ● job_title: Job title of the customer. <br>
 ● job_industry_category: Industry category of the customer’s job. <br>
 ● wealth_segment: Wealth segment classification of the customer (e.g., Mass Customer). <br>
 ● deceased_indicator: Indicator if the customer is deceased (Y/N). <br>
 ● default: Default status, including potential erroneous data. <br>
 ● owns_car: Indicates if the customer owns a car (Yes/No). <br>
 ● tenure: The tenure of the customer. <br>
3. Transactions Dataset <br>
Description: Contains details of transactions made by customers, including product details and transaction dates. <br>
Columns: <br>
 ● transaction_id: Unique identifier for each transaction. <br>
 ● product_id: Unique identifier for each product involved in the transaction. <br>
 ● customer_id: Unique identifier for the customer who made the transaction. <br>
 ● transaction_date: The date when the transaction occurred. <br>
 ● online_order: Indicates if the order was made online (TRUE/FALSE). <br>
 ● order_status: Status of the order (e.g., Approved). <br>
 ● brand: Brand of the product purchased. <br>
 ● product_line: Product line (e.g., Standard). <br>
 ● product_class: Product class (e.g., medium). <br>
 ● product_size: Size of the product. <br>
 ● list_price: Listed price of the product. <br>
 ● standard_cost: Standard cost of the product. <br>
 ● product_first_sold_date: The date when the product was first sold. <br>
4. New Customer List Dataset <br>
Description: Contains information about potential new customers, including their personal details, job information, and potential value. <br>
Columns: <br>
 ● first_name: First name of the potential new customer. <br>
 ● last_name: Last name of the potential new customer. <br>
 ● gender: Gender of the potential new customer. <br>
 ● past_3_years_bike_related_purchases: Number of bike-related purchases made in the past three years. <br>
 ● DOB:Date of birth of the potential new customer. <br>
 ● job_title: Job title of the potential new customer. <br>
 ● job_industry_category: Industry category of the potential new customer’s job. <br>
 ● wealth_segment: Wealth segment classification. <br>
 ● deceased_indicator: Indicator if the potential new customer is deceased (Y/N). <br>
 ● owns_car: Indicates if the potential new customer owns a car (Yes/No). <br>
 ● tenure: Tenure of the potential new customer. <br>
 ● address: Address of the potential new customer. <br>
 ● postcode: Postal code for the address. <br>
 ● state: State of residence. <br>
 ● country: Country of residence. <br>
 ● property_valuation: Valuation of the property. <br>
 ● Rank: Rank based on some criteria. <br>
 ● Value: Value of the potential new customer. <br>
Task 1: Data Cleaning  <br>
Objective: Prepare the datasets for analysis by cleaning and correcting any inconsistencies. <br>
1. Customer Address Data: <br>
 ○ Remove any duplicate records. <br>
 ○ Ensure all state names are correctly formatted. <br>
2. Customer Demographic Data: <br>
 ○ Identify and correct any erroneous data entries (e.g., invalid characters in default). <br>
 ○ Standardize the format for missing data entries. <br>
 ○ Correct any anomalies in gender representation. <br>
3. Transaction Data: <br>
 ○ Ensure that transaction_date is in a consistent date format. <br>
 ○ Removeanyrecords with missing or incomplete information. <br>
4. NewCustomer Data: <br>
 ○ Standardize address formatting. <br>
 ○ Ensure consistent gender representation. <br>
 ○ Correct any anomalies in job_title and job_industry_category. <br>
Task 2: Customer Segmentation  <br>
Objective: Segment customers based on demographic and transaction data to identify key customer groups. <br>
1. Segmentation by Wealth Segment: <br>
 ○ Showthenumber of customers in each wealth_segment. <br>
 ○ Calculate the average tenure for each wealth_segment. <br>
2. Segmentation by Gender: <br>
 ○ Showingthe number of customers by gender. <br>
 ○ Calculate the average past_3_years_bike_related_purchases for each gender. <br>
3. Segmentation by Job Industry: <br>
 ○ Showingthe number of customers in each job_industry_category. <br>
 ○ Analyze the distribution of wealth_segment within each industry. <br>
Task 3: Transaction Analysis  <br>
 Objective: Analyze transaction data to identify trends and patterns. <br>
1. Sales Trend Analysis: <br>
 ○ Create a chart showing the total sales per month. <br>
 ○ Identify any seasonal trends or significant spikes in sales. <br>
2. Product Performance Analysis: <br>
 ○ Showthetotal sales for each brand. <br>
 ○ Calculate the total sales and average list_price for each product_line. <br>
3. Customer Purchase Behavior: <br>
 ○ Identify the top 10 customers based on total transaction value. <br>
 ○ Calculate the average number of purchases per customer. <br>
Task 4: New Customer Insights  <br>
Objective: Analyze the new customer dataset to provide insights into potential new customer behavior and value. <br>
1. NewCustomer Demographics: <br>
 ○ Showthedistribution of new customers by wealth_segment and job_industry_category. <br>
 ○ Calculate the average past_3_years_bike_related_purchases for new customers. <br>
2. NewCustomer Location Analysis: <br>
 ○ Create a map or chart showing the distribution of new customers by state. <br>
 ○ Analyze the correlation between property_valuation and customer wealth_segment. <br>
3. Potential Revenue from New Customers: <br>
 ○ Estimate potential revenue based on past_3_years_bike_related_purchases and value. <br>
Task 5: Customer Lifetime Value (CLV) Analysis <br>
Objective: Calculate and analyze the customer lifetime value to identify the most valuable customers. <br>
1. CLVCalculation: <br>
 ○ Use the formula <br>
 ○ Calculate CLV for each customer using transaction data. <br>
 Formula <br>
  CLV=(Average Purchase Value×Purchase Frequency)×Customer Lifespan <br>
  Average Purchase Value (APV): <br>
  ● This is the average amount of money a customer spends in a single purchase. <br>
  APV=Total Revenue/ Number of purchases <br>
  ● Total Revenue is the sum of all revenues generated from all purchases. You can get the total revenue <br>
  by using Transactional data. <br>
  ● Number of Purchases is the total count of all transactions of that customer. <br>
  Purchase Frequency (PF): <br>
  ● This is the average number of times a customer makes a purchase in a given period. <br>
  PF= Total Number of Transactions / Number of Unique Customers <br>
  Customer Lifespan (CL): <br>
  ● This represents the average number of years a customer remains active. <br>
  ● In your dataset, this is represented by the tenure column in the Customer Demographic dataset. <br>
2. Segment CLV Analysis: <br>
 ○ Showaverage CLV by wealth_segment. <br>
 ○ Analyze the relationship between CLV and customer demographics (e.g., gender, job industry). <br>
Task 6: Executive Summary and Recommendations <br>
Objective: Summarize findings and provide actionable recommendations for business strategies. <br>
1. Summaryof Key Insights: <br>
 ○ Highlight key findings from customer segmentation, transaction analysis, new customer insights, and CLV analysis. <br>
2. Recommendations: <br>
 ○ Provide recommendations for marketing strategies targeting high-value customer segments. <br>
 ○ Suggest potential areas for business expansion based on new customer location analysis. <br>
 ○ Recommend improvements in product offerings based on transaction analysis. <br>
