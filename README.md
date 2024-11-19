Project Purpose
FLO aims to develop a roadmap for its sales and marketing strategies. This project supports the company’s medium- and long-term planning by forecasting the potential future value of existing customers.

Dataset
The project uses a dataset containing historical purchase data from OmniChannel customers who made purchases in both online and offline channels during 2020-2021. Key variables in the dataset include:

master_id: Unique customer identifier
order_channel: Platform used for shopping (e.g., Android, iOS, Desktop, Mobile, Offline)
last_order_channel: The platform of the most recent purchase
first_order_date: Date of the first purchase
last_order_date: Date of the most recent purchase
last_order_date_online: Date of the most recent online purchase
last_order_date_offline: Date of the most recent offline purchase
order_num_total_ever_online: Total number of online purchases
order_num_total_ever_offline: Total number of offline purchases
customer_value_total_ever_offline: Total expenditure in offline purchases
customer_value_total_ever_online: Total expenditure in online purchases
interested_in_categories_12: Categories shopped in during the last 12 months
Key Tasks
Task 1: Data Preparation
Clean and preprocess the data, including outlier handling and feature engineering.
Convert date columns to a proper datetime format.
Task 2: Building the CLTV Data Structure
Calculate required variables such as recency, frequency, and monetary for CLTV calculation.
Task 3: Modeling
Fit the BG/NBD model to estimate expected purchases in the next 3 and 6 months.
Fit the Gamma-Gamma model to predict average monetary values.
Calculate 6-month CLTV values.
Task 4: Segmentation
Segment customers into four groups (A, B, C, D) based on standardized CLTV scores.
Provide actionable insights and recommendations for selected segments.
Task 5: Functionality
Implement a function to automate the entire process from data preparation to CLTV calculation and segmentation.
Tools and Libraries
Python
Pandas
NumPy
Matplotlib
Datetime
Lifetimes

Contributing
Feel free to fork the repository and submit pull requests. Feedback and suggestions are always welcome!

License
This project is licensed under the MIT License.
