### Roster Details<br />
Team Name: Unsettled Resentment<br />
Roster: expSasiKi, Miami, rage, risk, SPine<br />
Global Rank: [175](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
<br />
Final Rank Value:  734.7<br />
<br />
Final Rank Value (734.7) = Starting Rank Value (730.3) + Head To Head Adjustments (4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.050[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 730.3
- 400 + ( ( 0.165 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 730.3


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
|           21 |       30 | 2025-02-25 | DogEvil                   | L   | 1.000      | -            | -                | -                | -         |   -10.33 | expSasiKi, Miami, rage, risk, SPine |
|           20 |       48 | 2025-02-24 | Just Swing (Chinese team) | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.351 (0.050)    | 0 (0.000) |    11.92 | expSasiKi, Miami, rage, risk, SPine |
|           19 |       59 | 2025-02-24 | Change The Game           | L   | 1.000      | -            | -                | -                | -         |   -17.00 | expSasiKi, Miami, rage, risk, SPine |
|           18 |      540 | 2025-02-11 | Lynn Vision Gaming        | L   | 1.000      | -            | -                | -                | -         |   -11.32 | expSasiKi, Miami, rage, risk, SPine |
|           17 |      602 | 2025-02-09 | Gods Reign                | W   | 1.000      | 0.143        | 0.018 (0.003)    | 0.412 (0.059)    | 0 (0.000) |    21.05 | expSasiKi, Miami, rage, risk, SPine |
|           16 |      608 | 2025-02-09 | Shika                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.374 (0.053)    | 0 (0.000) |     9.77 | expSasiKi, Miami, rage, risk, SPine |
|           15 |      644 | 2025-02-08 | Gods Reign                | L   | 1.000      | -            | -                | -                | -         |    -9.65 | expSasiKi, Miami, rage, risk, SPine |
|           14 |      801 | 2025-02-07 | IHC Esports               | L   | 1.000      | -            | -                | -                | -         |   -18.21 | expSasiKi, Miami, rage, risk, SPine |
|           13 |      809 | 2025-02-06 | Shika                     | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.374 (0.053)    | 0 (0.000) |     8.80 | expSasiKi, Miami, rage, risk, SPine |
|           12 |     1232 | 2024-12-30 | DogEvil                   | W   | 0.797      | 0.143        | 0.024 (0.003)    | 0.896 (0.102)    | 0 (0.000) |    16.08 | Miami, N1nE, rage, risk, SPine      |
|           11 |     1263 | 2024-12-29 | DogEvil                   | L   | 0.784      | -            | -                | -                | -         |    -9.23 | Miami, N1nE, rage, risk, SPine      |
|           10 |     1331 | 2024-12-27 | Lynn Vision Gaming        | L   | 0.772      | -            | -                | -                | -         |    -8.60 | Miami, N1nE, rage, risk, SPine      |
|            9 |     1336 | 2024-12-27 | Bromo                     | W   | 0.771      | 0.396        | 0.016 (0.005)    | 0.141 (0.043)    | 0 (0.000) |    11.76 | Miami, N1nE, rage, risk, SPine      |
|            8 |     4159 | 2024-11-02 | Lynn Vision Gaming        | L   | 0.404      | -            | -                | -                | -         |    -4.33 | FIOURN, Miami, rage, SPine, Zy88    |
|            7 |     4901 | 2024-10-18 | Chinggis Warriors         | W   | 0.305      | 0.417        | 0.016 (0.002)    | 0.567 (0.072)    | 0 (0.000) |     7.23 | FIOURN, Miami, rage, SPine, Zy88    |
|            6 |     5014 | 2024-10-16 | TYLOO                     | L   | 0.291      | -            | -                | -                | -         |    -4.16 | FIOURN, Miami, rage, SPine, Zy88    |
|            5 |     5076 | 2024-10-15 | The Huns Esports          | W   | 0.285      | 0.417        | 0.025 (0.003)    | 0.557 (0.066)    | 0 (0.000) |     6.76 | FIOURN, Miami, rage, SPine, Zy88    |
|            4 |     5351 | 2024-10-09 | KENLA Gaming              | W   | 0.245      | 0.417        | 0.000 (0.000)    | -                | 0 (0.000) |     1.02 | FIOURN, Miami, rage, SPine, Zy88    |
|            3 |     5357 | 2024-10-09 | KENLA Gaming              | W   | 0.245      | 0.417        | 0.000 (0.000)    | -                | 0 (0.000) |     1.03 | FIOURN, Miami, rage, SPine, Zy88    |
|            2 |     6398 | 2024-09-24 | Noobs But Diligent        | W   | 0.145      | 0.417        | -                | 0.011 (0.001)    | -         |     0.91 | FIOURN, Miami, rage, SPine, Zy88    |
|            1 |     6406 | 2024-09-24 | Noobs But Diligent        | W   | 0.145      | 0.417        | -                | 0.011 (0.001)    | -         |     0.92 | FIOURN, Miami, rage, SPine, Zy88    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,507.39)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-30 |      0.797 | $4,109.48      | $3,275.02       |
| 2024-11-03 |      0.411 | $3,000.00      | $1,232.36       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
