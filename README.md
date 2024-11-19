🌟 FLO CLTV Prediction
This project predicts Customer Lifetime Value (CLTV) for FLO customers using BG/NBD and Gamma-Gamma models. It helps in creating actionable insights for sales and marketing strategies, leveraging both online and offline purchase data.

🚀 Project Overview
📝 Purpose
FLO aims to enhance its medium- and long-term planning by predicting the future potential value of its customers. This project supports decision-making processes by analyzing historical customer data and segmenting customers based on their predicted CLTV.

📊 Dataset
The dataset consists of purchase history for customers who made transactions across OmniChannel platforms (online and offline) between 2020 and 2021.

📂 Dataset Features
Column Name	Description
master_id	Unique customer identifier
order_channel	Platform used for shopping (e.g., Android, iOS)
last_order_channel	Platform of the most recent purchase
first_order_date	Date of the first purchase
last_order_date	Date of the most recent purchase
order_num_total_ever_online	Total number of online purchases
order_num_total_ever_offline	Total number of offline purchases
customer_value_total_ever_online	Total spending on online purchases
customer_value_total_ever_offline	Total spending on offline purchases
interested_in_categories_12	Categories purchased in the last 12 months
🔧 Key Features
🛠 Tasks
Data Preparation: Clean and preprocess the data, handle outliers, and engineer new features.
Building CLTV Structure: Calculate metrics like recency, frequency, and monetary values.
Modeling:
Fit BG/NBD and Gamma-Gamma models.
Predict expected purchases and customer value for 3 and 6 months.
Segmentation: Create customer segments (A, B, C, D) based on standardized CLTV values.
Functionality: Automate the entire workflow into reusable functions.
📈 Project Workflow
1️⃣ Data Preparation
Handle outliers using thresholds.
Engineer total purchase and total spending features.
Convert date fields into appropriate formats.
2️⃣ CLTV Data Structure
Calculate:
Recency (weeks): Time between first and last purchase.
Frequency: Number of repeat purchases.
Monetary: Average spending per transaction.
3️⃣ Modeling
BG/NBD Model: Predict purchase frequency.
Gamma-Gamma Model: Predict monetary value.
Combine results to calculate 6-month CLTV.
4️⃣ Segmentation
Group customers into 4 segments (A, B, C, D) using CLTV values.
Provide actionable insights for strategic planning.
📊 Results
🎯 Outputs
Predicted CLTV for individual customers.
Customer Segments: A, B, C, D based on standardized CLTV.
🛠 Example Insights
Group A: High-value customers – focus on retention and upselling.
Group D: Low-value customers – optimize marketing expenses.
🛠 Tools and Libraries
Python
Pandas
NumPy
Lifetimes
Matplotlib
Scikit-learn
🌟 Contribution
Contributions are welcome!
Feel free to fork this repository, create issues, or submit pull requests for improvements.

📜 License
This project is licensed under the MIT License.

📧 Contact
For inquiries, please reach out at your-email@example.com.
