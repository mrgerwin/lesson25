# lesson25
Adding in DB Functions and Handling Database Errors

Use your own app from before or the one attached to continue on learning.
Last time we noticed that our customers and products were leaving when we closed the app.  Today we will fix this by bringing in a DB.

Part 4

Open a DB file like you have done before.  When you open one that doesn't exist, it will create the file.

Make a table for Customers and Products using the same data types that are in the list structure.

In the function that adds Customers, add the customer to the customers table in the db
Same with the Products.

Now when an error happens, how do we know if the error happened because the user put in bad information or if the database is having connection issues?

This is when we have several exception cases where we handle them differently depending on the error.

Write a function and add a button that will allow the data from the database to be added to the Products and Customers lists so that the app can interact with them.

Why is it important to handle errors separately instead of having a single catch all exception?
