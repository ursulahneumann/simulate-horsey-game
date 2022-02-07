# Simulate Horsey Game
A just-for-fun project that simulates our family's horsey game of chance.  A blog article about this project can be found [here](https://www.ursulahneumann.com/blog/horsey-game-probabilities/)

## Table of Contents
1) Project Motivation <br>
2) File Description <br>
3) Libraries Required <br>
4) Summary of Results <br>
5) Licensing and Acknowledgements <br>

## Project Motivation
Everybody claims to have witnessed horsey 2 (one of the long shots) winning a round at one time or another.  I wanted to calculate the odds of each horse winning as well as the distribution of pot sizes.

## File Descriptions

**README.md** - This file, describing the contents of this repo

**.gitignore** - The gitignore file ignoring mainly photos and images to be used in the blogpost.

**simulate_horsey_game.ipynb** - Jupyter Notebook file containing simulation and visualizations.

## Libraries Required
numpy, pandas, matplotlib

## Summary of Results
Horse #7 is the most likely to be scratched and horse 2 (and 12) is the least likely.  Interestingly, as you move to each new scratch, the probability of choosing a 7 decreases slightly, and the probability of choosing a 2 increases slightly. This is because each successive scratch must be different than ones previous chosen, so if a 7 is chosen as the first scratch, it cannot be chosen for the other scratches.

Despite the higher chances of a 7 being chosen as a scratch, #7 still remains the most likely horse to reach the end with a 16% chance of winning, while horse #2 has 0.7% chance of winning.

The minimum pot size is $2.1 set by the fact that all the scratch cards in people’s hand get paid before the round begins. The median pot size is $4.80, and with the histogram being slightly right-skewed, with the highest pot size being $13.55.

## Licenses and Acknowledgements
Thanks to my family for prompting the idea for this project!