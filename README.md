# Status
This project is currently within the data collection stages and therefore does not have a final visualization or recommendations. However, I encourage anyone interested in gaining insight into my approach to new projects to review the outline I’ve set up for the library initiative. It offers a clear view of my planning process, showcasing how I develop and structure ideas before diving into execution. 

# Table of Contents
1. [Defining the Problem](https://github.com/Mchapa817/Animal_Shelter_Analysis_and_Visualization#defining-the-problem)

2. [Data Collection](https://github.com/Mchapa817/Library_Funding_Analysis_and_Visualization#data-collection)
   
3. [Data Cleaning](https://github.com/Mchapa817/Library_Funding_Analysis_and_Visualization#data-cleaning)

4. [Data Analysis](https://github.com/Mchapa817/Library_Funding_Analysis_and_Visualization#data-analysis)
   
6. [Visualization and Final Recommendations](https://github.com/Mchapa817/Library_Funding_Analysis_and_Visualization#visualization-and-final-recommendations)
   
8. [References](https://github.com/Mchapa817/Library_Funding_Analysis_and_Visualization#references)

# Defining the Problem
On March 14, 2025, the Trump administration announced plans to defund the Institute of Museum and Library Services (IMLS) as a portion of the overall goal of reducing unnecessary bureaucracy. 

As an avid library patron, my goal is to examine to what extent current public library systems rely on federal grants. I am hoping to discover what changes in staffing, programs, and collections trends could be expected if grants were cut. 

# Data Collection
Sourcing the data for this project involved looking for publically available finance data. Some key sources such as the Institue of Museum and Library Science post a yearly budget. One challenge with their data is that the last available year posted is 2023. This means that when analyzing trends up to 2025 I am forced to use a regression based on previous years data. 

Another source was the Fort Vancouver Regional Libraries (FVRL). This is the controlling organization that oversees my local branch. I was able to find the 2025 data from their website but the challenge with them is that the data is presented in PDF format and that will need to be updated to either CSV/XLS.

Once all applicable data has been collected, the plan is to update all the documents to a local MySQL server for cleaning purposes.

# Data Cleaning
For this project, the first actionalble steps would be to use Python libraries to convert the PDF of the FVRL 2025 Budget into a usable XLS table on MySQL. A lot of the cleaning steps will be involve SQL queries to get the data in the format that is most usable for me.  

The second step would be to read the documentation for the IMLS tables and see which portions relate to the federal grants I want to keep vs drop. 

# Data Analysis
The bulk of this project will be using the Group By tool within SQL to get totals and averages within applicable rows. If possible, I want to conduct research into which programs are funded entirely or majorly by federal grants. 

# Visualization and Final Recommendations
Final visualizations would be 3-tiered. I want an overview of the national stats in the top row total dollars in grants, percentage of the federal budget, and total people affected. Next row will have state stats such as the total grants for Washington state. Final row would be a comparison of my local branch and a more rural branch within Washington State. 

# References 
Coote, D. (2025, April 7). Trump administration sued over dismantling of Institute of Museum and Library Services. Yahoo! News. https://www.yahoo.com/news/trump-administration-sued-over-dismantling-034852039.html?guccounter=1&guce_referrer=aHR0cHM6Ly9kdWNrZHVja2dvLmNvbS8&guce_referrer_sig=AQAAACHAYxYTjcl8xv559NaToTDIVmWDR85NGgEfO7TDjWq3hI3AZ0wr4-_zLjGbHY7Fl-7nlV5JTI6xUXDCZA3aoDiD2hZc1L-RL2QyhOsfJLEOBcqTmG7VzTldLpy-Q2NZMKWZZX9dCT1ZWbebHYc1F7QyzSRfonzBqdgN-ioRVNVR 

FVRLibraries. (n.d.). Budget 2025. Finances. https://www.fvrl.org/financial-documentation 

Trump, D. (2025, March 15). Continuing the reduction of the federal bureaucracy. The White House. https://www.whitehouse.gov/presidential-actions/2025/03/continuing-the-reduction-of-the-federal-bureaucracy/

Public libraries survey (PLS). Institute of Museum and Library Services. (n.d.). https://www.imls.gov/research-evaluation/surveys/public-libraries-survey-pls
