### Roster Details<br />
Team Name: Carnival Gaming<br />
Roster: clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN<br />
Global Rank: [532](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [85]( ../standings_asia.md)<br />
<br />
Final Rank Value:  487.8<br />
<br />
Final Rank Value (487.8) = Starting Rank Value (486.0) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 486.0
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 486.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     5979 | 2024-09-29 | True Rippers Esports | L   | 0.170      | -            | -                | -                | -         |    -3.31 | clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN |
|            4 |     6057 | 2024-09-28 | Victores Sumus       | W   | 0.164      | 0.143        | 0.006 (0.000)    | 0.173 (0.004)    | 0 (0.000) |     4.31 | clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN |
|            3 |     6077 | 2024-09-28 | Firedup Gaming       | W   | 0.163      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.98 | clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN |
|            2 |     6146 | 2024-09-27 | True Rippers Esports | L   | 0.157      | -            | -                | -                | -         |    -3.05 | clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN |
|            1 |     6222 | 2024-09-26 | Project Lethals      | W   | 0.150      | 0.143        | 0.000 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     1.81 | clouda, CycloneF, EmbeR, Gh0sTTTT, SpawN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
