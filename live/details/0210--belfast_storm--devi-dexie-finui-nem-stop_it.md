### Roster Details<br />
Team Name: Belfast Storm<br />
Roster: devi, dexie, Finui, Nem, Stop_it<br />
Global Rank: [210](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [150]( ../standings_europe.md)<br />
<br />
Final Rank Value:  706.8<br />
<br />
Final Rank Value (706.8) = Starting Rank Value (709.6) + Head To Head Adjustments (-2.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.216[<sup>2</sup>](#table1)
- Opponent Network: 0.012[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.6
- 400 + ( ( 0.155 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 709.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      166 | 2025-02-22 | DUSTY                      | L   | 1.000      | -            | -                | -                | -         |   -12.13 | devi, dexie, Finui, Nem, Stop_it    |
|           17 |      172 | 2025-02-22 | ALASKA                     | L   | 1.000      | -            | -                | -                | -         |    -9.40 | devi, dexie, Finui, Nem, Stop_it    |
|           16 |      197 | 2025-02-21 | The Last Resort            | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.159 (0.023)    | 1 (1.000) |    14.69 | devi, dexie, Finui, Nem, Stop_it    |
|           15 |     1421 | 2024-12-22 | NEVERMORE (Ukrainian team) | L   | 0.730      | -            | -                | -                | -         |    -9.51 | devi, dexie, Finui, PALM1, tsutskam |
|           14 |     1428 | 2024-12-22 | Doge Soldiers              | L   | 0.730      | -            | -                | -                | -         |   -18.06 | devi, dexie, Finui, PALM1, tsutskam |
|           13 |     2098 | 2024-12-07 | ALASKA                     | L   | 0.631      | -            | -                | -                | -         |    -4.78 | devi, dexie, Finui, Nem, tsutskam   |
|           12 |     3087 | 2024-11-20 | 8Sins                      | W   | 0.519      | 0.143        | 0.005 (0.000)    | 0.233 (0.017)    | 0 (0.000) |    11.77 | devi, dexie, Finui, Nem, tsutskam   |
|           11 |     3433 | 2024-11-14 | The Last Resort            | W   | 0.479      | 0.143        | 0.001 (0.000)    | 0.159 (0.011)    | 0 (0.000) |     7.44 | devi, dexie, Finui, Nem, tsutskam   |
|           10 |     3836 | 2024-11-07 | Dreams To Legends          | W   | 0.432      | 0.143        | 0.000 (0.000)    | 0.081 (0.005)    | 0 (0.000) |     4.81 | devi, dexie, Finui, Nem, tsutskam   |
|            9 |     3877 | 2024-11-06 | 8Sins                      | L   | 0.426      | -            | -                | -                | -         |    -3.42 | devi, dexie, Finui, Nem, tsutskam   |
|            8 |     3983 | 2024-11-04 | Glitchtech Esports         | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.086 (0.005)    | 0 (0.000) |     3.35 | devi, dexie, Finui, Nem, tsutskam   |
|            7 |     4247 | 2024-10-31 | TRAXXXMANIA                | W   | 0.386      | 0.143        | 0.000 (0.000)    | 0.126 (0.007)    | 0 (0.000) |     5.51 | devi, dexie, Finui, Nem, tsutskam   |
|            6 |     4293 | 2024-10-30 | ALASKA                     | W   | 0.379      | 0.143        | 0.031 (0.002)    | 0.867 (0.047)    | 0 (0.000) |    10.69 | devi, dexie, Finui, Nem, tsutskam   |
|            5 |     4569 | 2024-10-26 | TRAXXXMANIA                | L   | 0.349      | -            | -                | -                | -         |    -6.23 | devi, dexie, Finui, Nem, tsutskam   |
|            4 |     4594 | 2024-10-25 | ALASKA                     | L   | 0.345      | -            | -                | -                | -         |    -1.16 | devi, dexie, Finui, Nem, tsutskam   |
|            3 |     5057 | 2024-10-15 | Annex Esports              | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.058 (0.002)    | 0 (0.000) |     3.44 | devi, dexie, Finui, Nem, tsutskam   |
|            2 |     5291 | 2024-10-10 | The Last Resort            | W   | 0.245      | 0.143        | 0.001 (0.000)    | 0.159 (0.006)    | 0 (0.000) |     4.05 | devi, dexie, Finui, Nem, tsutskam   |
|            1 |     5419 | 2024-10-08 | ROYALS                     | L   | 0.232      | -            | -                | -                | -         |    -3.81 | devi, dexie, Finui, Nem, tsutskam   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($737.96)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-12-07 |      0.631 | $1,019.42      | $643.23         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
