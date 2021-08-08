# Excel-Kickstarter

Objective: Organize and analyze a database of 4,000 past projects in order to uncover any hidden trends, examine the funding process, and determine the outcome of the projects.

In this project, I started off by using conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, cancelled, or is currently live. I am also determining the percent funded in a seperate column, and using a three-color scale to determine how much money a campaign made to reach its initial goal. 
- Dark Red = 0
- Transition to Green = 100
- Transition to Blue = 200

There are also 3 pivot tables included in this workbook. 

1st: The first pivot table will analyze my initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category. 
2nd: The second pivot table will analyze my initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
3rd: The third pivot table will analyze a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years

Finally, the sheet titled "Final" will determine the final outcome based on Goals. 

- Green = Successful 
- Blue = Failed
- Blue = Cancelled 
