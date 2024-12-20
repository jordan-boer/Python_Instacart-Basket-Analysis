# Python_Instacart-Basket-Analysis
Career Foundry project using Python coding in Jupyter notebooks to conduct an analysis of Instacart's sales patterns and purchasing behaviors to develop targeted marketing strategies.
## Project Overview
Instacart is an online grocery store that operates through an app. Instacart already has very good sales, but they want to uncover more information about their sales patterns. I was tasked to perform an initial data and exploratory analysis of some of their data in order to derive insights and suggest strategies for better segmentation based on the provided criteria. Assuming they can't target everyone using the same methods, I looked at the variety of customers in their database along with their purchasing behaviors to implement a targeted marketing strategy. Stakeholders want to provide different customers with applicable marketing campaigns to see whether they have an effect on the sale of their products. My analysis will inform what this strategy might look like to ensure Instacart targets the right customer profiles with the appropriate products.
## Key Questions
- The sales team needs to know what the busiest days of the week and hours of the day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders.
- What are the particular times of the day when people spend the most money, as this might inform the type of products they advertise at these times?
- Are there certain types of products that are more popular than others? The marketing and sales teams want to know which departments have the highest frequency of product orders.
- What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?
- Are there differences in ordering habits based on a customer’s loyalty status?
- Are there differences in ordering habits based on a customer’s region?
- Is there a connection between age and family status in terms of ordering habits?
- What different classifications does the demographic information suggest? Age? Income? Certain types of goods? Family status?
- What differences can you find in ordering habits of different customer profiles? Consider the price of orders, the frequency of orders, the products customers are ordering, and anything else you can think of.
## Folders
Content description of project folders:
- 01 Project Management: contains the project brief that outlines the details of the project.
- 02 Data (not included due to size limitations): contains two subfolders:
- - Original Data: contains the original datasets of the project.
- - Prepared Data: cleaned, wrangled, and merged datasets used for analysis.
- 03 Scripts: contains Jupyter notebooks of each step of my analysis written in Python code.
- - Practice Scripts: contains Jupyter notebooks used during my read through of the Career Foundry course exercise.
- 04 Analysis: contains the subfolder "Visualizations" that includes all the visualizations I created to develop and explain insights.
- 05 Sent to client: contains an Excel file as the final deliverable outlining all the steps done in my analysis, along with my final visualizations and recommendations.
## Data
Original datasets used for this project and columns they contain:
- customers: user_id, First Name, Surnam, Gender, STATE, Age, date_joined, n-dependents, fam_status, income
- departments: department_id, department
- orders: order_id, user_id, eval_set, order_number, order_dow, order_hour_of_day, days_since_prior_order
- orders_products_prior: order_id, product_is, add_to_cart_order, reorder
- products: product_id, product_name, aisle_id, department_id, prices
Some columns were renamed for clarity and data sets were merged multiple times throughout the project.
## Tools
Code was written in Jupyter notebooks using Python and utilizing the following libraries:
- Pandas: for data manipulation and analysis
- NumPy: for mathematical functions
- OS: for reading/writing files and navigating file system
- Matplotlib.pyplot: for creating visualizations
- Matplotlib.cm: for adding color to plots using colormaps
- Seaborn: for more advanced statistical data visualizations
- Scipy: for scientific and technical computing with advanced mathematical functions
## Source and Disclaimer
Source: "The Instacart Online Grocery Shopping Dataset 2017”, Accessed from www.instacart.com/datasets/grocery-shopping-2017 via Kaggle
Disclaimer: Instacart is a real company and their data is available to the public online, however, the customer data, as well as the “prices” column in the products data set, were both fabricated for the purpose of Career Foundry's Data Analytics program.

