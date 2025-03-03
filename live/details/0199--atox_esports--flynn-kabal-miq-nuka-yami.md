### Roster Details<br />
Team Name: ATOX Esports<br />
Roster: flyNN, kabal, MiQ, nuka, yAmi<br />
Global Rank: [199](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [21]( ../standings_asia.md)<br />
<br />
Final Rank Value:  712.4<br />
<br />
Final Rank Value (712.4) = Starting Rank Value (714.7) + Head To Head Adjustments (-2.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.227[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.066[<sup>2</sup>](#table1)

The average of these factors is 0.157<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 714.7
- 400 + ( ( 0.157 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 714.7


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
|           14 |     4105 | 2024-11-02 | Lynn Vision Gaming      | L   | 0.402      | -            | -                | -                | -         |    -3.84 | flyNN, kabal, MiQ, nuka, yAmi   |
|           13 |     4164 | 2024-11-02 | TYLOO                   | L   | 0.396      | -            | -                | -                | -         |    -5.25 | flyNN, kabal, MiQ, nuka, yAmi   |
|           12 |     4921 | 2024-10-17 | Chinggis Warriors       | L   | 0.295      | -            | -                | -                | -         |    -2.20 | cool4st, kabal, MiQ, sk0R, yAmi |
|           11 |     4968 | 2024-10-17 | Clutch Gaming           | W   | 0.289      | 0.333        | 0.000 (0.000)    | 0.054 (0.005)    | 1 (0.289) |     2.55 | cool4st, kabal, MiQ, sk0R, yAmi |
|           10 |     5022 | 2024-10-16 | Lynn Vision Gaming      | W   | 0.283      | 0.417        | 0.017 (0.002)    | 0.365 (0.043)    | 0 (0.000) |     6.16 | flyNN, kabal, MiQ, nuka, yAmi   |
|            9 |     5034 | 2024-10-16 | Chinggis Warriors       | L   | 0.282      | -            | -                | -                | -         |    -2.08 | cool4st, kabal, MiQ, sk0R, yAmi |
|            8 |     5086 | 2024-10-15 | Chinggis Warriors       | W   | 0.277      | 0.417        | 0.016 (0.002)    | 0.563 (0.065)    | 0 (0.000) |     6.77 | flyNN, kabal, MiQ, nuka, yAmi   |
|            7 |     5098 | 2024-10-14 | The QUBE Esports        | W   | 0.275      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.275) |     1.30 | cool4st, kabal, MiQ, sk0R, yAmi |
|            6 |     5936 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.177      | -            | -                | -                | -         |    -3.31 | flyNN, kabal, MiQ, nuka, yAmi   |
|            5 |     5939 | 2024-09-30 | Nomads (Mongolian team) | L   | 0.177      | -            | -                | -                | -         |    -3.36 | flyNN, kabal, MiQ, nuka, yAmi   |
|            4 |     6071 | 2024-09-28 | The Huns Esports        | L   | 0.163      | -            | -                | -                | -         |    -1.11 | flyNN, kabal, MiQ, nuka, yAmi   |
|            3 |     6074 | 2024-09-28 | The Huns Esports        | L   | 0.163      | -            | -                | -                | -         |    -1.12 | flyNN, kabal, MiQ, nuka, yAmi   |
|            2 |     6406 | 2024-09-24 | The QUBE Esports        | W   | 0.137      | 0.417        | 0.000 (0.000)    | 0.009 (0.001)    | 0 (0.000) |     1.59 | flyNN, kabal, MiQ, nuka, yAmi   |
|            1 |     6413 | 2024-09-24 | The QUBE Esports        | W   | 0.137      | 0.417        | 0.000 (0.000)    | 0.009 (0.001)    | 0 (0.000) |     1.60 | flyNN, kabal, MiQ, nuka, yAmi   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,750.12)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-03 |      0.403 | $5,000.00      | $2,012.96       |
| 2024-10-17 |      0.295 | $2,500.00      | $737.15         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
