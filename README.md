# MattPortfolio
Project 6 uses some Excel data exploration for readability and adds a dashboard for quick insights.

The data here is from United Airlines in December 2015 from http://www.transtats.bts.gov/. I accessed this data in my Coursera Advanced Business Analytics Specialization Certificate course from the University of Boulder Colorado.

The first Excel was meant as an exercise for quick data cleaning and exploration. 
    I used Columns E and F to create new, more readable columns. Columns E and F are in minutes after 12:00AM, so I used nested IF statements to change the data to a more readable time (Columns L and M). 
    I also changed Column B from a number to a text value to become the day of the week.  
    Column G was used for Column N where I clarify if planes were late or early. 
    Columns I and J were used for Columns O and P. Here, I changed minutes to a combination of hours and minutes.

However, these just make the data more readable. The practicality of these new columns isn't warranted, so the next Excel document covers the dashboard. The data itself includes information about timliness, so the story it's trying to tell might have been about timliness. After some exploration with pivot tables, I found that the different airports (both origin and departure) have potential effects on delays. The obvious outliers here were the CVG-ORD flights, which had much longer delays. I assumed United would be well aware of thes outliers, but I still kept one table including these outliers. By filtering out the CVG-ORD flights, I was able to see that SFO was associated with larger delays. This is the real information I was looking for. The bar charts were colored to make this data finding clear, and they were added to the dashboard.
