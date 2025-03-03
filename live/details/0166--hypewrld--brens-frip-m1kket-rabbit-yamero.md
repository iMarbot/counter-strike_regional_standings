### Roster Details<br />
Team Name: Hypewrld<br />
Roster: Brens, Frip, m1kket, rabbit, Yamero<br />
Global Rank: [166](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [123]( ../standings_europe.md)<br />
<br />
Final Rank Value:  742.3<br />
<br />
Final Rank Value (742.3) = Starting Rank Value (729.1) + Head To Head Adjustments (13.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.273[<sup>1</sup>](#table2)
- Bounty Collected: 0.214[<sup>2</sup>](#table1)
- Opponent Network: 0.011[<sup>2</sup>](#table1)
- LAN Wins: 0.160[<sup>2</sup>](#table1)

The average of these factors is 0.165<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 729.1
- 400 + ( ( 0.165 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 729.1


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
|           13 |     1630 | 2024-12-15 | Way2go (Latvian team) | W   | 0.685      | 0.143        | 0.000 (0.000)    | 0.116 (0.011)    | 1 (0.685) |     8.22 | Brens, Frip, m1kket, rabbit, Yamero |
|           12 |     1655 | 2024-12-15 | EC BANGA              | W   | 0.683      | 0.143        | 0.001 (0.000)    | 0.096 (0.009)    | 1 (0.683) |     4.74 | Brens, Frip, m1kket, rabbit, Yamero |
|           11 |     2668 | 2024-11-27 | 500 Rush              | L   | 0.566      | -            | -                | -                | -         |   -10.67 | Brens, Frip, m1kket, rabbit, Yamero |
|           10 |     3029 | 2024-11-21 | SkyFury               | W   | 0.525      | 0.284        | 0.004 (0.001)    | 0.338 (0.050)    | 0 (0.000) |     7.05 | Brens, Frip, m1kket, rabbit, Yamero |
|            9 |     3038 | 2024-11-21 | KZ Esports            | W   | 0.525      | 0.284        | 0.009 (0.001)    | 0.112 (0.017)    | 0 (0.000) |     7.42 | Brens, Frip, m1kket, rabbit, Yamero |
|            8 |     3126 | 2024-11-20 | DEPO                  | L   | 0.518      | -            | -                | -                | -         |    -7.47 | Brens, Frip, m1kket, rabbit, Yamero |
|            7 |     3154 | 2024-11-19 | Sunshine!             | W   | 0.512      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.95 | Brens, Frip, m1kket, rabbit, Yamero |
|            6 |     3235 | 2024-11-17 | HAVENs                | W   | 0.499      | 0.143        | 0.000 (0.000)    | 0.089 (0.006)    | 0 (0.000) |     2.29 | Brens, Frip, m1kket, rabbit, Yamero |
|            5 |     3653 | 2024-11-10 | EC BANGA              | W   | 0.452      | 0.143        | 0.001 (0.000)    | 0.096 (0.006)    | 0 (0.000) |     3.46 | Brens, Frip, m1kket, rabbit, Yamero |
|            4 |     4463 | 2024-10-27 | INWESKO               | L   | 0.358      | -            | -                | -                | -         |    -9.04 | Brens, Frip, m1kket, rabbit, Yamero |
|            3 |     5066 | 2024-10-15 | MightyWolves          | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.039 (0.002)    | 0 (0.000) |     1.21 | Brens, Frip, m1kket, rabbit, Yamero |
|            2 |     5424 | 2024-10-08 | CyberMAN              | W   | 0.232      | 0.143        | 0.000 (0.000)    | 0.058 (0.002)    | 0 (0.000) |     1.45 | Brens, Frip, m1kket, rabbit, Yamero |
|            1 |     5522 | 2024-10-06 | Way2go (Latvian team) | W   | 0.218      | 0.143        | 0.000 (0.000)    | 0.116 (0.004)    | 0 (0.000) |     2.52 | Brens, Frip, m1kket, rabbit, Yamero |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($719.70)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $1,050.48      | $719.70         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
