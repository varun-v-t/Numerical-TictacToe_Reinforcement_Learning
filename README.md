# Numerical Tic Tac Toe Using Reinforcement Learning(Qlearning)

## Objective
- an RL agent that learns to play Numerical Tic-Tac-Toe with odd numbers using Q-Learning.
- The environment is playing randomly with the agent, i.e. its strategy is to put an even number randomly in an empty cell. 

## Reward
- If your agent wins the game, it gets 10 points, 
- if the environment wins, the agent loses 10 points. 
- And if the game ends in a draw, it gets 0. 
- Also, you want the agent to win in as few moves as possible, so for each move, it gets a -1 point.

## Rules of the Game:
1. The game will be played on a 3x3 grid (9 cells) using numbers from 1 to 9. Each number can be used exactly once in the entire grid.
2. There are two players: one is the Reinforcement Learning (RL) agent and other is the environment.
3. The RL agent is given odd numbers {1, 3, 5, 7, 9} and the environment is given the even numbers {2, 4, 6, 8}
4. Each of them takes a turn. The player with odd numbers always goes first.
5. At each round, a player puts one unused number on a blank spot.
6. The objective is to make 15 points in a row, column or a diagonal. The player can use the opponent's numbers in the grid to make 15.
7. The game terminates when any one of the players makes 15.

## Files
- the environment file: ‘TCGame_Env.py’
- the agent’s learning file: ‘TicTacToe_Agent.ipynb’
- Q dictionary and state action pairs Pickle Files 

## Execution Time
- The code takes around 1.5 hrs to run through all 6M Episodes in Google Colab
