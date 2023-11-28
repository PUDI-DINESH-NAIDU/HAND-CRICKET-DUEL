# HAND-CRICKET-DUEL
**Hand Cricket Duel: Multiplayer Cricket Game**

## Overview

**Hand Cricket Duel** is a multiplayer cricket game implemented in HTML, CSS, and JavaScript. The game allows two players to engage in a virtual cricket match, taking turns to bat and bowl. It includes a toss mechanism, player input for runs, and displays scores and results.

## Mechanism

1. **HTML Structure:**
   - The game interface is built using HTML, incorporating elements for player names, toss buttons, game status, and result displays.

2. **CSS Styling:**
   - CSS is used for styling to create a visually appealing and user-friendly interface. The layout is centered, and styling elements like buttons, input fields, and result displays are defined.

3. **JavaScript Functions:**

   - **`startToss(player)` Function:**
     - Initiates a coin toss for each player, determining the winner.
     - Displays toss results and decides who bats or bowls first.

   - **`enterRuns()` Function:**
     - Allows the current player to input runs for their turn.
     - Checks for valid input (between 1 and 6) and updates scores accordingly.
     - Switches players after each turn.
     - Handles the end of the game after the specified number of overs.

   - **`switchPlayer()` Function:**
     - Switches the current player after each turn.

   - **`endGame()` Function:**
     - Determines the winner based on the total scores.
     - Displays the result and congratulatory message.
     - Resets the game for a new match.

4. **Game Flow:**
   - Players input their names and initiate tosses to decide the batting/bowling order.
   - Players take turns entering runs, and the scores are updated.
   - The game ends after the specified number of overs, and the winner is declared.

## Uses and Benefits

- **Multiplayer Engagement:**
  - Enables two players to participate simultaneously, enhancing the multiplayer gaming experience.

- **Toss Mechanism:**
  - Incorporates a coin toss to decide which player bats or bowls first, adding an element of chance.

- **User Interaction:**
  - Engages users by allowing them to input runs for each turn, simulating a cricket match experience.

- **Dynamic Updates:**
  - Provides real-time updates on scores and results, creating an interactive and immersive gaming environment.

- **Customizable Gameplay:**
  - Allows players to set the number of overs, providing flexibility for a quick game or a more extended match.

- **Responsive Design:**
  - The game is designed to be responsive, ensuring a seamless experience on various devices.

- **Randomization:**
  - Uses randomization for the toss, adding unpredictability to the game.

## How to Play

1. Enter the names of Player 1 and Player 2.
2. Initiate tosses for each player to decide the batting/bowling order.
3. Players take turns entering runs (between 1 and 6) when prompted.
4. Scores are updated, and the game switches to the next player after each turn.
5. The game ends after the specified number of overs, and the winner is declared.
6. Click "New Game" to reset and start a new match.

Enjoy playing Hand Cricket Duel and experience the thrill of a virtual cricket match!
