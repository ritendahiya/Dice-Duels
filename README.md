# 🎲 Dice Game

This is a fun and interactive two-player dice game built with HTML, CSS, and JavaScript. The goal is to be the first player to reach a total score of 100. Players take turns rolling a dice and accumulating points, but they need to be cautious—rolling a 1 will lose their current round score and switch the turn to the other player. Players can also choose to "hold" their score to add their current round score to their total score and then pass the turn.

## How to Play

1. **🎲 Rolling the Dice**: On a player's turn, they can roll the dice. The rolled number is added to their current score.
2. **✋ Holding the Score**: A player can choose to hold their current score, adding it to their total score. This ends their turn and switches the play to the other player.
3. **🔄 Switching Players**: If a player rolls a 1, their current score for that round is lost, and the turn switches to the other player.
4. **🏆 Winning the Game**: The first player to reach a total score of 100 wins the game.
5. **🔁 Resetting the Game**: Players can reset the game at any time to start over.

## Flowchart

![Game Flowchart](./path-to-your-image/pig-game-flowchart.png)

This flowchart visually represents the game logic and flow:

1. **User Rolls Dice**:
   - A random dice roll is generated.
   - The dice roll is displayed.
   - If the roll is not a 1, the dice roll is added to the current score, and the new score is displayed.
   - If the roll is a 1, the current score is lost, and the turn switches to the other player.

2. **User Holds Score**:
   - The current score is added to the total score.
   - If the total score is 100 or more, the current player wins.
   - If the total score is less than 100, the turn switches to the other player.

3. **User Resets Game**:
   - All scores are set to 0.
   - Player 1 is set as the starting player.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/dice-game.git
