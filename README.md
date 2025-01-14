# Card-game
This project is a Python-based simulation of a card game. The program allows four players to engage in a trick-taking card game, where each round involves players strategically playing cards to win tricks based on the highest-ranking card of the lead suit. The game proceeds through 13 rounds, with a final winner determined based on specific game rules.

Features:

1. Full Deck Simulation: The game uses a standard 52-card deck, shuffled and distributed evenly among four players.
2. Trick-Taking Mechanics: Players compete to win individual tricks in each round, adhering to the rules of following the lead suit.
3. Dynamic Gameplay: The starting player for each round changes dynamically based on the winner of the previous round.
4. Scorekeeping: Tracks player performance and determines the ultimate winner at the end of the game.
5. User-Friendly Outputs: Prints detailed play-by-play logs for each round, including cards played, trick winners, and final results.

How It Works

Shuffling and Dealing:
A 52-card deck is shuffled and evenly distributed among four players.

Gameplay:
The game begins with the player holding the 2 of Clubs.
Each player plays one card per round, following the lead suit if possible.
The winner of the round is determined by the highest-ranked card of the lead suit.

Winning the Game:
After 13 rounds, the player with the fewest cards of a specific type (e.g., Hearts) wins the game.

Endgame:
Detailed player hands and the overall winner are displayed at the end of the game.
