# Rock-Paper-Scissors AI

This project is a simple implementation of the classic game **Rock, Paper, Scissors**, but with an AI component that uses machine learning techniques to predict the player's next move. The objective of this project is to demonstrate the use of artificial intelligence in a game setting using a rule-based AI strategy.

## Project Description

In this project, the user plays the game **Rock, Paper, Scissors** against an AI. The game follows the usual rules:
- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

The AI attempts to predict your move using a basic pattern, and then chooses its counter-move based on the prediction. Over time, the AI improves by adapting to your moves.

The project goal is to implement an interactive and simple game that uses AI for decision-making.

## Tech Stack

- **Python**: The main programming language used to build the game logic.
- **JavaScript**: Used for the front-end to create the interactive web page.
- **HTML/CSS**: For creating and styling the game’s user interface.
- **Machine Learning**: For AI decision-making.
- 
## How to Run

1. Clone this repository to your local machine or Gitpod workspace:

   ```bash
   git clone https://github.com/srepasup/Rock-Paper-Scissors-AI.git

2. Navigate to the project directory:
   ```bash
   cd Rock-Paper-Scissors-AI

3. Install the required dependencies (if any):
   ```bash
   pip install -r requirements.txt

4. Run the game script:
   ```bash
   python RPS.py

## How It Works
The player function takes in the last move of the opponent and returns the next move based on some AI logic.

The game tracks the results of each match and adapts based on the opponent's history.

The goal is to win at least 60% of the matches against different bots.

## Contributing
Feel free to fork the repository and create pull requests for improvements or bug fixes. Contributions are welcome!

## License
This project is open-source and available under the MIT License.







