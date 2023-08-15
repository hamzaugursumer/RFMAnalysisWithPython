# :computer: **RFM Analysis With Python** :hourglass: :bar_chart: :moneybag:

![png-rfm](https://www.dijitalmecmua.com/wp-content/uploads/2021/09/RFM-analizi-1200x642.jpg)


* RFM analysis is a statistical analysis method used to determine basic customer segments by measuring customers’ purchasing habits. RFM stands for Recency, Frequency, and Monetary. It is the process of labeling customers by determining the Recency, Frequency, and Monetary values of their purchases through a scoring model.

* Recency-Frequency-Monetary (RFM) Analysis is a marketing analysis tool used to define customers according to the nature of their purchasing habits. With RFM analysis, customers are evaluated by scoring them in three main categories: how recently they purchased, how often they purchased, and the size of their purchases.

* As a result of the RFM analysis, each customer is ranked numerically on a simple scale in each of these three categorical values. According to the ranking made, the “Best” customer will be the customer who receives the highest score in each category. Although this ranking is usually done between 1 and 5, it can also be done with letters (A,B,C, …), special name tags (Platinum, Gold, Classic etc.) or adjective definitions (Champions, Soon to Escape, Loyal Customers etc.).

* With RFM analysis, customers can be segmented and sales and marketing tactics and practices can be developed specifically for each segment. This helps companies reasonably estimate which customer segment is more likely to repurchase products, how much revenue/profit is generated from new customers, and how to convert relatively infrequent shoppers into more frequent shoppers.

* :pushpin: Dataset ; https://www.kaggle.com/nathaniel/uci-online-retail-ii-data-set
* There are two sheets in the dataset covering the years 2009 - 2010 and 2010 - 2011. While performing my analysis, I utilized the first sheet that encompasses the years 2009 - 2010.

## :pushpin: Variables:

| Variable     | Description                                                  |
|--------------|--------------------------------------------------------------|
| InvoiceNo    | Invoice number. It is a unique value. If starts with C, indicates a return. |
| StockCode    | Product code. A unique number for each product.             |
| Description  | Product name.                                               |
| Quantity     | Product quantity. Represents the quantity of sold items from invoices. Negative values for items starting with C. |
| InvoiceDate  | Date and time of the invoice.                               |
| UnitPrice    | Product price (in GBP - British Pounds).                     |
| CustomerID   | Customer number. A unique number for each customer.         |
| Country      | Country name. Indicates the country where the customer resides. |

# :computer: Result of RFM analysis

|                      |                RECENCY     |               |     FREQUENCY     |               |      MONETARY     |               |
| Customer Segment     |     Mean        | Count         |     Mean          | Count         |      Mean         | Count         |
|----------------------|-----------------|---------------|-------------------|---------------|-------------------|---------------|
| About to Sleep       | 52.726477       | 457           | 1.400438          | 457           | 523.735098        | 457           |
| At Risk              | 137.774775      | 444           | 4.281532          | 444           | 1827.981466       | 444           |
| Can't Lose           | 136.272727      | 11            | 19.363636         | 11            | 7028.365455       | 11            |
| Champions            | 5.846014        | 552           | 14.336957         | 552           | 8010.322451       | 552           |
| Hibernating          | 204.674400      | 1250          | 1.288800          | 1250          | 450.531211        | 1250          |
| Loyal Customers      | 33.546973       | 479           | 8.544885          | 479           | 3483.544061       | 479           |
| Need Attention       | 52.577778       | 225           | 3.431111          | 225           | 1412.024933       | 225           |
| New Customers        | 8.101124        | 89            | 1.000000          | 89            | 337.436854        | 89            |
| Potential Loyalists  | 17.054859       | 638           | 2.841693          | 638           | 1009.464625       | 638           |
| Promising            | 24.159763       | 169           | 1.000000          | 169           | 345.946805        | 169           |
