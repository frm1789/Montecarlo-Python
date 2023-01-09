## Overview about Montecarlo methods

### Definition

Monte Carlo simulations are a mathematical technique that predicts the possible outcomes of an uncertain event. Many problems have no analytic solution, for example, problem that has too many possibilities in each step that are unable to follow using a closed equation. Or process that has desicions in the middle of it. 

### Examples of problems

* Forecasting elections: where what people says that will vote frequently doesn't match with the real result. fivethirtyeight.com, a popular blog, explains how it use Montecarlo to forecast the outcomes of US election. (https://fivethirtyeight.com/features/frequently-asked-questions-last-revised/)
* Forecasting stock options: pricing options by Monte Carlo simulation is amongst the most popular ways to price certain types of financial options. 

### How a Montecarlo simulation works?

Montecarlo simulation relys  on the law of large numbers: “The average of the results obtained
from a large number of trials will converge to the expected value as the number of trials approaches infinity”
Therefore, a large number of trials lead us to close as we need to the true solution.
Another valuable hint is remember the law of Inertia of large numbers: Thelarger the sample, the more stable the calculations will be. For example, the mean and variance in a large sample of numbers. 

### Montecarlo's Pros and contras 

Domain knowledge is a key element of analysis, and require to spend a large quantity of time researching on it. On the other hand, this method could be used in infinite quantity of domains.

### Steps

1. Set up the predictive model
2. Specify IV probability distributions
3. Run simulations repeatedly
4. Compute summary statistics

### Classic problem to start with

* The Monty-Hall problem: In search of a new car, the player picks a door, say 1. The game host then opens one of the other doors, say 3, to reveal a goat and offers to let the player switch from door 1 to door 2. Should the player keep their choice or switch?
* Roulette: If a player bets on a single number in the American game there is a probability of 1⁄38 that the player wins 35 times the bet, and a 37⁄38 chance that the player loses their bet.
* Stock options: Make a bet on whether a stock will go up or down
