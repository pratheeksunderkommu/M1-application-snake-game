REQUIREMENTS 
============
____________
Features
--------
 1. Create the board for the game
  2. Create the Snake object (dot, square etc)
  3. Get keystrokes from the user to move the snake around
    * Snake will have to be control using the arrow keys
  4. Create a object for snake to eat
    * If the snake hits the object the snake grows
    * Else the snake doesn't grow
  5. Check for snake colliding to itself 
    * End game if snake collides with itself
    * Else continue with the game
    * Collision detection needed
  6. Check to see if snake has collided against the wall of board
    * End game if snake collides with wall
    * Else continue with the game.
    * Collision detection needed
    
4W&1H
------
1.How does the snake game work?

   The game normally starts with a dot,square,orobject on a borderedplans.As it moves forward,it leaves a trail behind,resembling a moving snake.In some games,the end of the 
 trail is in a fixed position,so the snake continually gets longer as it moves.
  
2.What is the purpose of the Snake game?

  Snake is a classic game that requires players to assess their surroundings and find the quickest or safest route to a point. This is an excellent opportunity to learn about 
spatial awareness and plan ahead to your next move.

3.Which algorithm is used in snake game?

  Scores given by these functions are aggregated by linear weighted sum, and the snake takes the action that leads to the highest score. To find a set of good weight values, we
apply an evolutionary. 

4.Where do we develop snake game?

  We can develop in any programming language and there are many sites to do that.But we are using the visual studio code to create the snake game.
  
5.When do we play the game?

  We play the game when we are bored or for entertainment.

SWOT Analysis
---------------

1.Strength
 
  Spatial awareness and plan ahead to your next move.
  
  It would educate on long term strategic planning.
  
  The game requires patience in order to grow and a cool head once you inevitably lose.
  
2.Weakness

  It is too addictive if you don't stop playing it continuously.
  
3.Opportunities  

  Can be implemented at any devices.
  
4.Threats

  There might be device damage while over using it.
  
STATE OF ART
------------

   The prototypical Snake game was Blockade developed in 1976 as a two-player arcade game in a dedicated upright cabinet. In this classic arcade game, players’ cursors started from predetermined and symmetrical positions and moved within a square making 90-degree turns. One of the difficulties players had to address was avoiding the running trail left behind their moving cursors. Hitting such trails would incur a loss for the infracting player. The movie Tron would also use  these mechanics in the bike scenes, in which the bikes would leave a wall behind, causing a barrier to crash into for other participants.
   
  Snake would become a single-player version of this add the idea of the walls left behind being limited in length and then encouraging the player to increase their score, and the risk of losing, via eating a power-up (known as an apple) to increase in length by a unit. This would serve as the foundation of all Snake games to come. Snake would be especially popularized via its inclusion on Nokia phones as a build-in monochromatic game. Our implementation for the contest game is closer to the Blockade in that it is a two-player version but uses the apples from the Snake variants to come.
  
  This work is motivated by a more ludic environment to teach programming concepts and introduce artificial intelligence methods in university-level courses.Students had the opportunity to develop the game and participate in a contest that rewarded students who implemented ingenious bots in a competition during the course. At the end of the semester, the instructors used the first Snakes match to reward students who developed ingenuous heuristics. The source code and example of bots are publicly available in GitHub1 and can be helpful resources for instructors willing to experiment with such an approach.
  
