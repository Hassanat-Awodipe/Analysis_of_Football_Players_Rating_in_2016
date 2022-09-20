# Analysis_of_Football_Players_Rating_in_2016

## Introduction
> Working with a database of European Soccer collected over a period of 9 years (2007 - 2016), the data was analysed to find out how **players attributes affect their overall and potential ratings for the year 2016**. To achieve this, I asked 6 questions that examined how the independent variables interacted with each other and with the dependent variable. 

### Dataset Description
>The database contained several tables like the countries involved, the football leagues the countries participated in, the players, their teams, etc. 
>
>To analyse the data based on the posed questions, I focused on two tables which were the Player.csv and Player_Attributes.csv. These tables were related through columns with the **api_id** suffix which was a foreign key in all tables of the database
>
>The Player.csv contained details of the players such as id, player_api_id, name of the player, fifa_api_id, date of birth, height and weight
>
>The Players' attributes were stored in the Player_Attribute.csv. It also contained the overall and potential ratings for the players. The overall rating is the actual rating of the player based on the attributes while the potential rating is the least expected rating for the player. Note that there were multiple ratings for the same player depending on the date the assessment was carried out.
>
>Another important column in the Player_Attribute.csv that I worked with was the preferred foot of the player. According to the [dataset description](https://sofifa.com/players), the soccer attributes of the players (crossing, finishing, heading_accuracy, short_passing, volleys, dribbling, curve, free_kick_accuracy, long_passing, ball_control, acceleration, sprint_speed, agility, reactions, balance, shot_power, jumping, stamina, strength, long_shots,aggression, interceptions, positioning, vision, penalties, marking, standing_tackle, sliding_tackle, gk_diving, gk_handling, gk_kicking, gk_positioning, gk_reflexes) can be summarised into 5 major groups: Attacking, Skill, Mentality, Movement, Power, Defending, GoalKeeping. These groups were defined in the analysis. Additionally, I created new columns to answer the analysis questions.


### Question(s) for Analysis
>The following questions were posed:
>
>1. What is the effect of prefferred foot on long shots?
>
>2. What relationship exists between age of the football players and the overall rating? 
>
>3. Find the mean overall rating. Make a comparison of players with attributes above the mean and players below the mean.
>
>4. Is there a relationship between the players' BMI and overall_rating? 
>
>5. Compare the trend for players general overall rating and potential in 2016. 
>
>6. Who are the top 10 players for the year 2016?

## Approach
> Firstly, I checked if playing with the left or right foot increased the player's shots and by extension, the overall rating of the player. Secondly, I considered the age of the player to determine if younger or older players had a high rating. Then I checked the attributes of the players such as agility, sprint speed, ball_control etc. and how each of them affected the rating score. At this point, I also checked the BMI of each player since it is considered that the weight of a person plays an important role in their well-being. Moving away from the players' attributes, I examined the general trend of potential and overall ratings for the players from the beginning of 2016. Here, I also identified how well players met up to their potential. Finally, I made a subset of the top 10 players for the year and verified if their attributes fitted into the insights gathered from the preceeeding questions.  
>

