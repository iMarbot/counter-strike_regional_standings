### Roster Details<br />
Team Name: Budapest Five<br />
Roster: DreaM, fleav, miwo, playN, Sorex<br />
Global Rank: [291](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [196]( ../standings_europe.md)<br />
<br />
Final Rank Value:  656.2<br />
<br />
Final Rank Value (656.2) = Starting Rank Value (640.0) + Head To Head Adjustments (16.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.262[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.052[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.0
- 400 + ( ( 0.120 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 640.0


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
|            7 |     3731 | 2024-11-09 | Team Hungary                  | L   | 0.445      | -            | -                | -                | -         |    -4.62 | DreaM, fleav, miwo, playN, Sorex    |
|            6 |     3746 | 2024-11-09 | Békéscsabai E-Sport Egyesület | W   | 0.444      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 1 (0.444) |     5.65 | DreaM, fleav, miwo, playN, Sorex    |
|            5 |     4205 | 2024-11-01 | SKIBIDIES                     | W   | 0.392      | 0.143        | 0.001 (0.000)    | 0.052 (0.003)    | 0 (0.000) |     5.66 | DreaM, miwo, playN, Sorex, strong3r |
|            4 |     4298 | 2024-10-30 | Myztro Gaming                 | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     4.66 | DreaM, miwo, playN, Sorex, strong3r |
|            3 |     4606 | 2024-10-25 | Team Hungary                  | L   | 0.344      | -            | -                | -                | -         |    -3.60 | DreaM, miwo, playN, Sorex, strong3r |
|            2 |     4660 | 2024-10-23 | Békéscsabai E-Sport Egyesület | W   | 0.332      | 0.143        | 0.000 (0.000)    | 0.034 (0.002)    | 0 (0.000) |     4.38 | DreaM, miwo, playN, Sorex, strong3r |
|            1 |     4804 | 2024-10-20 | ManageYself                   | W   | 0.311      | 0.143        | 0.000 (0.000)    | 0.018 (0.001)    | 0 (0.000) |     4.04 | DreaM, miwo, playN, Sorex, strong3r |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($501.70)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.445 | $658.32        | $292.69         |
| 2024-11-01 |      0.392 | $532.88        | $209.01         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
