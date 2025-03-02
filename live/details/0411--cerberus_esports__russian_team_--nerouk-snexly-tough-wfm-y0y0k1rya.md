### Roster Details<br />
Team Name: Cerberus eSports (Russian team)<br />
Roster: NerouK, SnexLy, TOUGH, WFM, y0y0k1rya<br />
Global Rank: [411](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [255]( ../standings_europe.md)<br />
<br />
Final Rank Value:  588.6<br />
<br />
Final Rank Value (588.6) = Starting Rank Value (595.5) + Head To Head Adjustments (-7.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.176[<sup>1</sup>](#table2)
- Bounty Collected: 0.206[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 595.5
- 400 + ( ( 0.098 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 595.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     2204 | 2024-12-04 | Donstu Esports         | L   | 0.620      | -            | -                | -                | -         |   -12.10 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           12 |     2327 | 2024-12-02 | SkyFury                | W   | 0.607      | 0.333        | 0.004 (0.001)    | 0.342 (0.069)    | 0 (0.000) |    11.78 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           11 |     2482 | 2024-11-30 | ALLINNERS              | W   | 0.594      | 0.333        | 0.002 (0.000)    | 0.151 (0.030)    | 0 (0.000) |    12.64 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           10 |     2710 | 2024-11-26 | Dreams To Legends      | L   | 0.567      | -            | -                | -                | -         |    -8.13 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            9 |     3677 | 2024-11-10 | VP.Prodigy             | L   | 0.458      | -            | -                | -                | -         |    -9.49 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            8 |     3678 | 2024-11-10 | Oshikousei             | W   | 0.458      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.63 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            7 |     4816 | 2024-10-20 | Poslednii3ae3d         | L   | 0.318      | -            | -                | -                | -         |    -4.36 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            6 |     6563 | 2024-09-21 | RUSH B (Russian team)  | L   | 0.127      | -            | -                | -                | -         |    -0.64 | ParliE, SnexLy, WFM, xnkka, y0y0k1rya |
|            5 |     7184 | 2024-09-11 | XPERION NXT            | L   | 0.059      | -            | -                | -                | -         |    -0.81 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            4 |     7282 | 2024-09-09 | Madagaskar             | W   | 0.047      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.49 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            3 |     7397 | 2024-09-07 | NO BYSTANDERS          | W   | 0.033      | 0.333        | 0.000 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     0.37 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            2 |     7562 | 2024-09-05 | Ex-Soul's Heart Esport | L   | 0.020      | -            | -                | -                | -         |    -0.28 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            1 |     7661 | 2024-09-04 | Dark Cloud Esports     | L   | 0.013      | -            | -                | -                | -         |    -0.08 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-23 |      0.140 | $50.00         | $7.00           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
