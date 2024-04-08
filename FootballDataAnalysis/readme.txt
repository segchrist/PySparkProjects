This project consists of analyzing FootBall match data from German divisions:

id: match identifier

div: division

season: the year of the season (a season spans 2 years ==> season=2009 is the 2009-2010 season)

date: date of match.

hometeam: home team.

awayteam: other team.

fthg: goals scored by home team.

ftag: goals scored by other team.

fth: indicates outcome of match. H==> hometeam won; A==> awayteam won; D==> draw

Approximately 24000 data.

The data comes from the git repo henokyemam/Wrangling_Pyspark The aim is to rank the best teams that scored each season.


Notions of pyspark covered: operations with columns, window function 