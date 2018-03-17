

Vibhor:

I worked on cleaning and aggregating data that would make things easy for the other team members to directly pull off the info from csv and visualize it, without having to clean/aggregate data individually. Also I worked on visualization Two (Multiple Stacked Bar chart) to visualize the distribution of different ethnic groups across different universities in US. I chose this data because this seemed interesting, to see and compare side by side the trend for population of different ethnic groups since 2003 for both Male and Females. 

Design Process: 

To start with, I took help of Tableau to visualize data and used SQL server to clean up and aggregate data. As tableau doesn’t support multiple stacked bar chart (multiple bars for each x-axis value), we had to resort to something else (d3 here) to customize it as per our requirement. As a way of interaction, I enabled the tooltip over the bars that would show the category (Male/Female), the ethnicity and the count, when one hovers mouse over any bar in the chart. Also, I worked on maintaining consistency across different charts made by all of us , in terms of use of axis labels, use of specific font size, style, color etc. 

Vipra:
I worked on making the third Data Visualization. I started off cleaning the data more. I was using the queryResults.csv dataset. It still had some nulls and repeated data for same institute ID. I aggregated that data so that we have unique Institute IDs. Then I made a scatterplot with the Institute ID vs the number of students graduated from that institute. 
I then extended it to create two separate ones, one for female and other for male.

Vilok:
I was mainly in charge of taking the three different visulas and combining them into one document (webpage). I created the whole navigation between different visuals and different webpages making it easy to move around our webpage. I was also in charge of doing some of the formatting and overall just making the webpage look a little cleaner. Finally, I combined all the documents and uploaded the necessary files to the GitHub along with Hemang!  

Design: I wanted to make everything look consistent. This meant changing the fonts and colors of the visuals and webpage to have everything look similar to one another. 

Ali:

I created the visual 1 and worked along with Vibhor in cleaning the data file so we can create interactive visualizations. Whereas I also worked with Vibhor in making the coordinated views in the visual 1.

Visual 1:

This visualization shows the SAT average scores between the Females and Males students that were admitted over the years. To make it interactive, if you hover your mouse on any data point then it will also show the SAT average from the other visualization as a comparison. This helps in doing year by year analysis and also provides a complete image of the data to facilitate the discussion about process.
 
Design process:
 
I created the visualization first using the Tableau to get an idea about which is the most suitable visualization that I can make out of this data. Selecting the data columns that make some sense was a little challenging because data file was not clean. So, we cleaned the data file and then average sat score comparison clicked me instantly because it can provide stakeholders with some insights over the past years. I selected scatter plot because it is one of the most widely used visualizations and even the naïve user can make sense out of it. By incorporating the interactivity, it became even more effective in communicating its meaning.


Hemang: 

Along with Vlok, I worked on the above and beyond part of the project. The task i took in that was to introduce dynamic queries to the visualization. Finally, I combined all the documents and uploaded the necessary files to the GitHub along with Vlok.
Dynamic Queries: Including UI widgets that allow you to change the current data field
After the visualizations were made , I identified the data that changes the visualization dynamically based on the user’s selection. 
In Visualization 1 , the user can choose between the Male, Female or both together to visualize average SAT scores. 
In visualization 2 the user can dynamically change the data that is the department that user wants to visualize from. There are 2 options, Computer Science department and all the other departments combined.
In visualization 3 the user can choose between male graduates and female graduates in different institutions. And also view them together to compare the male and female graduates of same institution id together.

DESIGN: To give the dynamic factor to these visualizations i introduced a dropdown menu from which a user can choose the visualization it wants to see. It has been done using d3 and select and passing options to it.


Team Roles:

Vibhor , Vipra and Ali (Each person worked on creating an interactive and meaningful visualization from the data)

Vilok and Hemang: (Both of them worked on the Above and Beyond part)


Running the project:

You can run the project by cloning/downloading the repository and using the index.html file as the main file. This file contain all the three interactive visualizations.

Features completed in above and beyond part:

Dashboarding: Navigation creating to move between all the three visualizations

Dynamic queries: Incorporated this part for three visualizations where you can change the data column dynamically and view the change in the visualization.

Missing data: Used SQL server to clean up and aggregate data

Coordinated views: In visual 1, both the visualizations can interact with each other. You can view the comparison between the Female and Male Sat scores across the years at the same time.

Overview and detail: Each visualization has interactivity that provide detail about the data and comparison across different views to get the maximum detail out of data.  

Style: We have kept style of all the visualization consistent so that viewer can easily make sense out of data and stay in the same context. 

Please run the project in full screen to see all the effects. Thanks.
