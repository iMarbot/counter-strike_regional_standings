### Roster Details<br />
Team Name: Soul's Heart Esport<br />
Roster: Altekz, Brillo, Rezst, Wumbo, yoomswa<br />
Global Rank: [434](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [270]( ../standings_europe.md)<br />
<br />
Final Rank Value:  571.2<br />
<br />
Final Rank Value (571.2) = Starting Rank Value (536.1) + Head To Head Adjustments (35.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.033[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.068<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 536.1
- 400 + ( ( 0.068 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 536.1


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
|           13 |     2417 | 2024-12-01 | FLuffy Gangsters  | L   | 0.600      | -            | -                | -                | -         |    -3.16 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           12 |     2702 | 2024-11-26 | Nuclear TigeRES   | L   | 0.567      | -            | -                | -                | -         |    -3.94 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           11 |     3008 | 2024-11-21 | PCIFIC Espor      | W   | 0.534      | 0.372        | 0.004 (0.001)    | 0.254 (0.051)    | 0 (0.000) |    12.57 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|           10 |     3087 | 2024-11-20 | FORZE Reload      | L   | 0.527      | -            | -                | -                | -         |    -2.96 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            9 |     3144 | 2024-11-19 | Daystar           | W   | 0.520      | 0.372        | 0.000 (0.000)    | 0.135 (0.026)    | 0 (0.000) |     9.52 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            8 |     3188 | 2024-11-18 | Underrated        | W   | 0.514      | 0.372        | 0.002 (0.000)    | 0.271 (0.052)    | 0 (0.000) |    10.53 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            7 |     3873 | 2024-11-06 | GODSENT           | L   | 0.434      | -            | -                | -                | -         |    -4.58 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            6 |     3985 | 2024-11-04 | HOTU              | W   | 0.420      | 0.372        | 0.003 (0.000)    | 0.777 (0.122)    | 0 (0.000) |     9.21 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            5 |     4064 | 2024-11-03 | Los kogutos       | W   | 0.412      | 0.372        | 0.032 (0.005)    | 0.527 (0.081)    | 0 (0.000) |    11.56 | Altekz, Brillo, Rezst, Wumbo, yoomswa |
|            4 |     6035 | 2024-09-28 | AgenciUSB         | L   | 0.173      | -            | -                | -                | -         |    -3.10 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            3 |     7446 | 2024-09-07 | 500 Rush          | L   | 0.032      | -            | -                | -                | -         |    -0.35 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            2 |     7472 | 2024-09-07 | EMERITOS BANDITOS | W   | 0.031      | 0.143        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.43 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |
|            1 |     7479 | 2024-09-07 | AgenciUSB         | L   | 0.030      | -            | -                | -                | -         |    -0.65 | Brillo, Ed1m, Rezst, Wumbo, yoomswa   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
