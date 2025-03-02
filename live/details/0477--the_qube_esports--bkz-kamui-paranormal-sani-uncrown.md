### Roster Details<br />
Team Name: The QUBE Esports<br />
Roster: bkz, Kamui, Paranormal, Sani, Uncrown<br />
Global Rank: [477](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [78]( ../standings_asia.md)<br />
<br />
Final Rank Value:  536.0<br />
<br />
Final Rank Value (536.0) = Starting Rank Value (505.1) + Head To Head Adjustments (30.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 505.1
- 400 + ( ( 0.053 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 505.1


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
|           12 |     1358 | 2024-12-24 | Chinggis Warriors  | L   | 0.756      | -            | -                | -                | -         |    -2.78 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|           11 |     1365 | 2024-12-24 | The Huns Esports   | L   | 0.751      | -            | -                | -                | -         |    -3.38 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|           10 |     1367 | 2024-12-23 | Clutch Gaming      | W   | 0.750      | 0.143        | 0.000 (0.000)    | 0.055 (0.006)    | 0 (0.000) |    12.17 | bkz, Kamui, Paranormal, Sani, Uncrown      |
|            9 |     2281 | 2024-12-03 | Harizma            | L   | 0.611      | -            | -                | -                | -         |    -4.43 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            8 |     2285 | 2024-12-03 | DEWA United        | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.161 (0.014)    | 0 (0.000) |    11.24 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            7 |     2294 | 2024-12-02 | Kadiliman Esports  | W   | 0.611      | 0.143        | 0.000 (0.000)    | 0.029 (0.002)    | 0 (0.000) |     6.54 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            6 |     2300 | 2024-12-02 | Eruption           | W   | 0.610      | 0.143        | 0.014 (0.001)    | 0.552 (0.048)    | 0 (0.000) |    17.05 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            5 |     2302 | 2024-12-02 | The Huns Esports   | L   | 0.610      | -            | -                | -                | -         |    -2.07 | bkz, crystalised, Kamui, Paranormal, ZeDGe |
|            4 |     2356 | 2024-12-02 | The Huns Esports   | L   | 0.604      | -            | -                | -                | -         |    -1.96 | aNSeLMO, bkz, Kamui, Paranormal, ZeDGe     |
|            3 |     2369 | 2024-12-01 | Zen-ei             | W   | 0.604      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.73 | aNSeLMO, bkz, Kamui, Paranormal, ZeDGe     |
|            2 |     3360 | 2024-11-15 | THE (Russian team) | L   | 0.497      | -            | -                | -                | -         |    -4.62 | bkz, Kamui, m4mc, Paranormal, ZeDGe        |
|            1 |     3363 | 2024-11-15 | Harizma            | L   | 0.497      | -            | -                | -                | -         |    -3.59 | bkz, Kamui, m4mc, Paranormal, ZeDGe        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
