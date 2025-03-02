### Roster Details<br />
Team Name: Békéscsabai E-Sport Egyesület<br />
Roster: CendiarY, er9k, flasi, pmk, vincso<br />
Global Rank: [427](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [265]( ../standings_europe.md)<br />
<br />
Final Rank Value:  575.8<br />
<br />
Final Rank Value (575.8) = Starting Rank Value (589.9) + Head To Head Adjustments (-14.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.222[<sup>1</sup>](#table2)
- Bounty Collected: 0.158[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 589.9
- 400 + ( ( 0.095 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 589.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     3718 | 2024-11-09 | SKIBIDIES     | L   | 0.453      | -            | -                | -                | -         |    -6.46 | CendiarY, er9k, flasi, pmk, vincso |
|            6 |     3734 | 2024-11-09 | Budapest Five | L   | 0.452      | -            | -                | -                | -         |    -5.74 | CendiarY, er9k, flasi, pmk, vincso |
|            5 |     4179 | 2024-11-01 | ManageYself   | L   | 0.400      | -            | -                | -                | -         |    -6.85 | CendiarY, er9k, kewS, pmk, vincso  |
|            4 |     4285 | 2024-10-30 | SKIBIDIES     | W   | 0.387      | 0.143        | 0.001 (0.000)    | 0.053 (0.003)    | 0 (0.000) |     6.75 | CendiarY, er9k, kewS, pmk, vincso  |
|            3 |     4575 | 2024-10-25 | Myztro Gaming | W   | 0.353      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     5.42 | CendiarY, er9k, kewS, pmk, vincso  |
|            2 |     4648 | 2024-10-23 | Budapest Five | L   | 0.340      | -            | -                | -                | -         |    -4.48 | CendiarY, er9k, kewS, pmk, vincso  |
|            1 |     4764 | 2024-10-20 | Team Hungary  | L   | 0.320      | -            | -                | -                | -         |    -2.71 | CendiarY, er9k, kewS, pmk, vincso  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($106.69)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-01 |      0.400 | $266.44        | $106.69         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
