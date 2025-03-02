### Roster Details<br />
Team Name: MightyWolves<br />
Roster: blazekinho, Emis2, karlisabc, keni, whitezins<br />
Global Rank: [618](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [378]( ../standings_europe.md)<br />
<br />
Final Rank Value:  392.1<br />
<br />
Final Rank Value (392.1) = Starting Rank Value (400.3) + Head To Head Adjustments (-8.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.3
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2697 | 2024-11-26 | HAVENs                | L   | 0.567      | -            | -                | -                | -         |    -8.35 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            7 |     3145 | 2024-11-19 | INWESKO               | L   | 0.520      | -            | -                | -                | -         |    -6.57 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            6 |     3535 | 2024-11-12 | Way2go (Latvian team) | L   | 0.473      | -            | -                | -                | -         |    -3.18 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            5 |     3926 | 2024-11-05 | CyberMAN              | W   | 0.427      | 0.143        | 0.000 (0.000)    | 0.059 (0.004)    | 0 (0.000) |     7.96 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            4 |     4699 | 2024-10-22 | EC BANGA              | L   | 0.333      | -            | -                | -                | -         |    -3.54 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            3 |     5054 | 2024-10-15 | Hypewrld              | L   | 0.286      | -            | -                | -                | -         |    -1.25 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            2 |     5406 | 2024-10-08 | Sunshine!             | W   | 0.240      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.71 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            1 |     5837 | 2024-10-01 | HAVENs                | W   | 0.193      | 0.143        | 0.000 (0.000)    | 0.090 (0.002)    | 0 (0.000) |     3.04 | blazekinho, Emis2, karlisabc, keni, whitezins |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
