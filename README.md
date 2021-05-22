# IPL-T20-Cricket-Analysis
---

The **Indian Premier League (IPL)** is a professional Twenty20 cricket league, contested by eight teams based out of eight different Indian cities. In this IPL analysis EDA Project, we have six datasets i.e. players, matches, deliveries, most_runs_avg_strikerate, teams and teamwise_home_and_away. 

Before moving to our analysis, we first cleaned the data by removing trash data and filling in the missing data. Further, we divided the complete project into three main parts i.e Match-wise Team analysis, Season-wise Team analysis, and Entire IPL analysis.

In **Match Wise Team Analysis** we focused mainly on the scorecards, match results and teams' performance in a particular match against each other and some more aspects concerning each team only.

In **Season-wise Team Analysis** we compared performances of various teams in a season through points table, the number of matches won, etc, found out top 10 batsmen and bowlers of the season and some more.

In the **Entire IPL Analysis**, we will look at the penetration of players from different countries in the IPL, consistent performers, total runs, strike rate, average runs of batsmen in the entire IPL, etc.

---
### **Datasets:**
 * Players Dataset
 * Deliveries Dataset
 * Matches Dataset
 * Most Runs, Average, and Strike Rate Dataset
 * Teams Dataset
 * Teamwise Home and Away Dataset

To analyse these datasets we divided the whole project into three parts:
### 1. Match Wise Team Analysis
### 2. Season Wise Team Analysis
### 3. Entire IPL Analysis

---
## 1. Match Wise Team Analysis

For the first part of analysis, We are looking at how teams are performing against each other, and for that we need scorecare of a match.
 
Here, we are going to define a <u>*scorecard*</u> function, to which if you give a *match_number*, it will return you the scorecard of both the innings.
 
Now, you may ask, if the match ties, then there would be super over innings as well i.e. third and fourth innings?
 
For that, we merged the third and fourth innings scores with the first and the second innings scores respectively. Why did we do that? Actually, we are not interested if the match ties or if a decision comes out after the second inning. We are more interested in the winner and the difference by which a team won the match, which shows the team's strength.

To make things a bit more interactive we added a slider, you just need to select a match number from slider and you will get the complete analysis of both inning of that match.

![image](https://user-images.githubusercontent.com/35359451/118688125-64d55200-b823-11eb-975c-570110ca3a01.png)

And the scorecard we get look like the below figure:
<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/35359451/118688293-8df5e280-b823-11eb-8268-823627ddddeb.png">
</p>


there is also similar scorecard for second inning

From this scorecard, we created different graphs like barplot for batting and bowling statistics, piechart for contribution of players, etc. to compare the performance of each player with others in that particular match.

---
## 2. Season Wise Team Analysis

Now we focused on analysis by season, i.e. we are analysing teams and thier performance on a particular season that you select, and to help you in selecting the season and to make it interactive we added a dropdown menu this time.

![image](https://user-images.githubusercontent.com/35359451/118693928-280c5980-b829-11eb-98ec-25ffc60d8ec5.png)
 
Once decided which season needs to be analysed, we present you a points table, which looks like below figure

<p align="center">
  <img src="https://user-images.githubusercontent.com/35359451/118694307-9224fe80-b829-11eb-89fa-25ab01006ce8.png">
</p>

From this points table we created graphs for batsman performance, bowler performance, teams performance on different ground and also visualized the above points table on the map of India.

---
## 3. Entire IPL Analysis​

We are now looking into the bigger picture, we are taking all the matches played till 2019 in IPL and created different graphs to show varius outcomes like contribution of player from different countries, Batsman ranking over, teams performance on different ground, etc.

We also used our mathematical brain and calculated and visualized different probabilities like winning probability, probability of winning on a ground when bat first/field first and match result analysis for different inning on a particular stadium.

---
# **Conclusion**

**Match-wise team analysis** results demonstrate the inning statistics of players and teams in each match, by employing combinations of various statistical techniques. Through this we formed out a conclusion over the runs made by each team per over, compared teams run rate.

**Season-wise team analysis** draws an idea regarding the various batsmen and bowlers' performance in a particular season. Here we provided a comparison of the matches won or lost by teams on the ground in a season. We found out the purple cap and orange cap winner and their leading competitors in a particular season. This helped in identifying the leaderboard position of teams through which we plotted a heat map that showed us the top team for the season.

**Entire IPL analysis** includes details regarding consistent performers in the IPL, best batsman based on their total runs, average runs, and strike rate. We also analyzed the team’s performance in their home and away grounds and we have also analyzed the most favorable ground for each team.

Through probability density, we have identified the winning probability on a ground which could help a team to decide whether to bat first or field first provided they won the toss. Through the score density graph, we have estimated the minimum and maximum targets. Through match result analysis, we can estimate the winning and losing chances in a match, and the boxplot signifies the minimum, maximum average, and exceptional(outliers) score at a ground. We have also compared the team's performances with itself on a particular ground.



## ***Talent wins games, but teamwork and intelligence wins championships***

Here is a glimpse of few graphs we plotted, there are many more in the notebook please have a look.
![image](https://user-images.githubusercontent.com/35359451/118698126-abc84500-b82d-11eb-9d40-271de5af17cf.png)| ![newplot](https://user-images.githubusercontent.com/61584385/118861787-881f0080-b8fa-11eb-8f63-86644ee2301d.png)|![image](https://user-images.githubusercontent.com/35359451/118698288-d914f300-b82d-11eb-99fc-4839972fe455.png)|
:-------------------------:|:-------------------------:|:-------------------------:
![image](https://user-images.githubusercontent.com/35359451/118698358-ec27c300-b82d-11eb-9a3f-143f6fdc163c.png) |![image](https://user-images.githubusercontent.com/35359451/118698498-18dbda80-b82e-11eb-8efd-4a8389b72035.png)| ![image](https://user-images.githubusercontent.com/35359451/118698569-31e48b80-b82e-11eb-994d-fc7c163423c0.png)|
![image](https://user-images.githubusercontent.com/35359451/118698654-4f195a00-b82e-11eb-9aec-bda201918a09.png)|![image](https://user-images.githubusercontent.com/35359451/118698704-5b9db280-b82e-11eb-8249-97d56139586d.png)| ![image](https://user-images.githubusercontent.com/35359451/118700561-7113dc00-b830-11eb-8b1c-61ce09f2ec1b.png) |
 ![image](https://user-images.githubusercontent.com/35359451/118698807-76702700-b82e-11eb-9cc1-3b3a67515d94.png) |![image](https://user-images.githubusercontent.com/35359451/118701856-d0beb700-b831-11eb-8606-1a38b65adaf5.png)|![image](https://user-images.githubusercontent.com/35359451/118698912-943d8c00-b82e-11eb-8f19-3ca49b23e5b2.png)|


---
---

Project Made By:

> Bhwesh Gaur: https://github.com/bhweshgaur

> S Sravya Sri : https://github.com/SSravyaSri

> Ankit Bansal : https://github.com/ankit986
