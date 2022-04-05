# Analysis-of-Olympic-Game
Analysis of the results of the Olympics Game. 


Dataset is avalibe from: 
- https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results?fbclid=IwAR0ssI28o0UdhhSPqxsFdOY0zeXYf_Ir1prfAGTyLUbB6pRPiuNSCvKH4hQ



Dataset:
This is a historical dataset on the modern Olympic Games, including all the Games from Athens 1896 to Rio 2016. I scraped this data from www.sports-reference.com in May 2018. Note that the Winter and Summer Games were held in the same year up until 1992. After that, they staggered them such that Winter Games occur on a four year cycle starting with 1994, then Summer in 1996, then Winter in 1998, and so on. A common mistake people make when analyzing this data is to assume that the Summer and Winter Games have always been staggered.
The file athlete_events.csv contains 271116 rows and 15 columns. Each row corresponds to an individual athlete competing in an individual Olympic event (athlete-events). The columns are:
- ID - Unique number for each athlete
- Name - Athlete's name
- Sex - M or F
- Age - Integer
- Height - In centimeters
- Weight - In kilograms
- Team - Team name
- NOC - National Olympic Committee 3-letter code
- Games - Year and season
- Year - Integer
- Season - Summer or Winter
- City - Host city
- Sport - Sport
- Event - Event
- Medal - Gold, Silver, Bronze, or NA


Purpose of the task:
Analysis is helpful for children and their parents, future athletes, current athletes and sports clubs and countries.


Analysis dataset:
- Dependence of the number of medals depending on the origin of the investor in winter competitions over the years
- The corelation between height and medals won
- The sports are dominated by short people (under 175cm)
- Dependence of Medals and the age of the athlete
- Number of countries broken down by the year of the Olympic Games
- other
