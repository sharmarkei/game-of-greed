# Game of Greed

**Author**: Sharmarke Ibrahim

**Version**: 1.0.0

## Overview
The Game of Greed aka Ten Thousand aka Zilch is a game of luck. You roll six dice and add up their values. The player who gets to 10,000 points first wins. At the start of the game you roll your six dice then calculate the points you rolled. Ones have a value of 100. Fives have a value of 50. The other numbers are worth nothing until you get to 3 of them. 

Three of kind are equal to 100 x the face value. More than three of the same number adds an additional tripple value for each aditional over three. Ex: (3,3,3) would yeild 300 points, (3,3,3,3) yeilds 600 points, (3,3,3,3,3) yeilds 900 points, and if every dice is a 3 it would yeild 1200 points!

A straight is worth 1500 points. 

Three pairs are worth 1500 points. Ex: (2,2,3,3,4,4)

## Getting Started
Follow the prompts to play the game!

## Functionality/Architecture
This game is using 'dice rolls', arguements in the form of tuples. The dice rolls are between 1 and 6 individually and there are six dice at the start of the game. An instance of a GameOfGreed is created upon game start (invoking GameOfGreed class object method play()).


Application should allow user to set aside dice each roll
Application should allow “banking” current score or rolling again.
Application should keep track of total score
Application should keep track of current round


## Change Log
Mon Dec 09 2019 20:40 Created Welcome and calculations.