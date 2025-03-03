### Roster Details<br />
Team Name: Copenhagen Wolves (American organization)<br />
Roster: eraa, Fessor, sausol, szejn, Tapewaare<br />
Global Rank: [454](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [283]( ../standings_europe.md)<br />
<br />
Final Rank Value:  556.7<br />
<br />
Final Rank Value (556.7) = Starting Rank Value (529.9) + Head To Head Adjustments (26.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.065<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 529.9
- 400 + ( ( 0.065 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 529.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           22 |     5860 | 2024-10-01 | ALTERNATE aTTaX  | L   | 0.184      | -            | -                | -                | -         |    -0.68 | eraa, Fessor, sausol, szejn, Tapewaare |
|           21 |     5968 | 2024-09-29 | G2 Ares          | L   | 0.171      | -            | -                | -                | -         |    -1.76 | eraa, Fessor, sausol, szejn, Tapewaare |
|           20 |     5978 | 2024-09-29 | Wild Lotus       | W   | 0.170      | 0.435        | 0.001 (0.000)    | 0.438 (0.032)    | 0 (0.000) |     4.05 | eraa, Fessor, sausol, szejn, Tapewaare |
|           19 |     6095 | 2024-09-28 | K27              | W   | 0.162      | 0.143        | 0.008 (0.000)    | 0.769 (0.018)    | 0 (0.000) |     4.55 | eraa, Fessor, sausol, szejn, Tapewaare |
|           18 |     6143 | 2024-09-27 | Passion UA       | L   | 0.157      | -            | -                | -                | -         |    -0.32 | eraa, Fessor, sausol, szejn, Tapewaare |
|           17 |     6200 | 2024-09-26 | GamerLegion      | L   | 0.151      | -            | -                | -                | -         |    -1.44 | eraa, Fessor, sausol, szejn, Tapewaare |
|           16 |     6316 | 2024-09-25 | Endpoint         | W   | 0.143      | 0.435        | 0.009 (0.001)    | 0.377 (0.023)    | 0 (0.000) |     3.52 | eraa, Fessor, sausol, szejn, Tapewaare |
|           15 |     6341 | 2024-09-25 | RUSTEC           | W   | 0.142      | -            | -                | -                | 0 (0.000) |     2.31 | eraa, Fessor, sausol, szejn, Tapewaare |
|           14 |     6423 | 2024-09-24 | K27              | L   | 0.136      | -            | -                | -                | -         |    -0.46 | eraa, Fessor, sausol, szejn, Tapewaare |
|           13 |     6471 | 2024-09-23 | ECSTATIC         | L   | 0.132      | -            | -                | -                | -         |    -0.55 | eraa, Fessor, sausol, szejn, Tapewaare |
|           12 |     6529 | 2024-09-22 | Team Space       | W   | 0.124      | -            | -                | -                | 0 (0.000) |     1.71 | eraa, Fessor, sausol, szejn, Tapewaare |
|           11 |     6541 | 2024-09-22 | Zero Tenacity    | W   | 0.123      | 0.435        | 0.028 (0.001)    | 0.684 (0.037)    | 0 (0.000) |     3.33 | eraa, Fessor, sausol, szejn, Tapewaare |
|           10 |     6581 | 2024-09-21 | FLuffy Gangsters | W   | 0.118      | 0.143        | 0.014 (0.000)    | 0.909 (0.015)    | 0 (0.000) |     3.00 | eraa, Fessor, sausol, szejn, Tapewaare |
|            9 |     6635 | 2024-09-20 | RUBY             | L   | 0.112      | -            | -                | -                | -         |    -1.06 | eraa, Fessor, sausol, szejn, Tapewaare |
|            8 |     6702 | 2024-09-19 | 9Pandas          | W   | 0.105      | 0.435        | 0.085 (0.004)    | 0.477 (0.022)    | 0 (0.000) |     3.04 | eraa, Fessor, sausol, szejn, Tapewaare |
|            7 |     6711 | 2024-09-19 | ALASKA           | W   | 0.104      | 0.143        | 0.031 (0.000)    | 0.867 (0.013)    | 0 (0.000) |     3.18 | eraa, Fessor, sausol, szejn, Tapewaare |
|            6 |     7058 | 2024-09-14 | FLuffy Gangsters | W   | 0.069      | 0.143        | 0.014 (0.000)    | 0.909 (0.009)    | 0 (0.000) |     1.76 | eraa, Fessor, sausol, szejn, Tapewaare |
|            5 |     7148 | 2024-09-12 | AMKAL ESPORTS    | W   | 0.057      | 0.143        | -                | 0.674 (0.006)    | -         |     1.41 | eraa, Fessor, sausol, szejn, Tapewaare |
|            4 |     7161 | 2024-09-12 | Astralis Talent  | L   | 0.056      | -            | -                | -                | -         |    -0.35 | eraa, Fessor, sausol, szejn, Tapewaare |
|            3 |     7225 | 2024-09-11 | ENCE Academy     | W   | 0.049      | 0.143        | 0.009 (0.000)    | 0.649 (0.005)    | -         |     1.29 | eraa, Fessor, sausol, szejn, Tapewaare |
|            2 |     7277 | 2024-09-10 | GameAgents       | L   | 0.042      | -            | -                | -                | -         |    -0.40 | eraa, Fessor, sausol, szejn, Tapewaare |
|            1 |     7485 | 2024-09-07 | Los kogutos      | W   | 0.023      | 0.333        | 0.032 (0.000)    | -                | -         |     0.67 | eraa, Fessor, sausol, szejn, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
