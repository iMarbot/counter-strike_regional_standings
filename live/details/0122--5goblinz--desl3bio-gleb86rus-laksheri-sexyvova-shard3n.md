### Roster Details<br />
Team Name: 5goblinz<br />
Roster: desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n<br />
Global Rank: [122](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [89]( ../standings_europe.md)<br />
<br />
Final Rank Value:  794.2<br />
<br />
Final Rank Value (794.2) = Starting Rank Value (781.2) + Head To Head Adjustments (13.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.374[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.172[<sup>2</sup>](#table1)

The average of these factors is 0.191<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 781.2
- 400 + ( ( 0.191 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 781.2


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
|            5 |      470 | 2025-02-14 | Hesta                | L   | 1.000      | -            | -                | -                | -         |   -15.26 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            4 |      777 | 2025-02-07 | S8 x SoulGame        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     3.21 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            3 |      784 | 2025-02-07 | Eternal premium      | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.215 (0.031)    | 0 (0.000) |    10.81 | desl3bio, gleb86rus, LAKSHERi, SEXYVOVA, Shard3n |
|            2 |     1395 | 2024-12-22 | Vezet                | W   | 0.739      | 0.143        | 0.013 (0.001)    | 0.034 (0.004)    | 1 (0.739) |     9.38 | berserk3r, br0werly, desl3bio, SEXYVOVA, Shard3n |
|            1 |     1452 | 2024-12-21 | Prius (Russian team) | W   | 0.733      | 0.143        | 0.004 (0.000)    | 0.000 (0.000)    | 1 (0.733) |     4.85 | berserk3r, br0werly, desl3bio, SEXYVOVA, Shard3n |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,182.87)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.739 | $9,713.87      | $7,182.87       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
