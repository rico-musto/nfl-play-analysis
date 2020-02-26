## Examining NFL Offenses on Third Down
### Background
The National Football League (NFL) is the most popular sports league in the United States. The basis of play is that each team has four chances to advance the ball ten yards. The most important of these trys is the third, referred to as third down. If the offense fails to advance ten total yards by their third try, most teams will elect to punt the ball to the opposing team on their fourth and final try, effectively ending their offensive possession. Being successful on third down is crucial for NFL defenses to stop the opposing offense and gain possession of the ball for their own team.

### The Data
The data set being used for this analysis contains every play that occured in the NFL from 2009-2018. This data was compiled by Carnegie Mellon University statistical researchers including Maksim Horowitz, Ron Yurko, and Sam Ventura. The data set contains around 450,000 rows and 250 columns and includes detailed information on game situation, players involved, results, and advanced metrics such as expected point and win probability values. The data was accessed through Kaggle at the following link: https://www.kaggle.com/maxhorowitz/nflplaybyplay2009to2016/download.

### Exploratory Data Analysis
#### Do teams run or pass more on third down?
The null hypothesis for the analysis is that there is no difference in the percentage of run plays or pass plays. For all third down plays, 19.57% plays are rush attempts, and 71.96% are passings plays. The difference in percentage is statistically significant with a p-value of 0. The null hypothesis is rejected and it is determenined that teams attempt pass plays more often on third down than running plays.

### Deep-Dive Data Analysis
Not all third downs are created equally. Teams can be put into drastically different third down scenarios. Teams can face a short third down attempt, with only two yards to go or be stuck in a long third and eight yard try. They could have possession of the ball with the lead or could be trying to come back from a deficit. 

#### Do teams run or pass more based on the yards to go on third down?
The null hypothesis for the analysis is that there is no difference in the percentage of run plays or pass plays for 3rd & 1 through 3rd & 10. Each scenario has a statistically significant difference between the percentage of rush and pass plays. The null hypothesis is rejected and the following is determined:
  * Teams are more likely to run than pass on 3rd Down with 1 yard to go.
  * Teams are more likely to pass than run on 3rd Down with between 2 and 10 yards to go.

#### Do teams run or pass more on third down while they are winning
The null hypothesis for the analysis is that there is no difference in the percentage of run plays or pass plays for 3rd & 1 through 3rd & 10 while teams are winning. Each scenario has a statistically significant difference between the percentage of rush and pass plays. The null hypothesis is rejected and the following is determined:
  * Teams that are winning are more likely to run than pass on 3rd Down with 1 yard to go.
  * Teams that are winning are more likely to pass than run on 3rd Down with between 2 and 10 yards to go.

### Results
Results from this analysis are useful to NFL defenses and allow them to better defend crucial third down plays. The main takeways that NFL defenses can use are as follows:
  * A team is more likely to run on 3rd Down & 1
  * A team is more likely to pass on 3rd Down and 2-10
  * A team that is losing increases their chance of passing by about 10 percentage points for all 3rd Down attempts.



















