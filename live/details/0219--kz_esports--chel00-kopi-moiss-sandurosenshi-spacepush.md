### Roster Details<br />
Team Name: KZ Esports<br />
Roster: CHEL00, kopi, moiss, SanduroSenshi, spacepush<br />
Global Rank: [219](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [26]( ../standings_asia.md)<br />
<br />
Final Rank Value:  696.8<br />
<br />
Final Rank Value (696.8) = Starting Rank Value (700.9) + Head To Head Adjustments (-4.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.327[<sup>1</sup>](#table2)
- Bounty Collected: 0.202[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.069[<sup>2</sup>](#table1)

The average of these factors is 0.151<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 700.9
- 400 + ( ( 0.151 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 700.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent        | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     1612 | 2024-12-15 | 4z              | L   | 0.694      | -            | -                | -                | -         |   -12.14 | CHEL00, kopi, moiss, SanduroSenshi, spacepush |
|            6 |     2157 | 2024-12-05 | 4z              | W   | 0.626      | 0.310        | 0.004 (0.001)    | 0.142 (0.028)    | 0 (0.000) |     8.56 | CHEL00, kopi, moiss, SanduroSenshi, spacepush |
|            5 |     2263 | 2024-12-03 | REDPack Esports | W   | 0.613      | 0.310        | 0.001 (0.000)    | 0.085 (0.016)    | 0 (0.000) |     7.53 | CHEL00, kopi, moiss, SanduroSenshi, spacepush |
|            4 |     2459 | 2024-11-30 | T-Torturers     | W   | 0.595      | 0.143        | 0.001 (0.000)    | 0.000 (0.000)    | 1 (0.595) |     5.07 | CHEL00, chujoi, kopi, moiss, spacepush        |
|            3 |     2476 | 2024-11-30 | C4PYBARAS       | W   | 0.594      | 0.310        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.13 | CHEL00, kopi, moiss, SanduroSenshi, spacepush |
|            2 |     3026 | 2024-11-21 | Hypewrld        | L   | 0.533      | -            | -                | -                | -         |    -7.51 | CHEL00, chujoi, kopi, moiss, spacepush        |
|            1 |     3104 | 2024-11-20 | SkyFury         | L   | 0.527      | -            | -                | -                | -         |    -8.64 | CHEL00, chujoi, kopi, moiss, spacepush        |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,912.64)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-15 |      0.694 | $1,200.00      | $832.50         |
| 2024-11-30 |      0.595 | $3,496.03      | $2,080.14       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
