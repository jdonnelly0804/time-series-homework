# Time-Series-Homework

*The Link to the Google Colab Notebook that contains all of my code can be accessed here:*

[Notebook](https://colab.research.google.com/drive/1hGwWsQIt3ZfAu3XaDD6_Hgu0P9xDJt6R#scrollTo=pt-JEuuIiGuE)
>
I will be doing a writeup including my findings and the relevant graphs/visualizations to answer questions below:
>
-Questions will be posed in bold
>
-Answers will be posed in italics

---

## Step 1: Find Unusual Patterns in Hourly Google Search Traffic
![may_2020](Images/may_2020data.PNG)
>
The above image shows the google search trends for MercadoLibre for the month of May 2020. The total searches for the month was 38,181, the median searches for each month of the year was 35,172.5. 

**Did the Google search traffic increase during the month that MercadoLibre released its financial results?**
>
*The google search traffic did increase the month that MercadoLibre released their financial results. There was a 8.53% increase in the number of searches if you compare the month of may to the median number of searches.*

---

## Step 2: Mine the Search Traffic Data for Seasonality
![heatmap](Images/heatmap.PNG)
>
The above heatmap shows the search trends for MercardoLibre based off the hour as well as the day of the week.
>
**Does any day-of-week effect that you observe concentrate in just a few hours of that day?**
>
*It seems that despite the day of the week, the search trends look pretty much similar across all times of the day*
>
![mean_by_week](Images/mean_by_week.PNG)
>
**Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?**
>
*The search traffic does appear to have a sharp increase in the winter holiday period, followed by a steep drop off at the last week of the year*