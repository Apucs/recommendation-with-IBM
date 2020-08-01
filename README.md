# Recommendations with IBM
## Introduction  
> For this project I have analyzed the interactions that users have with articles on the IBM Watson Studio platform,
and made recommendations to them about new articles thatv I thought they would like.  

Here is an example of what the dashboard could look like displaying articles on the IBM Watson Platform.  
<p align="center">
  <img src="./ibm.png" width=50% height=50% />
</p>

## Get the repository:  
`git clone https://github.com/Apucs/recommendation-with-IBM.git`  

## Project details:  

1. Exploratory Data Analysis:  

Before making recommendations of any kind, I have explored the data you was working with for the project.
Some basic, required questions were answered about the data that I have will be working with throughout the 
rest of the notebook. 

2. Rank Based Recommendations:  

To get started in building recommendations, firstly, I found the most popular articles simply based on the most interactions. 
Since there were no ratings for any of the articles, it was easy to assume the articles with the most interactions were the 
most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

3. User-User Based Collaborative Filtering: 

In order to build better recommendations for the users of IBM's platform, I have looked at users that are similar in terms of 
the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the 
right direction towards more personal recommendations for the users. I have implemented this in this part.  

4. Matrix Factorization:  

Finally, you completed a machine learning approach to building recommendations. Using the user-item interactions, I built out a matrix 
decomposition. Using that decomposition, I got an idea of how well I can predict new articles an individual might interact with. 



LICENSE: This project is licensed under the terms of the MIT license.
