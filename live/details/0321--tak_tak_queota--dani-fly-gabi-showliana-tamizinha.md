### Roster Details<br />
Team Name: Tak tak queota<br />
Roster: dani, fly, GaBi, showliana, tamizinha<br />
Global Rank: [321](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [65]( ../standings_americas.md)<br />
<br />
Final Rank Value:  639.2<br />
<br />
Final Rank Value (639.2) = Starting Rank Value (637.7) + Head To Head Adjustments (1.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.281[<sup>1</sup>](#table2)
- Bounty Collected: 0.192[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.7
- 400 + ( ( 0.119 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 637.7


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
|           14 |     1285 | 2024-12-28 | Atrix Esports       | L   | 0.773      | -            | -                | -                | -         |   -10.98 | dani, fly, GaBi, showliana, tamizinha       |
|           13 |     1286 | 2024-12-28 | Capivaras           | W   | 0.773      | 0.250        | 0.001 (0.000)    | 0.038 (0.007)    | 0 (0.000) |     7.76 | dani, fly, GaBi, showliana, tamizinha       |
|           12 |     2061 | 2024-12-07 | Fluxo Demons        | L   | 0.633      | -            | -                | -                | -         |    -6.50 | cellax, fly, paranoid, showliana, tamizinha |
|           11 |     2510 | 2024-11-30 | Fluxo Demons        | L   | 0.585      | -            | -                | -                | -         |    -6.17 | Babs, dani, GaBi, hera, showliana           |
|           10 |     2594 | 2024-11-29 | Imperial Female     | L   | 0.578      | -            | -                | -                | -         |    -1.89 | Babs, dani, GaBi, hera, showliana           |
|            9 |     4177 | 2024-11-01 | Girls Gift          | W   | 0.394      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.13 | Babs, dani, GaBi, hera, showliana           |
|            8 |     4178 | 2024-11-01 | Girls Gift          | W   | 0.393      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.17 | Babs, dani, GaBi, hera, showliana           |
|            7 |     4229 | 2024-10-31 | Alternidade Reativa | W   | 0.387      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.41 | Babs, dani, GaBi, hera, showliana           |
|            6 |     4233 | 2024-10-31 | Alternidade Reativa | W   | 0.387      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     2.46 | Babs, dani, GaBi, hera, showliana           |
|            5 |     4281 | 2024-10-30 | Capivaras           | W   | 0.380      | 0.143        | 0.001 (0.000)    | 0.038 (0.002)    | 0 (0.000) |     4.03 | Babs, dani, GaBi, hera, showliana           |
|            4 |     4283 | 2024-10-30 | Capivaras           | W   | 0.380      | 0.143        | 0.001 (0.000)    | 0.038 (0.002)    | 0 (0.000) |     4.15 | Babs, dani, GaBi, hera, showliana           |
|            3 |     4348 | 2024-10-29 | Atrix Esports       | L   | 0.374      | -            | -                | -                | -         |    -5.50 | Babs, dani, GaBi, hera, showliana           |
|            2 |     4351 | 2024-10-29 | Atrix Esports       | W   | 0.373      | 0.143        | 0.005 (0.000)    | 0.211 (0.011)    | 0 (0.000) |     6.40 | Babs, dani, GaBi, hera, showliana           |
|            1 |     6975 | 2024-09-14 | Quem sao elas       | W   | 0.073      | 0.250        | 0.001 (0.000)    | 0.066 (0.001)    | 0 (0.000) |     1.09 | dani, GaBi, hera, paranoid, tamizinha       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($902.34)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.773 | $250.00        | $193.30         |
| 2024-12-07 |      0.633 | $250.00        | $158.35         |
| 2024-12-01 |      0.593 | $836.91        | $496.10         |
| 2024-09-14 |      0.073 | $750.00        | $54.58          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
