### Roster Details<br />
Team Name: Undefined (American team)<br />
Roster: BeaKie, chop, CLASIA, motm, stamina<br />
Global Rank: [355](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [75]( ../standings_americas.md)<br />
<br />
Final Rank Value:  623.5<br />
<br />
Final Rank Value (623.5) = Starting Rank Value (618.8) + Head To Head Adjustments (4.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.263[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.109<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 618.8
- 400 + ( ( 0.109 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 618.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     6554 | 2024-09-21 | Akimbo Esports  | L   | 0.120      | -            | -                | -                | -         |    -1.74 | BeaKie, chop, CLASIA, motm, stamina |
|            7 |     6668 | 2024-09-19 | InControl       | W   | 0.107      | 0.372        | 0.001 (0.000)    | 0.084 (0.003)    | 0 (0.000) |     1.72 | BeaKie, chop, CLASIA, motm, stamina |
|            6 |     6799 | 2024-09-17 | MIGHT           | W   | 0.094      | 0.372        | 0.002 (0.000)    | 0.489 (0.017)    | 0 (0.000) |     2.17 | BeaKie, chop, CLASIA, motm, stamina |
|            5 |     6920 | 2024-09-15 | Final Form      | W   | 0.080      | 0.372        | 0.001 (0.000)    | 0.073 (0.002)    | 0 (0.000) |     1.23 | BeaKie, chop, CLASIA, motm, stamina |
|            4 |     7066 | 2024-09-13 | Exceritus       | W   | 0.067      | 0.372        | 0.000 (0.000)    | 0.238 (0.006)    | 0 (0.000) |     1.06 | BeaKie, chop, CLASIA, motm, stamina |
|            3 |     7169 | 2024-09-11 | Jahsdnmasjdm v2 | W   | 0.054      | 0.372        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     0.55 | BeaKie, chop, CLASIA, motm, stamina |
|            2 |     7336 | 2024-09-08 | Akimbo Esports  | L   | 0.034      | -            | -                | -                | -         |    -0.49 | BeaKie, chop, CLASIA, motm, stamina |
|            1 |     7559 | 2024-09-05 | MCS Gaming      | W   | 0.013      | 0.372        | 0.003 (0.000)    | 0.343 (0.002)    | 0 (0.000) |     0.23 | BeaKie, chop, CLASIA, motm, stamina |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($517.19)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.120 | $4,300.00      | $517.19         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
