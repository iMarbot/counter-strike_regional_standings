### Roster Details<br />
Team Name: Budapest Five<br />
Roster: DreaM, fleav, miwo, playN, Sorex<br />
Global Rank: [289](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [197]( ../standings_europe.md)<br />
<br />
Final Rank Value:  656.7<br />
<br />
Final Rank Value (656.7) = Starting Rank Value (640.2) + Head To Head Adjustments (16.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.2
- 400 + ( ( 0.120 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 640.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3719 | 2024-11-09 | Team Hungary                  | L   | 0.453      | -            | -                | -                | -         |    -4.68 | DreaM, fleav, miwo, playN, Sorex    |
|            6 |     3734 | 2024-11-09 | Békéscsabai E-Sport Egyesület | W   | 0.452      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | 1 (0.452) |     5.74 | DreaM, fleav, miwo, playN, Sorex    |
|            5 |     4193 | 2024-11-01 | SKIBIDIES                     | W   | 0.400      | 0.143        | 0.001 (0.000)    | 0.053 (0.003)    | 0 (0.000) |     5.78 | DreaM, miwo, playN, Sorex, strong3r |
|            4 |     4286 | 2024-10-30 | Myztro Gaming                 | W   | 0.387      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     4.75 | DreaM, miwo, playN, Sorex, strong3r |
|            3 |     4594 | 2024-10-25 | Team Hungary                  | L   | 0.352      | -            | -                | -                | -         |    -3.66 | DreaM, miwo, playN, Sorex, strong3r |
|            2 |     4648 | 2024-10-23 | Békéscsabai E-Sport Egyesület | W   | 0.340      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | 0 (0.000) |     4.48 | DreaM, miwo, playN, Sorex, strong3r |
|            1 |     4792 | 2024-10-20 | ManageYself                   | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     4.14 | DreaM, miwo, playN, Sorex, strong3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($511.46)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.453 | $658.32        | $298.09         |
| 2024-11-01 |      0.400 | $532.88        | $213.37         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
