### Roster Details<br />
Team Name: Pugdesonesto<br />
Roster: Bonecomeister, cLd, ganso, imoto, phx<br />
Global Rank: [322](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [66]( ../standings_americas.md)<br />
<br />
Final Rank Value:  638.5<br />
<br />
Final Rank Value (638.5) = Starting Rank Value (637.1) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.209[<sup>1</sup>](#table2)
- Bounty Collected: 0.257[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.1
- 400 + ( ( 0.119 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 637.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     3924 | 2024-11-05 | 9z Academy              | L   | 0.420      | -            | -                | -                | -         |    -5.83 | Bonecomeister, cLd, ganso, imoto, phx         |
|           19 |     3940 | 2024-11-05 | AMIGOS (Brazilian team) | L   | 0.419      | -            | -                | -                | -         |    -8.90 | Bonecomeister, cLd, ganso, imoto, phx         |
|           18 |     3988 | 2024-11-04 | FURIA Esports Female    | W   | 0.412      | 0.250        | 0.064 (0.007)    | 0.218 (0.022)    | 0 (0.000) |    10.98 | Bonecomeister, cLd, ganso, imoto, phx         |
|           17 |     4228 | 2024-10-31 | FURIA Esports Female    | W   | 0.387      | 0.250        | 0.064 (0.006)    | 0.218 (0.021)    | 0 (0.000) |    10.56 | Bonecomeister, cLd, ganso, imoto, phx         |
|           16 |     4417 | 2024-10-28 | VELOX Argentina         | L   | 0.366      | -            | -                | -                | -         |    -7.50 | Bonecomeister, cLd, ganso, imoto, phx         |
|           15 |     4623 | 2024-10-24 | X7 Team                 | L   | 0.340      | -            | -                | -                | -         |    -5.64 | Bonecomeister, cLd, ganso, imoto, phx         |
|           14 |     4697 | 2024-10-22 | Bad News Chickens       | W   | 0.326      | 0.143        | 0.002 (0.000)    | 0.234 (0.011)    | 0 (0.000) |     5.83 | Bonecomeister, cLd, ganso, imoto, phx         |
|           13 |     4884 | 2024-10-18 | Galorys Academy         | W   | 0.299      | 0.250        | 0.001 (0.000)    | 0.154 (0.012)    | 0 (0.000) |     4.81 | Bonecomeister, cLd, ganso, imoto, phx         |
|           12 |     4925 | 2024-10-17 | 9z Academy              | L   | 0.293      | -            | -                | -                | -         |    -4.09 | Bonecomeister, cLd, ganso, imoto, phx         |
|           11 |     4987 | 2024-10-16 | Martians Oldsters       | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.046 (0.002)    | 0 (0.000) |     2.64 | Bonecomeister, ganso, imoto, phx, Thuister    |
|           10 |     4989 | 2024-10-16 | DB Peek Esports         | W   | 0.285      | 0.143        | 0.000 (0.000)    | 0.236 (0.010)    | 0 (0.000) |     4.23 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            9 |     5056 | 2024-10-15 | SoJoga                  | W   | 0.279      | 0.143        | 0.000 (0.000)    | 0.031 (0.001)    | 0 (0.000) |     3.51 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            8 |     5060 | 2024-10-15 | Myth e-Sports           | L   | 0.278      | -            | -                | -                | -         |    -4.78 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            7 |     5717 | 2024-10-03 | Floripa Stars           | L   | 0.200      | -            | -                | -                | -         |    -2.95 | Bonecomeister, cLd, ganso, imoto, phx         |
|            6 |     5719 | 2024-10-03 | FURIA Esports Female    | L   | 0.199      | -            | -                | -                | -         |    -0.75 | Bonecomeister, cLd, ganso, imoto, phx         |
|            5 |     6369 | 2024-09-24 | X7 Team                 | W   | 0.139      | 0.250        | 0.000 (0.000)    | 0.054 (0.002)    | 0 (0.000) |     2.15 | Bonecomeister, cLd, ganso, imoto, phx         |
|            4 |     6447 | 2024-09-23 | 9z Academy              | L   | 0.132      | -            | -                | -                | -         |    -1.88 | Bonecomeister, freitas, ganso, imoto, phx     |
|            3 |     6815 | 2024-09-17 | MIBR Academy            | L   | 0.092      | -            | -                | -                | -         |    -1.30 | Bonecomeister, freitas, ganso, imoto, Striker |
|            2 |     7344 | 2024-09-08 | Só os do JOB            | W   | 0.032      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.21 | Bonecomeister, freitas, ganso, imoto, Striker |
|            1 |     7399 | 2024-09-07 | Aura (Brazilian team)   | W   | 0.025      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.17 | Bonecomeister, freitas, ganso, imoto, Striker |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($53.21)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-06 |      0.426 | $125.00        | $53.21          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
