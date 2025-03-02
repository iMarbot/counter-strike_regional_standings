### Roster Details<br />
Team Name: Make Your Mind<br />
Roster: HorizoN, karv3r, Rulik, S0ph3R, s1rena<br />
Global Rank: [144](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [104]( ../standings_europe.md)<br />
<br />
Final Rank Value:  769.1<br />
<br />
Final Rank Value (769.1) = Starting Rank Value (706.4) + Head To Head Adjustments (62.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.350[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 706.4
- 400 + ( ( 0.153 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 706.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1743 | 2024-12-13 | Undone               | W   | 0.682      | 0.143        | 0.002 (0.000)    | 0.286 (0.028)    | 0 (0.000) |    11.38 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|           11 |     1746 | 2024-12-13 | Final Form           | W   | 0.682      | 0.143        | 0.001 (0.000)    | 0.076 (0.007)    | 0 (0.000) |     6.81 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|           10 |     1754 | 2024-12-13 | Axolotls             | W   | 0.682      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.65 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            9 |     1966 | 2024-12-08 | Alter Iron Club      | W   | 0.649      | 0.372        | 0.009 (0.002)    | 0.356 (0.086)    | 0 (0.000) |    10.07 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            8 |     2241 | 2024-12-03 | Chicken Coop Esports | W   | 0.616      | 0.372        | 0.006 (0.001)    | 0.189 (0.043)    | 0 (0.000) |     8.88 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            7 |     2309 | 2024-12-02 | Undone               | W   | 0.609      | 0.372        | 0.002 (0.001)    | 0.286 (0.065)    | 0 (0.000) |    11.09 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            6 |     2380 | 2024-12-01 | HoleSmokers          | W   | 0.602      | 0.372        | 0.000 (0.000)    | 0.028 (0.006)    | 0 (0.000) |     2.91 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            5 |     2562 | 2024-11-29 | LOSTHILLS            | W   | 0.589      | 0.372        | -                | 0.027 (0.006)    | 0 (0.000) |     2.84 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            4 |     2764 | 2024-11-24 | MCS Gaming           | W   | 0.556      | 0.233        | 0.003 (0.000)    | 0.344 (0.044)    | 0 (0.000) |     7.34 | HorizoN, karv3r, Rulik, s1rena, stanf1x |
|            3 |     2766 | 2024-11-24 | Milky Gooners        | W   | 0.555      | 0.233        | 0.000 (0.000)    | -                | 0 (0.000) |     4.21 | HorizoN, karv3r, Rulik, s1rena, stanf1x |
|            2 |     2927 | 2024-11-22 | Blahaj               | L   | 0.542      | -            | -                | -                | -         |   -12.50 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |
|            1 |     2933 | 2024-11-22 | Immigrants Peek      | W   | 0.542      | 0.143        | 0.001 (0.000)    | 0.366 (0.028)    | -         |     6.99 | HorizoN, karv3r, Rulik, S0ph3R, s1rena  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,682.14)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.649 | $7,000.00      | $4,543.19       |
| 2024-11-24 |      0.556 | $250.00        | $138.95         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
