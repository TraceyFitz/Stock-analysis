# VBA of Wall Street

## Overview of Project - Steve is helping his parents find clean energy stocks to invest in. His parents are particularly interested in a stock called Daqo (ticker DQ). Steve would like to find the total daily volume and annual return for each stock. Please note - Daily volume is the total number of shares traded throughout the day; it measures how actively a stock is traded. Annual return is the percentage difference in price from the beginning of the year to the end of the year. 


## Results - Using the total daily volume and yearly return we are able to determine Daqo was a good investment in 2017 but was not a good investment in 2018. I added a filter to the daily volume and return columns to analyze the stocks by highest performing for each. 

For the year 2017, let's look at the three best performing stocks. DQ had the lowest daily volume but the highest return of 199.4%. Ticker SEDG had the second highest return at 184.5% and a daily volume ranked 6th. Ticker ENPH is the third highest performing stock with a return of 129.5% and a daily volume ranked 5th. See screen shot:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/14b31e11af06011b0e0d8119756f69372e18214c/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_2017.png)


For the year 2018, DQ is ranked 9th in terms of daily volume. Its return is -62.6%. There are other stocks in the green energy portfolio that perform much better in 2018. For example ENPH has the highest daily volume and an 81.9% return. Ticker RUN has the second highest daily volume and a whopping 84% return. The other green energy stocks all performed at a loss for the year 2018. See screenshot:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/14b31e11af06011b0e0d8119756f69372e18214c/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_2018.png)


It would seem the stock ENPH had more consistent returns over the years 2017 and 2018 and would therefore be a better investment for Steve's parents. Although the daily volume differed over the two years, I see no correlation between the annual returns for each year and the daily volume.


## Summary 

Refactoring is basically tweaking our existing code to run more efficiently. We are not necessarily adding any new functionality but for example using less memory, reducing the number of steps or improving the logic of the code to make it easier for others to read. Refactoring is very common and provides an avenue to collaborate and improve our code. 

I did not see much of an improved performance in the timer for the refactored code. In fact, it seemed the non refactored code was slightly faster than refactored code in the 2017 analysis. Refactored code for 2017 and 2018 were both timed at .07421875. The non refactored code for 2017 was slightly faster on the timer at .078125, but 2018 was the same. See timer screenshots in Module 2 VBA Challenge folder for png files with timer in the name on GIT or reference below. 

Refactored All Stock Analysis Code 2017 Timer:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/6924fca97fb747a9fda55adc4c941eec55309f7d/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_2017_Timer.png)

Refactored All Stock Analysis Code 2018 Timer:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/9d08b3d0c311c62832c61f97612f0b7b78eb40ec/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_2018_Timer.png)


Non Refactored All Stock Analysis 2017 Timer:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/14b31e11af06011b0e0d8119756f69372e18214c/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_Nonrefactored_code_2017_Timer.png)

Non Refactored All Stock Analysis 2018 Timer:
![This is an image](https://github.com/TraceyFitz/stock-analysis/blob/14b31e11af06011b0e0d8119756f69372e18214c/MODULE%202%20VBA%20Challenge-Resources/VBA_Challenge_Nonrefactored_code_2018_Timer%20.png)
