### Roster Details<br />
Team Name: CyberMAN<br />
Roster: ASTR, Dabok, H1kari, meowpop, vladick<br />
Global Rank: [560](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [345]( ../standings_europe.md)<br />
<br />
Final Rank Value:  471.7<br />
<br />
Final Rank Value (471.7) = Starting Rank Value (480.6) + Head To Head Adjustments (-8.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.160[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 480.6
- 400 + ( ( 0.040 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 480.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent              | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2721 | 2024-11-26 | HAVENs                | L   | 0.567      | -            | -                | -                | -         |   -10.59 | ASTR, Dabok, H1kari, meowpop, vladick |
|            7 |     2776 | 2024-11-24 | EC BANGA              | W   | 0.553      | 0.143        | 0.001 (0.000)    | 0.097 (0.008)    | 0 (0.000) |     9.73 | ASTR, Dabok, H1kari, meowpop, vladick |
|            6 |     3226 | 2024-11-17 | INWESKO               | W   | 0.507      | 0.143        | 0.000 (0.000)    | 0.056 (0.004)    | 0 (0.000) |     8.32 | ASTR, Dabok, H1kari, meowpop, vladick |
|            5 |     3926 | 2024-11-05 | MightyWolves          | L   | 0.427      | -            | -                | -                | -         |    -7.96 | ASTR, Dabok, H1kari, meowpop, vladick |
|            4 |     4695 | 2024-10-22 | Way2go (Latvian team) | L   | 0.333      | -            | -                | -                | -         |    -3.02 | ASTR, Dabok, H1kari, meowpop, vladick |
|            3 |     4766 | 2024-10-20 | HAVENs                | L   | 0.320      | -            | -                | -                | -         |    -6.21 | ASTR, Dabok, H1kari, meowpop, vladick |
|            2 |     5412 | 2024-10-08 | Hypewrld              | L   | 0.240      | -            | -                | -                | -         |    -1.50 | ASTR, Dabok, H1kari, meowpop, vladick |
|            1 |     5841 | 2024-10-01 | Sunshine!             | W   | 0.193      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.36 | ASTR, Dabok, H1kari, meowpop, vladick |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
