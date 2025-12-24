# &nbsp; # DAX Measures Documentation

Project: Pizza Sales Analysis (SQL + Power BI)



\## 1. Total Revenue

\*\*DAX Formula:\*\*

```DAX

Total Revenue = SUM(pizza\_sales\[total\_price])

Business Purpose:

Calculates the total sales revenue generated from all pizza orders.

Used to measure overall business performance.

2.Total Orders 

Total Orders = DISTINCTCOUNT(pizza\_sales\[order\_id])

Business Purpose:

Counts the number of unique customer orders to understand demand volume.

3.Total Pizzas Sold

Total Pizzas Sold = SUM(pizza\_sales\[quantity])

Business Purpose:

Measures total quantity sold to analyze sales volume and inventory movement.

4)Average Order Value

Average Order Value = DIVIDE(\[Total Revenue], \[Total Orders])

Business Purpose:

Measures total quantity sold to analyze sales volume and inventory movement.

5)Average Pizzas per Order

Average Pizzas per Order = DIVIDE(\[Total Pizzas Sold], \[Total Orders])

Business Purpose:

Indicates whether customers tend to buy single items or multiple pizzas per order.









