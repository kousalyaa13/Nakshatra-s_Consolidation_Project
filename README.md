# Consolidation_project : Dice Game! 

## Functionality & How to Run: 
1. **Starting the Game**:  
Upon running the program, it will prompt you for player names. At this point, enter the names of the players playing the game, separated by a comma. The game supports more than two players!  
   _Example_: `player 1, player 2, player 3`

2. **Game Setup**:  
After entering the names, the game begins. It will display the name and initial score (0) of the first player.

3. **Rolling the Dice**:  
After that, it will present player 1's first roll. The three numbers rolled on each of the three die will be printed to the screen in parentheses. 
   _Example_: `(1, 4, 6)`

4. **Scoring or Rerolling**:  
The player will be asked:  
   - `Do you want to stop and score your current roll? (yes/no):`  
   - If you type `yes`, the player’s name and score (sum of the rolled dice) will be displayed, and the turn ends.  
   - If you type `no`, the dice will be rolled again, and the question will repeat.  

5. **Fixed Dice**:  
   If two dice have the same value (e.g., `(4, 4, 2)`), those dice are "fixed." The program will ask:  
   - `Do you want to reroll the non-fixed dice? (yes/no):`  
   You can choose to reroll only the non-fixed die or stop and add up yoru score for the roll.

6. **Risk of Tupling Out**:  
   If all three dice show the same value after a roll or reroll (e.g., `(5, 5, 5)`), this is called "tupling out." It results in **0 points** for that round.

7. **Next Player's Turn**:  
   After a player's turn ends, the game moves to the next player. Their name and current score will be displayed before rolling the dice.

8. **Game Continuation**:  
   The game continues in turns, with scores being updated for each player.

9. **Winning the Game**:  
   When a player reaches the maximum score (25), the game ends. The program will display the winner's name followed by "wins!"  
   _Example_: `player 2 wins!`


## Sample Play: 

### Start the Game
**Enter player names separated by commas:**  
`player 1, player 2, player 3`

---

### Player 1's Turn  
**player 1's score:** 0  
**player 1 rolled:** `(3, 1, 6)`  
`Do you want to stop and score your current roll? (yes/no): yes`  
**player 1's score:** 10  

---

### Player 2's Turn  
**player 2's score:** 0  
**player 2 rolled:** `(4, 4, 2)`  
**Fixed dice:** Number 4 was rolled twice.  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 2 rerolled:** `(4, 4, 1)`  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 2 rerolled:** `(4, 4, 6)`  
`Do you want to reroll the non-fixed dice? (yes/no): no`  
**player 2's score:** 14  

---

### Player 3's Turn  
**player 3's score:** 0  
**player 3 rolled:** `(1, 6, 2)`  
`Do you want to stop and score your current roll? (yes/no): no`  
**player 3 rolled:** `(6, 5, 3)`  
`Do you want to stop and score your current roll? (yes/no): yes`  
**player 3's score:** 14  

---

### Player 1's Turn  
**player 1's score:** 10  
**player 1 rolled:** `(3, 4, 4)`  
**Fixed dice:** Number 4 was rolled twice.  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 1 rerolled:** `(3, 4, 4)`  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 1 rerolled:** `(4, 4, 4)`  
**Tupled out!** Zero points for this turn.  
**player 1's score:** 10  

---

### Player 2's Turn  
**player 2's score:** 14  
**player 2 rolled:** `(5, 4, 1)`  
`Do you want to stop and score your current roll? (yes/no): no`  
**player 2 rolled:** `(4, 4, 4)`  
**Tupled out!** Zero points for this turn.  
**player 2's score:** 14  

---

### Player 3's Turn  
**player 3's score:** 14  
**player 3 rolled:** `(1, 6, 5)`  
`Do you want to stop and score your current roll? (yes/no): no`  
**player 3 rolled:** `(2, 3, 5)`  
`Do you want to stop and score your current roll? (yes/no): no`  
**player 3 rolled:** `(1, 1, 4)`  
**Fixed dice:** Number 1 was rolled twice.  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 3 rerolled:** `(1, 1, 4)`  
`Do you want to reroll the non-fixed dice? (yes/no): yes`  
**player 3 rerolled:** `(1, 1, 6)`  
`Do you want to reroll the non-fixed dice? (yes/no): no`  
**player 3's score:** 22  

---

### Player 1's Turn  
**player 1's score:** 10  
**player 1 rolled:** `(4, 3, 2)`  
`Do you want to stop and score your current roll? (yes/no): no`  
**player 1 rolled:** `(3, 6, 2)`  
`Do you want to stop and score your current roll? (yes/no): yes`  
**player 1's score:** 21  

---

### Player 2's Turn  
**player 2's score:** 14  
**player 2 rolled:** `(5, 1, 6)`  
`Do you want to stop and score your current roll? (yes/no): yes`  
**player 2's score:** 26  

---

### Result  
**player 2 wins!**