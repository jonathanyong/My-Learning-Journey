# Tic-Tac-Toe
First Milestone project completed from Udemy: Complete Python Bootcamp course - Jose Portilla

# BlackJack
Second Milestone project completed from Udemy: Complete Python Bootcamp course - Jose Portilla

# TslaFGMAnalysis
Third Milestone project completed from Udemy: Python for Financial Analysis and Algorithmic Trading - Jose Portilla

Embarking on this third milestone project taught me more about visualization techniques and tools using pandas, matplotlib, pandas_datareader, and pulling data from online sources such as yahoo finance. This project taught me more about Quandl as a company and the different financial data API that can be attained from their website. These data are valuable in financial analysis, and greatly value-adds to coders out there. 

However, there were some roadblocks along the way, such as google changing its API, matplotlib.finance having changed its API to mpl_finance instead, not understanding what candlestick_ohlc actually means, not understanding what date2num from matplotlib.dates actually does, as well as understanding how to calculate cumulative daily return using .cumprod(). There are 2 issues which I felt could be improved on, including the difference in code for plotting a histogram vs. plotting a kde graph. A histogram plot code e.g. Tesla['Volume'].hist() , while a kde is Tesla['Volume'].plot(kind='kde') instead of Tesla['Volume'].kde(). The other issue would be that why do we need to concatenate data when plotting a boxplot but not a histogram or kde? It was a challenge trying to apply what was taught in the matplotlib lectures on changing datalabels, formatting datetime indexes into non-datetime etc. 

Overall, I felt that learning the basics of financial analysis using python and data visualization will be much helpful in pursuing much in-depth financial analysis. 

Investment analysts today still rely heavily on spreadsheets to do their financial modelling etc, which makes me wonder whether it is possible (and easier) to conduct financial analysis methods (e.g. DCF) using python? Has anyone produced a fintech product which could automatically generate a DCF model and its results just by importing a PDF file? At the back of my mind, I believe that there will be alot of junk data and noise data which hinders the ease of making analysis automated today, hence the need for what they call a "Data Analyst" to clean up the data.
