# game-task4-visible-bounds
 
 ![screenshot](https://user-images.githubusercontent.com/57709369/99371046-191f0b80-28c7-11eb-9108-e57eb57c3635.jpg)
 
 The game has 3 main objects:
 
   1. player- has collider and rigidbody. Player also has a scripts that made him move, killed when it hit enemy, and shoot laser.
      https://github.com/Noa-Amit/game-task4-visible-bounds/blob/main/Assets/Scripts/1-movers/KeyboardMover.cs
      https://github.com/Noa-Amit/game-task4-visible-bounds/blob/main/Assets/Scripts/3-collisions/DestroyOnTrigger2D.cs
      https://github.com/Noa-Amit/game-task4-visible-bounds/blob/main/Assets/Scripts/2-spawners/LaserShooter.cs
      
   
   2. enemySpawner- a prefab that spawn the enemies.
     https://github.com/Noa-Amit/game-task4-visible-bounds/blob/main/Assets/Prefabs/EnemySpawner.prefab
   
   3. Wall- a prefab that has collider and rigidbody. The player can't go through the wall.
     https://github.com/Noa-Amit/game-task4-visible-bounds/blob/main/Assets/Prefabs/Wall.prefab
     We put 4 walls at the camera's frame.
