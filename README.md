# Northwinds_Analysis

This was a project to conduct comparative analysis for business optimization for the Northwinds Shipping company.

## Data
The data for this project is sourced from the Northwinds sqlite database. I use sqlite3 in Python to extract the tables from the db and use a series of joins to query and build the needed dataframes.

## The Problem
There were 4 business questions I needed to answer:
- Does the discount amount have a significant effect on teh quantity of products sold in an order? If so, at what discount rates?
- Is there a difference in the mean "time to ship" between the 3 shippers used by Northwinds?
- Is there a significant difference in freight costs depending on which shipper is used?
- If Northwinds offers first time customers a discount on their first purchase, will they be retained as customers?

## The Method

