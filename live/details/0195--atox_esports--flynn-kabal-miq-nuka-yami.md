### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: flyNN, kabal, MiQ, nuka, yAmi<br />
Global Rank: [195](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
<br />
Final Rank Value:  713.4<br />
<br />
Final Rank Value (713.4) = Starting Rank Value (715.6) + Head To Head Adjustments (-2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.068[<sup>2</sup>](#table1)

The average of these factors is 0.158<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 715.6
- 400 + ( ( 0.158 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 715.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                          |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     4093 | 2024-11-02 | Lynn Vision Gaming      | L   | 0.410      | -            | -                | -                | -         |    -3.91 | flyNN, kabal, MiQ, nuka, yAmi   |
|           13 |     4152 | 2024-11-02 | TYLOO                   | L   | 0.405      | -            | -                | -                | -         |    -5.36 | flyNN, kabal, MiQ, nuka, yAmi   |
|           12 |     4909 | 2024-10-17 | Chinggis Warriors       | L   | 0.303      | -            | -                | -                | -         |    -2.24 | cool4st, kabal, MiQ, sk0R, yAmi |
|           11 |     4957 | 2024-10-17 | Clutch Gaming           | W   | 0.297      | 0.333        | 0.000 (0.000)    | 0.055 (0.005)    | 1 (0.297) |     2.63 | cool4st, kabal, MiQ, sk0R, yAmi |
|           10 |     5010 | 2024-10-16 | Lynn Vision Gaming      | W   | 0.292      | 0.417        | 0.017 (0.002)    | 0.368 (0.045)    | 0 (0.000) |     6.34 | flyNN, kabal, MiQ, nuka, yAmi   |
|            9 |     5022 | 2024-10-16 | Chinggis Warriors       | L   | 0.291      | -            | -                | -                | -         |    -2.12 | cool4st, kabal, MiQ, sk0R, yAmi |
|            8 |     5074 | 2024-10-15 | Chinggis Warriors       | W   | 0.285      | 0.417        | 0.016 (0.002)    | 0.567 (0.067)    | 0 (0.000) |     7.00 | flyNN, kabal, MiQ, nuka, yAmi   |
|            7 |     5086 | 2024-10-14 | The QUBE Esports        | W   | 0.283      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.283) |     1.34 | cool4st, kabal, MiQ, sk0R, yAmi |
|            6 |     5924 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.185      | -            | -                | -                | -         |    -3.46 | flyNN, kabal, MiQ, nuka, yAmi   |
|            5 |     5927 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.185      | -            | -                | -                | -         |    -3.52 | flyNN, kabal, MiQ, nuka, yAmi   |
|            4 |     6059 | 2024-09-28 | The Huns Esports        | L   | 0.172      | -            | -                | -                | -         |    -1.16 | flyNN, kabal, MiQ, nuka, yAmi   |
|            3 |     6062 | 2024-09-28 | The Huns Esports        | L   | 0.171      | -            | -                | -                | -         |    -1.17 | flyNN, kabal, MiQ, nuka, yAmi   |
|            2 |     6394 | 2024-09-24 | The QUBE Esports        | W   | 0.145      | 0.417        | 0.000 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     1.68 | flyNN, kabal, MiQ, nuka, yAmi   |
|            1 |     6401 | 2024-09-24 | The QUBE Esports        | W   | 0.145      | 0.417        | 0.000 (0.000)    | 0.010 (0.001)    | 0 (0.000) |     1.70 | flyNN, kabal, MiQ, nuka, yAmi   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,811.57)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.411 | $5,000.00      | $2,053.94       |
| 2024-10-17 |      0.303 | $2,500.00      | $757.64         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
