# Heroes of Pymoli

[![](img/Fantasy.png)]()      

## Introduction

Games are currently very important since many types of people currently use them either to earn money, as a hobby or to learn. These, being highly demanded, generate a lot of information that is very valuable when making decisions for the good of the users, that's why this time we are going to analyze the information of the game called Heroes of Pymoli.

Heroes of Pymoli is a game of fantasy, like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, a report was generated that breaks down the game's purchasing data into meaningful insights.

## Tools

The following tools were used to do the analysis.

#### Analysis:
- Python 3
- Pandas
- Jupyter Notebook

## Data

The information used is from the game Heroes of Pymoli provided by Tecnologico de Monterrey, is a CSV file stored in resources folder

#### Schema

|   Column   | Data Type |
| ---------- | ----------|
| PurchaseId |   `int`   |
|     SN     |   `str`   |
|     Age    |   `int`   |
|   Gender   |   `str`   |
|   ItemId   |   `int`   |
|   ItemName |   `str`   |
|    Price   |  `float`  |

- PurchaseId  -> Id for the purchase item
- SN          -> Name of the player
- Age         -> Age of the player
- Gender      -> Gender of the Player
- ItemId      -> Id for the item
- ItemName    -> Name of the item
- Price       -> Price of the item


## The Report

The final report include each of the following:

+ Player count
    * Total Number of Players

+ Purchasing Analysis (Total)
    * Number of Unique Items
    * Average Purchase Price
    * Total Number of Purchases
    * Total Revenue

+ Gender Demographics
    * Percentage and Count of Male Players
    * Percentage and Count of Female Players
    * Percentage and Count of Other / Non-Disclosed

- Purchasing Analysis (by Gender)
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person by Gender

+ Gender Demographics (each broken into bins of 4 years)
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value
    * Average Purchase Total per Person by Age Group

+ Top Spenders (top 5 spenders in the game by total purchase value)
    * SN
    * Purchase Count
    * Average Purchase Price
    * Total Purchase Value

+ Most Popular Items (by purchase count)
    * Item ID
    * Item Name
    * Purchase Count
    * Item Price
    * Total Purchase Value

+ Most Profitable Items ( 5 most profitable items by total purchase value)
    * Item ID
    * Item Name
    * Purchase Count
    * Item Price
    * Total Purchase Value
