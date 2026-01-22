# Predictive-and-Forecasting-Analysis-for-super-Store-dataset
In this Project we developed our works from the previous stages: data preprocessing,[Descriptive Analytics](https://github.com/ishraq-dagamseh/SuperStore-Data-Analysis-using-PowerBI) to find out What happend ,and [Diagnostic Analytics ](https://github.com/ishraq-dagamseh/Diagnostic-Analytics-to-superstore-dataset) to find out Why it happened, by creating a third type of data analysis, which is: predictive analysis to find out what will happen in the future.

# Our steps:
1. make line chart to show the current relationship between the profit Margin and the Date (Month and years), then we add Forcasting feature To predict the future relationship for the next 6 months with Confidence Interval of 95%.
2. make line chart to show the current relationship between the Total sales and the Date (Month and years), then we add Forcasting feature To predict the future relationship for the next 6 months with Confidence Interval of 95%.
3. Three measurements added to the Dashboard: Expected margin to Estimate the margin for the next month using time intelligencebased on this equation: Expected Margin = CALCULATE([Profit Margin1],DATEADD('Sample - Superstore'[Date], 1, MONTH)),
   Margin Trend to Compares expected margin with the current margin based on  this equation: Margin Trend = IF([Expected Margin] < [Profit Margin1], "⬇️ Decline", "⬆️ Growth"), and and Classifies business risk using a predefined threshold (0.1) based on this equation: Risk Level = IF([Expected Margin] < 0.1, "High Risk", "Normal").
4. Two matrix visuals were created to summarize predictive insights:
	•	Matrix 1: Measures by Category
	•	Matrix 2: Measures by Region

Each matrix displays:
	•	Expected Margin
	•	Margin Trend
	•	Risk Level
   
# Our findings and Conclusions:
   •	The forecast indicates that profit margin is expected to increase from 0.10 to approximately 0.13, after which it remains stable for around four months.
	•	Sales forecasts show noticeable instability during the same period.
	•	The Expected Margin stabilizes at 0.13, while the Margin Trend shows a decline, but still within a Normal Risk level.
	•	From the Category-based matrix:
	   Technology category is expected to generate the highest margin with Normal Risk.
	•	Furniture category presents a High Risk, requiring attention.
	•	From the Region-based matrix:
	   The Central region shows the highest risk level, followed by the South region.
# The Final Dashboard
<img width="879" height="494" alt="image" src="https://github.com/user-attachments/assets/016c7b29-58ed-4f62-b1be-d37766f9722a" />

   


