# Social-Buzz

Social Buzz is a repository of the work I have done as part of the [Accenture Virtual Internship](https://www.theforage.com/virtual-internships/prototype/hzmoNKtzvAzXsEqx8/data-analytics-virtual-experience?forceFastTrackV2=true) program at Forage, a free self-paced virtual experience for building skills on a real world problem and dataset. 

My role in the internship was as a Data Analyst at Accenture, where I was working with a large team with each team member having a different role and level of responsibility. I was assigned a project called as Social Buzz. 
 
## Client Background
* Social Buzz is a fast-growing social media organization and over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.

* Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain.

* Up until this point, they have not relied on any third-party firms to help them get to where they are. However, one of the main reasons why they are looking to at bringing in external expertise is because, they want to learn data best practices from a large corporation. Due to the nature of their business, they have a massive amount of data so they are keen on understanding how the world’s biggest companies manage the challenges of big data.

## Business Problem
The client has reached a massive scale within recent years and does not have the resources internally to handle its data.

## Tasks

The following tasks were performed by me to address the business problem:
### 1. Project Understanding
This task was a project brief on:
   - Understanding the client and business problem at hand.
   - Identifying the requirements that need to be delivered for the project.
   - Identifying the tasks to focus on as a Data Analyst.
   
### 2. Data Cleaning & Modelling
This task involved analyzing 7 datasets given by the client and creating a data model to merge several tables. I performed data modelling in Microsoft Excel using Vlookup function. The following steps were followed to make sure I was using the right data to answer the business question:
   1) Requirement Gathering
   * The relevant datasets selected for answering the business question were - Reaction, Content, and Reaction Types. 
   * The reason for selecting these datasets is:
      - The client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
      - As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
      - We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
      - So, to figure out popularity, we’ll have to add up which content categories have the largest score.

   2) Data Cleaning
   * The Data Cleaning task was done in Microsoft Excel and the following was performed -
      - removing rows that have values which are missing,
      - changing the data type of some values within a column, and
      - removing columns which are not relevant to this task
   
   
   3) Data Modelling
   * The following steps were performed in Data Modelling - 
      - Created a final data set by merging three tables together. 
      -The reaction table was used as a base table then joining the Content data set and Reaction Types data set using VlookUp formula.

   * Figuring out the Top 5 performing categories
      - Added up the total scores for each category. Using the “Sum If” formula.


The end result was a spreadsheet which contains:

- A cleaned dataset
- The list of top 5 categories

### 3. Data Visualization & Storytelling
After cleaning the dataset and doing analysis, the next step was to communicate the relevant insights in a concise and engaging way for client and team members to understand. This involved bringing the data to life using visualizations to support the story I wanted to tell. I used Microsoft PowerBI for the visualization insights.

## Overall View of Dashboard
![](Social_Buzz_PowerBI.png)
