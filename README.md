Team ID : T04  

Team Name : Data Crew


# **Purpose of the Project**:

•	To predict the tournament's winner based on historical and current data.

•	To analyse various cricket-related data, including team performance, player statistics.


# **Tools/Libraries required**:

•	Google Colab

•	VS code

•	Beautifulsoup

•	Pickle

•	FastAPI

•	Basic python libraries like Tensorflow, sklearn, numpy, pandas

# **Data**:

We created three files:
1.	ICC Rankings: We scraped the ICC rankings of teams participating in world cup from Espncricinfo
2.	Fixtures: We scarped the entire schedule of ICC world cup from Cricbuzz.
3.	ODI results: We collected the data of ODI matches from 2015 to 2023 using Espncricinfo query page.


# **Task 1**:

We selected two problem statements:
1. Predicting Runs of Batsman 
2. Predicting Wickets of Bowler


•	For both of the above tasks, we scraped the records of different bowlers and batters of current and past world cup.

•	Used Linear Regression and ANN models to predict the runs given Innings, Average, Strike Rate, Hundreds, Fifties, Fours, Sixes of the batsman and wickets given Innings, Overs, Maidens, Economy, 4-wickets, 5-wickets of the bowler. 

•	We have also made API endpoints using FastAPI for predicting wickets and runs based on user input.

# **Task 2 and 3**:

•	After scraping the fixtures and ICC rankings, we first predicted the results of every fixture match. We used MLP Classifier and Random Forest Classifier, to predict match outcomes based on team features. 

•	Based on the result of fixture match, we predicted the finalist teams. We analysed and visualized batter and bowler presence in matches for both teams and determined the players that are most likely to be in playing XI in the finals.

•	And then, we predicted the winner of ICC world cup.


# **Conclusion**:

By using the Random Forest model , we predicted that New Zealand and South Africa will be playing the final. Based on the outcomes of this model, South Africa has higher chances of winning the World Cup.
