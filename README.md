# Analysis-of-a-Betting-Strategy-in-Sports
In this project we will apply probability theory to a betting scenario. This will help us to think about how to use the theory to get a better understanding of the probability of an event happening, and how to use software to help you with the related calculations.

## Problem Statement
Suppose that New York Yankees and Boston Red Sox (two American League baseball teams) are scheduled to play a best of three series. The winner of the series will be the first team that wins two of the three games. The probability that the Red Sox win a game in their home stadium is 0.6 and the probability that Yankees win their home game is 0.57. Next, suppose that you place a bet on each game played where you win $500 if the Red Sox win and you lose $520 if the Red Sox lose the game. Assume that the outcomes of the games are independent of each other. This project has 3 parts.

## Introduction to Assignment:
Overview and Rationale
This assignment applies probability theory to a sports betting scenario involving a best-of-three series between two Major League Baseball teams, the Boston Red Sox and the New York Yankees. The objective is to analyze a betting strategy by calculating the probability of the Red Sox winning the series and the corresponding net winnings. This analysis aims to provide insights into how probability theory can be leveraged to make informed betting decisions and evaluate the expected financial outcome of a given strategy.
Betting in sports inherently involves uncertainty and risk, which makes it an ideal scenario for applying probability theory. Understanding the likelihood of different outcomes allows for better decision-making and risk assessment. Additionally, simulating the series multiple times enables us to observe the distribution of possible outcomes, estimate the expected net winnings, and verify the theoretical calculations through statistical tests.

## Description of Problem Statement
The Boston Red Sox and New York Yankees are scheduled to play a best-of-three series, where the first team to win two games emerges as the winner. The series can follow two different sequences:
1.	Game 1 in Boston, Game 2 in New York, and Game 3 in Boston.
2.	Game 1 in New York, Game 2 in Boston, and Game 3  in New York.
   
The probabilities for each team winning a game are as follows:
•	The probability of the Red Sox winning at home (Boston) is 0.6.
•	The probability of the Yankees winning at home (New York) is 0.57.

The betting scenario involves the following stakes:
•	If the Red Sox win a game, the bettor wins $500.
•	If the Red Sox lose a game, the bettor loses $520.

The outcomes of the games are assumed to be independent of each other.

## Tasks to Solve
For each part, the following tasks will be completed:

1.	Calculate the Probability of Winning the Series:
o	Identify all the possible ways the Red Sox can win the series.
o	Calculate the probability of each scenario.
o	Sum up the probabilities to get the total probability of winning the series.

2.	Construct the Theoretical Probability Distribution:
o	Identify all possible net winnings.
o	Calculate the probability associated with each net winning.
o	Compute the Expected Value (E(X)) and Standard Deviation (SD(X)) of the net winnings.

3.	Simulation of Series Outcomes:
o	Simulate 10,000 series using Python to generate random outcomes for each game.
o	Calculate the net winnings for each series.
o	Estimate the expected net winnings using a 95% confidence interval.

4.	Frequency Distribution and Chi-Squared Goodness of Fit Test:
o	Construct a frequency distribution for the simulated net winnings.
o	Perform a Chi-squared goodness of fit test to compare the simulated distribution with the theoretical distribution.

5.	Evaluation of Betting Strategy:
o	Compare the expected value from the theoretical distribution with the mean of the simulated outcomes.
o	Analyze whether the confidence interval contains 

