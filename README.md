#SkywardSeeker

This is a two-player game where players race to the top of the screen to capture an item. Players must navigate through obstacles and enemies, using their skills and strategies to reach the goal. The game features three levels of increasing difficulty, each with unique themes and challenges.



Game Overview

- Objective: Reach the top to capture the item before the other player.
- Gameplay: Players navigate through static and moving platforms while evading randomly generated enemies.
- Lives: Each player starts with three lives. A life is lost upon collision with an enemy or falling to the ground (specific to level 3).
- Winning Condition: The first player to capture the item at the top wins. Alternatively, if a player loses all three lives, the other player is declared the victor.


Levels

Level 1: Forest Land
- Theme: Forest environment with static platforms.
- Enemies: 
  - Type 1: Drops from platforms above.
  - Type 2: Pop-up attacks on the platform.
  - Type 3: Flies across the screen.
- Challenges: Players must avoid enemies while navigating static platforms.

Level 2: Sky and Fairyland
- Theme: A sky and fairyland with both static and moving platforms.
- Enemies: 
  - Type 1 and Type 2 remain, Type 3 is not present.
- Player Skills: 
  - Each player has three bullets to shoot at the other player.
  - Bullets can make a player fall to the ground.
- Power-ups: Floating bubbles that increase life or bullets.

 Level 3: Snow Land
- Theme: A snowy environment with static and moving platforms.
- Enemies: Same as Level 2.
- Player Skills: 
  - Introduces frozen bullets that freeze the opponent for 3 seconds.
- Power-ups: Pop-ups that increase life or frozen bullets.
- Additional Challenge: Players lose one life if they fall to the ground.


Features

Instruction Screen
- Welcomes players at the start.
- Provides instructions on controls and objectives for each level.

Two-Player Mode
- Two player objects with separate controls and life hearts.
- Movement and attack capabilities for each player.

Platforms
- Static and moving platforms, depending on the level.
- Gaps between platforms to challenge player navigation.

Random Enemies
- Auto-generated enemies with different movements and directions.
- Collision detection with players, leading to damage effects.

Power-Ups
- Randomly appear on platforms.
- Increase life, bullets, or frozen bullets based on the level.

Player Attacks
- Players can shoot bullets to hit the other player.
- Frozen bullets (Level 3) freeze the opponent for 3 seconds.

Level System
- Allows players to select from three different levels.

Life and Score System
- Tracks player lives and determines game status.
- Displays winner when a player reaches the item or loses all lives.
- Scores are displayed individually for each level.

Visuals and Sound
- Engaging backgrounds, character designs, enemies, platforms, and sound effects.



Getting Started

Prerequisites
- Processing IDE installed on your machine.
- Basic knowledge of Python and Processing.

Installation
1. Clone the Repository:
2. Open the Project in Processing:
   - Open the Processing IDE.
   - Open the main `.pyde` file in the project directory.
3. Run the Game:
   - Click the "Run" button in Processing to start the game.

How to Play

1. Controls:
   - Each player uses three keys for movement (up, left, and right).
   - Additional keys for shooting bullets (Levels 2 and 3).
2. Objective:
   - Navigate platforms, avoid enemies, and reach the top to capture the item.
   - Use bullets strategically to hinder the other player.
3. Winning:
   - Capture the item first or outlast the opponent by avoiding losing all lives.

Contribution

Contributions are welcome! Here's how you can help:

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature-YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-YourFeature`).
5. Open a Pull Request.


Acknowledgments

- Processing IDE for providing an accessible platform for game development.
- Open-source resources for sound effects and character sprites.




