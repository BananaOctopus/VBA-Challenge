# Stock Analysis from 2017 and 2018 using Excel VBA
## 1.	Overview of Project
The purpose of this analysis was to check how much each stock’s return was over one year of price changes. So, for each year, in the end, each stock either had a positive or negative return rate, and this would indicate how well it did over the course of the year and whether it would be worth investing in in the future.
## 2. Results
All the tickers except for TERP had positive returns in 2017, which is great until 2018, were all tickers except ENPH and RUN experienced negative return. This is shown after running the All Stocks Analysis and the Refactor. 

![All Stocks 2017](https://user-images.githubusercontent.com/84158312/124669522-85637500-de80-11eb-981f-e0de3839f9af.png)

![All Stocks 2018](https://user-images.githubusercontent.com/84158312/124669541-8d231980-de80-11eb-86af-5dc632222601.png)

How quickly the programs got to these conclusions did differ, with the 2017 data set being ran 0.01 seconds slower via the refactor program than through the All Stocks Analysis. 

![image](https://user-images.githubusercontent.com/84158312/124670262-b8f2cf00-de81-11eb-863f-ae244b74e261.png)

![image](https://user-images.githubusercontent.com/84158312/124670283-c019dd00-de81-11eb-8a79-a928c7c8ca24.png)

The refactory analysis did run the 2018 year data more quickly than running it through the more basic All Stocks Analysis code, by 0.17 seconds.

![image](https://user-images.githubusercontent.com/84158312/124670708-62d25b80-de82-11eb-8d86-05a0d8121db3.png)

![image](https://user-images.githubusercontent.com/84158312/124670719-66fe7900-de82-11eb-95b4-23b8337e782d.png)

### The code for the All Stocks Analysis results is below:

![AllStocksAnalysis Total](https://user-images.githubusercontent.com/84158312/124672213-a9c15080-de84-11eb-9786-b98070ae3b00.png)

### The code for the All Stocks Refactored Analysis is below:

![Refactored Analysis All](https://user-images.githubusercontent.com/84158312/124672281-c52c5b80-de84-11eb-84b6-b9d3fac215d3.png)
