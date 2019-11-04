### 1. For the daily number of employees and LinkedIn followers of a company, the data can be downloaded via this link: https://us8.mailchimp.com/mctx/click?url=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fdocuments.thinknum.com%2Fdataset_dump%2Fflikerqvnk%2Ftemp_datalab_records_linkedin_company.zip&xid=fe7824d9e0&uid=29791003&pool=&subject=

### The columns for LinkedIn data:
#### 1.1 dataset_id: Basically, dataset_id can refer to a company. But dataset_id and company_name have a many-to-many relation. Whereas, dataset_id  has a one-to-one relation with link, which is the LinkedIn web page.
#### 1.2 as_of_date: The date that correspond to followers_count and employees_on_platform.
#### 1.3 company_name: The name of a company.
#### 1.4 followers_count: The number of LinkedIn followers.
#### 1.5 employees_on_platform: The number of employees that are LinkedIn followers.
#### 1.6 link: The link for the LinkedIn page of the company.
#### 1.7 industry: The industry that the company belongs to.

### 2. For the daily stock price, the data can be obtained in Quandl: https://www.quandl.com/data/EOD-End-of-Day-US-Stock-Prices?keyword=
### The columns for stock price data:
#### 2.1 Date: The date the correspond to the stock price.
#### 2.2 Open: The open price for a stock
#### 2.3 High: The highest price of a stock at that day.
#### 2.4 Low: The lowest price of a stock at that day.
#### 2.5 Close: The close price of a stock at that day.
#### 2.6 Volume: The trading volume of a stock at that day.
