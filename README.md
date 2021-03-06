# BACKEND SKILLS ASSESSMENT PROJECT

For this task you will be creating a **Java application** that will expose an **Web API**. This application will take various input parameters and store data about transactions.

**It must be production quality according to your understanding of it: testing, readme.MD etc. We run on Unix environment, if there's no instruction how to run the code or/and it doesn't compile, it will NOT QUALIFY**

The application have to store data on the file system under the folder where the application is. So there is no need to use a database but if you feel that using a database can help your exercise, feel free to do so. We only ask you to not delegate any logic to the database like sum and others. We want to know your code.

The API should have the following features:

## ADD TRANSACTION
Receives <user_id> add <transaction_data> params.

This feature should add a transaction to the user specified in <user_id> using the information specified in <transaction_data>.  The transaction data should have the following data:


amount -> 1.23

description -> Joes Tacos

date -> 2018-12-30

user id -> 345


This command should return a version of the transaction added with a unique id for the transaction like this:


transaction_id -> 2299ce24-9eaf-417f-82d6-e57f93777dc4

amount -> 1.23

descrption -> Joes Tacos

date -> 2018-12-30

user_id -> 345


## SHOW TRANSACTION
Receives <user_id> <transaction_id> params.

This feature should return the transaction specified in the transaction_id. 

If the user_id is not the user_id that corresponds with the user_id for the specified transaction,  you should return _Transaction not found_. 

If the transaction does exists, you should print out the information for the transaction like this:


transaction_id -> 2299ce24-9eaf-417f-82d6-e57f93777dc4

amount -> 1.23

descrption -> Joes Tacos

date -> 2018-12-30

user_id -> 345


## LIST TRANSACTIONS
Receives <user_id> param.

This feature should print all the transactions associated with the user specified by user_id. The transactions should be in chronological order.

If the user_id does not exist, then the response should return an empty list. You should print the items with the following data:


List of ->

  transaction_id -> 2299ce24-9eaf-417f-82d6-e57f93777dc4
  
  amount -> 1.23
  
  descrption -> Joes Tacos
  
  date -> 2018-12-30
  
  user_id -> 345
  

## SUM TRANSACTIONS
Receives <user_id> param.

This command should sum all the transactions associated with the user specified by user_id. 

It should printout the sum with the following data:


user_id -> 123

sum -> 234.76


## FINAL CONSIDERATIONS
Please write this application in Java. You are free to implement this however you’d like with whatever resources or 3rd party code you’d want.

**Deadline**: We expect you to get back to us with the solution in 5 days. It won't be better if you delivery before, so if you finish early, improve your code. Finally, don't rush, if you need more time please ask us whenever you need.

Create a private project in GitHub and share with us your code.

The repo should have your name, for example **"_yor-name-sample-java-test_"**, it will help us to identify your test.

Feel free to ask questions at any time (jose.dominguez@aditus.mx).


