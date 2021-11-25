## 1.IDENTIFY FEATURE

Online access, Search function using (playstore,ios,chrome) ,Flexibility.

## 2.STATE OF ART

A snake game pro is a software application that uses in both Mobile applications(Android, Ios), pc. It use to store the database of the user of whom signed the game. Users can sign in using Gmail, facebook.

## 3.4 W and 1 H

## WHEN

One can play his game whenever he/she is free and want some refreshment but also they want to do some productive work.

## WHO

Every person with electronic devices need games nowdays for refreshment and relaxing.So,anyone can play this game.

## WHAT

A game which can be used to check or enhance our general knowledge.

## WHERE

It can be played by everyone and everywhere irrespective of their age.

## HOW

One can simply enter his name and start playing.

## 4.SWOT ANALYSIS

## Strength 

1.it can be accessible to mobile and pc with basic minimum requirments.
2.with or without  internet connection it can be played. 

## Weakness  

it cannot be palyed on high resolution graphics.

## 5.HIGH LEVEL REQUIREMENTS

1.Create a board.

2.Create a snake.

3.Moving the snake.

4.Create a target(Food).

5.Create a records of players.

## 6.LOW LEVEL REQUIREMENTS

1.Create borders.

2.Create coordinates for snake body.

3.Create multiple coordinates.

4.Right, left, up&down moves.

5.Generate scores of players.

## FUNCTIONAL REQUIREMENTS

WASD keys for W-Up, A-Left, S-Down, D-Right change the snake's direction.
The sake has a velocity in the direction it is moving. That velocity increases with time. (Provide function of time for detailed requirement.)
Randomly place power-ups:
Slow snake velocity.
Food makes the snake longer.
Bonus targets gain bonus points.
etc.
If the sake collides with the snake the round ends and a new round starts.
At the end of rounds, the score is registered as the player’s highest if it is better than any recorded before. The highest registered score is tracked between all players on a leaderboard.
Log in to identify the player. (Details should include username/password requirements, is two-factor auth needed, should obscene words be allowed as usernames? etc..?)
Options menu to set music and sound effects volumes. Color scheme?

## NON-FUNCTIONAL REQUIREMENTS

On cutting-edge computers, as of 2010, it should get a 40 FPS refresh rate.
The leaderboard needs to support 9 million concurrent users.
The leaderboard must be updated within 2 min after a new high score is registered by a play.
This is the idea. For real game development documentation, you would also want some discussion about monetization and promotion. You would want some details about the look and feel. (Is it neon colors, does it use a disco beat to the music/effects, should be it slower and more casual or fast and intense? Etc…)

A good game design document is more than requirements. But, the requirements are a major part of it. Functional requirements are about what it should do. Non-Functional requirements are about how well it should perform on which platforms.

## BEHAVIORAL DIAGRAM 1
![Behavioral diagram 1](https://user-images.githubusercontent.com/94282195/143449513-fa587d41-7679-44ec-8582-82baf46b6f4e.png)

## BEHAVIROL DIAGRAM 2
![Behavioral diagram 2](https://user-images.githubusercontent.com/94282195/143449613-dc0a0cca-cd1a-4405-ae2f-8e640837a8db.png)

## STRUCTURAL DIAGRAM 1
![Structural diagram 1](https://user-images.githubusercontent.com/94282195/143449730-3251c2b5-688f-43af-9517-b45475804048.jpg)

## STRUCTURAL DIAGRAM 2
![structural diagram2](https://user-images.githubusercontent.com/94282195/143449824-1fd57620-6e32-4a83-bd7b-2c0ec85ff6e7.png)

### High Level Test Cases
| Test Id |	Description |	Expected output |	Actual output |	Pass/Fail(Result) |
|-------|----------------|---------|------|------|
| TID 1 | Handle four user-defined functions| SUCCESS |	SUCCESS |	PASS 
| TID 2 | Build a boundary within which game will be played|	SUCCESS	| SUCCESS	 | PASS
| TID 3	| Snake can move in any direction according to the user with the help of the keyboard (W, A, S, D keys) |	SUCCESS |	SUCCESS	|PASS

### Low Level Test Cases
| Test Id |	Description |	Expected output |	Actual output |	Pass/Fail(Result) |
|------|------|------|------|------|
| TID 1 |Fruit will generate automatically within the boundaries | SUCCESS | SUCCESS | PASS 
| TID 2 |Whenever the snake will touch the boundary the game is over | SUCCESS | SUCCESS |  PASS




