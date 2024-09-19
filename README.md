# Video Game Sales
###### This project was completed as a requirement for the Data Analytics Program by CareerFoundry

## Project Overview

#### GameCo, a fictional video game company, aims to leverage data insights to guide the development of new games. To support this initiative, you have been tasked with conducting a descriptive analysis of a video game sales dataset. The goal is to gain a deeper understanding of market performance trends and provide actionable insights for future game releases. Additionally, you have been asked to design an interactive dashboard that visualizes sales trends across various categories to aid in strategic decision-making.

## Key Questions
#### GameCo executives are open to hearing any insights you can pull from the data but are specifically interested in these questions:
##### ● Are certain types of games more popular than others?
##### ● What other publishers will likely be the main competitors in certain markets?
##### ● Have any games decreased or increased in popularity over time?
##### ● How have their sales figures varied between geographic regions over time?

## Context

#### As a professional data analyst, it’s essential that you’re able to understand a problem, map it onto a type of analysis, use data to confirm a hypothesis, and communicate any insights back to the client. Producing an end-to-end analysis will allow you to present the work you’ve done while displaying your hands-on technical skills.
#### Most analyses these days are done using computer software, which is exactly what you’ll focus on throughout this course, developing the behind-the-scenes technical skills that form the core of any good analysis. While your project will involve data from a specific domain, the individual Tasks could be applied to any domain and will highlight your aptitude as a problem solver for a variety of clients.
#### The goal here is for the individual Tasks to help you work incrementally towards your final analysis. As well as helping break your final project into more manageable chunks, the Exercises are designed to introduce you to the ins and outs of the data analyst’s workflow.
#### The target audience/key stakeholders are GameCo's executives, including the following:
##### ● Vice President of Marketing
##### ● Chief Financial Officer
##### ● Senior Vice President of Sales

## Data

#### This data was drawn from the website VGChartz.

#### Important points regarding the data set:
##### ● It tracks the total number of units of games sold (not financial figures) from 1980 to 2016.
##### ● The numbers represent units sold in millions. When you see the number “1.2,” for instance, this represents a total of 1.2 million units sold.
#### Download the video game sales data set: https://images.careerfoundry.com/public/courses/intro-to-data/E1/vgsales.xlsx
##### To get a better sense of the approach used to gather and correlate this data, take a look at VGChartz’s methodology: http://vgchartz.com/methodology.php


## Tools and Skills
#### Tools: Microsoft Excel
#### Skills: Data Cleaning, Grouping and Summarizing Data, Descriptive Analysis, Developing Insights, Data Visualizations, Storytelling/Presenting Data

## Final Dashboard
#### To view the dashboard (and further details for the analysis), download the “vg_sales.xlsx” file. The dashboard includes the following charts: Total video game sales by region; proportion of sales by region; top selling 10 publishers; top selling genres; and top 10 selling games. The dashboard can be adjusted according to time frame and video game genre, using the slicer.

![dashboard](Project_Folder/images/dashboard.png)


## Steps to Analysis

##### Step 1. Initial Exploration (Yellow Tab on Excel Worksheet)
##### Step 2. Data Cleaning (Orange Tabs)
##### Step 3. Descriptive Analysis (Blue Tabs)
##### Step 4. Create Visualizations for Dashboard (Blue Tabs)
##### Step 5. Create Dashboard (Green Tabs)
##### Step 6. Record Insights and Provide Recommendations (Green Tabs)


## Key Insights & Trends

#### Use this legend for all of the following visualizations. All sales are measured in the total number of units sold (not by currency).

![Legend](Project_Folder/images/legend.png)


#### 1) There was a steady rise in global sales of hardware games (in all regions) from 1980-2008/2009, before a steep decline from 2010-2016

##### Sales data during the period of a steep decline may be misleading due to a shift to digital gaming

#### 2) North America has been the most dominant market since the early 1990s

##### Europe took over as the 2nd leading market a few years after and its sales continued to rise until the global decline
##### Japan's sales have remained stagnant between the 1990s-2000s (before a brief rise between 2004-2006)

![Sales Over Time](Project_Folder/images/global_sales_over_time.png)

#### 3) The top 3 most popular game genres globally were Action, Sports and Platform
##### In Japan, Role-Playing was the most popular genre
##### Racing and Shooter games were also particularly popular in North America and Europe

![Sales by Genre](Project_Folder/images/sales_by_genre.png)

#### 4) The top 3 selling publishers were Nintendo, Electronic Arts and Sony Computer Entertainment
##### Nintendo was the most popular in all three major regions
##### Electronic Arts was not popular at all in Japan
##### Activision was also popular in North America (3rd most popular in this region, and 4th most popular globally)

![Sales by Publisher](Project_Folder/images/sales_by_publisher.png)

#### 5) Insights for Action games - the top selling genre:

##### Nintendo (the most popular publisher) was not in the top 10 publishers of Action games.
##### The top 5 publishers of Action games were Take-Two Interactive, Activision, EA, THQ, and Ubisoft. These publishers sold more action games in the "other regions" category than in Japan.
##### Capcom was by far the best selling publisher for Action games in Japan (and 6th overall)

![Action](Project_Folder/images/publisher_action_games.png)

###### * Action Games Only

#### 6) Insights for Sports games - the second top selling genre:

##### Electronic Arts sold the most sports games, followed by Nintendo, Konami and Activision
##### Electronic Arts sold very well in North America, Europe and Other Regions but not at all in japan
##### Nintendo sports games sold well in all regions 
##### Konami sold better in Japan, Europe and other regions than in North America
##### Activision was the second third best selling publisher of sports games in North America

![Sports](Project_Folder/images/publisher_sports_games.png)

*Sports Games Only

## Recommendations

#### The following recommendations are a result of my descriptive analysis of global video games sales between 1980-2016. 

#### 1) Further Research: Discover when/if the data for games sold became less reliable

##### The decline in sales after 2010 seems rather unrealistic, and may likely be more indicative of a shift to digital gaming
##### Japan's earlier "stagnation" may also require further research; did they shift to digital gaming earlier?
##### Key insights may be missed or overlooked if the post-2010 data is misleading

#### 2) Further Research: Will the same genres and publishers see similar levels of success and presence in the digital gaming world?

##### Do certain games/genres appeal better/worse to audiences on a digital/mobile platform?

#### 3) North American Marketing Strategy

##### Market games by the top 3 globally selling publishers (Nintendo, EA and Sony) as well as Activision, which is especially popular in North America
##### Focus marketing strategy on Action, Sports, Shooter, Racing, Role-Playing and Platform games.

#### 4) European Marketing Strategy

##### Market games by the top 3 globally selling publishers (Nintendo, EA and Sony) and Activision. 
##### Focus marketing strategy on Action, Sports, Shooter, Racing, Role-Playing and Platform games.

#### 5) Japanese Marketing Strategy 

##### Focus marketing strategy mainly on Role-Playing games, followed by the top 3 globally selling genres. 

#### 6) Further Research: More research needed on which genres each publisher excels in (or if certain publishers are "jack of all genres")

##### For example, Nintendo dominates the Role-Playing games; Take-Two dominates Action games; EA dominates sports games (but not at all in Japan)

