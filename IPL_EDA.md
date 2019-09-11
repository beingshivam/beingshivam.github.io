## IPL: Exploratory Data Analysis
  
  <img src="images/wp2458583.jpg?raw=true"/>

**Project description:** Data Analytics is all about finding valuable insights that help businesses take right decisions. In this Project, I have done exploratory data analysis using python. The dataset in action is IPL(Indian Premier League) dataset between 2008 and 2016. IPL is world's most famous cricket tournament which is held every year, it is one of the most successful tournament. In this analysis I have tried to explore the data set using different plots.

### 1. About Dataset

The dataset is picked from kaggle. It consist of total 18 columns and 636 rows. The columns are namely:

('id', 'season', 'city', 'date', 'team1', 'team2', 'toss_winner','toss_decision', 'result', 'dl_applied', 'winner', 
'win_by_runs','win_by_wickets', 'player_of_match', 'venue', 'umpire1', 'umpire2','umpire3')

Just to get a rough idea about the dataset below is the variable(cloumn) details:


* Data columns (total 18 columns):

Variables         | Description
------------------|--------------------
id                | 636 non-null int64
season            | 636 non-null int64
city              | 629 non-null object
date              | 636 non-null object
team1             | 636 non-null object
team2             | 636 non-null object
toss_winner       | 636 non-null object
toss_decision     | 636 non-null object
result            | 636 non-null object
dl_applied        | 636 non-null int64
winner            | 633 non-null object
win_by_runs       | 636 non-null int64
win_by_wickets    | 636 non-null int64
player_of_match   | 633 non-null object
venue             | 636 non-null object
umpire1           | 635 non-null object
umpire2           | 635 non-null object
umpire3           | 0 non-null float64

* Data types

datatype| total
--------|------
float64 |  1 
int64   |  5 
object  |  12




### 2. Requirements

*  The jupyter notebook environment that I have used is [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb#).
*  The dataset can be downloaded from [Kaggle](https://www.kaggle.com/manasgarg/ipl/data).
*  The Python packages that I have used are :numpy, pandas, matplotlib, and seaborn.


### 3. Complete code (notebook)

To view the notebook see [GitHub](https://github.com/beingshivam/Python-projects/blob/master/IPL_EDA.ipynb).


### 4. Results

* Number of matches played in IPL:
  <img src="images/number_of_matches1.png?raw=true"/>

* Best IPL team:
  <img src="images/Most_successful_ipl_team.png?raw=true"/>
  
* City with most number of matches:
  <img src="images/city_most_matches.png?raw=true"/>
  
* Venue with most number of matches:
  <img src="images/venue_matches.png?raw=true"/>

* All top 10 players:
  <img src="images/Top_player.png?raw=true"/>

* Are match Winning and Toss Winning Correlated? 
  <img src="images/match_winning_toss_winning.png?raw=true"/>
  
  
### Conclusion

This notebook shows Exploratory Data Analysis of IPL dataset. There is lot more to explore in this dataset when one deep dives as which venue(stadium) had most number of wins, which city has most number of wins etc.

