# Superstore Sales Analysis

## Overview
This project involves an analysis of a fictional Superstore's sales dataset. The primary objective is to derive meaningful business insights, explore customer purchasing behavior, and identify trends across categories, regions, and time periods. The analysis covers various aspects such as customer segmentation, product performance, shipping modes, and seasonal trends. It also investigates correlations between key variables, providing a comprehensive understanding of sales dynamics.

## Dataset
The dataset represents sales data from a superstore and contains the following columns:

| Column Name      | Description                                    | Data Type         |
|------------------|------------------------------------------------|-------------------|
| Order Date       | Date when the order was placed                | datetime64[ns]   |
| Ship Date        | Date when the order was shipped               | datetime64[ns]   |
| Ship Mode        | Mode of shipping (e.g., Standard, Expedited)  | object           |
| Customer Name    | Name of the customer                         | object           |
| Segment          | Customer segment (e.g., Consumer, Corporate) | object           |
| Country          | Country of the customer                      | object           |
| City             | City of the customer                         | object           |
| State            | State of the customer                        | object           |
| Postal Code      | Postal code of the customer                  | float64          |
| Region           | Region of the customer                      | object           |
| Product ID       | Unique identifier for the product            | object           |
| Category         | Category of the product                      | object           |
| Sub-Category     | Sub-category of the product                  | object           |
| Product Name     | Name of the product                          | object           |
| Sales            | Total sales amount for the order             | float64          |


# Exploratory Data Analysis

## Sales analysis

The sales of main categories are roughly the same, but in sub categories Chairs and Phone are higher by a wide margin.
![obraz](https://github.com/user-attachments/assets/43b2e43d-6423-4ccc-b337-42e883b14a2f)

The most profitable product is a copier, making over a double of the second most profitable product.
![obraz](https://github.com/user-attachments/assets/e9076048-791f-4a18-86c1-53a76e964406)



# Region analysis
The most profitable region is California, followed by New York.

![obraz](https://github.com/user-attachments/assets/ae4e4a6f-fd01-42c3-b2a9-23e1d4199efd)
![newplot](https://github.com/user-attachments/assets/a985f02b-d85e-4714-8f28-dd07863697a8)


# Customer and order analysis
Consumer sales bring the most profit.

![obraz](https://github.com/user-attachments/assets/3254229c-0645-4633-8420-91121fc5e8e9)

There's no overlap between top 10 customers by number of orders and by number of sales, indicating that the most profitable customers create less, but higher value orders.

![obraz](https://github.com/user-attachments/assets/336ad44c-e3cc-4f3a-8d7c-2b2354e6cc1a)

Most customers create less than 15 orders, and majority of the sales comes from them.

![obraz](https://github.com/user-attachments/assets/7f3aa47e-2724-40ad-8f33-35d28dd1296d)

Majority of orders are for a single item, and the number of orders halves for each consecutive number of products in an order.

![obraz](https://github.com/user-attachments/assets/e17b41d0-e030-4644-ac56-10df4a8fb4a9)

Most orders are shipped as standard class.

![obraz](https://github.com/user-attachments/assets/9f98341a-698c-4d20-8495-88f7671ccd12)

Majority of orders have less than 8 products.

![obraz](https://github.com/user-attachments/assets/928dca85-d90e-4ef0-a855-cd5c24ad12b7)

# Temporal and seasonal analysis
Number of orders is slowly but steadily increasing over time.

![obraz](https://github.com/user-attachments/assets/da6e426c-f482-40ba-bb6c-2543f031ffc6)

Most popular season is fall.

![obraz](https://github.com/user-attachments/assets/5517e27d-1176-47a4-af54-4fc83b170430)

In march, there's a sudden spike in technology sales.

![obraz](https://github.com/user-attachments/assets/aedd57f6-aa5a-41bd-bc90-ff8c67a3c7e1)
