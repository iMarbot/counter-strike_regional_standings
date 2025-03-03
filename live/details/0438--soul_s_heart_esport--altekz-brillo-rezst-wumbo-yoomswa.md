### Roster Details<br />
Team Name: Soul's Heart Esport<br />
Roster: Altekz, Brillo, Rezst, Wumbo, yoomswa<br />
Global Rank: [438](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [270]( ../standings_europe.md)<br />
<br />
Final Rank Value:  570.2<br />
<br />
Final Rank Value (570.2) = Starting Rank Value (535.5) + Head To Head Adjustments (34.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 535.5
- 400 + ( ( 0.068 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 535.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2427 | 2024-12-01 | FLuffy Gangsters  | L   | 0.592      | -            | -                | -                | -         |    -3.15 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           12 |     2714 | 2024-11-26 | Nuclear TigeRES   | L   | 0.559      | -            | -                | -                | -         |    -3.86 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           11 |     3020 | 2024-11-21 | PCIFIC Espor      | W   | 0.525      | 0.372        | 0.004 (0.001)    | 0.251 (0.049)    | 0 (0.000) |    12.38 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           10 |     3099 | 2024-11-20 | FORZE Reload      | L   | 0.519      | -            | -                | -                | -         |    -2.91 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            9 |     3156 | 2024-11-19 | Daystar           | W   | 0.512      | 0.372        | 0.000 (0.000)    | 0.131 (0.025)    | 0 (0.000) |     9.35 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            8 |     3200 | 2024-11-18 | Underrated        | W   | 0.505      | 0.372        | 0.002 (0.000)    | 0.268 (0.050)    | 0 (0.000) |    10.37 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            7 |     3885 | 2024-11-06 | GODSENT           | L   | 0.425      | -            | -                | -                | -         |    -4.51 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            6 |     3997 | 2024-11-04 | HOTU              | W   | 0.412      | 0.372        | 0.003 (0.000)    | 0.768 (0.118)    | 0 (0.000) |     9.03 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            5 |     4076 | 2024-11-03 | Los kogutos       | W   | 0.404      | 0.372        | 0.032 (0.005)    | 0.515 (0.077)    | 0 (0.000) |    11.33 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            4 |     6047 | 2024-09-28 | AgenciUSB         | L   | 0.164      | -            | -                | -                | -         |    -2.95 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            3 |     7458 | 2024-09-07 | 500 Rush          | L   | 0.023      | -            | -                | -                | -         |    -0.26 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            2 |     7484 | 2024-09-07 | EMERITOS BANDITOS | W   | 0.023      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.32 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            1 |     7491 | 2024-09-07 | AgenciUSB         | L   | 0.022      | -            | -                | -                | -         |    -0.47 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
