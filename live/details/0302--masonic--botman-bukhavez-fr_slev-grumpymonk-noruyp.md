### Roster Details<br />
Team Name: MASONIC<br />
Roster: Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp<br />
Global Rank: [302](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [202]( ../standings_europe.md)<br />
<br />
Final Rank Value:  648.1<br />
<br />
Final Rank Value (648.1) = Starting Rank Value (663.5) + Head To Head Adjustments (-15.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.231[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.047[<sup>2</sup>](#table1)

The average of these factors is 0.132<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 663.5
- 400 + ( ( 0.132 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 663.5


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
|           22 |      117 | 2025-02-23 | K27                       | L   | 1.000      | -            | -                | -                | -         |    -9.30 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           21 |      154 | 2025-02-22 | Chimera Esports           | W   | 1.000      | 0.143        | 0.026 (0.004)    | 0.586 (0.084)    | 0 (0.000) |    24.00 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           20 |     1010 | 2025-02-04 | Johnny Speeds             | L   | 1.000      | -            | -                | -                | -         |   -20.78 | Botman, Bukhavez, Frøslev, grumpyMonk, Noruyp       |
|           19 |     2421 | 2024-12-01 | FORZE Reload              | L   | 0.592      | -            | -                | -                | -         |    -4.18 | Botman, Bukhavez, Frøslev, Noruyp, Skejs            |
|           18 |     2425 | 2024-12-01 | XI Esport                 | W   | 0.592      | 0.143        | 0.001 (0.000)    | 0.282 (0.024)    | 0 (0.000) |    10.56 | Botman, Bukhavez, Frøslev, Noruyp, Skejs            |
|           17 |     3159 | 2024-11-19 | HyperioN                  | W   | 0.512      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.24 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           16 |     3607 | 2024-11-11 | Copenhagen Wolves Academy | W   | 0.459      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.74 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           15 |     3619 | 2024-11-11 | WOPA Esport               | L   | 0.458      | -            | -                | -                | -         |    -3.36 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           14 |     3985 | 2024-11-04 | Astralis Talent           | L   | 0.412      | -            | -                | -                | -         |    -4.74 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           13 |     4003 | 2024-11-04 | XI Esport                 | L   | 0.412      | -            | -                | -                | -         |    -6.06 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|           12 |     4125 | 2024-11-02 | Preasy Esport             | L   | 0.399      | -            | -                | -                | -         |    -4.12 | Botman, FrekaFiskeNN, Frøslev, NoProblemGuy, Noruyp |
|           11 |     4147 | 2024-11-02 | LEO Esports               | W   | 0.398      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.398) |     2.38 | Botman, FrekaFiskeNN, Frøslev, NoProblemGuy, Noruyp |
|           10 |     4437 | 2024-10-28 | Denial (Danish team)      | W   | 0.365      | 0.143        | 0.001 (0.000)    | 0.104 (0.005)    | 0 (0.000) |     5.75 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            9 |     4443 | 2024-10-28 | Preasy Esport             | L   | 0.365      | -            | -                | -                | -         |    -3.71 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            8 |     4730 | 2024-10-21 | XI Esport                 | L   | 0.318      | -            | -                | -                | -         |    -6.91 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            7 |     5478 | 2024-10-07 | Denial (Danish team)      | L   | 0.225      | -            | -                | -                | -         |    -3.66 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            6 |     5910 | 2024-09-30 | WOPA Esport               | W   | 0.178      | 0.143        | 0.032 (0.001)    | 0.777 (0.020)    | 0 (0.000) |     4.16 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            5 |     5923 | 2024-09-30 | Copenhagen Wolves Academy | W   | 0.178      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.05 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            4 |     6456 | 2024-09-23 | XI Esport                 | W   | 0.132      | 0.143        | 0.001 (0.000)    | 0.282 (0.005)    | 0 (0.000) |     2.22 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            3 |     6469 | 2024-09-23 | XI Esport                 | L   | 0.132      | -            | -                | -                | -         |    -2.93 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            2 |     6891 | 2024-09-16 | Astralis Talent           | L   | 0.085      | -            | -                | -                | -         |    -0.92 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |
|            1 |     6902 | 2024-09-16 | Preasy Esport             | L   | 0.084      | -            | -                | -                | -         |    -0.82 | Botman, Frøslev, NoProblemGuy, Noruyp, Patti        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($188.14)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-02 |      0.399 | $471.67        | $188.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
