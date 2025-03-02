### Roster Details<br />
Team Name: ANTARCTICA (British team)<br />
Roster: Cher1on, Ehgren, Fizzy, Igorek, joeski<br />
Global Rank: [232](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [163]( ../standings_europe.md)<br />
<br />
Final Rank Value:  686.6<br />
<br />
Final Rank Value (686.6) = Starting Rank Value (679.6) + Head To Head Adjustments (6.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.269[<sup>1</sup>](#table2)
- Bounty Collected: 0.173[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.117[<sup>2</sup>](#table1)

The average of these factors is 0.140<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 679.6
- 400 + ( ( 0.140 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 679.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      151 | 2025-02-22 | Ctrl Alt Defeat | L   | 1.000      | -            | -                | -                | -         |    -8.59 | Cher1on, Ehgren, Fizzy, Igorek, joeski |
|            5 |      159 | 2025-02-22 | 8Sins           | L   | 1.000      | -            | -                | -                | -         |    -8.07 | Cher1on, Ehgren, Fizzy, Igorek, joeski |
|            4 |      184 | 2025-02-21 | Viperio Academy | W   | 1.000      | 0.143        | 0.001 (0.000)    | 0.114 (0.016)    | 1 (1.000) |    10.88 | Cher1on, Ehgren, Fizzy, Igorek, joeski |
|            3 |     2655 | 2024-11-27 | No Pauses       | W   | 0.574      | 0.143        | 0.001 (0.000)    | 0.025 (0.002)    | 0 (0.000) |     7.06 | Fizzy, Igorek, joeski, LTH, SAVAGE     |
|            2 |     2952 | 2024-11-22 | Half Natty      | W   | 0.540      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.88 | Fizzy, Igorek, joeski, LTH, SAVAGE     |
|            1 |     3180 | 2024-11-18 | Hoes no jutsu   | W   | 0.514      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.78 | Fizzy, Igorek, joeski, LTH, SAVAGE     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($635.86)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-02-23 |      1.000 | $94.73         | $94.73          |
| 2024-11-27 |      0.574 | $942.93        | $541.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
