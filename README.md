# Big-Data-Processing-with-Apache-Spark-RDDs
Project made for the subject Big Data

You and your team were hired to process data using MapReduce. Your company has access to a
dataset with commercial transactions between countries during the past 30 years. For each transaction,
the dataset contains the following variables:
Variable (column) Description
Country Country involved in the commercial transaction
Year Year in which the transaction took place
Commodity code Commodity identifier
Commodity Commodity description
Flow Flow, e.g. Export or Import
Price Price, in USD
Weight Commodity weight
Unit Unit in which the commodity is measured, e.g. Number of items
Amount Commodity amount given in the aforementioned unit
Category Commodity category, e.g. Live animals
The dataset has over 8 million instances (rows, or commercial transactions). The dataset is made
available in CSV format. Columns are separated by semi-colons (“;”). The image below exhibits the first 5
rows of the dataset:
Given this context, you are in charge of developing a set of solutions that allow the company to
answer the following demands:
1. (Easy) The number of transactions involving Brazil;
2. (Easy) The number of transactions per flow type and year;
3. (Easy) The average of commodity values per year;
4. (Easy) The average price of commodities per unit type, year, and category in the export flow
in Brazil;
5. (Medium) The maximum, minimum, and mean transaction price per unit type and year;
6. (Hard) The country with the largest average commodity price in the Export flow;
o Important: a single country must be output in this solution!
7. (Hard) The most commercialized commodity (summing the quantities) in 2016, per flow
type
