### Roster Details<br />
Team Name: SHOO7ERS<br />
Roster: Blacc, kapa, Xbenz, xezr, zteeek<br />
Global Rank: [262](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [183]( ../standings_europe.md)<br />
<br />
Final Rank Value:  672.6<br />
<br />
Final Rank Value (672.6) = Starting Rank Value (655.1) + Head To Head Adjustments (17.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.252[<sup>1</sup>](#table2)
- Bounty Collected: 0.179[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.075[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 655.1
- 400 + ( ( 0.128 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 655.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1826 | 2024-12-12 | Wu-Tang Clan              | L   | 0.674      | -            | -                | -                | -         |   -11.04 | Blacc, kapa, Xbenz, xezr, zteeek   |
|           11 |     1868 | 2024-12-11 | XGOD ARENA                | W   | 0.667      | 0.274        | 0.000 (0.000)    | 0.039 (0.007)    | 0 (0.000) |     7.78 | Blacc, kapa, Wahtzz, Xbenz, zteeek |
|           10 |     1911 | 2024-12-10 | Yamato Esports            | W   | 0.660      | 0.274        | 0.000 (0.000)    | 0.020 (0.004)    | 0 (0.000) |     5.88 | Blacc, kapa, Wahtzz, Xbenz, zteeek |
|            9 |     1994 | 2024-12-08 | Truck Drivers             | L   | 0.647      | -            | -                | -                | -         |    -9.96 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            8 |     2007 | 2024-12-08 | M1Z                       | W   | 0.646      | 0.143        | 0.000 (0.000)    | 0.113 (0.010)    | 1 (0.646) |     3.95 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            7 |     3231 | 2024-11-17 | M1Z                       | W   | 0.506      | 0.143        | 0.000 (0.000)    | 0.113 (0.008)    | 0 (0.000) |     3.06 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            6 |     3642 | 2024-11-10 | ANimaleGG                 | W   | 0.460      | 0.143        | 0.000 (0.000)    | 0.056 (0.004)    | 0 (0.000) |     3.87 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            5 |     4045 | 2024-11-03 | W2TE                      | W   | 0.413      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 0 (0.000) |     2.32 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            4 |     4452 | 2024-10-27 | Truck Drivers             | W   | 0.367      | 0.143        | 0.002 (0.000)    | 0.122 (0.006)    | 0 (0.000) |     6.37 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            3 |     5070 | 2024-10-15 | FullShock (Estonian team) | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     1.66 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            2 |     5133 | 2024-10-13 | Godne                     | W   | 0.273      | 0.143        | 0.000 (0.000)    | 0.045 (0.002)    | 0 (0.000) |     1.62 | Blacc, hY, kapa, wahtzz, Xbenz     |
|            1 |     5511 | 2024-10-06 | GENESIS (Estonian team)   | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.109 (0.004)    | 0 (0.000) |     1.99 | Blacc, hY, kapa, wahtzz, Xbenz     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($362.24)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $325.00        | $225.49         |
| 2024-12-08 |      0.647 | $211.52        | $136.75         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
