### Roster Details<br />
Team Name: Tak tak queota<br />
Roster: dani, fly, GaBi, showliana, tamizinha<br />
Global Rank: [321](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [63]( ../standings_americas.md)<br />
<br />
Final Rank Value:  639.3<br />
<br />
Final Rank Value (639.3) = Starting Rank Value (637.5) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.5
- 400 + ( ( 0.119 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 637.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent            | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |     1273 | 2024-12-28 | Atrix Esports       | L   | 0.781      | -            | -                | -                | -         |   -11.10 | dani, fly, GaBi, showliana, tamizinha       |
|           13 |     1274 | 2024-12-28 | Capivaras           | W   | 0.781      | 0.250        | 0.001 (0.000)    | 0.039 (0.008)    | 0 (0.000) |     7.81 | dani, fly, GaBi, showliana, tamizinha       |
|           12 |     2049 | 2024-12-07 | Fluxo Demons        | L   | 0.642      | -            | -                | -                | -         |    -6.57 | cellax, fly, paranoid, showliana, tamizinha |
|           11 |     2498 | 2024-11-30 | Fluxo Demons        | L   | 0.593      | -            | -                | -                | -         |    -6.24 | Babs, dani, GaBi, hera, showliana           |
|           10 |     2582 | 2024-11-29 | Imperial Female     | L   | 0.587      | -            | -                | -                | -         |    -1.90 | Babs, dani, GaBi, hera, showliana           |
|            9 |     4165 | 2024-11-01 | Girls Gift          | W   | 0.402      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.16 | Babs, dani, GaBi, hera, showliana           |
|            8 |     4166 | 2024-11-01 | Girls Gift          | W   | 0.402      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.21 | Babs, dani, GaBi, hera, showliana           |
|            7 |     4217 | 2024-10-31 | Alternidade Reativa | W   | 0.395      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.46 | Babs, dani, GaBi, hera, showliana           |
|            6 |     4221 | 2024-10-31 | Alternidade Reativa | W   | 0.395      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.51 | Babs, dani, GaBi, hera, showliana           |
|            5 |     4269 | 2024-10-30 | Capivaras           | W   | 0.388      | 0.143        | 0.001 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     4.11 | Babs, dani, GaBi, hera, showliana           |
|            4 |     4271 | 2024-10-30 | Capivaras           | W   | 0.388      | 0.143        | 0.001 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     4.23 | Babs, dani, GaBi, hera, showliana           |
|            3 |     4336 | 2024-10-29 | Atrix Esports       | L   | 0.382      | -            | -                | -                | -         |    -5.63 | Babs, dani, GaBi, hera, showliana           |
|            2 |     4339 | 2024-10-29 | Atrix Esports       | W   | 0.382      | 0.143        | 0.005 (0.000)    | 0.215 (0.012)    | 0 (0.000) |     6.54 | Babs, dani, GaBi, hera, showliana           |
|            1 |     6963 | 2024-09-14 | Quem sao elas       | W   | 0.081      | 0.250        | 0.001 (0.000)    | 0.066 (0.001)    | 0 (0.000) |     1.21 | dani, GaBi, hera, paranoid, tamizinha       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($919.44)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.781 | $250.00        | $195.35         |
| 2024-12-07 |      0.642 | $250.00        | $160.40         |
| 2024-12-01 |      0.601 | $836.91        | $502.96         |
| 2024-09-14 |      0.081 | $750.00        | $60.73          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
