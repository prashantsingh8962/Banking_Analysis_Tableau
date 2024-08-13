# Banking_Analysis_Tableau


## Project Overview
Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market. 

[Codebasics Resume Project Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge/11)

AtliQ Data Services came to know about this through an internal link and approached Mitron Bank with a proposal to implement this project. However, the strategy director of Mitron Bank, Mr. Bashnir Rover is skeptical and asked them to do a pilot project with the sample data before handing over them the full project. They provided a sample dataset of 4000 customers across five cities on their online spending and other details.

This project is designed to provide actionable insights to stakeholders, enabling them to make informed decisions that will drive the company's continued success.

## Tech Stacks
- Tableau Desktop
- Excel
- Calculated Fields
- Data Modeling
- Tableau Prep (for data preparation)

## Tableau Techniques Learned
- Key questions to ask before starting a dashboard project
- Creating calculated fields
- Using parameters for dynamic filtering and interaction
- Data modeling and relationships
- Bookmarking and navigating between different visualizations
- Avoiding zero-division errors using the `DIVIDE()` function
- Creating custom date tables using calculated fields
- Designing dynamic titles based on filters applied
- Implementing KPIs and conditional formatting
- Data validation and accuracy checks
- Publishing and managing Tableau dashboards on Tableau Server or Tableau Public
- Setting up scheduled data refreshes
- Collaboration and access management in Tableau Server
- And more...

## Dataset Understanding
Understanding the available data is crucial for effective analysis. Here’s a breakdown of the dataset used in this project:

- **Dimension Tables**: Contain static data such as customer and product details.
- **Fact Tables**: Contain transactional data.

### Key Tables:
## Column Description for dim_customers:
- customer_id: This column represents the Unique ID assigned to each customer.
- gender: This column represents the gender of the customer. (Male, Female)
- age_group: This column categorizes the customer into different age groups. (21-24, 25-34, 35-45, 45+)
- marital_status: This column indicates the marital status of the customer (single, married).
- city: This column represents the city of residence for the customer. (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru)
- occupation: This column denotes the occupation or profession of the customer. (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees)
- average_income: This column indicates the monthly average income of the customer, in INR currency.


## Column Description for fact_spends:
- customer_id: This column represents the Unique ID of each customer, linking to the dim_customer table.
- month: This column indicates the month in which the spending was recorded. (May, June, July, August, September, October)
- category: This column describes the category of spending (Entertainment, Apparel, Electronics, etc).
- payment_type: This column specifies the type of payment used by the customer (Debit Card, Credit Card, UPI, Net Banking).
- spends: This column shows the total amount spent by the customer in the specified month, category and payment_type.

## Data Modeling
Data modeling is the foundation of the Tableau report. A well-structured data model enhances the performance and accuracy of the dashboard. This project follows best practices in data modeling, utilizing a snowflake schema.

<img src="https://github.com/prashantsingh8962/Banking_Analysis_Tableau/blob/main/Resources/data%20model%20.png" class="center">

## Dashboard Design
The dashboard design is based on mockups received from stakeholders. Each view serves a specific business function:

- **Demographic View**: 
  <img src="https://github.com/prashantsingh8962/Banking_Analysis_Tableau/blob/main/Resources/Demographic.png" class="center">

- **Sales Analysis 1 View**: 
  <img src="https://github.com/prashantsingh8962/Banking_Analysis_Tableau/blob/main/Resources/Sale%20analysis1.png" class="center">

- **Sales Analysis 2 View**: 
  <img src="https://github.com/prashantsingh8962/Banking_Analysis_Tableau/blob/main/Resources/sale%20analysis%202.png" class="center">


## Project Outcome
This Tableau report enables data-driven decision-making, helping to address various business challenges and opportunities. Stakeholders can use this report to answer critical business questions and drive future growth.

## Report Links
- [Live Dashboard Link](https://github.com/prashantsingh8962/Banking_Analysis_Tableau/blob/main/Dashboard/My%20Banking%20tableau.twb)


This README provides a clear and comprehensive overview of the Tableau project, emphasizing the tools, techniques, and outcomes. It’s designed to be informative for anyone looking to understand the project's scope and implementation.
