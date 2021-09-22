# Backtesting_Investment_Strategies
The goal of this project is to create active strategies that outperform a passive buy and hold strategy for the Dow Jones index. 

Backtest means to test how an investment strategy performed over a historical period. This is how to simulate winning strategies without having to wait years. 

Strategies used - 

*Simple Momentum Strategy*

Positions:

+1: Investing in DJI (long position)
-1: Short Selling DJI (short position)
0: No position (neutral)

Strategies:
-Buy and Hold (Basic Strategy - passive): Initially Investing into DJI and do nothing (Position: +1 on any given day)

-Simple Momentum (active Strategy to be tested):
a) Investing (+1) into DJI tomorrow if today´s return was positive
b) Short selling (-1) DJI tomorrow if today´s return was negative


*Simple Contrarian Strategy*

Strategies:
-Buy and Hold (Basic Strategy): Initially Investing into DJI and do nothing (Position: +1 on all days)

-Simple Contrarian (Strategy to be tested):
a) Short Selling (-1) DJI tomorrow if today´s return was positive
b) Investing (+1) into DJI tomorrow if today´s return was negative


*Simple Moving Averages*

Strategies:
-Buy and Hold (Basic Strategy): Initially Investing into DJI and do nothing (Position: +1 on all days)

-SMA Crossover (Momentum) (Strategy to be tested):
a) Investing (+1): SMA50 > SMA200
b) Short Selling (-1): SMA50 < SMA200
