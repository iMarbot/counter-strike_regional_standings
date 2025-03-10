### Roster Details<br />
Team Name: Boo Bees<br />
Roster: avo, Creative28, Graceyy, ihatejess, Psycho<br />
Global Rank: [345](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [55]( ../standings_asia.md)<br />
<br />
Final Rank Value:  627.1<br />
<br />
Final Rank Value (627.1) = Starting Rank Value (650.8) + Head To Head Adjustments (-23.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.189[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.054[<sup>2</sup>](#table1)

The average of these factors is 0.125<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 650.8
- 400 + ( ( 0.125 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 650.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     1309 | 2024-12-28 | Kitsune Kenko                | L   | 0.771      | -            | -                | -                | -         |   -11.26 | avo, Creative28, Graceyy, ihatejess, Psycho |
|            7 |     2099 | 2024-12-07 | Kitsune Kenko                | L   | 0.631      | -            | -                | -                | -         |    -9.49 | avo, Creative28, leafy, Psycho, queenza     |
|            6 |     2539 | 2024-11-30 | Kitsune Kenko                | W   | 0.584      | 0.233        | 0.004 (0.000)    | 0.117 (0.016)    | 0 (0.000) |     9.82 | avo, Creative28, ihatejess, leafy, queenza  |
|            5 |     3562 | 2024-11-12 | Team Australia (Female team) | L   | 0.464      | -            | -                | -                | -         |    -6.16 | avo, Graceyy, ihatejess, M3gzz, Pixar       |
|            4 |     3577 | 2024-11-12 | Team Norway (Female team)    | W   | 0.463      | 0.557        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.463) |     2.95 | avo, Graceyy, ihatejess, M3gzz, Pixar       |
|            3 |     3641 | 2024-11-11 | YUME                         | L   | 0.456      | -            | -                | -                | -         |    -8.84 | avo, Graceyy, ihatejess, M3gzz, Pixar       |
|            2 |     7002 | 2024-09-14 | Kitsune Kenko                | L   | 0.071      | -            | -                | -                | -         |    -1.14 | avo, Graceyy, ihatejess, leafy, queenza     |
|            1 |     7018 | 2024-09-14 | Diamond Divas                | W   | 0.070      | 0.233        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.44 | avo, Graceyy, ihatejess, leafy, queenza     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($425.37)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-28 |      0.771 | $150.00        | $115.64         |
| 2024-12-07 |      0.631 | $150.00        | $94.65          |
| 2024-11-30 |      0.584 | $350.00        | $204.41         |
| 2024-09-14 |      0.071 | $150.00        | $10.68          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
