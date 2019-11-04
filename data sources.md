### For the daily number of employees and LinkedIn followers of a company, the data can be downloaded via this link: https://us8.mailchimp.com/mctx/click?url=https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fdocuments.thinknum.com%2Fdataset_dump%2Fflikerqvnk%2Ftemp_datalab_records_linkedin_company.zip&xid=fe7824d9e0&uid=29791003&pool=&subject=

### The columns for LinkedIn data:
#### dataset_id: Basically, dataset_id can refer to a company. But dataset_id and company_name have a many-to-many relation. Whereas, dataset_id  has a one-to-one relation with link, which is the LinkedIn web page.
#### as_of_date: The date that correspond to followers_count and employees_on_platform.
#### company_name: The name of a company.
#### followers_count: The number of LinkedIn followers.
#### employees_on_platform: The number of employees that are LinkedIn followers.
#### link: The link for the LinkedIn page of the company.
#### industry: The industry that the company belongs to.

### For the daily stock price, the data can be obtained in Quandl: https://www.quandl.com/data/EOD-End-of-Day-US-Stock-Prices?keyword=
### The columns for stock price data:
#### Date: The date the correspond to the stock price.
#### Open: The open price for a stock
#### High: The highest price of a stock at that day.
#### Low: The lowest price of a stock at that day.
#### Close: The close price of a stock at that day.
#### Volume: The trading volume of a stock at that day.
