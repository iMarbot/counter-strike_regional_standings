### Roster Details<br />
Team Name: X7 Team<br />
Roster: aDr, gsr, pab1, R4N, sai<br />
Global Rank: [416](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [95]( ../standings_americas.md)<br />
<br />
Final Rank Value:  587.8<br />
<br />
Final Rank Value (587.8) = Starting Rank Value (627.5) + Head To Head Adjustments (-39.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.209[<sup>1</sup>](#table2)
- Bounty Collected: 0.241[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 627.5
- 400 + ( ( 0.114 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 627.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2083 | 2024-12-07 | ArtGamerz            | L   | 0.632      | -            | -                | -                | -         |   -13.29 | aDr, gsr, pab1, R4N, sai |
|           18 |     2260 | 2024-12-03 | Guará eSports        | L   | 0.607      | -            | -                | -                | -         |   -13.04 | aDr, gsr, pab1, R4N, sai |
|           17 |     2473 | 2024-11-30 | DB Peek Esports      | L   | 0.587      | -            | -                | -                | -         |    -8.98 | aDr, gsr, pab1, R4N, sai |
|           16 |     3936 | 2024-11-05 | Floripa Stars        | L   | 0.419      | -            | -                | -                | -         |    -5.91 | aDr, gsr, pab1, R4N, sai |
|           15 |     3989 | 2024-11-04 | Galorys Academy      | W   | 0.412      | 0.250        | 0.001 (0.000)    | 0.154 (0.016)    | 0 (0.000) |     6.45 | aDr, gsr, pab1, R4N, sai |
|           14 |     4130 | 2024-11-02 | FURIA Esports Female | L   | 0.398      | -            | -                | -                | -         |    -1.66 | aDr, gsr, pab1, R4N, sai |
|           13 |     4245 | 2024-10-31 | 9z Academy           | L   | 0.386      | -            | -                | -                | -         |    -5.56 | aDr, gsr, pab1, R4N, sai |
|           12 |     4623 | 2024-10-24 | Pugdesonesto         | W   | 0.340      | 0.250        | 0.000 (0.000)    | 0.098 (0.008)    | 0 (0.000) |     5.64 | aDr, gsr, pab1, R4N, sai |
|           11 |     4624 | 2024-10-24 | FURIA Esports Female | W   | 0.339      | 0.250        | 0.064 (0.005)    | 0.218 (0.018)    | 0 (0.000) |     9.50 | aDr, gsr, pab1, R4N, sai |
|           10 |     4930 | 2024-10-17 | Floripa Stars        | L   | 0.292      | -            | -                | -                | -         |    -4.09 | aDr, gsr, pab1, R4N, sai |
|            9 |     5663 | 2024-10-04 | Galorys Academy      | L   | 0.205      | -            | -                | -                | -         |    -3.02 | aDr, gsr, pab1, R4N, sai |
|            8 |     5722 | 2024-10-03 | 9z Academy           | L   | 0.199      | -            | -                | -                | -         |    -2.73 | aDr, gsr, pab1, R4N, sai |
|            7 |     6028 | 2024-09-28 | Dusty Roots          | L   | 0.165      | -            | -                | -                | -         |    -1.48 | aDr, gsr, pab1, R4N, sai |
|            6 |     6369 | 2024-09-24 | Pugdesonesto         | L   | 0.139      | -            | -                | -                | -         |    -2.15 | aDr, gsr, pab1, R4N, sai |
|            5 |     6678 | 2024-09-19 | TROPA DOS 7          | L   | 0.106      | -            | -                | -                | -         |    -2.31 | aDr, gsr, pab1, R4N, sai |
|            4 |     6818 | 2024-09-17 | FURIA Esports Female | W   | 0.092      | 0.250        | 0.064 (0.001)    | 0.218 (0.005)    | 0 (0.000) |     2.56 | aDr, gsr, pab1, R4N, sai |
|            3 |     7128 | 2024-09-12 | Yawara E-Sports      | W   | 0.059      | 0.250        | 0.002 (0.000)    | 0.448 (0.007)    | 0 (0.000) |     1.08 | aDr, gsr, pab1, R4N, sai |
|            2 |     7283 | 2024-09-09 | Galorys Academy      | L   | 0.039      | -            | -                | -                | -         |    -0.59 | aDr, gsr, pab1, R4N, sai |
|            1 |     7561 | 2024-09-05 | Floripa Stars        | L   | 0.013      | -            | -                | -                | -         |    -0.19 | aDr, gsr, pab1, R4N, sai |

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
