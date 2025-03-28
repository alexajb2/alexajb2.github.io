
## Introduction
This project involves training a reinforcement learning (RL) agent to play the game Cuphead, specifically to defeat the Root Pack boss fight. We use a YOLO object detection model to analyze the game's screen in real-time, then feed the data through a Deep-Q Network (DQN) model which learns to make optimal decisions and execute inputs based on the observed state of the game. The project aims to explore the challenges of training AI in fast-paced, visually complex environments such as video games.

## Information
### Winning Run of the AI Cuphead Agent Beating the Root Pack Boss (No Talking)
<iframe width="578" height="326" src="https://www.youtubeeducation.com/embed/LerQo3rzL9k" title="CupBot CupWins" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


### This graph plots the 50-episode moving average of rewards when learning. An episode is a singular run of the boss battle. 
![RL reward Graph](final_training_curve.png){: height="400" }

### Implementation Details of the Cuphead AI Using DQN Reinforcement Learning
<iframe width="560" height="315" src="https://www.youtube.com/embed/LJXqEdy_ocg?si=0piAyGilAccg_3GJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>