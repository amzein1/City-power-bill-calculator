### CPRG 200 Lab Assignment 2 


Program Description 

this application for the city power company to store in a file calculated charge 
amounts for multiple customers. In addition to the data that you collect from each customer you will 
need to also collect a name and account number. You will be storing for each customer the following 
data: 

. AccountNo – a positive integer value 
. CustomerName – a non-empty string (there is no restriction on what characters a name can be 
made of; some companies have names that include numbers or even punctuation characters) 
. CustomerType – a single character string that can be “R”, “C”, or “I” (capital letters) 
. ChargeAmount ( a numeric value, not a string) 


NO need to store kWH values for the customers. 

As the new customers’ data is added, or before the application closes, the current collection of 
customer data needs to be written to the file. When the application starts next time, data is read from 
this file to allow more adding more customers. 

This application displays at all times the current collection of customer’s data as listed above. In 
addition, it calculate and display the following statistics: 

. the total number of customers, 
. the sum of charges for each customer type (three values), and 
. the sum of all charges. 

 
