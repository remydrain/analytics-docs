---
tags: project, meritamerica, forage
---
## Brief
You're performing data analysis for Social Buzz of their content categories that highlights the top 5 categories with the largest aggregate popularity.

## Data sets
We've identified Reaction, Content, and Reaction Types as our relevant data sets because:
- The brief carefully states that the client wanted to see "An analysis of their content categories showing the top 5 categories with teh largest popularity."
- As explained in the data model, popularity is quantified by the "Score" given to each reaction type.
- We therefore need data showing teh content ID, category, content type, reaction type, and reaction score
- So, to figure out popularity, we'll have to add up which content categories have the largest score.

## Data Cleaning
We'll need to clean the data by:
- removing rows that have missing values
- changing the data type of some values within a column
- removing columns which are not relevant to this task
	- Think about how each column might be relevant to the business question you're investigating. If you can't think of why a column may be useful, it may not be worth including it.

## Build your presentation Structure
Before you start creating data charts, you should plan your presentation structure. This will ensure your presentation answers the right questions.

For each slide in the template, think about:
- Agenda - What will your presentation cover?
- Project Recap - What are the key points from the brief?
- Problem - What is the problem that you answer in this presentation?
- The Analytics team - Who is on your team?
	- Use the Internal stakeholder chart
- Process - How did you complete your analysis?