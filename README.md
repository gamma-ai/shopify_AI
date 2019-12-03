## ShopifyAI_API
###### -->QUANTIFYING PRICES TO GAIN A RETURN ON EACH PURCHASE BASED ON LOW TO HIGH PRICES IN RETAIL

## Overview
###### starting_balance = 6000 
###### spent in the 10 categories = 600
###### biweekly dropshipping = 26 weeks 
###### first 30 items of each category

This algorithm/analysis is broken down to form a simplistic automated pricing tool to find how much to price an item based on the initial starting balance with a return/profit target in mind while analyzing risk in a volatile marketplace. 

### Step 1:
#### The procedure will consist of building a webscraper via python,beautifulsoup and pandas. 
#### After this step in the procedure we will be classifying the price versus the item in the category and join the price to the category to optimize classification(Graphs and code are located in shopifai_ai directory).

### Step 2:
#### After the first step in the procedure has been finished, the next step will be to calculate  the mean in a  to identify the average price in each of the ten categories in the store.
(Tops,
Graphic T's,
Bottom, 
Plus, 
Dresses, 
Outerwear - Cardigans, 
Shoes and Accessories, 
Senegence Lipsense & Shadowsense, 
Bags).

#### PRICING TOOL IMPLENTATION
While the prices and items have been joined via the webscraper, we can now plot the prices and items to find the average price in each category and find a price to sell items at and still have a biweekly/annual return percentage. 
This will help us to develop an automated tool to price the items to compete in the market.

#### Automate the dropshipping process by optimizing the stores traffic by A/B testing the number of sales compared to incoming items.
#### Output will be 
(IF I PAY $15, AND MY STARTING INVESTMENT IS: $6000, 
WITH AN INVENTORY OF: 60 ITEMS,
WHILE I HAVE A PROFIT TARGET OF: $294.2307692307692 BIWEEKLY, 
MY RETURNS WILL BE: 0.05769230769230769 PER SALE, 
WHILE THE ITEM WILL HAVE A NEW PRICE OF: $16.153846153846153, 
WITH A PRICE RANGE OF: 3.8461538461538467,
OPTIMAL PRICE: 16.153846153846153,
PROFIT OVER THE NEXT YEAR IF FOLLOWED THIS STRATEGY WILL BE: $346.15384615384613, 
FOR ITEMS IN EACH OF THE TEN CATEGORIES THAT COST: $20,
ANNUAL PROFIT: 3461.5384615384614).
