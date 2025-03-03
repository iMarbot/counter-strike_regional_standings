### Roster Details<br />
Team Name: Jahsdnmasjdm v2<br />
Roster: calamity, dea, intra, LEARSI, sacrifice<br />
Global Rank: [533](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [121]( ../standings_americas.md)<br />
<br />
Final Rank Value:  487.8<br />
<br />
Final Rank Value (487.8) = Starting Rank Value (486.2) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.170[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 486.2
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 486.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     6360 | 2024-09-24 | Final Form                | L   | 0.139      | -            | -                | -                | -         |    -1.49 | cypress, intra, LEARSI, raw1, sacrifice |
|            8 |     6509 | 2024-09-22 | Vagrants                  | W   | 0.126      | 0.371        | 0.001 (0.000)    | 0.276 (0.013)    | 0 (0.000) |     2.87 | calamity, dea, intra, LEARSI, sacrifice |
|            7 |     6674 | 2024-09-19 | Homyno                    | L   | 0.107      | -            | -                | -                | -         |    -0.75 | cypress, intra, LEARSI, raw1, sacrifice |
|            6 |     6808 | 2024-09-17 | Familia Maquininha        | L   | 0.093      | -            | -                | -                | -         |    -0.76 | cypress, intra, LEARSI, raw1, sacrifice |
|            5 |     7130 | 2024-09-12 | Chill Guys                | W   | 0.059      | 0.371        | 0.003 (0.000)    | 0.310 (0.007)    | 0 (0.000) |     1.37 | cypress, intra, LEARSI, raw1, sacrifice |
|            4 |     7169 | 2024-09-11 | Undefined (American team) | L   | 0.054      | -            | -                | -                | -         |    -0.55 | calamity, cypress, intra, LEARSI, raw1  |
|            3 |     7282 | 2024-09-09 | Creeps                    | W   | 0.040      | 0.372        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.48 | calamity, cypress, intra, LEARSI, raw1  |
|            2 |     7385 | 2024-09-07 | MarcaRegistrada           | W   | 0.027      | 0.372        | 0.000 (0.000)    | 0.124 (0.001)    | 0 (0.000) |     0.56 | calamity, cypress, intra, LEARSI, raw1  |
|            1 |     7558 | 2024-09-05 | Straykids                 | L   | 0.014      | -            | -                | -                | -         |    -0.20 | calamity, cypress, intra, LEARSI, raw1  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
