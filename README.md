# stocks-analysis

## Overview of Project and Purpose.
The purpose of this Module Challenge was to use our newly learned Excel VBA skills to refactor code that we created previosuly in the module. The purpose of refactoring is to create a code that runs more effeciently which can speed up the process of data analysis. In this challenge, we used logic statements such as If-Then and For Loops as a way to sort through our data as well as arrays and various formatting elements. 

## Results
These are the results

### Analysis of Outcomes Based on Launch Date
For the first deliverable, we were asked to create a graphical representation of the campaign outcomes based on the launch date. In order to do this, we first needed to use the YEAR() function to obtain the year from each datapoint and then we created a PivotTable to count all of the different outcomes (for Theaters only). From there, we just created a line chart and added a chart header to it. 

### Analysis of Outcomes Based on Goals
For the second deliverable, we were asked to create a graphical representation of the campaign outcomes based on the goal. In order to do this, we needed to use the COUNTIFS() function which essentially filters through a data set by the columns you enter in the function. Using this function, we created a table based on the different outcomes (successful, failed, canceled) and by different ranges (for the goal amount). 

### Challenges and Difficulties Encountered
I did not have many problems with this challenge but I did struggle a little bit on the second deliverable. For some reason my chart was looking a little bit off but then I reread the deliverable instructions and found out that my ranges were off a little and I was using the entire dataset and not filtering by “plays”. I reread the instructions and went through the functions in the cells to make sure I had done everything correctly; I retraced my steps and double checked my work. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

From looking at the chart, we can tell that from all the theater launches, there have been a lot more successful outcomes than failed or canceled outcomes in each month. We can also tell that successful outcomes tend to fall towards the end of the year while canceled and failed outcomes stay relatively stable throughout the year compared to the successful outcomes. 

- What can you conclude about the Outcomes based on Goals?

From looking at the graph, we can tell that the percentage of canceled outcomes is 0% in the given goal ranges. Moreover, we can tell that the combination of Percentage Successful and Percentage Canceled adds up to 100%. This is seen on the chart as the Percentage Successful and Percentage Failed graphs are mirror opposites of each other. 

- What are some limitations of this dataset?

There is a lot of data in the dataset and it needs to be filtered if an individual wants to see something specific about it. 

- What are some other possible tables and/or graphs that we could create?

We could create a table/graph for Outcomes Based on Country to see how each country does compared to the other. We could also create a table/graph for Average Donation Based on Country to see how the donations differ based on each country. 
