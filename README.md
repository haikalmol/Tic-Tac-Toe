# Tic Tac Toe solution

Tic Tac Toe is a simple game in which two players alternately put Xs and Os in compartments of a figure formed by two vertical lines crossing two horizontal lines and each tries to get a row of three Xs or three Os before the opponent does.

What unique about this project is you have two options whether to play vs CPU or another player which makes the game here is more interesting.

The game is fully responsive and was set with some animations and a little twist representing CPU thinking.

![Responsive Mockup](./designs/main-screenshot.png)

## Features

- **Welcome Screen**

  - This is the welcome screen. Here the user has the option to select X or O mark and to decide whether to play againest the CPU or another player.

![Responsive Mockup](./designs/desktop-new-game-menu.png)

- **Gameplay Start**

  - This is the gameboard before any of the users or CPU selects a cell.

![Responsive Mockup](./designs/desktop-game-start.png)

- **Solo Gameplay**
  - If the user decided to play againest the CPU then the scoreboard will be updated with proper titles that matches the game situation.
  - The computer will start first if the player selected O mark since X will start first in all cases.
  - The user will start first if he selected the X mark.

![Responsive Mockup](./designs/desktop-game-multiplayer.png)

- **Multiplayer Gameplay**
  - If the user decided to play againest another player then the scoreboard will be updated with proper titles that matches the game situation.
  - X will start first then O

![Responsive Mockup](./designs/desktop-game-solo.png)

- **Round Tie**
  - The message that will be displayed if there is a tie
  - There will be two options wether to go for the next round or to quit the game and return back to the welcome screen.

![Responsive Mockup](./designs/desktop-round-tied.png)

- **Multiplayer Player 1 Win**
  - The message that should be displayed if the user starts with multiplayer version and Player 1 wins.

![Responsive Mockup](./designs/desktop-game-multiplayer-player1-win.png)

- **Multiplayer Player 2 Win**
  - The message that should be displayed if the user starts with multiplayer version and Player 2 wins.

![Responsive Mockup](./designs/desktop-game-multiplayer-player2-win.png)

- **Solo Gameplay CPU Wins**
  - The message that should be displayed if the user starts with solo gameplay and CPU wins.

![Responsive Mockup](./designs/desktop-game-solo-player-loss.png)

- **Solo Gameplay Player Wins**
  - The message that should be displayed if the user starts with solo gameplay and the player wins.

![Responsive Mockup](./designs/desktop-game-solo-player-win.png)

- **Restart Button**
  - When clicking the RESTART button. The user has two options whether to cancel and returns back to the gameplay or to restart the game so all the cards will be rest so the user can start a new game.

![Responsive Mockup](./designs/desktop-restart-game.png)

## Technologies Used

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- SASS
- Vanilla Javascript
