# MachineLearning_2
## a sample dataset of an online retail

the usful libraries in this project :
- Pandas
- Matplotlib
- Numpy

## reading our data:

!['newPic'](imgs/pic1.png)

we have a dataframe that shows our monthly revenue :

Revenue = Active Customer Count * Order Count * Average Revenue per Order

!['newPic'](imgs/pic3.png)

Scatter plot:

!['newPic'](imgs/pic2.png)

## Monthly Revenue Growth Rate :

!['newPic'](imgs/MonRevRate.png)

- we need to identify what exactly happened on April!!!

## The bar plot of Monthly Active Customers :

- we will be focusing on UK data only (which has the most records).
- In April, Monthly Active Customer number dropped to 817 from 923 (-11.5%).

!['newPic'](imgs/pic4.png)

## bar plot of Monthly Order Count :

!['newPic'](imgs/Quantity.png)

## Average Revenue per Order :

- we need to calculate the average of revenue for each month

!['newPic'](imgs/averageRevenu.png)

### its bar plot :

!['newPic'](imgs/averagRevenuePlot.png)

---
### New Customer Ratio :
- In our dataset, we can assume a new customer is whoever did his/her first purchase in the time window we defined.

- We will be using .min() function to find our first purchase date for each customer and define new customers based on that


### Dataframe output after merging with First Purchase Date:

!['newPic'](imgs/theActiveCustomers.png)


### Existing & New Customers scatter plot :

!['newPic'](imgs/Existing&NewCustomers.png)

### New Customer Ratio

!['newPic'](imgs/NewCustomerRatio.png)

## Retention table with crosstab() function :

Retention table shows us which customers are active on each month (1 stands for active).

!['newPic'](imgs/1.png)

### calculate Retention Rate :

- Monthly Retention Rate = Retained Customers From Prev. Month /Active Customers Total

- We will be using crosstab() function of pandas which makes calculating Retention Rate super easy.



!['newPic'](imgs/2.png)

### Retention Rate plot :

!['newPic'](imgs/MonthlyRetentionRate.png)


### showing new cohort based retention table :

Cohort Based Retention Rate

!['newPic'](imgs/End.png)

