# Unity Learn: AI for Beginners

My implementations of the projects following the tutorials from the [AI for Beginners course on Unity Learn](https://learn.unity.com/course/artificial-intelligence-for-beginners).

### How To Play: 

Download and extract the .zip file of the game. Navigate to the `Build` folder and open the Unity Application file of the game.

### Projects

<details>
 <summary><h4>Tank AutoPilot<h4></summary>
 
 Toggle an AutoPilot function to move a tank towards the fuel canister
   * Use `T` to toggle autopilot mode
   * Use `WASD` or Arrow Keys to move tank around world
</details>

<details>
 <summary><h4>Tank Battle<h4></summary>
 
 Move a red tank around a world while a green tank calculates trajectories and fires shells at you.
  * Use `WASD` or Arrow Keys to move red tank around the world
  
</details>
  
<details>
 <summary><h4>Tank Racing<h4></summary>  
 
Tanks race around a circuit using a waypoint system

</details>

<details>
 <summary><h4>Tank Patrol<h4></summary>
 
Click buttons to send the tank to the area. Uses a waypoint system with graphs and the A* algorithm to find the shortest path
from start to destination waypoint.

</details>

<details>
 <summary><h4>Tank Patrol 2<h4></summary>
 
Click buttons to send the tank to the area. Uses a waypoint system and NavMesh to travel between locations.

</details>

<details>
 <summary><h4>Path Finder<h4></summary>

Uses the A* algorithm to traverse a maze from a start to goal position
  * Press `P` to clean and generate new start and goal positions on the map
  * Press `C` to perform one step of the A* algorithm
  * Press `M` when the goal is reached to view the path taken

</details>

<details>
 <summary><h4>Station Navigation<h4></summary>
 
Click anywhere in view to set a destination for red and blue agents to go to. The agents use a NavMesh system to go to the point.

</details>

<details>
 <summary><h4>Zombie Chaser<h4></summary>

Run as a zombie chases you throughout a warehouse. Uses a NavMesh system with off-mesh links to cross mesh gaps and drops.
  * Use `WASD` to move
  * Use `Space` to jump

</details>

<details>
 <summary><h4>Guard Patrol<h4></summary>
 
A guard patrols an area. If the guard can see you, he will chase and attack. If you sneak up behind him, he will run to the safe point. The guard uses a finite state machine to toggle between the different states, as NavMesh system and vector calculations to determine what to do within states.
  * Use `WASD` to move
  * Use `Space` to jump
  
</details>
  
<details>
 <summary><h4>Cops & Robbers<h4></summary>
  
The player is a cop chasing down a couple of robbers in the area. The robbers will wander around, hide behind obstacles, try to sneak up on the player, and evade based on the player's movement, look direction, and distance. Uses implementations of common steering behaviors for autonomously moving agents.
  * Use `WASD` to move.

  </details>
