# Urban League Capstone Project

## Project Overview

The goal of this project is to track and utilize voter turnout data to assist efforts in increasing voter turnout in upcoming elections based both at the local and national level, specifically in low propensity areas. The client is focused on communities of color and precincts with lower turnout. 

Our hope is that the social pressure information will show a discernible increase in those locations.

During Spring 2025, we focused our project on the city of Chelsea, Massachusetts. We:
combined census-tract-level data (Census, American Community Survey) with precinct-level data (in person, early, and absentee voting data for Chelsea, MA 2013~2023)
created a dashboard containing this data, filterable by precinct and election date

The folder ‘2025’ contains work from Spring 2025, including EDA notebooks and data.

Next tasks for future student teams include:
add missing data to our final dataset, which contains only 76% of voter data we had access to (the remaining 24% were missing DOB and date of registration).
identify precincts that would benefit most from campaigning.
focus on another city in Eastern MA (e.g. Malden, Framingham).

### Team:

List each team member, along with each individual at the client that will be participating.

| Name | Role | Email Address |
| ----------- | ----------- | ----------- |
| Tanvi Chennuru | Student | tanvic@bu.edu |
| Aidan Thorp | Student |azthorp@bu.edu |
| Taiyo Nakai | Student | tnakai@bu.edu |
| Cole Whittington | Student | crwhitt@bu.edu |
| Rahsaan Hall | Client | rhall@ulem.org |

### User Stories:

As the President of the Urban League of Eastern Massachusetts, I would like to identify low-propensity voters in Malden, Chelsea, and Framingham to assist in increasing voter turnout in upcoming elections.

As the President of the Urban League of Eastern Massachusetts, I would like to build off of previous project work focused on Brockton, MA and apply similar methods to other precincts of cities in Eastern MA with majority non-white or low income voters so that we can drive equitable policy changes, improve community resources, and enhance civic engagement in historically underserved areas. 

As the President of the Urban League of Eastern Massachusetts, I want to identify precincts with the lowest voter turnout so that we can focus our outreach and intervention efforts in the areas that need them the most.

As the President of Urban League, I would like to analyze the previous municipal elections data from the last 5 years to establish a threshold for participation increase.


### Solution:

We created a dashboard using Tableau. This included graphs and plots representing voter turnout for the past 10 years based on voter information and demographics, as well as an interactive map for income/voting behavior.

### Tools:

1. Tableau
2. BigQuery
3. Python
4. Notion

### Data Sources:

1. US Census Bureau 
2. Chelsea Public Voting Records

### Data Preparation:

1  Translating demographic data from the census-tract level to precinct level. This was a crucial part of our project, but also means that our demographic numbers for each precinct are estimates.
2. We temporarily removed 24% of our data due to missing values (date of birth and date of registration of individuals). We were later provided with the remaining data, but it is not yet included in our final dataset.

### Final Deliverable:

https://public.tableau.com/app/profile/taiyo.nakai/viz/ChelseaDashboard2_17467631311760/CityofChelsea#1
Red is the main hue in our dashboard, and is based on that used by our client, the Urban League of Eastern Massachusetts. Vertical labels either were intentionally omitted (e.g. vertical labels along the y-axis of graphs) or rotated to be horizontal (e.g. year labels along the x-axis of graphs).

### User Guide
The first page has a map of the city of Chelsea split up by precinct. You can go through each year right above the map which will filter through various elections. When you click on a precinct you will get information about the ward number, precinct number, average CVAP percentage, and the average number of people who voted. Next to it you get a bar graph of race and ethnicity demographic information as well as voter turnout throughout the years. You can then toggle to “all precincts” where you get specific precinct information such as turnout throughout the years, the race and ethnicity by precinct and median household income by precinct. If you click on a line in the graph it will highlight that information in the table and graph. Lastly, you can go to the analysis page where you will get an analysis by race and ethnicity as well as the voting gap and how it relates to income.  
