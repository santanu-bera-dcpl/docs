# League Wise Gameplay
The card game section is always league wise. 

# Player Selection By Users
The user logs into the website, and is allowed for 5 minutes before the game starts to choose their players. Within this 5 minutes user can choose one or multiple players and setup their lineup. After the 5 minutes over, the user won't be able to select any players for the day.

# HeadToHead - Challange
User can invite any other user to challange their lineup to see who wins. It is a direct challange to someone. For example, if user A selects 5 players and if user B selects 7 players, and at the end of the day if the sum of all player's score of user A is 30 and and sum of all player's score of user B is 50, then B will be the winner. Whoever has the heighest total score will be the winner.

# HeadToHead - invitation/accept/reject
For a head to head challange User A needs to send a invitation request to user B, with a price. Both user's account should have the specified amount available. User B can either accept the request or reject it. If user B accepts the challange, the specified price will be deducted from both user's account and will be credited to Admin wallet. And the challanges will be active.

# HeadToHead - Winner
The winning process will be triggered from the Admin. When the winning process is triggered from the admin, it will determine the winner of all active head to head challanges to see which user own the challanges. But before admin can trigger this winning process, the admin needs to generate user's lineup score report.

# User Lineup Score Report
Admin can trigger the process for generating user's lineup score summary report. Each user has their lineup(player selection) saved in the database in daily basis or weekly basis. This process will fetch score of all players for each lineup and make a summary of total score for each lineup.
```JS
{
	userId
}
```