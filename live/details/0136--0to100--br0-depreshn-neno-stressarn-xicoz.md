### Roster Details<br />
Team Name: 0to100<br />
Roster: br0, DEPRESHN, NENO, stressarN, xicoz<br />
Global Rank: [136](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [99]( ../standings_europe.md)<br />
<br />
Final Rank Value:  777.5<br />
<br />
Final Rank Value (777.5) = Starting Rank Value (752.1) + Head To Head Adjustments (25.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.315[<sup>1</sup>](#table2)
- Bounty Collected: 0.236[<sup>2</sup>](#table1)
- Opponent Network: 0.037[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.176<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 752.1
- 400 + ( ( 0.176 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 752.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     1304 | 2024-12-28 | NEVERMORE (Ukrainian team)                | L   | 0.778      | -            | -                | -                | -         |   -11.49 | br0, DEPRESHN, NENO, stressarN, xicoz    |
|            8 |     1453 | 2024-12-21 | Copenhagen Wolves (American organization) | W   | 0.733      | 0.303        | 0.016 (0.003)    | 1.000 (0.222)    | 0 (0.000) |    14.90 | br0, DEPRESHN, NENO, stressarN, xicoz    |
|            7 |     1476 | 2024-12-21 | Dragon Esports Club                       | W   | 0.731      | 0.303        | 0.007 (0.001)    | 0.312 (0.069)    | 0 (0.000) |     8.43 | br0, DEPRESHN, NENO, stressarN, xicoz    |
|            6 |     1973 | 2024-12-08 | RUSH B (Russian team)                     | L   | 0.647      | -            | -                | -                | -         |    -6.70 | DEPRESHN, meztal, NENO, stressarN, xicoz |
|            5 |     1975 | 2024-12-08 | Nuclear TigeRES                           | W   | 0.647      | 0.143        | 0.004 (0.000)    | 0.586 (0.054)    | 0 (0.000) |    11.05 | DEPRESHN, meztal, NENO, stressarN, xicoz |
|            4 |     1982 | 2024-12-08 | RUSTEC                                    | W   | 0.647      | 0.143        | 0.000 (0.000)    | 0.217 (0.020)    | 0 (0.000) |     5.19 | DEPRESHN, meztal, NENO, stressarN, xicoz |
|            3 |     3225 | 2024-11-17 | Zero Tenacity                             | L   | 0.507      | -            | -                | -                | -         |    -5.31 | dan1, DEPRESHN, NENO, SENER1, stressarN  |
|            2 |     3242 | 2024-11-17 | Juggernauts                               | W   | 0.506      | 0.143        | 0.003 (0.000)    | 0.030 (0.002)    | 1 (0.506) |     5.81 | dan1, DEPRESHN, NENO, SENER1, stressarN  |
|            1 |     3334 | 2024-11-16 | MADNESS (Kosovar team)                    | W   | 0.498      | 0.143        | 0.003 (0.000)    | 0.019 (0.001)    | 1 (0.498) |     3.60 | dan1, DEPRESHN, NENO, SENER1, stressarN  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,260.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.780 | $500.00        | $389.83         |
| 2024-11-17 |      0.507 | $3,690.62      | $1,870.17       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
