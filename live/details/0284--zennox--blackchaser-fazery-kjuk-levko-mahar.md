### Roster Details<br />
Team Name: ZennoX<br />
Roster: Blackchaser, fazery, kjuK, Levko, MahaR<br />
Global Rank: [284](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [191]( ../standings_europe.md)<br />
<br />
Final Rank Value:  659.3<br />
<br />
Final Rank Value (659.3) = Starting Rank Value (639.2) + Head To Head Adjustments (20.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.238[<sup>1</sup>](#table2)
- Bounty Collected: 0.222[<sup>2</sup>](#table1)
- Opponent Network: 0.019[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.2
- 400 + ( ( 0.120 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 639.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1932 | 2024-12-10 | XPERION NXT     | L   | 0.652      | -            | -                | -                | -         |   -10.26 | Blackchaser, fazery, kjuK, Levko, MahaR |
|            4 |     1990 | 2024-12-08 | Rhyno Esports   | W   | 0.639      | 0.333        | 0.013 (0.003)    | 0.441 (0.094)    | 0 (0.000) |    15.60 | Blackchaser, fazery, kjuK, Levko, MahaR |
|            3 |     2278 | 2024-12-03 | Chimera Esports | L   | 0.605      | -            | -                | -                | -         |    -4.18 | Blackchaser, fazery, kjuK, Levko, MahaR |
|            2 |     2506 | 2024-11-30 | GardenGarage    | W   | 0.585      | 0.333        | 0.001 (0.000)    | 0.408 (0.080)    | 0 (0.000) |    11.73 | Blackchaser, fazery, kjuK, Levko, MahaR |
|            1 |     2639 | 2024-11-28 | Fragmatic       | W   | 0.572      | 0.333        | 0.000 (0.000)    | 0.068 (0.013)    | 0 (0.000) |     7.19 | Blackchaser, fazery, kjuK, Levko, MahaR |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($205.21)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.684 | $300.00        | $205.21         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
