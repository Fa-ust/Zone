# Zone

Console-Based Python Game Documentation
Overview
This is a console game made with Python. In this game, you fight enemies and bosses, level up, and use different attacks. The player can choose from different attacks like wind, fire, light, and grass. Each attack is stronger or weaker against certain enemies. There is also an ultimate attack you can use, and it can do a lot of damage, but you can only use it after waiting for a few turns. Your goal is to fight and level up to defeat bosses.

Features
Player Character: You can give your character a name and level up by getting experience (XP).
Enemies: There are normal enemies and rare, powerful bosses with different weaknesses.
Combat: You can attack using wind, fire, light, and grass, and you can make the enemy weak by using the right attack.
Ultimate Attack: A special powerful attack that does a lot of damage. It needs to wait for a few turns to be used again.
Leveling: You get XP after every fight, and once you have enough, you level up. Each level gives you more health and damage.
Boss Fights: After defeating 5 normal enemies, you can fight a boss.
Camp: You can go back to camp to heal, but if you do, you lose progress toward fighting a boss.
Running Away: You can try to run from a fight, but there’s only a 50% chance it will work.
Game Logic
Player Actions:
Attack: You can attack with one of four types: Wind, Fire, Light, or Grass. Some enemies are weak to certain attacks.
Ultimate Attack: A big attack that does 70 damage to any enemy. You can only use it after 5 turns.
Run: If you want to run, you have a 50% chance to escape the fight.
Enemies:
Normal Enemies: There are different enemies with weak points, like Grass Trent (weak to fire) and Fire Demon (weak to water).
Bosses: Strong enemies like Romax, Justin, Eric, and Andrew. You fight them after defeating 5 normal enemies.
Combat:
After you attack, the enemy will attack back with either light, heavy, or lethal attacks.
Light attack deals 10 damage, heavy does 15 damage, and lethal does 20 damage.
Your health goes down after enemy attacks. You need to reduce the enemy’s health to 0 before they reduce yours.
Leveling:
You get 20 XP for defeating normal enemies and 90 XP for defeating bosses.
When you get 100 XP, you level up. You get 10 more health and 5 more damage each time you level up.
If you go back to camp, your progress toward bosses resets.
End of the Game:
The game ends when your health reaches 0.
How to Run the Game
Requirements:
Python 3.x
Steps to Run:
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/yourusername/repository-name.git
Go to the Project Folder:

bash
Copy
Edit
cd repository-name
Run the Game: Type this in the terminal or command prompt:

bash
Copy
Edit
python game.py
Follow the instructions on the screen to enter your name, choose actions, and fight enemies.

File Structure
game.py: This is the main file. It has the code for the game, including the player, enemy, and combat system.
README.md: This file has the documentation.
Code Overview
The code has the following parts:

Player Class: Manages the player's health, damage, XP, and level.
Enemy Class: Manages the enemies' health, attacks, and weaknesses.
Combat Functions: Functions to handle attacking, healing, and using the ultimate attack.
Game Flow: Controls how the game goes, including encounters and leveling up.
Contributing
If you want to help improve this game, you can fork the repo and send a pull request. Contributions are welcome!

License
This project uses the MIT License - see the LICENSE file for details.

