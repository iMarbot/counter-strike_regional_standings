### Roster Details<br />
Team Name: SKIBIDIES<br />
Roster: Boci, esor, excien, kr1stilio, medz1<br />
Global Rank: [358](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [232]( ../standings_europe.md)<br />
<br />
Final Rank Value:  619.3<br />
<br />
Final Rank Value (619.3) = Starting Rank Value (623.7) + Head To Head Adjustments (-4.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.240[<sup>1</sup>](#table2)
- Bounty Collected: 0.155[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.053[<sup>2</sup>](#table1)

The average of these factors is 0.112<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 623.7
- 400 + ( ( 0.112 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 623.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3718 | 2024-11-09 | Békéscsabai E-Sport Egyesület | W   | 0.453      | 0.143        | 0.000 (0.000)    | 0.035 (0.002)    | 1 (0.453) |     6.46 | Boci, esor, excien, kr1stilio, medz1 |
|            6 |     3746 | 2024-11-09 | Team Hungary                  | L   | 0.451      | -            | -                | -                | -         |    -3.98 | Boci, esor, excien, kr1stilio, medz1 |
|            5 |     4193 | 2024-11-01 | Budapest Five                 | L   | 0.400      | -            | -                | -                | -         |    -5.78 | Boci, esor, excien, medz1, Memeske   |
|            4 |     4285 | 2024-10-30 | Békéscsabai E-Sport Egyesület | L   | 0.387      | -            | -                | -                | -         |    -6.75 | Boci, esor, excien, medz1, Memeske   |
|            3 |     4574 | 2024-10-25 | ManageYself                   | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     4.67 | Boci, esor, excien, medz1, Memeske   |
|            2 |     4649 | 2024-10-23 | Team Hungary                  | L   | 0.340      | -            | -                | -                | -         |    -3.31 | Boci, esor, excien, medz1, Memeske   |
|            1 |     4791 | 2024-10-20 | Myztro Gaming                 | W   | 0.319      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     4.32 | Boci, esor, excien, medz1, Memeske   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($225.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.453 | $263.33        | $119.24         |
| 2024-11-01 |      0.400 | $266.44        | $106.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
