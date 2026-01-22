# Predictive-and-Forecasting-Analysis-for-super-Store-dataset
In this Project we developed our works from the previous stages: data preprocessing,[Descriptive Analytics](https://github.com/ishraq-dagamseh/SuperStore-Data-Analysis-using-PowerBI) to find out What happend ,and [Diagnostic Analytics ](https://github.com/ishraq-dagamseh/Diagnostic-Analytics-to-superstore-dataset) to find out Why it happened, by creating a third type of data analysis, which is: predictive analysis to find out what will happen in the future.

# Our steps:
1. make line chart to show the current relationship between the profit Margin and the Date (Month and years), then we add Forcasting feature To predict the future relationship for the next 6 months with Confidence Interval of 95%.
2. make line chart to show the current relationship between the Total sales and the Date (Month and years), then we add Forcasting feature To predict the future relationship for the next 6 months with Confidence Interval of 95%.
3. Three measurements added to the Dashboard: Expected margin By adding this equation Expected Margin = CALCULATE([Profit Margin1],DATEADD('Sample - Superstore'[Date], 1, MONTH)),
   Margin Trend to show the expected trend to Expected Margin by adding this equation: Margin Trend = IF([Expected Margin] < [Profit Margin1], "⬇️ Decline", "⬆️ Growth"), and and decided default value to the risk level by 0.1 based on this equation: Risk Level = IF([Expected Margin] < 0.1, "High Risk", "Normal").
4. Two matrix to summarize the 3 measurements based on category and another based on the Region.

   # Our Conclusion:
   we concluded that the model forecast that the “profit margin is forecasted to increase to 0.13, after which it stabilizes with limited growth potential. and the salles will be unstable during this months.  Expected Margin will be 0.13 and Margin Trend decline with Normal level of the Risk. From the matrices we concluded that the most expected margin will come from the technology category with normal risk and the Furniture will cause High risk. From the second Matrix we noticed that the higher risk will come from Central region then South Region.
# The Final Dashboard
<img width="879" height="494" alt="image" src="https://github.com/user-attachments/assets/016c7b29-58ed-4f62-b1be-d37766f9722a" />

   


