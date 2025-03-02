### Roster Details<br />
Team Name: Real Original Gaming<br />
Roster: BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89<br />
Global Rank: [169](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [16]( ../standings_asia.md)<br />
<br />
Final Rank Value:  738.9<br />
<br />
Final Rank Value (738.9) = Starting Rank Value (705.6) + Head To Head Adjustments (33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.325[<sup>1</sup>](#table2)
- Bounty Collected: 0.229[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.048[<sup>2</sup>](#table1)

The average of these factors is 0.153<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 705.6
- 400 + ( ( 0.153 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 705.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2535 | 2024-11-30 | Gods Reign    | W   | 0.592      | 0.333        | 0.018 (0.004)    | 0.412 (0.081)    | 0 (0.000) |    12.42 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |
|            5 |     2802 | 2024-11-24 | Ego accendent | W   | 0.552      | 0.333        | 0.002 (0.000)    | 0.050 (0.009)    | 0 (0.000) |     6.80 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |
|            4 |     2899 | 2024-11-23 | -72C          | W   | 0.545      | 0.333        | 0.001 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     4.32 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |
|            3 |     4094 | 2024-11-02 | Ego accendent | W   | 0.410      | 0.143        | 0.002 (0.000)    | 0.050 (0.003)    | 1 (0.410) |     5.14 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |
|            2 |     5223 | 2024-10-12 | Ego accendent | W   | 0.265      | 0.143        | 0.002 (0.000)    | 0.050 (0.002)    | 0 (0.000) |     3.39 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |
|            1 |     5266 | 2024-10-11 | GHOSTprotocol | W   | 0.258      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 0 (0.000) |     1.24 | BoonRywin, Geniuss, MAIROLLS, RoLEX, SeveN89 |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,849.37)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-30 |      0.592 | $4,000.00      | $2,366.67       |
| 2024-11-02 |      0.410 | $1,177.33      | $482.71         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
