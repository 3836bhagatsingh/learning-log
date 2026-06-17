Day4-learning



\#SQL code I wrote



1-select \* from orders where year(order\_date) = 2024;

2- select \* from orders where total\_amount > 5000;

3-select \* from orders order by total\_amount desc;

4-select \* from orders where city  = 'Delhi';

5-select \* from  orders order by order\_date desc limit 10;

6-select \* from orders where status = 'cancelled' and order\_date>date\_sub(now(),interval 30 day)  order by order\_date desc;

7-select \* from orders order by total\_amount desc limit 5;

8-select \* from orders where total\_amount between 2000 and 8000;

9-select \* from orders where status not in ('delivered');

10-select \* from customers where year(signup\_date)>'2023' and country = "India";

11-select \* from customers order by signup\_date asc;

12-select  \* from orders where DAYOFWEEK(order\_date) in ('1','7');

13- select \* from orders where city is NULL or city ='';

14-select \* from orders order by total\_amount in ('1000','2000','5000');

15-select \* from orders where order\_amount = (select order\_amount from orders order by order\_amount asc limit 1 

or select order\_amount from orders order by order\_amount desc limit 1 );



\# Python learning

Exception Handling and its flow

raise -> keyword for raising our own exceptions

Assertion -> Assertions are for programmer errors, not user errors.

logging , logfiles, breakpoints





\#Revisit 

logging module internals and exception handling









Note

Tables -> Database

Tables in Proper Architecture like medallion -> DWH

Hadoop MapReduce -> Distribute work among nodes (very less used now)

Apache Spark -> DAG(Directed Salic Graph) and RDD(Resilient )

