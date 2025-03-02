### Roster Details<br />
Team Name: MASONIC<br />
Roster: Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp<br />
Global Rank: [301](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [203]( ../standings_europe.md)<br />
<br />
Final Rank Value:  648.2<br />
<br />
Final Rank Value (648.2) = Starting Rank Value (663.7) + Head To Head Adjustments (-15.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.7
- 400 + ( ( 0.132 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 663.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |      102 | 2025-02-23 | K27                       | L   | 1.000      | -            | -                | -                | -         |    -9.31 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           21 |      139 | 2025-02-22 | Chimera Esports           | W   | 1.000      | 0.143        | 0.025 (0.004)    | 0.595 (0.085)    | 0 (0.000) |    24.07 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           20 |      998 | 2025-02-04 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -20.79 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           19 |     2404 | 2024-12-01 | FORZE Reload              | L   | 0.600      | -            | -                | -                | -         |    -4.21 | Botman, Bukhavez, Frøslev, Noruyp, Skejs            |
|           18 |     2413 | 2024-12-01 | XI Esport                 | W   | 0.600      | 0.143        | 0.001 (0.000)    | 0.287 (0.025)    | 0 (0.000) |    10.73 | Botman, Bukhavez, Frøslev, Noruyp, Skejs            |
|           17 |     3147 | 2024-11-19 | HyperioN                  | W   | 0.520      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.30 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           16 |     3595 | 2024-11-11 | Copenhagen Wolves Academy | W   | 0.467      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.79 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           15 |     3607 | 2024-11-11 | WOPA Esport               | L   | 0.466      | -            | -                | -                | -         |    -3.40 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           14 |     3973 | 2024-11-04 | Astralis Talent           | L   | 0.421      | -            | -                | -                | -         |    -4.83 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           13 |     3991 | 2024-11-04 | XI Esport                 | L   | 0.420      | -            | -                | -                | -         |    -6.17 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           12 |     4113 | 2024-11-02 | Preasy Esport             | L   | 0.407      | -            | -                | -                | -         |    -4.19 | Botman, FrekaFiskeNN, Frøslev, NoProblemGuy, Noruyp |
|           11 |     4135 | 2024-11-02 | LEO Esports               | W   | 0.406      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.406) |     2.43 | Botman, FrekaFiskeNN, Frøslev, NoProblemGuy, Noruyp |
|           10 |     4425 | 2024-10-28 | Denial (Danish team)      | W   | 0.373      | 0.143        | 0.001 (0.000)    | 0.106 (0.006)    | 0 (0.000) |     5.89 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            9 |     4431 | 2024-10-28 | Preasy Esport             | L   | 0.373      | -            | -                | -                | -         |    -3.78 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            8 |     4718 | 2024-10-21 | XI Esport                 | L   | 0.327      | -            | -                | -                | -         |    -7.07 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            7 |     5466 | 2024-10-07 | Denial (Danish team)      | L   | 0.233      | -            | -                | -                | -         |    -3.79 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            6 |     5898 | 2024-09-30 | WOPA Esport               | W   | 0.187      | 0.143        | 0.031 (0.001)    | 0.785 (0.021)    | 0 (0.000) |     4.36 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            5 |     5911 | 2024-09-30 | Copenhagen Wolves Academy | W   | 0.186      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.10 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            4 |     6444 | 2024-09-23 | XI Esport                 | W   | 0.140      | 0.143        | 0.001 (0.000)    | 0.287 (0.006)    | 0 (0.000) |     2.36 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            3 |     6457 | 2024-09-23 | XI Esport                 | L   | 0.140      | -            | -                | -                | -         |    -3.11 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            2 |     6879 | 2024-09-16 | Astralis Talent           | L   | 0.093      | -            | -                | -                | -         |    -1.01 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            1 |     6890 | 2024-09-16 | Preasy Esport             | L   | 0.092      | -            | -                | -                | -         |    -0.89 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($192.01)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-02 |      0.407 | $471.67        | $192.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
