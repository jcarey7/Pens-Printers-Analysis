Data Information:

The data is pulled from a sales tracking system. Numbers for how much time was spent on each customer are not included, but there is other useful information.
The data only relates to the new products sold. As there is a variety of different products, the revenue will vary depending on which products were sold.
You can find the data [here](https://s3.amazonaws.com/talent-assets.datacamp.com/product_sales.csv).

The data has not yet been validated or cleaned.

| Column name:               | Details:                                                                                          |
| ------------               | ---------------------------------------                                                           |
| [week]                     | Week sale was made, counted as weeks since product launch.                                        |
| [sales_method]             | Character, which of the three sales methods were used for that customer.                          |
| [customer_id]              | Character, unique identifier for the customer.                                                    |
| [nb_sold]                  | Numeric, numebr of new products sold.                                                             |
| [revenue]                  | Numeric, revenue from the sales, rounded to 2 decimal places.                                     |
| [years_as_customer]        | Numeric, number of years customer has been buying from the company (company was founded in 1984). |
| [nb_site_visits]           | Numeric, number of times the customer has visited the company website in the last 6 months.       |
| [state]                    | Character, location of the customer i.e. where orders are shipped.                                |
