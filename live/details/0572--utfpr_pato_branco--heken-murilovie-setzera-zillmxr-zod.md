### Roster Details<br />
Team Name: UTFPR Pato Branco<br />
Roster: Heken, murilovie, setzera, zillmxr, zod<br />
Global Rank: [572](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [134]( ../standings_americas.md)<br />
<br />
Final Rank Value:  454.2<br />
<br />
Final Rank Value (454.2) = Starting Rank Value (450.6) + Head To Head Adjustments (3.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.101[<sup>2</sup>](#table1)

The average of these factors is 0.025<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 450.6
- 400 + ( ( 0.025 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 450.6


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
|            5 |     4933 | 2024-10-17 | Minerva Esports UFRJ | W   | 0.299      | 0.143        | 0.000 (0.000)    | 0.027 (0.001)    | 1 (0.299) |     4.47 | Heken, murilovie, setzera, zillmxr, zod |
|            4 |     4974 | 2024-10-16 | URI Sailor           | L   | 0.294      | -            | -                | -                | -         |    -4.38 | Heken, murilovie, setzera, zillmxr, zod |
|            3 |     5040 | 2024-10-15 | UFMG Fênix Esports   | W   | 0.287      | 0.143        | 0.000 (0.000)    | 0.013 (0.001)    | 1 (0.287) |     4.09 | Heken, murilovie, setzera, zillmxr, zod |
|            2 |     5089 | 2024-10-14 | UnB Green Owls       | L   | 0.281      | -            | -                | -                | -         |    -4.42 | Heken, murilovie, setzera, zillmxr, zod |
|            1 |     5090 | 2024-10-14 | CAAP E-Sports        | W   | 0.281      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.281) |     3.79 | Heken, murilovie, setzera, zillmxr, zod |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
