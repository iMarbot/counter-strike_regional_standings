### Roster Details<br />
Team Name: Straykids<br />
Roster: Beastman, Danejoris, Pr0mise, Reason, zebra<br />
Global Rank: [526](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [119]( ../standings_americas.md)<br />
<br />
Final Rank Value:  490.5<br />
<br />
Final Rank Value (490.5) = Starting Rank Value (509.6) + Head To Head Adjustments (-19.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.219[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 509.6
- 400 + ( ( 0.055 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 509.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     2399 | 2024-12-01 | Ascend            | L   | 0.594      | -            | -                | -                | -         |   -10.01 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            6 |     2703 | 2024-11-26 | Edgebugoffsilo    | L   | 0.561      | -            | -                | -                | -         |    -9.44 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            5 |     7067 | 2024-09-13 | MIGHT             | L   | 0.067      | -            | -                | -                | -         |    -0.34 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            4 |     7120 | 2024-09-12 | Take Flyte FRAUDS | W   | 0.060      | 0.372        | 0.000 (0.000)    | 0.004 (0.000)    | 0 (0.000) |     0.88 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            3 |     7340 | 2024-09-08 | InControl         | L   | 0.033      | -            | -                | -                | -         |    -0.35 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            2 |     7558 | 2024-09-05 | Jahsdnmasjdm v2   | W   | 0.014      | 0.372        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     0.20 | Beastman, Danejoris, Pr0mise, Reason, zebra |
|            1 |     7710 | 2024-09-03 | Lycus Empire      | W   | 0.000      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.00 | Beastman, Danejoris, Pr0mise, Reason, zebra |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($90.21)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.120 | $750.00        | $90.21          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
