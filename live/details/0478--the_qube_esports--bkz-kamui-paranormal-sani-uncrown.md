### Roster Details<br />
Team Name: The QUBE Esports<br />
Roster: bkz, Kamui, Paranormal, Sani, Uncrown<br />
Global Rank: [478](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [78]( ../standings_asia.md)<br />
<br />
Final Rank Value:  535.6<br />
<br />
Final Rank Value (535.6) = Starting Rank Value (505.2) + Head To Head Adjustments (30.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 505.2
- 400 + ( ( 0.053 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 505.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |     1370 | 2024-12-24 | Chinggis Warriors  | L   | 0.748      | -            | -                | -                | -         |    -2.77 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|           11 |     1377 | 2024-12-24 | The Huns Esports   | L   | 0.743      | -            | -                | -                | -         |    -3.34 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|           10 |     1379 | 2024-12-23 | Clutch Gaming      | W   | 0.742      | 0.143        | 0.000 (0.000)    | 0.054 (0.006)    | 0 (0.000) |    12.02 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|            9 |     2293 | 2024-12-03 | Harizma            | L   | 0.603      | -            | -                | -                | -         |    -4.39 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            8 |     2297 | 2024-12-03 | DEWA United        | W   | 0.603      | 0.143        | 0.000 (0.000)    | 0.158 (0.014)    | 0 (0.000) |    11.06 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            7 |     2306 | 2024-12-02 | Kadiliman Esports  | W   | 0.602      | 0.143        | 0.000 (0.000)    | 0.028 (0.002)    | 0 (0.000) |     6.45 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            6 |     2312 | 2024-12-02 | Eruption           | W   | 0.602      | 0.143        | 0.014 (0.001)    | 0.551 (0.047)    | 0 (0.000) |    16.82 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            5 |     2314 | 2024-12-02 | The Huns Esports   | L   | 0.602      | -            | -                | -                | -         |    -2.04 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            4 |     2368 | 2024-12-02 | The Huns Esports   | L   | 0.596      | -            | -                | -                | -         |    -1.94 | aNSeLMO, bkz, Kamui, Paranormal, ZeDGe     |
|            3 |     2381 | 2024-12-01 | Zen-ei             | W   | 0.595      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.64 | aNSeLMO, bkz, Kamui, Paranormal, ZeDGe     |
|            2 |     3372 | 2024-11-15 | THE (Russian team) | L   | 0.489      | -            | -                | -                | -         |    -4.54 | bkz, Kamui, m4mc, Paranormal, ZeDGe        |
|            1 |     3375 | 2024-11-15 | Harizma            | L   | 0.489      | -            | -                | -                | -         |    -3.56 | bkz, Kamui, m4mc, Paranormal, ZeDGe        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
