##Pig Solitaire



#Normal Mode
Create a simulation of different types of players of Pig Solitaire. You will start with a base Player class that only rolls once per turn. Then create Player subclasses -- at least 2 -- that have different strategies.


#The Rules of Pig Solitaire

In 7 turns, you are attempting to get the highest score possible.

Each turn, you have two choices:

Roll. Roll a six-sided die. If it comes up one, your turn is over and you add nothing to your score. If it comes up two through six, you add that number to your turn total and choose again.
Hold. If you hold, you add the turn total to your score.
An example:

The first turn, I roll a 1 immediately. I receive no points.

The second turn, I roll a 5. I choose to roll again. I roll a 3, for a turn total of 8. I choose to roll again. I roll a 3, for a turn total of 11. I hold, receiving 11 points. My score is 11.

The third turn, I roll a 5 again. I choose to roll again. I roll a 6, for a turn total of 11. I choose to roll again. I roll a 4, for a turn total of 15. I decide to roll once more. I roll a 6, for a turn total of 21. I hold, receiving 21 points. My score is 32.

The fourth turn, I roll a 6. I choose to roll again. I roll a 3, for a turn total of 9. I choose to roll again. I roll a 3, for a turn total of 12. I choose to roll again. I roll a 4, for a turn total of 16. I hold, receiving 16 points. My score is 48.

The fifth turn, I roll a 6. I choose to roll again. I roll a 6, for a turn total of 12. I choose to roll again. I roll a 3, for a turn total of 15. I choose to roll again. I roll a 4, for a turn total of 19. I choose to roll again. I roll a 6, for a turn total of 25. I hold, receiving 25 points. My score is 73.

The sixth turn, I roll a 6. I choose to roll again. I roll a 1, and receive no points.

The seventh turn, I roll a 5. I choose to roll again. I roll a 1, and receive no points.

My final score is 73.

#Instructions

As each game is run, it'll show the total score for the three players. In order from top to bottom, they are the average player, cautious one, and aggressive one. 
