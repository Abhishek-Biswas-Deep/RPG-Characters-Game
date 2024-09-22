<img src="https://github.com/user-attachments/assets/2ad86f70-12b4-4500-997d-9f8c1874a9b5" alt="Dal logo" width="80"/>
<h1>Associated with Dalhousie University</h1>

### CSCI1110
### RPG Characters Game
Welcome to the RPG Characters Game project! This program simulates a simple RPG (Role-Playing Game) where different types of characters engage in a turn-based duel. Each character has unique abilities and roles, and they can attack, heal, or defend based on their class.

#### Objective
The game simulates a duel between two characters, where each turn, one character can either attack or heal. The objective is to defeat the opponent by reducing their HP to zero before they can do the same to you.

#### Characters and Roles
The game includes three different types of characters, each with its own strengths and abilities. 
#### Here’s a breakdown:
#### 1. Mage
- Role: Damage Dealer
- Special Ability: Casts powerful spells from a distance.
#### Attacks:
1. Fire Ball: A high-damage spell that can hit targets far away.
2. Frost Ball: Slows down enemies while dealing moderate damage.
3. Lightning: An expensive but powerful spell with great damage.

#### When to use a Mage:
If you want to deal heavy damage to enemies from a safe distance, the Mage is your go-to character.

#### 2. Priest
- Role: Healer and Support
- Special Ability: Can heal itself and allies, as well as deal moderate damage.
#### Attacks:
1. Flash Heal: Quickly restores health to the priest or allies.
2. Smite: A ranged spell that deals damage to enemies.
3. Resurrection: Can bring back a fallen ally (not fully implemented in the demo).
#### When to use a Priest: 
If you want to focus on keeping your team alive while doing some damage, the Priest is essential.

#### 3. Warrior
- Role: Tank and Physical Damage Dealer
- Special Ability: Performs close-range attacks that rely on physical strength.
#### Attacks:
1. Punch: A basic, energy-free attack that deals minor damage.
2. Slam: Deals more damage but consumes energy.
3. Charge: A powerful move that consumes a lot of energy but deals massive damage to a distant enemy.
#### When to use a Warrior: 
The Warrior excels in close combat, absorbing damage while dishing out powerful physical attacks.

#### Game Mechanics
This game uses turn-based mechanics, where two characters take turns performing actions. Each character can move, attack, or heal based on their abilities.

- Health (HP): Each character has a maximum HP. If HP drops to 0, the character is defeated.
- Mana (for Mages and Priests) and Energy (for Warriors) determine how often a character can perform special abilities.

#### How Attacks Work
Each character has a range of attacks with varying costs (in Mana or Energy) and damage potential.
Some attacks are melee (close-range), while others are ranged (long-distance).

#### Healing
Priests can heal themselves or their allies using abilities like Flash Heal.
Healing restores lost HP, but the character cannot exceed their maximum HP.

#### How to Play
- Clone the repository
- Navigate to that project
- Compile and run the game in your preferred IDE (like IntelliJ).


