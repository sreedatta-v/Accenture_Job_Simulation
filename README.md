# Introduction 
This is a Job Simulation program hosted by Accenture on Forage platform for newbies who are looking for Certifications or experience in Data analyst roles. 

[Task1]()


## Task 1

### Role:  
-> I will be working as a data analyst at Accenture.  

-> I will work within a larger team, where each member has a different role and level of responsibility.  

-> My team has been assigned a new project for a Social Buzz client.  

### Key roles and responsibilities of a Data Analyst from point of Company ( Accenture ): 


• The Business refers to the client and your internal team members who won’t be involved in detailed data analysis.  

They rely on your analysis to make strategic business decisions.  

Importantly, not everyone will have a strong understanding of data. Your job is to communicate your data findings simply and clearly for everyone to understand.  
 
• The Data refers to the relevant data sources that you will clean, process, and use to generate interesting insights for the business.  

## Goal: 
My first task is to read the brief from Social Buzz and complete a short knowledge check before the call.

### Read the brief to:

1. Understand the client and business problem at hand.
2. Identify the requirements that need to be delivered for this project.
3. Identify which tasks you should focus on as a Data Analyst.

A downloadable brief of Company ( Social Buzz ) is attached below, Which is downloadable ↡  

[Brief about Social Buzz](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf)

Incase if above link is broken, 

```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf
```

### Task : 
1. Audit of big data practice
2. Recommendations for IPO
3. Analysis of popular content

## Data collection & Data Modelling ( Task 2 )

The client has sent through:

<b>7 data sets </b> - each data set contains different columns and values  
<b> A data model - </b> this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.  

There is a lot of information here and it’s easy to get lost in the data. So, to make sure you are using the right data to answer the business questions you’ll follow these steps:

• Requirements gathering   
• Data cleaning    
• Data modelling  

[A sample of data model](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf)

Incase of above link is broken, 
```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf
```

### Definitions of different data types:

<b> String </b> - Sequence of characters, digits, or symbols—always treated as text.  
<b> UUID </b> - Universally Unique Identifiers.  
<b> Array </b> - List with a number of elements in a specific order—typically of the same type.  
<b> Integer </b> - Numeric data type for numbers without fractions.  
<b> Timestamp </b> - Number of seconds that have elapsed since midnight (00:00:00 UTC), 1st January 1970 (Unix time).  

<b> Q1. Which three data sets will you need to complete your analysis? </b>  
Reaction, Content, Reaction Types: Our job is to identify which content categories are most popular. Popularity is determined based on reaction scores.

### Quick Explanation of Data sets

To clarify why we made this selection:

1. The brief carefully it states that the client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.  

2. As explained in the data model, popularity is quantified by the “Score” given to each reaction type.  

3. We therefore need data showing the <b>content ID, category, content type, reaction type, and reaction score.  </b>

4. So, to figure out popularity, we’ll have to add up which content categories have the largest score.

## Data Cleaning

Before performing cleaning operating, I've attached downloadable assets below, simply datasets. 

[Reaction Types](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298399720/ReactionTypes.csv)  
[Reactions](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298375459/Reactions.csv)  
[Content](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298350004/Content.csv)  
 

In case the above link is broken, I'm providing the direct downloadable link below. 
<B> Reaction Type </b>
```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298399720/ReactionTypes.csv
```
<b> Reactions </b> 

```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298375459/Reactions.csv
```

<b> Content </b>
```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664298350004/Content.csv
```

Task : 
Clean the data by:

1. removing rows that have values that are missing,  
2. changing the data type of some values within a column, and  
3. Remove columns that are not relevant to this task.  
   
Think about how each column might be relevant to the business question you’re investigating. If you can’t think of why a column may be useful, it may not be worth including it.  

## Data Modelling  
Now we want to figure out the top 5 categories. To complete your data modelling, follow these steps:  

1. Create a final data set by merging your three tables together  

We recommend using the Reaction table as your base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set.  

Hint: You can use a “VLookUp” formula  
 
2. Figure out the Top 5 performing categories  

Add up the total scores for each category.  

Hint: You can use the “Sum If” formula  

The end result should be one spreadsheet which contains:  

1. A cleaned dataset  
2. The top 5 categories


## Task 3
### Build your presentation Structure

I'm attaching a downloadable [Accenture presentable template](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664567797956/Data%20Analytics%20template%20-%20Task%203_final.pptx)

In case above link is broken, 
```
https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664567797956/Data%20Analytics%20template%20-%20Task%203_final.pptx
```

### Presentation details:   
<b>Agenda</b> - What will your presentation cover?  
<b>Project Recap</b> - What are the key points from the brief?  
<b>Problem</b> - What is the problem that you answer in this presentation?  
<b>The Analytics team</b> - Who is on your team?  
<b>As a reminder from the earlier task</b> - this includes: Andrew Fleming (Chief Technical Architect), Marcus Rompton (Senior Principle), and yourself!  
<b>Process</b> - How did you complete your analysis?  

