# Pizza-Runner
8-Week SQL Challenge - Case Study 2 

![1__qg3jgz0W4aJ8AQEFyNesw](https://user-images.githubusercontent.com/98917179/189134586-abfb6db6-b4c6-4997-bf82-03e7e8525179.png)

This is my solution to Danny Ma's 8 Week SQL Challenge Case Study 2 using PostgreSQL. Danny has just launched his business 'Pizza Runner', and needs to derive insight for informed business decisions from the data collected. You could check out the full challebge [here](https://8weeksqlchallenge.com/case-study-2/). You could also read a full blog post with my explained solution [here]()
# Questions and Solutions (A-Pizza metrics)
Question 1: How many pizzas were ordered
Solution: I used the function COUNT(*) to calculate the total number of pizzas ordered from the customer_orders table.
```SELECT COUNT(*) AS no_of_pizzas_ordered
FROM pizza_runner.customer_orders;```
Question 2: How many unique customer orders were made?
