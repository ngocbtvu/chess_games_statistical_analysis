# Chess Games Statistical Analysis

This project performes a statistical analysis of chess games data, using the chess_games.csv dataset obtained from Kaggle. For a detailed look at the code, please refer to the Jupyter Notebook file Chess_Games_Statistical_Analysis.ipynb.

## EDA

What percentage of games were won by white? How many ended in a draw?

<img src="image/eda1.png?raw=true"/>

What percentage of games are won by the player with the higher rating?

<img src="image/eda2.png?raw=true"/>

Which opening move was most frequently used in games in which black won?

<img src="image/eda3.png?raw=true"/>

What about when white won?

<img src="image/eda4.png?raw=true"/>

What is the most significant opening technique?

<img src="image/eda5.png?raw=true"/>

## Statistical Analysis
Is the white player more likely to win the game or not?

### Confidence Interval

<img src="image/test1.png?raw=true"/>

From the plot, we are 95% sure that the difference in postion of is in the interval [ .03 , .05 ], which means that the white winner is more likely to win the game, but by small amount.

## Hyphothesis Testing

- Null Hypothesis: portion of white winners <= portion of black winners [difference =< 0]
- Alternative Hypothesis: portion of white winners > portion of black winners [difference >0]

<img src="image/test2.png?raw=true"/>

Assuming the Null Hypothesis , what is the p-value?

<img src="image/test3.png?raw=true"/>

The p-value = 0 so the Null Hypothesis is rejected, which means that
the white winner is more likely to win the game, but by small amount.
