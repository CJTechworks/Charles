
Steps to test app

1.Create database customer_db.

2.Create the following table inside the db

3.CREATE TABLE Customer( CUSTOMER_ID INT NOT NULL AUTO_INCREMENT, NAME VARCHAR(150) NOT NULL, ADDRESS1 VARCHAR(150), ADDRESS2 VARCHAR(150), ZIP_CODE VARCHAR(10), CITY VARCHAR(100), COUNTRY VARCHAR(100), PRIMARY KEY (CUSTOMER_ID) )

4.Update Servlet-context.xml with my sql specific properties

5.Create Customer -- > Run CreateCustomerTest.java

6.Get list of customers -- > http://localhost:8080/mySpringWeb/user

the below 2 steps for only Junit tests calling the dataaccess. I will integrate these 2 with the UI after the initial review of the view page in the step 6

7.Update Customer --> Run UpdateCustomerTest.java

8.Delete Customer -- >Run DeleteCustomerTest.java
