# Chinese-Restuarant-Process
### Stochastic Process Project 

The Chinese restaurant process is a discrete-time stochastic process, analogous to 
seating customers at tables in a Restaurant. 

A Chinese restaurant has an infinite number of tables, each of the tables has no limit on the number of customer seated at that table. 

The first customer seats at the first table, the second customer will seat to the first table with a proportion of __1/(α+1)__
and choose a new table with the proportion __α/(α+1)__. 
  
Here  **‘α’** called the concentration parameter (also known as scaling parameter).

This process continues, with each customer 
choosing to either sit at an occupied table with a probability proportional to the 
number of customers already there (i.e., they are more likely to sit at a table with 
many customers than few), or an unoccupied table. The results 
of this process are exchangeable, meaning the order in which the customers sit 
does not affect the probability of the final distribution. This property greatly 
simplifies a number of problems in *population genetics, linguistic analysis, and 
image recognition*.
