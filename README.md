**How to trade with Mean-Reversion Strategy?**

I find it enjoyable to analyze global macroeconomics on paper, but I am particularly fond of putting that knowledge into practice to see how it can be profitable.

Owing to the year-end holidays, I freed up some time to study mean-reversion (thanks Google!), which is a type of quantitative trading strategy. This strategy involves buying (long) undervalued assets and selling (short) overvalued assets, with the expectation that the prices of these assets will eventually revert back to their historical averages - hence mean-reversion.

I then use Python to test this strategy on the DXY, a proxy for the US dollar to see how it performs under different macroeconomic regimes. These are the steps I have taken to execute the strategy:



Step 1. Import libraries (numpy, pandas, matplotlib) and data (historical prices of DXY)

Step 2. Calculate the moving averages and moving standard deviation of DXY 

Step 3. Compute the bollinger band - the upper and lower band of DXY based on the results of step 2 (Chart 1) 

**Chart 1**

![Slide2](https://user-images.githubusercontent.com/121606452/210162495-47377ed5-b468-4981-b831-87a3980c2097.JPG)


Step 4. Define the benchmark for long/short's entry and exit points, ie if DXY < lower band, go long DXY and vice versa

Step 5. Execute the strategy and calculate the Profit & Loss (PnL).




Looking at the cumulative PnL over the years had the strategy been implemented, this strategy appears to produce consistent profit (Chart 2), not bad! 


**Chart 2**

![1672371595702-_1_](https://user-images.githubusercontent.com/121606452/210162558-de5a15da-072b-4e10-9cf8-844f3d13e4ad.jpeg)



Interestingly, it also performs relatively well in a stable environment when volatility is low, but not so well when there is a regime change in the macro backdrop.

Happy to discuss/share further on this (the codes, analysis etc). Hit me up!

Oh and, happy new year in advance everyone!!

