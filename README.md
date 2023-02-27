# Project description

The data set I have worked on in this project is a free data set from kaggler.com, it consists of 128,975 orders on Amazon India these orders were placed in the year 2022, and these orders are in the clothing sector.

## The main opjective of the project
<br> **determine what are the factors that affects the clothing category.**

## Main questions 
<br> **Who is the biggest supplier for each clothing category?**
<br> **What is the market size in each clothing category?**
<br> **How clothing category is affected by location?** 

## Steps taken

### Cleaning the data set
<br> There were a lot of missing values but I couldn't just delete these rows or it will negatively affect the analysis, so I replaced them with the average value.
<br> I had to edit the values in the "states" columns and in the "shipping status" column, for more information take a look at the notebook provided.

### Answering the questions
<br> after cleaning the data set I started my analysis by classifing the clothing types in the data set into three main categories ("Traditionla indian", "Sets" and "others").
<br> Then I made my analysis based on these threee main categories
<br> When I tried to find out how clothing type is affected by states, I faced a problem, there are 36 Indian states and this number was a lot to contain in my graphs, so I searched and found out that India consists of seven regions, so I classified the states into these seven regions and continued my analysis.
