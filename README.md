# Rock Paper Scissors

This is the boilerplate for the Rock Paper Scissors project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/rock-paper-scissors

This program is a solution to a machine learning challenge where I developed an intelligent Rock, Paper, Scissors (RPS) player that consistently defeats multiple bot opponents. The objective was to write a function that plays RPS not randomly, but strategically - learning and adapting based on the opponent's past moves.

## My Contribution
- Developed a player function in **RPS.py** that uses opponent move history to predict and counter future moves
- Implemented adaptive logic and pattern recognition to detect repetitive or probabilistic behaviours from each bot
- Designed multiple strategies and adjusted them dynamically based on the specific opponent
- Thoroughly test the function against all provided bots to ensure consistent performance

## Strategy Summary
Each bot uses a unique strategy (e.g., fixed patterns, probabilistic moves). My player function analyzes the opponent’s move history and my own, using different techniques — such as frequency analysis, last-move tracking, and prediction models — to effectively counter their strategies.
Each bot in the game follows a predictable or semi-predictable pattern. My approach was to:
1. Identify the bot early using a fingerprint of its first three moves.
2. Maintain state across moves using default mutable arguments to track opponent and my own move histories.
3. Implement a tailored counter-strategy once the bot was identified:


## Key skills developed
- Implemented stateful logic in a stateless function using default mutable arguments
- Practiced strategic thinking in code through game theory
- Learned to build adaptable algorithms with limited data
- Reinforced test-driven development and modular programming
