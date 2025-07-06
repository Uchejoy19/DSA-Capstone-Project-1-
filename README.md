# DSA-Capstone-Project-1-
## Solution to Question 2

## Project Topic(Kultra Mega Stores Inventory)

### Project Overview
This project aims at providing data-driven insights into the performance of Kultra Mega Stores (KMS), to support the operations of its other division. KMS is a retail and wholesale company specializing in office supplies and furniture, serving a diverse customer base that includes individual consumers, small businesses, and large corporate clients.

### Data sources
The primary source of data for this project is a Microsoft Excel spreadsheet provided by the KMS Business Manager. The file contains detailed historical order data from 2009 to 2012 and includes the following types of information from Order details, Returns data and Customer information such as:
- Order ID, Date, and Product Details  
- Sales, Profit, and Shipping Costs  
- Customer Segment and Region

### Tools Used
- MS Excel (for data collection)[Download here](https://www.microsoft.com)
- SQL | In-depth querying, grouping, summarizing

### Case Scenerio 1 & Insights 
#### Highest Sales by Product Category  
   - (based on actual query result)
#### Top 3 Regions by Sales  
   - Lagos, Abuja, Kano  
   
#### Bottom 3 Regions by Sales  
   - Kaduna, Benue, 
#### Total Sales of Appliances in Ontario  
   - sales on specific product

#### Recommendations for 10 bottom  Customers
   - Provide tailored promotions or bundles
   - Improve customer service follow-up
#### Shipping Method with Highest Cost
   - Express Air (or actual method based on data available)


### Case Scenario II

#### Most Valuable Customers & Their Purchases
   - Customers that often buy *Technology* and *Office Supplies*

#### Top Small Business Customer by Sales
   - Small businesses filtered and ranked

#### Top Corporate Customer with large Number of Orders
   - Corporate segments that placed orders between 2009–2012

#### Most Profitable Consumer Customer
   - Customers with large profit contribution

#### Customer(s) Who Returned Items
   - Join between project and return_orders to isolate customer Segment

#### Shipping Costs vs. Order Priority Evaluation
   - Evaluated whether fast or Economical should match urgency and level of orders
      
   ### Observation
   - High-cost methods (e.g.Express Air) are often used for low-priority orders.
   - A large number of orders especially low and medium orders were shipped using Express Air which is Expensive.
   - Apparently, some urgent priority orders were shipped using trucks, which happened to be the slowest means and also contradicts the goal of the business.
   - This shows that the company did not consistently optimize shipping in relation to urgency. Therefore, the company in order to better align shipping methods should
   - Reduce shipping cost for the goods that are not urgent
   - Improve delivery performance for urgent orders by ensuring they are always shipped using metered means.

### Recommendation:
   - Align shipping methods with order priority to reduce costs. Automated shipping rules should be implemented in the order processing system to enforce the right method.


