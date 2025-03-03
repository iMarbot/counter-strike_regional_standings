### Roster Details<br />
Team Name: Way2go (Latvian team)<br />
Roster: emzijs, flairr, fnplaya, rud, Zan1S<br />
Global Rank: [310](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [205]( ../standings_europe.md)<br />
<br />
Final Rank Value:  644.7<br />
<br />
Final Rank Value (644.7) = Starting Rank Value (632.6) + Head To Head Adjustments (12.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.229[<sup>1</sup>](#table2)
- Bounty Collected: 0.153[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.080[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.6
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent     | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     1630 | 2024-12-15 | Hypewrld     | L   | 0.685      | -            | -                | -                | -         |    -8.22 | emzijs, flairr, fnplaya, rud, Zan1S |
|            8 |     1639 | 2024-12-15 | HAVENs       | W   | 0.684      | 0.143        | 0.000 (0.000)    | 0.089 (0.009)    | 1 (0.684) |     4.78 | emzijs, flairr, fnplaya, rud, Zan1S |
|            7 |     2786 | 2024-11-24 | HAVENs       | W   | 0.545      | 0.143        | 0.000 (0.000)    | 0.089 (0.007)    | 0 (0.000) |     3.65 | emzijs, flairr, fnplaya, rud, Zan1S |
|            6 |     3547 | 2024-11-12 | MightyWolves | W   | 0.465      | 0.143        | 0.000 (0.000)    | 0.039 (0.003)    | 0 (0.000) |     3.13 | emzijs, flairr, fnplaya, rud, Zan1S |
|            5 |     3661 | 2024-11-10 | Sunshine!    | W   | 0.452      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.75 | emzijs, flairr, fnplaya, rud, Zan1S |
|            4 |     4707 | 2024-10-22 | CyberMAN     | W   | 0.325      | 0.143        | 0.000 (0.000)    | 0.058 (0.003)    | 0 (0.000) |     2.95 | emzijs, flairr, fnplaya, rud, Zan1S |
|            3 |     5063 | 2024-10-15 | EC BANGA     | W   | 0.278      | 0.143        | 0.001 (0.000)    | 0.096 (0.004)    | 0 (0.000) |     3.13 | emzijs, flairr, fnplaya, rud, Zan1S |
|            2 |     5138 | 2024-10-13 | INWESKO      | W   | 0.265      | 0.143        | 0.000 (0.000)    | 0.055 (0.002)    | 0 (0.000) |     2.52 | emzijs, flairr, fnplaya, rud, Zan1S |
|            1 |     5522 | 2024-10-06 | Hypewrld     | L   | 0.218      | -            | -                | -                | -         |    -2.52 | emzijs, flairr, fnplaya, rud, Zan1S |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($143.94)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.685 | $210.10        | $143.94         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
