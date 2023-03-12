# Social-Buzz

Social Buzz is a repository of the work I have done as part of the Accenture Virtual Internship program, a free self-paced virtual experience for building skills on a real world problem and dataset.

My role in the internship was as a Data Analyst at Accenture, where I was working with a large team with each team member having a different role and level of responsibility. I was assigned a project called as Social Buzz. 

These are the tasks I have worked on in the project:

## 1. Project Understanding
This task was a project brief on:
   - Understanding the client and business problem at hand.
   - Identifying the requirements that need to be delivered for the project.
   - Identifying the tasks to focus on as a Data Analyst.
   
## 2. Data Cleaning & Modelling
This task involved analyzing 7 datasets and creating a data model to merge tables. The data modelling was done in Microsoft Excel using Vlookup function. The following steps were followed to make sure I am using the right data to answer the business question:
   - Requirement Gathering
   * The relevant datasets selected for answering the business question were - Reaction, Content, and Reaction Types. 
   * The clarification for selecting these datasets is:
      - The brief carefully states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
      - As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
      - We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
      - So, to figure out popularity, we’ll have to add up which content categories have the largest score.

   - Data Cleaning
   * The following was performed in Data Cleaning - 
      - removing rows that have values which are missing,
      - changing the data type of some values within a column, and
      - removing columns which are not relevant to this task
   * This data cleaning was done in excel.
   
   - Data Modelling
   * The following steps were performed in Data Modelling - 
      - Created a final data set by merging three tables together. 
      -The reaction table was used as a base table then joining the Content data set and Reaction Types data set using VlookUp formula.

   * Figure out the Top 5 performing categories
      - Added up the total scores for each category. Using the “Sum If” formula.


The end result was a spreadsheet which contains:

- A cleaned dataset
- The top 5 categories

## 3. Data Visualization & Storytelling
After cleaning the dataset and doing analysis, the next step was to communicate the relevant insights in a concise and engaging way for client and team members to understand. This involved bringing the data to life using visualizations to support the story I wanted to tell. I used Microsoft PowerBI for the visualization insights.
