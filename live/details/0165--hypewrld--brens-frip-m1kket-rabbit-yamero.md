### Roster Details<br />
Team Name: Hypewrld<br />
Roster: Brens, Frip, m1kket, rabbit, Yamero<br />
Global Rank: [165](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
<br />
Final Rank Value:  742.8<br />
<br />
Final Rank Value (742.8) = Starting Rank Value (729.4) + Head To Head Adjustments (13.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.162[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 729.4
- 400 + ( ( 0.165 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 729.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     1618 | 2024-12-15 | Way2go (Latvian team) | W   | 0.693      | 0.143        | 0.000 (0.000)    | 0.118 (0.012)    | 1 (0.693) |     8.31 | Brens, Frip, m1kket, rabbit, Yamero |
|           12 |     1643 | 2024-12-15 | EC BANGA              | W   | 0.691      | 0.143        | 0.001 (0.000)    | 0.097 (0.010)    | 1 (0.691) |     4.79 | Brens, Frip, m1kket, rabbit, Yamero |
|           11 |     2656 | 2024-11-27 | 500 Rush              | L   | 0.574      | -            | -                | -                | -         |   -10.80 | Brens, Frip, m1kket, rabbit, Yamero |
|           10 |     3017 | 2024-11-21 | SkyFury               | W   | 0.533      | 0.284        | 0.004 (0.001)    | 0.342 (0.052)    | 0 (0.000) |     7.16 | Brens, Frip, m1kket, rabbit, Yamero |
|            9 |     3026 | 2024-11-21 | KZ Esports            | W   | 0.533      | 0.284        | 0.009 (0.001)    | 0.114 (0.017)    | 0 (0.000) |     7.51 | Brens, Frip, m1kket, rabbit, Yamero |
|            8 |     3114 | 2024-11-20 | DEPO                  | L   | 0.526      | -            | -                | -                | -         |    -7.53 | Brens, Frip, m1kket, rabbit, Yamero |
|            7 |     3142 | 2024-11-19 | Sunshine!             | W   | 0.520      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.97 | Brens, Frip, m1kket, rabbit, Yamero |
|            6 |     3223 | 2024-11-17 | HAVENs                | W   | 0.507      | 0.143        | 0.000 (0.000)    | 0.090 (0.007)    | 0 (0.000) |     2.33 | Brens, Frip, m1kket, rabbit, Yamero |
|            5 |     3641 | 2024-11-10 | EC BANGA              | W   | 0.460      | 0.143        | 0.001 (0.000)    | 0.097 (0.006)    | 0 (0.000) |     3.51 | Brens, Frip, m1kket, rabbit, Yamero |
|            4 |     4451 | 2024-10-27 | INWESKO               | L   | 0.367      | -            | -                | -                | -         |    -9.25 | Brens, Frip, m1kket, rabbit, Yamero |
|            3 |     5054 | 2024-10-15 | MightyWolves          | W   | 0.286      | 0.143        | 0.000 (0.000)    | 0.040 (0.002)    | 0 (0.000) |     1.25 | Brens, Frip, m1kket, rabbit, Yamero |
|            2 |     5412 | 2024-10-08 | CyberMAN              | W   | 0.240      | 0.143        | 0.000 (0.000)    | 0.059 (0.002)    | 0 (0.000) |     1.50 | Brens, Frip, m1kket, rabbit, Yamero |
|            1 |     5510 | 2024-10-06 | Way2go (Latvian team) | W   | 0.226      | 0.143        | 0.000 (0.000)    | 0.118 (0.004)    | 0 (0.000) |     2.62 | Brens, Frip, m1kket, rabbit, Yamero |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($728.31)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.693 | $1,050.48      | $728.31         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
