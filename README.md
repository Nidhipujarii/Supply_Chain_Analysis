# Supply Chain Analysis

## **Comapny's background**
AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

## **Problem Statement**
+ AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. 
+ It is speculated that customer retention issues due to possible delays or incomplete deliveries of essential products, impacting the overall customer service.
+ Management wants to fix this issue before expanding to other cities. 
+ So they have tasked the supply chain analytics team with tracking the **'On-time delivery (OT) %'**,**'In-full delivery (IF) %'**,' and **'OnTime in full (OTIF) %'** for all customer orders on a daily basis. 

## Let's understand the key metrics before diving deep:                                                                

### ***On Time delivery % (OT%)***                                                                                    
+ It determines if an order is delivered as per the agreed time with the customer. 

### Formula: 
+ Number of orders delivered On Time / Total Number of Orders                                   

###  ***In Full delivery % (IF%)***                                                                                                
+ It determines if an order is delivered in full as per the requested quantity by the customer.   

### Formula: 
+ Number of orders delivered in Full quantity / Total Number of Orders        
                                                                                   
### ***On Time In Full (OTIF) %***                                                                           
+ It determines if an order is delivered BOTH in full and On Time as per the customer order request.

### Formula: 
+ Number of orders delivered both IN Full & On Time / Total Number of Orders

### ***Line Fill Rate (LIFR%)***                                                                                          
+ IT is an important metric to understand how many lines they shipped out of the total lines ordered. 

### Formula: 
+ Number of order lines shipped In Full Quantity / Total Order Lines

### ***Volume Fill Rate (VOFR%)***                                                                                         
+ It is understand the total quantity they are able to ship for a customer per order or for a given period of time

### Formula: 
+ Total Quantity shipped / Total Quantity Ordered

### ***Orders and Lines***
+ Orders are nothing but a unique request placed by a customer on a given date
+ Within an order, a customer could request multiple items. Each of these items requested within the order is called an order line


## DASHBOARD OVERVIEW
LINK: https://app.powerbi.com/links/lgbWiMA3qp?ctid=9a85a132-3ea9-40f7-bb17-28ce875728cc&pbi_source=linkShare&bookmarkGuid=2de39884-180e-4571-8e57-323859f733e2

![Screenshot (203)](https://github.com/Nidhipujarii/Supply_Chain_Analysis/assets/107934279/90e74992-2bdc-49e9-85d8-f332b242c41c)

![Screenshot (204)](https://github.com/Nidhipujarii/Supply_Chain_Analysis/assets/107934279/331ac756-211e-499d-bf56-435519a831e5)

![Screenshot (205)](https://github.com/Nidhipujarii/Supply_Chain_Analysis/assets/107934279/7d4d1871-c7dd-4d68-86af-2b5849d43a16)


### Key Insights:

+ All key metrics **(OT%, IF%, OTIF%)** significantly **lag** behind the set targets.
+ Out of a total of **13.43 million** orders, **458K** remain **undelivered**.
+ **AM Milk**, **AM Curd**, and **AM Butter** are identified as the items with the highest number of **undelivered orders**.
+ Products like **Ghee**, **Curd**, and **Butter** experience the most **delays in delivery**.
+ **Lotus Mart**, **Coolblue**, and **Acclaimed Stores** emerge as the customers with the **highest order** volumes.
+ Despite ongoing efforts, there is a **lack of noticeable improvement** in any of the **key metrics** over the past few months.

## Tools Used: 
### Powerbi (
### Explored 🔁 Revised 🔁 Practiced 🔁 various New DAX function. It was Fun🥳
### HAPPY ANALYZING💻
