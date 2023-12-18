Data Set Description

df is a dataset of all basketball shots made in 2014-2015 NBA season. Each row is a shot taken during the season.
players is a dataset of all players during the 2014-2015 season and their background information. Each row is a player.
df2 is the merged dataset between df and players .

Important columns in df are:

LOCATION: If the game was away or home.
W or L: If the game resulted in a win or loss.
FINAL_MARGIN: The amount of points away from taking the lead when the shot was attempted.
PERIOD: The quarter the shot attempt was made. There are 4 quarters, 5 to 7 are overtime
GAME_CLOCK: Time left in the game. There are 12 minutes per quarter and the clock ticks down to the end of the quarter. End of quarter is 0 second.
SHOT_CLOCK: The time left for the offensive team to shoot. The offensive team is given 24 seconds to attempt a field goal.
DRIBBLES: Number of dribbles player make before taking a shot.
TOUCH_TIME: How long in seconds the shooting player touched the ball before attempting a shot.
SHOT_DIST: Distance of a shot in feet.
PTS_TYPE: The type of field goal attempted. 2 or 3 point shots.
CLOSE_DEF_DIST: How far away the defener is when shot was attempted in feet.
FGM: Field goals made. 1 if shot is made, 0 is missed.

Important columns in players are:

Age: Age of player
Experience: Years of experience the player has in the NBA. R stands for rookie, first year.
First_Name: First name of shooter
Pos: Position of the player. There are 5 positions: Point Guard (PG), Shooting Guard (SG), Center (C), Power Foward (PF), Small Forward (SF)
Surname: Last name of shooter

Intersting Finding:
During the last two minutes of the quarter, point guards tend to have more touch time with the ball and attempt more field goals than any other positions and time in the game. Also, compared to other quarters they tend to make more field goal attempts during this time, especially 3 pointers.
Background: Point guards are one of five positions in basketball and are known as the team leader  on the court. They  control the ball and run the team's offensive plays, hence they have more ball handling and control the tempo of the game. They provide scoring opportunities for their team through passing the ball as they deem fit.

Managerial Insights:

During the last two minutes of the game, point guards have more time on the ball. There are a couple of speculations as to why this occurred:

There are probably more scripted plays during last two minutes (especially if there is a low margin to victory). Hence point guards are relied upon to carry out the team's plays to increase their lead.
The team is ahead so the point guards waste time to keep their lead.
This is a surprised finding as one may think historically shooting guards (e.g. Michael Jordan, Dwayne Wade, Kobe Bryant...) would handle the last couple minutes of the game. It appears that during this time in the NBA (2014-2015 season), we started to see that point guards and quick ball movement are becoming more prominent.

Therefore, from a defender perspective, place your best defender or double team against the opposing PG last couple minutes to prevent scoring. There are many factors to the game (who the PG is, the nature of the team, team rivalry, injuries, etc.) so it is best to plan ahead before a game and strategize how to defend the opposing team's PG.
