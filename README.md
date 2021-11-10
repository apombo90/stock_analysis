# **Analysing Green Energy Stocks to support investment decisions**
## Project overview:
- On this project I analyzed Green Energy Stock data from 2017 and 2018, to identify what would be the best option to invest in. The analysis doesn't take into account external factors such as company performance, supply and demand, speculations, interest rate, ect., i.e, the analysis is based on stucks returns and daily volumes through all the year. To accomplish this analysis, I created a code using VBA to loop through all the data and collect all the information to present the stocks performance. For this I incorporated arrays, nested loops, conditional formatting, static formatting, and macro buttons to make the outcome easer to understand. Finally, this version is refactored, I made the code more efficient and readible.

## **Analysis:**

### Stocks Performance 2017:
- Table shows that only one stock (TERP) had a negative return in 2017.
- There are four stocks (DQ*, ENPH, FSLR SEDG) that double their price through the begining and end of 2017. **DQ almost triple their price in 2017.* 
- It is possible to determine that there are two stocks (SPWR and FSLR) with very high liquidity as the number of shares traded in 2017 surpases 6 million.
- Nevertheless, DQ was the stock with higher return but with less shares traded in 2017. This could tell us that the stock is not easy to trade.

![All_Stocks_2017.png](Resources/All_Stocks_2017.png)

### Stocks Performance 2018:
- 83% of the stocks had a negative return in 2018. Only ENPH and RUN had positive returns.
- ENPH and RUN had a significant increase in their number of shares trade in 2018 compared to 2017. Respectively, this represents a 174% and 88% increase.
- TERP had a two year consecutive negative return. 
- On the other hand, ENPH and RUN where the only stocks who had postivie returns in both years.

### Code's versions comparison:
