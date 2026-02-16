Twitter Analytics Dashboard – Task 1
Project Overview.

This project analyzes the relationship between Media Views and Media Engagements using a Power BI scatter chart. The dashboard applies strict filtering conditions as specified in the task.
Objective

To identify tweets that satisfy the following conditions:
- Replies greater than 10
- Engagement Rate greater than 5%
- Tweet Word Count above 50
- Tweet posted on an odd date
- Tweet posted between 6 PM and 11 PM IST
- Media Views and Media Engagements not blank

Tools Used
- Power BI
- DAX
- CSV Dataset

Data Transformations
- Extracted Hour from timestamp
- Created Tweet Word Count calculated column
- Created IsOddDate flag
- Created IsEveningTime flag (6 PM – 11 PM filter)

KPIs Measured
- Engagement Rate
- Replies
- Media Views
- Media Engagements
- Tweet Word Count

After applying all required constraints simultaneously, no tweets in the dataset satisfied every condition. Therefore, the scatter chart does not display any data points.

