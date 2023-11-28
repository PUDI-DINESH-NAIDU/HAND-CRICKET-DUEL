# HAND-CRICKET-DUEL
Hand Cricket Duel: Interactive Cricket Game

Overview
Hand Cricket Duel is a browser-based interactive cricket game implemented in HTML, CSS, and JavaScript. The game simulates a cricket match between two players, allowing them to participate in a virtual duel of batting and bowling. The game involves a toss, player turns, score tracking, and ends with a winner or a tie.

Mechanism
HTML Structure:

The game interface is structured with sections for player names, toss buttons, toss result display, and the main game container. Player names and inputs for entering runs are organized in a visually appealing layout.
CSS Styling:

The CSS styling enhances the readability and aesthetics of the game. It provides a clean and organized appearance, aligning with the game's theme.
JavaScript Functions:

Toss Mechanism (startToss(player)) Function:

Simulates a toss for each player, displaying the result (Heads or Tails) and determining the toss winner. The toss winner gets the first turn, and the game interface is revealed.
Run Entry (enterRuns()) Function:

Allows players to input runs (between 1 and 6) during their turn. Validates the input and updates the game state, including scores, current turn, and result display.
Switch Player (switchPlayer()) Function:

Alternates the turn between Player 1 and Player 2 after each valid run entry.
End Game (endGame()) Function:

Concludes the game by displaying the final result, including the winner or indicating a tie.
Game Flow:

The game progresses through tosses, player turns, and score updates based on the runs entered by players. The match concludes after a set number of overs, revealing the winner or declaring a tie.
Uses and Benefits
Entertainment:

Hand Cricket Duel provides an engaging and interactive experience for cricket enthusiasts and casual players alike.
Two-Player Interaction:

Allows two players to compete against each other, adding a social and competitive element to the game.
Randomized Toss:

Incorporates a toss mechanism with random outcomes, adding an element of unpredictability to the game.
User-Friendly Interface:

The clean and intuitive interface makes it easy for players to understand and enjoy the game.
Score Tracking:

Tracks and displays scores for both players in real-time, enhancing the competitiveness of the match.
Dynamic Turn Switching:

Alternates turns between players, creating a dynamic and engaging gameplay experience.
Game Conclusion:

Provides a clear and conclusive end to the game, announcing the winner or indicating a tie.
Customizable:

Players can customize the game by entering their names, adding a personal touch to the gaming experience.
How to Play
Enter the names of Player 1 and Player 2.
Click the "Player 1 Toss" and "Player 2 Toss" buttons to determine the order of play.
Follow the on-screen instructions to enter runs during your turn (between 1 and 6).
Scores are updated in real-time.
The game concludes after the specified number of overs, revealing the winner or indicating a tie.
Enjoy the virtual duel of Hand Cricket!
