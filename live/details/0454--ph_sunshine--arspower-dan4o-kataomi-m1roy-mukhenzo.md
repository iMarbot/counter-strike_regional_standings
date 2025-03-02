### Roster Details<br />
Team Name: PH SunShine<br />
Roster: ARSPOWER, dan4o, kataomi, m1roy, mukhenzo<br />
Global Rank: [454](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [284]( ../standings_europe.md)<br />
<br />
Final Rank Value:  556.8<br />
<br />
Final Rank Value (556.8) = Starting Rank Value (555.1) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.159[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.150[<sup>2</sup>](#table1)

The average of these factors is 0.078<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 555.1
- 400 + ( ( 0.078 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 555.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2009 | 2024-12-08 | Dmoai        | L   | 0.645      | -            | -                | -                | -         |   -11.45 | ARSPOWER, dan4o, kataomi, m1roy, mukhenzo |
|            4 |     2018 | 2024-12-08 | WAKANDA      | W   | 0.644      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.644) |     5.38 | ARSPOWER, dan4o, kataomi, m1roy, mukhenzo |
|            3 |     2025 | 2024-12-08 | 69peek       | L   | 0.644      | -            | -                | -                | -         |    -5.23 | ARSPOWER, dan4o, kataomi, m1roy, mukhenzo |
|            2 |     2029 | 2024-12-07 | AimAssassins | L   | 0.644      | -            | -                | -                | -         |    -2.19 | ARSPOWER, dan4o, kataomi, m1roy, mukhenzo |
|            1 |     2034 | 2024-12-07 | 69peek       | W   | 0.643      | 0.143        | 0.001 (0.000)    | 0.120 (0.011)    | 1 (0.643) |    15.23 | ARSPOWER, dan4o, kataomi, m1roy, mukhenzo |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
