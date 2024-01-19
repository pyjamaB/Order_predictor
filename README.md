# E-store order predictor
Building AI course project

# Project Title

E-store order predictor - Final project for the Building AI course

## Summary

This project is an idea about an order predicting tool for e-stores that deliver groceries at home.


## Background

Quite often it is hard to predict how many orders an e-store gets each day. There's always a lot of variation in the quantity of orders between different days. Also the types of products customers order vary a lot between different days. There are a lot of different variables that affect the amount and type of orders that the e-store gets: For example during bad weather people don't want to go buy groceries themselves, so they order online. During good weather e-stores usually get less orders. Customers also order different kinds of products each day and each season. During Christmas for example the orders are a lot different compared to summer. For the reasons stated before it is difficult to predict how many workers you need each day. To minimize labor costs you can't have too many workers. At the same time having too little workers means that there's a risk that the orders are going to be delivered too late to the customers. Because customers have reserved a certain time slot for a certain day for their order the e-store might have to offer compensation to the customer if the order is delivered late. It is even harder to predict the quantities of different products you need to have in stock. At an internet based grocery store you can't have too many products in stock because they might expire before they are sold to customers. That could create a lot of waste and costs for the store. At the same time you can't have too little products in stock either because then customers might not get all the products they want. So you need to have the right amount of different products in stock at the right time. If you could predict better the amount of orders and the amount of different products customers order each day, it would make running an internet based grocery store much easier and it would also save costs and increase profits.


## How is it used?

The tool is used every day by the store managers who plan how many workers they need each day and decide about the quantities of products they need to have in stock each day.

## Data sources and AI methods

The data for the tool comes from the e-store's own registers that contain information about the quantities of orders from previous days, weeks, months and years. The store's data contains also information about the quantities of products that have been ordered and the current status of the store's stocks. The tool would use linear regression to predict the amount of orders for each day and also the amount of different products that are going to be sold each day. The tool would also take in to consideration the weekday, the season and different holidays.

## Challenges

The main challenge for the project is that predictions are never going to be perfect. There are so many variables that have an effect on the amount and type of orders an e-store gets that you can't always have exactly the right amount of staff working or different products in stock. But the tool might make predicting orders a little bit easier.

## What next?

Next step would be to create a first model of the tool and present the idea to e-store managers. The tool could later take in to consideration also data for example from weather forecasts.
