![image](https://github.com/user-attachments/assets/31b8bc5a-d26f-4102-86de-247f85920cdd)# Dannys_Diner_8_Week_SQL_Challenge
# Overview
Danny seriously loves Japanese food so in the beginning of 2021, he decides to embark upon a risky venture and opens up a cute little restaurant that sells his 3 favourite foods: sushi, curry and ramen. Danny’s Diner is in need of your assistance to help the restaurant stay afloat - the restaurant has captured some very basic data from their few months of operation but have no idea how to use their data to help them run the business.
# Problem Statement
Danny wants to use the data to answer a few simple questions about his customers, especially about their visiting patterns, how much money they’ve spent and  which menu items are their favourite. Having this deeper connection with his customers will help him deliver a better and more personalised experience for his loyal customers.

He plans on using these insights to help him decide whether he should expand the existing customer loyalty program. Additionally he needs help to generate some basic datasets so his team can easily inspect the data without needing to use SQL.

Danny has provided you with a sample of his overall customer data due to privacy issues but he hopes that these examples are enough for you to write fully functioning SQL queries to help him answer his questions!

Danny has shared with you 3 key datasets for this case study:

1. sales
2. menu
3. members

# Entity Relationship Diagram
![](entity_relationship_diagram.png)

# Dataset
## Sales Table
The sales table captures all customer_id level purchases with an corresponding order_date and product_id information for when and what menu items were ordered.

![](sales_table.png)

## Menu table
The menu table maps the product_id to the actual product_name and price of each menu item.

![](menu_table.png)

## Members table
The final members table captures the join_date when a customer_id joined the beta version of the Danny’s Diner loyalty program.

![](members_table.png)

# Question 1 : What is the total amount each customer spent at the restaurant?
![](question_1.png)

# Question 2 : How many days has each customer visited the restaurant?
![](question_2.png)

# Question 3 : What was the first item from the menu purchased by each customer?
![](question_3.png)

# Question 4 : What is the most purchased item on the menu and how many times was it purchased by all customers?
![](question_4.png)

# Question 5 : Which item was the most popular for each customer?
![](question_5.png)

# Question 6 : Which item was purchased first by the customer after they became a member?
![](question_6.png)

# Question 7 : Which item was purchased just before the customer became a member?
![](question_7.png)

# Question 8 : What is the total items and amount spent for each member before they became a member?
![](question_8.png)

# Question 9 : If each $1 spent equates to 10 points and sushi has a 2x points multiplier- how many points would each customer have?
![](question_9.png)

# Question 10 : In the first week after a customer joins the program (including their join date) they earn 2x points on all items, not just sushi – how many points do customer A and B have at the end of January?
![](question_10.png)
