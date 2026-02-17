# Financial Analysis Data Stock UNVR
This project consists of analyzing the current condition of UNVR stock data and comparing it with the prices and growth of competitor stocks using python. The main objective of this project is to provide investors with insights into UNVR stocks.

## Tools
* **Platform:** Jupyter Notebook.
* **Data Manipulation:** Python (Pandas & Datetime).
* **Data Source:** <a href=https://finance.yahoo.com/>yfinance API</a>.
* **Data Visualization:** Matplotlib (Static plots) & Plotly (Interactive dashboards).

## KPIs / Business Questions
1. Which stock delivered the best return for long-term investors (2017–2026) among UNVR, ICBP, and MYOR?
2. What is the risk–return profile of each stock, and which one is the most optimal?
3. What are the characteristics of UNVR’s daily price movements, and what is the dominant pattern?
4. How has UNVR trended since 2017, and are there any signals of a trend reversal?

## Project Insight
1. Stock Price Performance & Growth Analysis (UNVR, ICBP & MYOR)
   - Top performer: Although MYOR.JK appears “cheap” in nominal price (around Rp2,000), in percentage terms it outperformed the others with a +65.2% growth since 2017.
   - Sharp decline: UNVR.JK experienced the opposite outcome. Since 2021, its price has dropped significantly compared to competitors like ICBP. From the 2017 starting point, UNVR investors actually suffered a loss of around -60.6%.
   - Conclusion: A high stock price (such as ICBP at around Rp8,000) does not guarantee the highest growth.
  
2. Risk & Return (UNVR, ICBP & MYOR)
   - UNVR (High Risk, Negative Return):Based on daily data, UNVR has the highest risk level (standard deviation) at 0.021968, but with a negative average return (-0.000177), which leads to investor losses.
   - MYOR (The Profitable Choice): This stock performs best, delivering the highest average daily return (0.000437) with a still-manageable risk level (0.016603).
   - ICBP (Middle Ground): Sits in the middle with +15% growth. Although it has the highest price, it is the most stable on a daily basis with the lowest risk (0.016603).

3. Stock Characteristics from the Histogram
   - UNVR histogram: The bars are mostly concentrated in the middle-left area. This visually shows that the stock more often stagnates or declines rather than generates profit.
   - Distribution:
Unlike its competitors, UNVR’s histogram indicates that downward pressure is stronger than its attempts to recover upward.

4. Stock Movement Details (Candlestick)
   - Downtrend: Since reaching its peak in 2018 (around Rp7,500), UNVR’s price has continued to form a descending pattern.
   - Recovery attempts: There are visible increases in volume and price from mid-2025 to early-2026, attempting to break the long-term average line (MA200). However, overall, the trend still struggles to reverse completely due to strong historical selling pressure.
  
## Contact Me
* **LinkedIn:** (www.linkedin.com/in/jefry-ramadhan)
* **Email:** rahmadjefry@gmail.com 
