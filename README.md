

*Simon Says* is a game that displays a series of tones and lights in random order and requires a player to repeat the sequence from memory. The game typically displays four colored pads. Each pad produces a particular tone when it is pressed. The tone helps the player remember the sequence. With each additional round, the number of pads in the sequence increases by one. Once the player makes a mistake, the game ends and resets.

In this project, I applied my HTML, CSS, and JavaScript skills to bring the classic Simon Says game to life. The game challenges players to remember and repeat a sequence of tones and lights.

**User Stories and Implementation:**
I followed the user stories provided by the game designer, making sure to complete each task in the specified order. The game now includes:

- Basic game structure (title, start button, status message, four colored pads).
- Initialization of the game with setLevel() and startButtonHandler().
- Computer's turn with playComputerTurn(), getRandomItem(), setText(), activatePad(), and activatePads().
- Player's turn with playHumanTurn(), padHandler(), checkPress(), and checkRound().
- Game reset with resetGame().
