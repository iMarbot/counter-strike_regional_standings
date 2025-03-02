### Roster Details<br />
Team Name: IHC Esports<br />
Roster: AccuracyTG, efire, rate, ROUX, Zesta<br />
Global Rank: [268](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [36]( ../standings_asia.md)<br />
<br />
Final Rank Value:  668.3<br />
<br />
Final Rank Value (668.3) = Starting Rank Value (660.8) + Head To Head Adjustments (7.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.287[<sup>1</sup>](#table2)
- Bounty Collected: 0.225[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.131<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 660.8
- 400 + ( ( 0.131 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 660.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3808 | 2024-11-08 | Ex-GR Gaming                  | L   | 0.444      | -            | -                | -                | -         |    -5.87 | AccuracyTG, efire, rate, ROUX, Zesta |
|            4 |     3813 | 2024-11-07 | The Huns Esports              | W   | 0.443      | 0.333        | 0.025 (0.004)    | 0.557 (0.082)    | 0 (0.000) |    11.47 | AccuracyTG, efire, rate, ROUX, Zesta |
|            3 |     3860 | 2024-11-06 | Clutch Gaming                 | W   | 0.437      | 0.333        | 0.000 (0.000)    | 0.055 (0.008)    | 0 (0.000) |     4.98 | AccuracyTG, efire, rate, ROUX, Zesta |
|            2 |     3960 | 2024-11-04 | Ex-GR Gaming                  | L   | 0.424      | -            | -                | -                | -         |    -5.70 | AccuracyTG, efire, rate, ROUX, Zesta |
|            1 |     3961 | 2024-11-04 | NOVA Esports (Mongolian team) | W   | 0.423      | 0.333        | 0.000 (0.000)    | 0.038 (0.005)    | 0 (0.000) |     2.65 | AccuracyTG, efire, rate, ROUX, Zesta |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,111.23)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-08 |      0.444 | $2,500.00      | $1,111.23       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
