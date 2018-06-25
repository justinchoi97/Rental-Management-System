# Rental-Management-System
C# windows form based rental management system program used for keeping record of available vehicles in the fleet and customer information.

Author: Justin Choi, Nick Jensen 

This was a part of cabstone project for 2018 semester 1 at QUT.

The operators of MRRC require the following functionality:
1. Enter/modify/delete customers
2. Enter/modify/delete cars
3. Search for suitable vehicles based on customers’ requests
4. Rent out cars to customers
5. Return cars from customers
6. Display a rented cars report

There are 5 classes: customer, CRM, vehicle, fleet and search. 
customer: contains customer information 
CRM: manages the customer lists and contains methods to perform operations on customer lists.
vehicle: contains vehicle information
fleet: manages lists of rented cars and available cars. Contains methods to modify the lists 
search: processes user inputs as free text query form and returns the search result accordingly. 

The windows form based GUI has four different tabs: 
fleet: sections for viewing current fleet information and performing operations (addition, deletion, modification, etc)
customers: section for viewing customer information and performing operations.
rental report: section for viewing vehicles that are currently rented
rental search: section for searching vehicles according to the descriptions.

For search functionality, a user may enter a combination of any number of attributes, using both AND and OR with AND having the same
priority (precedence) as OR (Note the search is not case sensitive).
For example: Economy OR Family AND 4-Cylinders
  Red OR Blue OR Green OR Purple AND GPS
  
The repository includes sample dataset for customer, rental and fleet database in the form of .CSV file. Feel free to modify the database.

Run MRRC.sln file to start the program. 
