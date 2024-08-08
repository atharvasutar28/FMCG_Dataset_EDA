# FMCG Dataset EDA
AtliQ is an industry in FMCG sector. In the FMCG world, there is a common problem of maintaining the custumor service and product quality.
I have addressed this problem and generated a full fledged EDA reporting for the company to understand where the company is actually lacking. You'll find the project in the jupyter file.
I have used numpy, pandas, seaborn and matplotlib for DataFrame and Visualization.

## Acknowledgements

 - [Codebasics Resume Project Challenges](https://codebasics.io/challenge/codebasics-resume-project-challenge)

## Data Overview
1. dim_customers.csv dataset contains customer id which is the unique id for every customer, customer name and city where the customer is located.
2. dim_date.csv dataset contains all the information about dates important for the company.
3. dim_product.csv dataset contains product name, product id which is the unique id for every product and product category.
4. dim_targets_orders.csv dataset contains customer id of every customer, on time % which represents percentage of orders delivered on time, in full % represents percentage of orders delivered on time and in full % both to check the customer service of the company.
5. fact_order_lines.csv dataste contains all information about orders and each item inside the orders.
6. fact_orders_aggregate.csv dataset contains information about OnTime, InFull and OnTime Infull information aggregated at the order level per customer.

## Tool -> Jupyter Notebook

## Authors

- [@atharvasutar28](https://www.github.com/atharvasutar28)

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

## Deployment

To deploy this project just download the raw file run it in your Jupyter Notebook.

## Note
If the gauge charts are not reflecting in the repo or there is some problem in loading the jupyter file, please download the raw file and try running it in your machine.

## Feedback

If you have any feedback, please reach out to us at atharvaz.at.work@gmail.com

## Contributing

Contributions are always welcome!

## Support

For support, email atharvaz.at.work@gmail.com or follow me and dm me on my social media handles.

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/atharvasutar28" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="atharvasutar28" height="30" width="40" /></a>
<a href="https://linkedin.com/in/https://www.linkedin.com/in/atharvasutar/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/atharvasutar/" height="30" width="40" /></a>
<a href="https://kaggle.com/atharvasutar28" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/kaggle.svg" alt="atharvasutar28" height="30" width="40" /></a>
<a href="https://discord.gg/atharvasutar28" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="atharvasutar28" height="30" width="40" /></a>
</p>

