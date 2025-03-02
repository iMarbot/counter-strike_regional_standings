### Roster Details<br />
Team Name: E9 Esports<br />
Roster: 1230, neverland, Tikkkkk, YellowpandaYC, Yolo267<br />
Global Rank: [570](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [91]( ../standings_asia.md)<br />
<br />
Final Rank Value:  459.5<br />
<br />
Final Rank Value (459.5) = Starting Rank Value (506.3) + Head To Head Adjustments (-46.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.053<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 506.3
- 400 + ( ( 0.053 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 506.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |      114 | 2025-02-22 | Shika                | L   | 1.000      | -            | -                | -                | -         |   -10.59 | 1230, neverland, Tikkkkk, YellowpandaYC, Yolo267 |
|            4 |      435 | 2025-02-14 | Loveset              | L   | 1.000      | -            | -                | -                | -         |   -19.02 | 1230, Neverland, Tikkkkk, YellowPandaYC, Yolo267 |
|            3 |      445 | 2025-02-14 | TangSongYuanMingQing | L   | 1.000      | -            | -                | -                | -         |   -19.60 | 1230, Neverland, Tikkkkk, YellowPandaYC, Yolo267 |
|            2 |      865 | 2025-02-05 | Believe.             | L   | 1.000      | -            | -                | -                | -         |   -16.35 | 1230, neverland, Tikkkkk, YellowpandaYC, Yolo267 |
|            1 |     1234 | 2024-12-30 | Bromo                | W   | 0.796      | 0.143        | 0.016 (0.002)    | 0.141 (0.016)    | 0 (0.000) |    18.80 | 1230, neverland, Tikkkkk, YellowpandaYC, Ygg     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
