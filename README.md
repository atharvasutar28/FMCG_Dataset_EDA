# FMCG Dataset EDA
AtliQ is an industry in FMCG sector. In the FMCG world, there is a common problem of maintaining the custumor service and product quality.
I have addressed this problem and generated a full fledged EDA reporting for the company to understand where the company is actually lacking. You'll find the project in the jupyter file.
I have used numpy, pandas, seaborn and matplotlib for DataFrame and Visualization.

## Data Overview
1. dim_customers.csv dataset contains customer id which is the unique id for every customer, customer name and city where the customer is located.
2. dim_date.csv dataset contains all the information about dates important for the company.
3. dim_product.csv dataset contains product name, product id which is the unique id for every product and product category.
4. dim_targets_orders.csv dataset contains customer id of every customer, on time % which represents percentage of orders delivered on time, in full % represents percentage of orders delivered on time and in full % both to check the customer service of the company.
5. fact_order_lines.csv dataste contains all information about orders and each item inside the orders.
6. fact_orders_aggregate.csv dataset contains information about OnTime, InFull and OnTime Infull information aggregated at the order level per customer.

## Tool -> Jupyter Notebook

## Approach
Step 1 -> Importing all necessary libraries and loading all datasets
Step 2 -> Cleaning the data and merging the tables. 
Step 3 -> Viewing the dataset info.
Step 4 -> Analyzing all important insights and performing data vizualization.

### Key Performance Indicators
1. ontime_target% - contains the percent of deliveries delivered on time.
2. infull_target% - contains the percent of deliveries delivered in full quantity.
3. otif_target% - contains the percent of deliveries delivered on time and in full quantity both.
4. order_qty - It is the number of products requested by the customer to be delivered.
5. delivered_qty: It is the number of products that are actually delivered to the customer.
6. agreed_delivery_date: It is the date agreed between the customer and Atliq Mart to deliver the products.
7. actual_delivery_date: It is the actual date Atliq Mart delivered the product to the customer.

### Skills Acquired
1.Data Cleaning
2. Data Transformation
3. Data Analysis
4. Data Visualization
6. Python
7. Numpy, Pandas, Seaborn and Matplotlib.

## Note
If the gauge charts are not reflecting in the repo or there is some problem in loading the jupyter file, please download the raw file and try running it in your machine.
