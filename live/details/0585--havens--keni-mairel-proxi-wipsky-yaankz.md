### Roster Details<br />
Team Name: HAVENs<br />
Roster: keni, mairel, proxi, WIPSKY, yaankz<br />
Global Rank: [585](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [357]( ../standings_europe.md)<br />
<br />
Final Rank Value:  420.2<br />
<br />
Final Rank Value (420.2) = Starting Rank Value (400.7) + Head To Head Adjustments (19.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.7
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     1494 | 2024-12-20 | Nuclear TigeRES       | L   | 0.727      | -            | -                | -                | -         |    -2.77 | keni, mairel, proxi, WIPSKY, yaankz    |
|           10 |     1628 | 2024-12-15 | Way2go (Latvian team) | L   | 0.692      | -            | -                | -                | -         |    -4.84 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            9 |     2697 | 2024-11-26 | MightyWolves          | W   | 0.567      | 0.143        | 0.000 (0.000)    | 0.040 (0.003)    | 0 (0.000) |     8.35 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            8 |     2721 | 2024-11-26 | CyberMAN              | W   | 0.567      | 0.143        | 0.000 (0.000)    | 0.059 (0.005)    | 0 (0.000) |    10.59 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            7 |     2774 | 2024-11-24 | Way2go (Latvian team) | L   | 0.554      | -            | -                | -                | -         |    -3.70 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            6 |     3223 | 2024-11-17 | Hypewrld              | L   | 0.507      | -            | -                | -                | -         |    -2.33 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            5 |     3929 | 2024-11-05 | INWESKO               | W   | 0.427      | 0.143        | 0.000 (0.000)    | 0.056 (0.003)    | 0 (0.000) |     8.23 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            4 |     4448 | 2024-10-27 | Sunshine!             | W   | 0.367      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     5.57 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            3 |     4766 | 2024-10-20 | CyberMAN              | W   | 0.320      | 0.143        | 0.000 (0.000)    | 0.059 (0.003)    | 0 (0.000) |     6.21 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            2 |     5123 | 2024-10-13 | EC BANGA              | L   | 0.273      | -            | -                | -                | -         |    -2.82 | mairel, proxi, v1trage, WIPSKY, yaankz |
|            1 |     5837 | 2024-10-01 | MightyWolves          | L   | 0.193      | -            | -                | -                | -         |    -3.04 | mairel, proxi, v1trage, WIPSKY, yaankz |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
