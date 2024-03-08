# Renewal customer analysis

## Project Overview🧾🧾
This project aimed to analyze a large CSV file to identify new and repeating customers. The analysis involved cleaning the data, creating a funnel visualization, and generating charts to understand the frequency and timing of repeat visits.

## Data Preparation
The first step was to load the CSV file into a Pandas DataFrame. The data was then cleaned by removing duplicate rows and correcting any data inconsistencies.

## Identifying New and Repeating Customers
To identify new and repeating customers, the data was grouped by customer ID. Customers who had only one row in the DataFrame were considered new customers. Customers with multiple rows were considered repeating customers.

## Funnel Visualization 📈
A funnel visualization was created to show the number of customers who visited the store multiple times. The funnel included the following categories:
- 2 visits
- 3 visits
- 4 visits
- ...
- 10+ visits

## Charts 📈
Charts were created to analyze the timing of repeat visits. The charts divided the data into the following time periods:
- 0-5 days
- 6-30 days
- 31-90 days
- 91-200 days
- 201-365 days
- 365+ days

The charts showed the number of customers who returned to the store within each time period.

## Libraries Used 📚📚
The project used the following Python libraries:
- Pandas for data manipulation and analysis
- NumPy for numerical operations
- Matplotlib for creating visualizations

## Conclusion
The analysis revealed insights into the customer base, including the number of new and repeating customers, the frequency of repeat visits, and the timing of those visits. This information can be used to inform marketing and customer service strategies.
