### Roster Details<br />
Team Name: 5goblinz<br />
Roster: desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n<br />
Global Rank: [124](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [88]( ../standings_europe.md)<br />
<br />
Final Rank Value:  794.3<br />
<br />
Final Rank Value (794.3) = Starting Rank Value (781.4) + Head To Head Adjustments (12.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.375[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.170[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.4
- 400 + ( ( 0.191 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 781.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      482 | 2025-02-14 | Hesta                | L   | 1.000      | -            | -                | -                | -         |   -15.27 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            4 |      789 | 2025-02-07 | S8 x SoulGame        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.20 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            3 |      796 | 2025-02-07 | Eternal premium      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.215 (0.031)    | 0 (0.000) |    10.85 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            2 |     1407 | 2024-12-22 | Vezet                | W   | 0.731      | 0.143        | 0.013 (0.001)    | 0.034 (0.004)    | 1 (0.731) |     9.28 | berserk3r, br0werly, desl3bio, SEXYVOVA, Shard3n |
|            1 |     1464 | 2024-12-21 | Prius (Russian team) | W   | 0.724      | 0.143        | 0.004 (0.000)    | 0.000 (0.000)    | 1 (0.724) |     4.80 | berserk3r, br0werly, desl3bio, SEXYVOVA, Shard3n |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,103.27)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.731 | $9,713.87      | $7,103.27       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
