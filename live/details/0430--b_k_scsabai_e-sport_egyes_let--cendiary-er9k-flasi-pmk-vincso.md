### Roster Details<br />
Team Name: Békéscsabai E-Sport Egyesület<br />
Roster: CendiarY, er9k, flasi, pmk, vincso<br />
Global Rank: [430](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [264]( ../standings_europe.md)<br />
<br />
Final Rank Value:  576.2<br />
<br />
Final Rank Value (576.2) = Starting Rank Value (590.0) + Head To Head Adjustments (-13.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.222[<sup>1</sup>](#table2)
- Bounty Collected: 0.157[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.095<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 590.0
- 400 + ( ( 0.095 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 590.0


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
|            7 |     3730 | 2024-11-09 | SKIBIDIES     | L   | 0.445      | -            | -                | -                | -         |    -6.35 | CendiarY, er9k, flasi, pmk, vincso |
|            6 |     3746 | 2024-11-09 | Budapest Five | L   | 0.444      | -            | -                | -                | -         |    -5.65 | CendiarY, er9k, flasi, pmk, vincso |
|            5 |     4191 | 2024-11-01 | ManageYself   | L   | 0.392      | -            | -                | -                | -         |    -6.70 | CendiarY, er9k, kewS, pmk, vincso  |
|            4 |     4297 | 2024-10-30 | SKIBIDIES     | W   | 0.379      | 0.143        | 0.001 (0.000)    | 0.052 (0.003)    | 0 (0.000) |     6.61 | CendiarY, er9k, kewS, pmk, vincso  |
|            3 |     4587 | 2024-10-25 | Myztro Gaming | W   | 0.345      | 0.143        | 0.000 (0.000)    | 0.016 (0.001)    | 0 (0.000) |     5.29 | CendiarY, er9k, kewS, pmk, vincso  |
|            2 |     4660 | 2024-10-23 | Budapest Five | L   | 0.332      | -            | -                | -                | -         |    -4.38 | CendiarY, er9k, kewS, pmk, vincso  |
|            1 |     4776 | 2024-10-20 | Team Hungary  | L   | 0.312      | -            | -                | -                | -         |    -2.65 | CendiarY, er9k, kewS, pmk, vincso  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($104.50)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-01 |      0.392 | $266.44        | $104.50         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
