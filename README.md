# Excel-Sales-and-Financial-Analytics

## Project Overview
The [**Codebasics Data Analytics Bootcamp**](https://codebasics.io/bootcamps/data-analytics-bootcamp-with-practical-job-assistance) exhibits a fictional company called **AtliQ Technologies**. The objective of this project is to use **Excel** to generate 2 **sales reports** and 3 **finance reports** that will enable AtliQ Technologies to make informed, data-driven decisions.


## AtliQ Technologies Business Model

<details>
  <summary><b>Overview</b></summary>

AtliQ manufactures computer hardware **products** (e.g., mouse, keyboard, printer, monitor) and then sells them to various **customers** which are stores such as Amazon and Best Buy. Hence, AtliQ's customers are in the form of <ins>store businesses</ins> (e.g., Amazon, Best Buy) and should not be confused with customers in the form of people (i.e., the people purchasing products from Amazon or Best Buy).

<br>
</details>

<details>
  <summary><b>Customers</b></summary>

AtliQ's customers are categorized into two different **platforms**:
1. Brick & Motar
   * stores that have physical location(s)
2. E-Commerce
   * stores which only sell products online
<br>

AtliQ's customers are categorized into three different **channels**:
1. Retailer
   * Stores not owned by AtliQ (e.g. Amazon, Best Buy)
3. Direct
   * Stores owned by AtliQ. These are AltiQ Exclusive and AtliQ E-Store.
5. Distributor
   * Some markets have laws/regulations which only allow AtliQ to sell products to a distributor type customer within that market. AtliQ sells products to the distributor; the distributor then sells the products to various stores within that market.

<br>
</details>

<details>
  <summary><b>Profit and Loss (P&L) Statement</b></summary>

This simplified P&L statement should give a better understanding of AtliQ's business model. In this example, the P&L values are derived from one sale transaction of one product being sold to one customer.
| P&L Line Item | Description | P&L Value Formula | P&L Value Calculation | Final P&L Value |
| :- | :- | :- | :- | -: |
| Gross Price |  The base price of a product | not applicable | `not applicable` | `$50.00` |
| Pre-Invoice Deduction | For every fiscal year, the sales team determines a<br>pre-invoice deduction percentage for each<br><ins>specific customer</ins>. The pre-invoice deduction<br>percentage is based on AtliQ's relationship and<br>experience with the customer. The pre-invoice<br>deduction is applied to the gross price of the<br>product before it is billed to the customer. In this<br>example, the customer receives a pre-invoice<br>deduction of 10% of gross price. | (Gross Price $) *<br> (Pre&nbsp;Invoice&nbsp;Deduction&nbsp;%) | `$50.00` *<br>`0.10` | `$5.00` |
| Net Invoice Sales | The amount of money that is billed to the<br>customer to obtain the product, after<br>pre-invoice deductions are subtracted<br>from gross price. | (Gross Price $) -<br>(Pre&nbsp;Invoice Deduction $) | `$50.00` -<br>`$5.00` | `$45.00` |
| Post-Invoice Deudctions | For&nbsp;each&nbsp;calendar&nbsp;month,&nbsp;the&nbsp;sales&nbsp;team<br>determines&nbsp;a&nbsp;post-invoice&nbsp;deduction&nbsp;percentage<br>based&nbsp;on&nbsp;a&nbsp;<ins>specific&nbsp;customer&nbsp;and&nbsp;product</ins>.&nbsp;For<br>example,&nbsp;if&nbsp;AtliQ&nbsp;sells&nbsp;a&nbsp;product&nbsp;to&nbsp;a&nbsp;customer<br>and&nbsp;that&nbsp;customer&nbsp;agrees&nbsp;to&nbsp;display&nbsp;the&nbsp;product&nbsp;at<br>a&nbsp;prime&nbsp;location&nbsp;within&nbsp;the&nbsp;store&nbsp;during&nbsp;a<br>specific&nbsp;calendar&nbsp;month,&nbsp;AtliQ&nbsp;may&nbsp;pay&nbsp;that<br>customer&nbsp;a&nbsp;post-invoice&nbsp;deduction.&nbsp;AtliQ&nbsp;pays&nbsp;a<br>post-invoice&nbsp;deduction&nbsp;amount&nbsp;as&nbsp;a&nbsp;rebate&nbsp;to&nbsp;the<br>customer&nbsp;after&nbsp;net&nbsp;invoice&nbsp;sales.&nbsp;In&nbsp;this&nbsp;example,<br>the&nbsp;customer&nbsp;receives&nbsp;a&nbsp;post-invoice&nbsp;deduction&nbsp;of<br>20%&nbsp;of&nbsp;net&nbsp;invoice&nbsp;sales. | (Net Invoice Sales $) *<br>(Post-Invoice Deduction %) | `$45.00` *<br>`0.20` | `$9.00` |
| Net Sales | Revenue | (Net Invoice Sales $) -<br>(Post-Invoice Deudctions $) | `$45.00` -<br>`$9.00` | `$36.00` |
| Cost of Goods Sold (COGS) | Expenses AtliQ incurs such as manufacturing<br>products, shipping products, and storing products<br>in warehouses. | (Manufacturing Cost $) +<br>(Freight Cost $) +<br>(Other COGS $) | `$9.00` +<br>`$4.00` +<br>`$3.00` | `$16.00` |
| Gross Margin | AtliQ's Profit after deducing COGS from Net Sales. | (Net Sales $) -<br>(COGS $) | `$36.00` -<br>`$16.00` | `$20.00` |
| Operational Expenses | Expenses AtliQ incurs from activities such as<br>advertising and promotions of products<br>performed by the marketing team. | (Ads & Promotions $) +<br>(Other&nbsp;Operational&nbsp;Expense&nbsp;$) | `$10.00` +<br>`$5.00` | `$15.00` |
| Net Profit | AtliQ's Profit after deducting operational expenses<br>from gross margin. | (Gross Margin $) -<br>(Operational Expenses $) | `$20.00` -<br>`$15.00` | `$5.00` |

<br>
</details>


<details>
  <summary><b>AtliQ Fiscal Dates</b></summary>

AtliQ's fiscal year begins in September and ends in August the following year. The example below shows AtliQ's fiscal dates for fiscal year 2021 compared to calendar dates.
| 	Calendar Month and Year	 | 	AtliQ Fiscal Year	 | 	AtliQ Fiscal Month Number | 	AtliQ Fiscal Quarter	 |
| 	-:	 | 	-:	 | 	-:	 | 	-:	 |
| 	September 2020	 | 	2021	 | 	1	 | 	Q1	 |
| 	October 2020	 | 	2021	 | 	2	 | 	Q1	 |
| 	November 2020	 | 	2021	 | 	3	 | 	Q1	 |
| 	December 2020	 | 	2021	 | 	4	 | 	Q2	 |
| 	January 2021	 | 	2021	 | 	5	 | 	Q2	 |
| 	February 2021	 | 	2021	 | 	6	 | 	Q2	 |
| 	March 2021	 | 	2021	 | 	7	 | 	Q3	 |
| 	April 2021	 | 	2021	 | 	8	 | 	Q3	 |
| 	May 2021	 | 	2021	 | 	9	 | 	Q3	 |
| 	June 2021	 | 	2021	 | 	10	 | 	Q4	 |
| 	July 2021	 | 	2021	 | 	11	 | 	Q4	 |
| 	August 2021	 | 	2021	 | 	12	 | 	Q4	 |

<br>
</details>



## Data Sources

<details>
  <summary><b>Dimension Tables</b></summary>

### Dimension Tables
The following **dimension tables** were given in .csv format. Sample records from the dimension tables are provided below.

**dim_customer.csv**
| customer_code | customer         | market      | platform     | channel   |
|--------------:|:-----------------|:------------|:-------------|:----------|
| 90004067      | Amazon           | Japan       | E-Commerce   | Retailer  |
| 90004068      | Amazon           | Japan       | E-Commerce   | Retailer  |
| 90007197      | Amazon           | South Korea | E-Commerce   | Retailer  |
| 90022081      | Amazon           | USA         | E-Commerce   | Retailer  |
| 90022082      | Amazon           | USA         | E-Commerce   | Retailer  |
| 90023023      | Amazon           | Canada      | E-Commerce   | Retailer  |
| 90023030      | Amazon           | Canada      | E-Commerce   | Retailer  |
| 70004070      | Atliq e Store    | Japan       | E-Commerce   | Direct    |
| 70007199      | Atliq e Store    | South Korea | E-Commerce   | Direct    |
| 70022085      | Atliq e Store    | USA         | E-Commerce   | Direct    |
| 70023032      | Atliq e Store    | Canada      | E-Commerce   | Direct    |
| 70004069      | Atliq Exclusive  | Japan       | Brick & Mortar | Direct  |
| 70007198      | Atliq Exclusive  | South Korea | Brick & Mortar | Direct  |
| 70022084      | Atliq Exclusive  | USA         | Brick & Mortar | Direct  |
| 70023031      | Atliq Exclusive  | Canada      | Brick & Mortar | Direct  |
| 90022078      | Costco           | USA         | Brick & Mortar | Retailer |
| 90023027      | Costco           | Canada      | Brick & Mortar | Retailer |
| 90022080      | Staples          | USA         | Brick & Mortar | Retailer |
| 90023029      | Staples          | Canada      | Brick & Mortar | Retailer |
| 80001019      | Neptune          | China       | Brick & Mortar | Distributor |
| 80006154      | Synthetic        | Philippines | Brick & Mortar | Distributor |

Notes:
* `customer_code` is a primary key field.


**dim_market.csv**
| market           | sub_zone | region |
|:-----------------|:---------|:-------|
| Canada           | nan      | nan    |
| USA              | nan      | nan    |
| United Kingdom   | NE       | EU     |
| Austria          | NE       | EU     |
| Sweden           | NE       | EU     |
| Spain            | SE       | EU     |
| Portugal         | SE       | EU     |
| Poland           | NE       | EU     |
| Norway           | NE       | EU     |
| Netherlands      | NE       | EU     |
| Italy            | SE       | EU     |
| Germany          | NE       | EU     |
| France           | SE       | EU     |
| Bangladesh      | ROA      | APAC   |
| New Zealand      | ANZ      | APAC   |
| Australia        | ANZ      | APAC   |
| South Korea      | ROA      | APAC   |
| Philippines      | ROA      | APAC   |
| Pakistan         | ROA      | APAC   |
| Japan            | ROA      | APAC   |
| Indonesia        | ROA      | APAC   |
| India            | India    | APAC   |
| China            | ROA      | APAC   |

Notes:
* `market` is a natural primary key field.

**dim_product.csv**
| 	product_code	 | 	division	 | 	segment	 | 	category	 | 	product	 | 	variant	 |
| 	-:	 | 	:-	 | 	:-	 | 	:-	 | 	:-	 | 	:-	 |
| A7119160102    | N & S    | Networking | Wi fi extender         | AQ Wi Power Dx1  | Plus        |
| A7119160103    | N & S    | Networking | Wi fi extender         | AQ Wi Power Dx1  | Premium     |
| A7118160101    | N & S    | Networking | Wi fi extender         | AQ Wi Power Dx1  | Standard    |
| A6419160302    | N & S    | Storage    | External Solid State Drives | AQ Clx1      | Plus        |
| A6419160303    | N & S    | Storage    | External Solid State Drives | AQ Clx1      | Premium     |
| A6419160301    | N & S    | Storage    | External Solid State Drives | AQ Clx1      | Standard    |
| A3119150303    | P & A    | Accessories| Keyboard               | AQ Gamers        | Plus 1      |
| A3120150304    | P & A    | Accessories| Keyboard               | AQ Gamers        | Plus 2      |
| A3120150305    | P & A    | Accessories| Keyboard               | AQ Gamers        | Premium 1   |
| A3120150306    | P & A    | Accessories| Keyboard               | AQ Gamers        | Premium 2   |
| A3119150301    | P & A    | Accessories| Keyboard               | AQ Gamers        | Standard 1  |
| A3119150302    | P & A    | Accessories| Keyboard               | AQ Gamers        | Standard 2  |
| A0721150402    | P & A    | Peripherals| Graphic Card           | AQ GT 21         | Plus 1      |
| A0721150403    | P & A    | Peripherals| Graphic Card           | AQ GT 21         | Plus 2      |
| A0721150404    | P & A    | Peripherals| Graphic Card           | AQ GT 21         | Premium     |
| A0721150401    | P & A    | Peripherals| Graphic Card           | AQ GT 21         | Standard    |
| A4118110105    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Plus Blue   |
| A4118110104    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Plus Grey   |
| A4118110106    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Plus Red    |
| A4118110107    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Premium Black|
| A4118110102    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Standard Blue|
| A4118110101    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Standard Grey|
| A4118110103    | PC       | Notebook   | Personal Laptop        | AQ Aspiron       | Standard Red|

Notes:
* `product_code` is a primary key field.

</details>




<details>
  <summary><b>Fact Tables</b></summary>

### Fact Tables
The following **fact tables** were given in .csv format. Sample records from the fact tables are provided below.


**fact_sales_monthly_with_cogs.csv**
| date       | product_code | customer_code | Qty  | net_sales_amount | freight_cost | manufacturing_cost |
|:-----------|:-------------|:--------------|-----:|-----------------:|-------------:|-------------------:|
| 01-09-2019 | A0118150101  | 70002017      | 137  | 1219.35          | 41.214       | 687.8359           |
| 01-09-2019 | A0118150101  | 70002018      | 47   | 321.88           | 10.8795      | 235.9729           |
| 01-09-2019 | A0118150102  | 70002017      | 122  | 1346.2           | 45.5016      | 697.596            |
| 01-09-2019 | A0118150102  | 70002018      | 24   | 238.2            | 8.0512       | 137.232            |
| 01-10-2019 | A0118150101  | 70002017      | 40   | 408.34           | 13.8019      | 200.828            |
| 01-10-2019 | A0118150101  | 70002018      | 32   | 220.56           | 7.4549       | 160.6624           |
| 01-10-2019 | A0118150102  | 70002017      | 189  | 2180.02          | 73.6847      | 1080.702           |
| 01-10-2019 | A0118150102  | 70002018      | 139  | 1218.23          | 41.1762      | 794.802            |
| 01-09-2020 | A0118150101  | 70002017      | 248  | 2628.35          | 88.8382      | 1368.2656          |
| 01-09-2020 | A0118150101  | 70002018      | 240  | 2127.05          | 71.8943      | 1324.128           |
| 01-09-2020 | A0118150102  | 70002017      | 42   | 523.05           | 17.6791      | 263.907            |
| 01-09-2020 | A0118150102  | 70002018      | 91   | 915.35           | 30.9388      | 571.7985           |
| 01-10-2020 | A0118150101  | 70002017      | 297  | 3224.98          | 109.0043     | 1638.6084          |
| 01-10-2020 | A0118150101  | 70002018      | 119  | 1038.28          | 35.0939      | 656.5468           |
| 01-10-2020 | A0118150102  | 70002017      | 275  | 3426.57          | 115.8181     | 1727.9625          |
| 01-10-2020 | A0118150102  | 70002018      | 284  | 2991.32          | 101.1066     | 1784.514           |

Notes:
* This table contains monthly-level data on the sold quantity, net sales amount (INR), freight cost (INR), and manufacturing cost (INR) for specific products that were sold to specific customers.
* The columns `date`, `product_code`, and `customer_code` make up a **composite primary key**
* Sales data is available for fiscal years 2019 - 2021






**ns_targets_2021.csv**
| market    | date       | ns_target  |
|:----------|:-----------|-----------:|
| Australia | 01-09-2020 | 1382159.39 |
| Australia | 01-10-2020 | 2451000.08 |
| Australia | 01-11-2020 | 2459652.74 |
| Australia | 01-12-2020 | 2742446.53 |
| Australia | 01-01-2021 | 1729612.92 |
| Australia | 01-02-2021 | 2231597.38 |
| Australia | 01-03-2021 | 1459573.96 |
| Australia | 01-04-2021 | 1441866.81 |
| Australia | 01-05-2021 | 1915141.92 |
| Australia | 01-06-2021 | 2079358.25 |
| Australia | 01-07-2021 | 1879802.47 |
| Australia | 01-08-2021 | 1431823.83 |
| Japan     | 01-09-2020 | 715752.76  |
| Japan     | 01-10-2020 | 722257.34  |
| Japan     | 01-11-2020 | 1005447.89 |
| Japan     | 01-12-2020 | 1077076.2  |
| Japan     | 01-01-2021 | 671610.08  |
| Japan     | 01-02-2021 | 590203.95  |
| Japan     | 01-03-2021 | 501434.68  |
| Japan     | 01-04-2021 | 530307.52  |
| Japan     | 01-05-2021 | 647880.92  |
| Japan     | 01-06-2021 | 542891.58  |
| Japan     | 01-07-2021 | 537450.29  |
| Japan     | 01-08-2021 | 706669.66  |


Notes:
* This table contains monthly-level net sales targets (INR) for specific markets.
* The columns `market` and `date` make up a **composite primary key**
* Net sales target data is available for fiscal year 2021









</details>




## Generating the Reports in Excel

<details>
  <summary><b>Generating the Reports in Excel</b></summary>

The dimension and fact tables were imported into Excel using Power Query, with an additional `dim_date` table created within Power Query. The data was then loaded into the Power Pivot data model, where relationships between the tables were defined (screenshot of Power Pivot data model below). KPIs such as net sales were calculated using DAX measures within Power Pivot. Finally, PivotTables were used to build the sales and finance reports.

![Power Pivot Data Model](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/refs/heads/main/Power%20Pivot%20Data%20Model.PNG)
</details>










## Sales Reports
Click the links below to view PDFs of sales reports:

[🔗 **Net Sales Performance by Customer (FY2019 - FY2021)**](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/main/Customer%20Performance%20Report.pdf)

[🔗 **FY2021 Net Sales Performance by Market: Actual vs Target**](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/main/Market%20Performance%20vs%20Target%20Report.pdf)


## Finance Reports
Click the links below to view PDFs of finance reports:

[🔗 **Profit and Loss (P&L) Statement by Fiscal Year (FY2019 - FY2021)**](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/main/P%26L%20Statement%20by%20Fiscal%20Year.pdf)

[🔗 **Profit and Loss (P&L) Statement by Month (FY2019 - FY2021)**](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/main/P%26L%20Statement%20by%20Months.pdf)

[🔗 **Profit and Loss (P&L) Statement by Market (FY2021)**](https://raw.githubusercontent.com/mike-li8/Excel-Sales-and-Financial-Analytics/main/P%26L%20Statement%20by%20Markets.pdf)
