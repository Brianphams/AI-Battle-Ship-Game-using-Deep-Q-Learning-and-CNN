🔫 Battleship AI (CNN + DQN)
This project develops an AI agent to play the classic game of Battleship on a 5×5 grid with two randomly placed ships.

🧩 Problem
The AI must efficiently find and sink hidden ships with incomplete information.
The game presents a massive state space (~660 trillion states), making it infeasible to store or search all possibilities explicitly.

🧠 Our Approach
To tackle this, we combine:

A Convolutional Neural Network (CNN) to approximate the Q-function, avoiding the need to track every state.

A Deep Q-Learning (DQN) framework to help the AI learn from experience.

A simple hunting strategy to enhance decision-making after a hit is detected.

This hybrid method balances exploration (finding ships) and exploitation (following up hits) for better performance.

System Architect or the AI :

<img width="431" height="281" alt="BTS drawio" src="https://github.com/user-attachments/assets/fc834305-9cff-4a60-b538-e2d76dbe5345" />


Video Example of the AI :

https://github.com/user-attachments/assets/b31a9174-473f-4ab6-a28a-4cfcf372fe74



