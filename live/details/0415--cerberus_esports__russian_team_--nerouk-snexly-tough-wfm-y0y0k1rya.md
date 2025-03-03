### Roster Details<br />
Team Name: Cerberus eSports (Russian team)<br />
Roster: NerouK, SnexLy, TOUGH, WFM, y0y0k1rya<br />
Global Rank: [415](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [255]( ../standings_europe.md)<br />
<br />
Final Rank Value:  588.6<br />
<br />
Final Rank Value (588.6) = Starting Rank Value (595.3) + Head To Head Adjustments (-6.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.175[<sup>1</sup>](#table2)
- Bounty Collected: 0.205[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 595.3
- 400 + ( ( 0.098 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 595.3


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
|           13 |     2216 | 2024-12-04 | Donstu Esports         | L   | 0.612      | -            | -                | -                | -         |   -11.95 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           12 |     2339 | 2024-12-02 | SkyFury                | W   | 0.599      | 0.333        | 0.004 (0.001)    | 0.338 (0.067)    | 0 (0.000) |    11.62 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           11 |     2494 | 2024-11-30 | ALLINNERS              | W   | 0.586      | 0.333        | 0.002 (0.000)    | 0.149 (0.029)    | 0 (0.000) |    12.45 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|           10 |     2722 | 2024-11-26 | Dreams To Legends      | L   | 0.559      | -            | -                | -                | -         |    -8.04 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            9 |     3689 | 2024-11-10 | VP.Prodigy             | L   | 0.450      | -            | -                | -                | -         |    -9.33 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            8 |     3690 | 2024-11-10 | Oshikousei             | W   | 0.450      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.56 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            7 |     4828 | 2024-10-20 | Poslednii3ae3d         | L   | 0.309      | -            | -                | -                | -         |    -4.25 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            6 |     6575 | 2024-09-21 | RUSH B (Russian team)  | L   | 0.118      | -            | -                | -                | -         |    -0.60 | ParliE, SnexLy, WFM, xnkka, y0y0k1rya |
|            5 |     7196 | 2024-09-11 | XPERION NXT            | L   | 0.051      | -            | -                | -                | -         |    -0.70 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            4 |     7294 | 2024-09-09 | Madagaskar             | W   | 0.038      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.40 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            3 |     7409 | 2024-09-07 | NO BYSTANDERS          | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.018 (0.000)    | 0 (0.000) |     0.28 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            2 |     7574 | 2024-09-05 | Ex-Soul's Heart Esport | L   | 0.012      | -            | -                | -                | -         |    -0.17 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |
|            1 |     7673 | 2024-09-04 | Dark Cloud Esports     | L   | 0.005      | -            | -                | -                | -         |    -0.03 | NerouK, SnexLy, TOUGH, WFM, y0y0k1rya |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($6.59)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-23 |      0.132 | $50.00         | $6.59           |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
