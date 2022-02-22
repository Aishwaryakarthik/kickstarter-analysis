# kickstarter-analysis

performing analysis on Kickstarter data to uncover trendsKickstarter analysis

1.Overview of the project

We do an analysis in the Kickstarter projects to derive multiple outcomes.

1.To find the theatre outcome based on the launching date:
    In this, we are able to obtain the results and visualize the number of successful, failed and canceled Kickstarter Campaigns based on the launching date given in the master data table. We end up depicting this in a graph that we create.
    
2.To find the outcomes based on the goal amounts:
    In this, we are able to obtain to obtain the results and visualize the number of successful, failed and canceled campaigns based on the funding goal ranges given in the master table for one particular subcategory-plays. We end up showing the results in a graph that we create.



2.Analysis and Challenges
 
Theatre Outcomes based on the launching date:

Creating a pivot table

We take the Kickstarter analysis worksheet, we add a new column years and save the worksheet along with existing data.
 Use year() function to get the year from the ‘date created conversion’ column. We save the table and select the entire table using ctrl A and create a new pivot table and label it with a ‘theatre outcomes based on launch date’. 
Make sure to include the entire cell range to a new worksheet. On the right side filter the data using parent category and years and outcomes as row values and column. Click on the years cell range and group them to get the months. 
A new pivot table with filters and values are ready to view. Use filters in row labels to check canceled, successful and failed outcomes. Filter the parent category to theatre and check select all in years.

https://1drv.ms/x/s!AlKtrx-dsEKQgQVJr99hEHHPhHyr?e=vgUTMt

 Our pivot table with theatre outcome based on the launching dare is ready now. Create a pivot chart by selecting the entire pivot table that we just created. Choose ‘stacked line chart’ and remember to add the chart title to it.
 
 ![theatre outcome based on launch date](https://user-images.githubusercontent.com/99555513/155052985-c2a2bdec-5c5a-48eb-b3e2-8fadab7bd63c.png)




	Creating a pivot chart

Select the entire pivot table we created and go to ribbon and choose option insert a new pivot chart and choose line chart as needed based on our requirement. Here for this we choose stacked line chart and add a chart title as ‘Theatre outcome based on the launching date’ and save it in PNG file format.

To find the outcomes based on the goal amount

In this we create a new table based on the master table-Kickstarter analysis and name it as ‘outcomes based on goal’. In the goal column we add the multiple range from less than 1000 to 50000 or more. Also we add several other columns like # successful, #failed and #canceled and percentage successful, percentage failed and percentage canceled. 
We use COUNTIFS() function to populate #successful #failed and #cancelled campaigns. We use percentage formula and SUM() function to fill the data in the other columns.

Our table will look as follows:

https://1drv.ms/x/s!AlKtrx-dsEKQgQVJr99hEHHPhHyr?e=0GDwu5
 
Creating a line chart

We can now select the entire worksheet labeled ‘outcomes based on goal’ and create a new line chart and choose stacked line chart option and once the chart is selected filter the options to display for the desired goal range vs percentage of successful, failed and canceled kickstarter-campaigns for plays subcategory only. Add a corresponding chart title and save it in the PNG format.

The line chart will result as follows:

![outcomes based on goal](https://user-images.githubusercontent.com/99555513/155053682-cfe0b07a-106d-4ef8-a534-d2049b0b5a00.png)

 
Challenges and difficulties encountered:

 In the portion of the outcomes based on the goals part of the project, a lot of formulas and functions needed to be retyped multiples times for the multiple goal ranges. Also the chances of getting an error was high when we simply mistype the cell reference while typing the formula.


3.Results

•	Conclusion drawn from the outcomes based on launch date:

We can see the number of successful kickstarter campaigns are more than the failed and cancelled ones.
Also the successful campaigns reached high in the month of may-june.

•	Conclusion based on goal:
We can conclude saying that when the more the goal amounts less are the failed projects.

•	Limitation of the dataset:
            Potential limitations of this dataset relate to lack of data about the   exposure and impressions of the projects: having metrics about clickthrough rate, overall impressions that can be mapped against the total backers provided, etc., which are all valuable pieces of data, are missing here and can provide deeper analysis about what contributes to the most successful campaigns on Kickstarter.

 The other tables and graph that we can create using the same data:
 
Photography outcome based on the launching date.

https://1drv.ms/x/s!AlKtrx-dsEKQgQVJr99hEHHPhHyr?e=DpYgIp

![photography outcome based on launch date](https://user-images.githubusercontent.com/99555513/155054424-bcb6d652-8fac-4e60-a3c5-71acd19ccb5f.png)




