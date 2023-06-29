# Regression-Model-For-Time-Series-Forcasting
Regression model to predict product sales using the Corporation Favorita Products
# Introduction

The development of machine learning has been effectively applied to solve problems in everyday life. Humans are becoming more inventive as time passes, thanks to our knowledge of the potential applications of machine learning. In the real world, forecasting seems to be where machine learning is most frequently used.Businesses predict product demand, which is a typical job for data scientists. For grocery stores, forecasts are especially important because they must carefully balance how much inventory to purchase. If you overestimate, grocery stores will be stuck with extra perishables. If you make a slight error, popular items will sell out quickly, costing you money and upsetting your customers. Machine learning's improved forecasting capabilities may help retailers please customers by stocking just the right amount of the right products at the right time.

# Aim ✅
Biuld a model that accurately predict store sales on data from Corporation Favorita, a large Ecuadorian-based grocery retailer.
The model should be able to predict the unit sales for thousands of items sold at different Favorita stores.

# About dataset 	📁
The prediction model is designed on the a train data with colmuns below
 1 id           
 2 date        
 3 store_nbr    
 4 family       
 5 sales       
 6 onpromotion 
## oil data with columns 📂📂
1. date
2. oil price
## holiday with columns 📂📂
1. date
2. type - gives the holiday type
3. local - describe if the holiday is a national, regional or local
4. local name - the name of the holiday
5. description - a description of the holiday type
6. transfereed - a true or false  to describe if the holiday was moved to another day or not
## Stores with columns 📂📂
1. Store nbr -  the store number which matches the store number in the train dataset
2. city - the city the store is located
3. state - the state the store is located
4. type - store type which ranges from A to D
5. clustur - store clustur which ranges from 1 to 15

# Process/ Method ♻️
1. Data Understanding
2. Data cleaning and merging of datasets
3. Data preprocesing which include encoding, scaling, splitting data into train and evaluation etc.
4. Build model
5. Model evaluation

# Setup/Tools ❇️
To run this file, you need python installed with scikit learn and pandas.
