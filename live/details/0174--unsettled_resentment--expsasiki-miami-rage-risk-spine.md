### Roster Details<br />
Team Name: Unsettled Resentment<br />
Roster: expSasiKi, Miami, rage, risk, SPine<br />
Global Rank: [174](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  734.5<br />
<br />
Final Rank Value (734.5) = Starting Rank Value (730.5) + Head To Head Adjustments (4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.049[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.5
- 400 + ( ( 0.165 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 730.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |       45 | 2025-02-25 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |   -10.35 | expSasiKi, Miami, rage, risk, SPine |
|           20 |       63 | 2025-02-24 | Just Swing (Chinese team) | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.346 (0.049)    | 0 (0.000) |    11.92 | expSasiKi, Miami, rage, risk, SPine |
|           19 |       74 | 2025-02-24 | Change The Game           | L   | 1.000      | -            | -                | -                | -         |   -16.95 | expSasiKi, Miami, rage, risk, SPine |
|           18 |      552 | 2025-02-11 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -11.35 | expSasiKi, Miami, rage, risk, SPine |
|           17 |      614 | 2025-02-09 | Gods Reign                | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.407 (0.058)    | 0 (0.000) |    21.13 | expSasiKi, Miami, rage, risk, SPine |
|           16 |      620 | 2025-02-09 | Shika                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.375 (0.054)    | 0 (0.000) |     9.78 | expSasiKi, Miami, rage, risk, SPine |
|           15 |      656 | 2025-02-08 | Gods Reign                | L   | 1.000      | -            | -                | -                | -         |    -9.57 | expSasiKi, Miami, rage, risk, SPine |
|           14 |      813 | 2025-02-07 | IHC Esports               | L   | 1.000      | -            | -                | -                | -         |   -18.20 | expSasiKi, Miami, rage, risk, SPine |
|           13 |      821 | 2025-02-06 | Shika                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.375 (0.054)    | 0 (0.000) |     8.81 | expSasiKi, Miami, rage, risk, SPine |
|           12 |     1244 | 2024-12-30 | DogEvil                   | W   | 0.789      | 0.143        | 0.024 (0.003)    | 0.895 (0.101)    | 0 (0.000) |    15.90 | Miami, N1nE, rage, risk, SPine      |
|           11 |     1275 | 2024-12-29 | DogEvil                   | L   | 0.776      | -            | -                | -                | -         |    -9.14 | Miami, N1nE, rage, risk, SPine      |
|           10 |     1343 | 2024-12-27 | Lynn Vision Gaming        | L   | 0.764      | -            | -                | -                | -         |    -8.53 | Miami, N1nE, rage, risk, SPine      |
|            9 |     1348 | 2024-12-27 | Bromo                     | W   | 0.763      | 0.396        | 0.016 (0.005)    | 0.140 (0.042)    | 0 (0.000) |    11.65 | Miami, N1nE, rage, risk, SPine      |
|            8 |     4171 | 2024-11-02 | Lynn Vision Gaming        | L   | 0.395      | -            | -                | -                | -         |    -4.26 | FIOURN, Miami, rage, SPine, Zy88    |
|            7 |     4913 | 2024-10-18 | Chinggis Warriors         | W   | 0.297      | 0.417        | 0.016 (0.002)    | 0.563 (0.070)    | 0 (0.000) |     7.00 | FIOURN, Miami, rage, SPine, Zy88    |
|            6 |     5026 | 2024-10-16 | TYLOO                     | L   | 0.283      | -            | -                | -                | -         |    -4.05 | FIOURN, Miami, rage, SPine, Zy88    |
|            5 |     5088 | 2024-10-15 | The Huns Esports          | W   | 0.277      | 0.417        | 0.025 (0.003)    | 0.553 (0.064)    | 0 (0.000) |     6.56 | FIOURN, Miami, rage, SPine, Zy88    |
|            4 |     5363 | 2024-10-09 | KENLA Gaming              | W   | 0.237      | 0.417        | 0.000 (0.000)    | -                | 0 (0.000) |     0.99 | FIOURN, Miami, rage, SPine, Zy88    |
|            3 |     5369 | 2024-10-09 | KENLA Gaming              | W   | 0.237      | 0.417        | 0.000 (0.000)    | -                | 0 (0.000) |     1.00 | FIOURN, Miami, rage, SPine, Zy88    |
|            2 |     6410 | 2024-09-24 | Noobs But Diligent        | W   | 0.137      | 0.417        | -                | 0.011 (0.001)    | -         |     0.86 | FIOURN, Miami, rage, SPine, Zy88    |
|            1 |     6418 | 2024-09-24 | Noobs But Diligent        | W   | 0.137      | 0.417        | -                | 0.011 (0.001)    | -         |     0.87 | FIOURN, Miami, rage, SPine, Zy88    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,449.13)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.789 | $4,109.48      | $3,241.35       |
| 2024-11-03 |      0.403 | $3,000.00      | $1,207.78       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
