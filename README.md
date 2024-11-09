CREATE TABLE supermarket_sales (
    Invoice_ID STRING,
    Branch STRING,
    City STRING,
    Customer_type STRING,
    Gender STRING,
    Product_line STRING,
    Unit_price FLOAT,
    Quantity INT,
    Tax FLOAT,
    Total FLOAT,
    Date STRING,
    Time STRING,
    Payment STRING,
    COGS FLOAT,
    Gross_margin_percentage FLOAT,
    Gross_income FLOAT,
    Rating FLOAT
)
ROW FORMAT DELIMITED
FIELDS TERMINATED BY ','
STORED AS TEXTFILE;
