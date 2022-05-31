# Analysis_of_Football_Players_Rating_in_2016
<a id='intro'></a>
## Introduction

### Dataset Description 

> Working with a database of European Soccer collected over a period of 9 years (2007 - 2016), the data will be analysed to find out how **players attributes affect the overall and potential ratings of the players for the year 2016**. To achieve this, I have asked 6 questions that examines how the independent variables interact with each other and with the dependent variable. 
>
> Firstly, we get to understand if playing with the left or right increases the player's shots and by extension, the overall rating of the player. Secondly, we will consider the age of the player to determine if younger or older players have a high rating. Then we will check the attributes of the players such as agility, sprint speed, ball_control etc. and how each of them affects the rating score. At this point, we will check The BMI of each player since it is considered that the weight of a person plays an important role in their well-being. Moving away from the players' attributes, we will understand the general trend for potential and overall ratings for the players from the beginning of 2016. Here, we will also identify how well players meet up to their potential. Finally, we will extract the data of the top 10 players for the year and see how their attributes fit into the detials we have gathered from above.  
>
>The database contains several tables like the countries involved, the football leagues the countries participated in, the players, their teams, etc. 
>
>To analyse the data based on the posed questions, we will be focused on two tables which are the Player.csv and Player_Attributes.csv. These tables are related through columns with the **api_id** suffix which is a foreign key in all tables of the database
>
>The Player.csv contains details of the players such as id, player_api_id, name of the player, fifa_api_id, date of birth, height and weight
>
>The Players' attributes are stored in the Player_Attribute.csv. This is where we have the overall and potential ratings for the players. The overall rating is the actual rating of the player based on the attributes while the potential rating is the least expected rating for the player. Note that there are multiple ratings for the same player depending on the date the assessment is carried out.
>
>Another important column in the Player_Attribute.csv that we would be working with include the preferred foot of the player. According to the [dataset description](https://sofifa.com/players), the soccer attributes of the players (crossing finishing, heading_accuracy, short_passing, volleys, dribbling, curve, free_kick_accuracy, long_passing, ball_control, acceleration, sprint_speed, agility, reactions, balance, shot_power, jumping, stamina, strength, long_shots,aggression, interceptions, positioning, vision, penalties, marking, standing_tackle, sliding_tackle, gk_diving, gk_handling, gk_kicking, gk_positioning, gk_reflexes) can be summarised into 5 major groups: Attacking, Skill, Mentality, Movement, Power, Defending, GoalKeeping. These groups will be defined later on. Additionally, we will have to create some columns to answer our questions.


### Question(s) for Analysis
>The following questions are posed:
>
>1. What is the effect of prefferred foot on long shots?
>
>2. What relationship exists between age of the football players and the overall rating? 
>
>3. Find the mean overall rating. Make a comparison for players with attributes above the mean(green) and players below the mean(red).
>
>4. Is there a relationship between the players' BMI and overall_rating? 
>
>5. Compare the trend for players general overall rating and potential in 2016. 
>
>6. Who are the top 10 players for the year?
