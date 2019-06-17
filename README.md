# Module Two Final Project

By: Jonathan Ericksen

For: Northwind

### Background:
>Northwind is a small company looking to gain critical insights provided by the data housed within their data warehouse. Northwind is looking to make strategic moves based on insights gleaned from the data. As a small company, their reserouces are limited, thus, Northwind has contracted with JE Consulting to analyze the data and perform a number of statistical tests answering key questions posed by management.

### Objective:
>The objective for JE Consulting is to extract the necessary data from their SQL based database and perform four statistical tests that determine with confidence whether or not previous, non-data driven assumptions about their operations, are indeed correct. 

>The results of these tests will be used by the management team to assess future strategies for improving revenue growth and improving overall operational efficiency. These tests will direct  company resources towards yielding the highest return on companies capital. The conclusions of these tests, and the implications for Northwind, will be summarized in the 'Conclusions' portion of the notebook. 

>Last, JE Consulting was asked to provide recommendations for further work as they continue to seek areas for further statistical analysis. JE Consulting will provide these recommendations in the 'Future Work' portion of the notebook. 

### Hypothesis Testing:
*Below are the tests we ran during this project followed by the restults:*

>#### Hypothesis Test #1:
>Do discounts have a statistically significant effect on the number of products customers order? If so, at what level(s) of discount?
>#### Hypothesis Test #2:
>Is the average order size in North America larger than international order sizes?
>#### Hypothesis Test #3:
>Does order size vary in a statistically signficant way between Northwind employees?
>#### Hypothesis Test #4:
>Does the average revenue per order differ in 2014 from 2012 & 2013?

#### The following is a summation of our findings :

>#### Test One (Discounts):
>Do discounts have a statistically significant effect on the number of products customers order? If so, at what level(s) of discount?
>#### Conclusion One:
>Part One: Yes, discounts do have a significant impact on the number of products ordered. Not only do they increase the number of products ordered, but we can say the impact of applying disounts is signficant.
>Part Two: Generally, discounts have signficantly impact the number of products ordered at most levels with the exception of discounts at the 10% level.

>#### Test Two (Efficiency):
>Is the average order size in North America larger than international order sizes?
>#### Conclusion Two:
>Order sizes in North America are indeed higher on average than international order sizes. The impact on order size between domestic and foriegn shipping is significant.

>#### Test Three (Employees):
>Does order size vary in a statistically signficant way between Northwind employees?
Conclusion Three:
>#### Conclusion Three:
>There seems to be no statistically significant variation in the average size per order between Northwind employees.

>#### Test Four (Revenue):
>Does the average revenue per order differ in 2014 from 2012 & 2013?
> #### Conclusion Four:
>The average revenue per order does not vary from 2014 to 2012 & 2013. In fact, it appears revenue per order decreases slightly from 2014 to 2012 & 2013. However, we cannot accept this conclusion with confidence.

### Future Work

There is much to be done to continue drawing insights from our data. Below we provide recommendations for future work to further advance :

**Discounts**:
>Use them to push inventory, but further work is needed to asses the impact of discounts on revenue. Although discounts lead to higher inventory turnover, we don't yet have an understanding of their impact on revenue. Additional tests are needed to assess whether or not discounts impact revenue, and if so, to test and quantify the impact of discounts on revenue.

**Efficiency:**
> If the goal is to increase revenue per order, and thus efficiency, we must better understand why order sizes in North America are larger on average than international orders. Does shipping costs impact order size? Are international customers operating under different storage constraints than domestic customers? Do international customers submit more orders on average than domestic? We must investigate these factors and apply resources towards increasing the order size of the international customers. 

**Employees:**
> We concluded there is no variation in order size per employee. That said, further research is needed to suss out employees that perform better by other metric means. Perhaps the number of orders vary significantly between employees? And if so, how do we extract techniques from higher performing employees and apply those to lower performing employees? Further, we might look at the cost per order based on the employees salary. If order size, and thus efficiency, does not vary between employees, then what about the costs per order associated with each employee and their respective salary? 

**Revenue:**
> Revenue per order does not increase between 2012 & 2013 to 2014, which is not ideal from the standpoint of cost reduction. Northwind's goal should center on increasing revenue per order. We must further investigate factors that influence revenue per order and apply the necessary resources to improve the established KPIs around efficiency. 
