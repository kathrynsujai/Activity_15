#Plan

#Goals:
#Goal 1: Create a QMD File that contains plots from Army Data, DcNames, and the Box function.
1.a) Create plot for Army Data
1.b) Create plot for DcData
1.c) Create plot for Box Plot
1.d) What I've Learned section
1.e) Code Appendix
#Goal 2: Create a Repository on Github that will contain all the files in the project.

#Needs:
Goal 1a) Armed Forces Active Duty Data from "https://docs.google.com/spreadsheets/d/19xQnI1cBh6Jkw7eP8YQuuicMlVDF7Gr-nXCb5qbwb_E/edit?gid=597536282#gid=597536282", 
Pay Garde and Rank from "https://neilhatfield.github.io/Stat184_PayGradeRanks.html"
Goal 1b) DcData
Goal 2) GitHub

#Steps:
Goal 1.a:
1) Load Packages. Needed Packages:({tidyverse}, {rvest}, {googlesheets4})
2) Load Data (Armed Forces Active Duty Data, Pay Garde and Rank)
3) Extract data and wrangle any necessary tables to get needed data. 
4) Make group case data frame from Armed Forces Active Duty Data
4.a) Rename column names for better readability, filter out unnesessary data, and combine data into four columns: pay grade, branchm gender, and total soldiers.
4.b) select table with needed information from Army Rank data website
4.c) rename column names for better readability, filter out unnesessary data, and combine data.
5) Join the two cleaned data sets togther 
6) Make single case data frame. Duplicate group data to fit each count of soliders
7) Turn Individual Data into Frequency Table
7.a) filter army officer from the individual dataframe 
7.b)create a table
8) Write a paragraph explaining the the table and the connection between gender and position. 

Goal 1.b:
1) Select four popular names and create a new dataframe
2) use new data frame to create a plot of the trend of names
2.a) Use ggplot to create a plot
3) Write a paragraph explaining the graph and its features including what it could mean and why the names were choosen. 

Goal 1.c:
1) create a function that finds the max volume of the paper box
2) use function to create a plot of the function
3) Write an explanation about the relationship portrayed in the graph. 

Goal 1.d:
1) Create a subsection that explains eveyrthing learned in this class

Goal 1.e:
1) Create a code appendix showcasing all the code using the codeAppend function
and echo = True to show the code at the end. 

Goal 2:
1) Create a new repository on GitHub and link it to R.
2) Follow the steps to create a qmd file that will hold all the needed data.
3) Push and commit all changes into the repo.
4) Make sure there are no issues within the file and that all needed elements are in the repo. 

