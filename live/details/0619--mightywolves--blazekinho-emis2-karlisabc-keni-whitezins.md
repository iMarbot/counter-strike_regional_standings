### Roster Details<br />
Team Name: MightyWolves<br />
Roster: blazekinho, Emis2, karlisabc, keni, whitezins<br />
Global Rank: [619](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [377]( ../standings_europe.md)<br />
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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.3


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
|            8 |     2709 | 2024-11-26 | HAVENs                | L   | 0.559      | -            | -                | -                | -         |    -8.23 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            7 |     3157 | 2024-11-19 | INWESKO               | L   | 0.512      | -            | -                | -                | -         |    -6.46 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            6 |     3547 | 2024-11-12 | Way2go (Latvian team) | L   | 0.465      | -            | -                | -                | -         |    -3.13 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            5 |     3938 | 2024-11-05 | CyberMAN              | W   | 0.419      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     7.82 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            4 |     4711 | 2024-10-22 | EC BANGA              | L   | 0.325      | -            | -                | -                | -         |    -3.45 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            3 |     5066 | 2024-10-15 | Hypewrld              | L   | 0.278      | -            | -                | -                | -         |    -1.21 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            2 |     5418 | 2024-10-08 | Sunshine!             | W   | 0.232      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.59 | blazekinho, Emis2, karlisabc, keni, whitezins |
|            1 |     5849 | 2024-10-01 | HAVENs                | W   | 0.185      | 0.143        | 0.000 (0.000)    | 0.089 (0.002)    | 0 (0.000) |     2.92 | blazekinho, Emis2, karlisabc, keni, whitezins |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
