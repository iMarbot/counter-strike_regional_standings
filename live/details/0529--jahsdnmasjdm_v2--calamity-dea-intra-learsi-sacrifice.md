### Roster Details<br />
Team Name: Jahsdnmasjdm v2<br />
Roster: calamity, dea, intra, LEARSI, sacrifice<br />
Global Rank: [529](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [120]( ../standings_americas.md)<br />
<br />
Final Rank Value:  488.7<br />
<br />
Final Rank Value (488.7) = Starting Rank Value (486.9) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 486.9
- 400 + ( ( 0.044 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 486.9


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
|            9 |     6348 | 2024-09-24 | Final Form                | L   | 0.148      | -            | -                | -                | -         |    -1.58 | cypress, intra, LEARSI, raw1, sacrifice |
|            8 |     6497 | 2024-09-22 | Vagrants                  | W   | 0.134      | 0.371        | 0.001 (0.000)    | 0.278 (0.014)    | 0 (0.000) |     3.06 | calamity, dea, intra, LEARSI, sacrifice |
|            7 |     6662 | 2024-09-19 | Homyno                    | L   | 0.115      | -            | -                | -                | -         |    -0.81 | cypress, intra, LEARSI, raw1, sacrifice |
|            6 |     6796 | 2024-09-17 | Familia Maquininha        | L   | 0.102      | -            | -                | -                | -         |    -0.81 | cypress, intra, LEARSI, raw1, sacrifice |
|            5 |     7118 | 2024-09-12 | Chill Guys                | W   | 0.068      | 0.371        | 0.003 (0.000)    | 0.313 (0.008)    | 0 (0.000) |     1.55 | cypress, intra, LEARSI, raw1, sacrifice |
|            4 |     7157 | 2024-09-11 | Undefined (American team) | L   | 0.062      | -            | -                | -                | -         |    -0.63 | calamity, cypress, intra, LEARSI, raw1  |
|            3 |     7270 | 2024-09-09 | Creeps                    | W   | 0.048      | 0.372        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.58 | calamity, cypress, intra, LEARSI, raw1  |
|            2 |     7373 | 2024-09-07 | MarcaRegistrada           | W   | 0.035      | 0.372        | 0.000 (0.000)    | 0.125 (0.002)    | 0 (0.000) |     0.73 | calamity, cypress, intra, LEARSI, raw1  |
|            1 |     7546 | 2024-09-05 | Straykids                 | L   | 0.022      | -            | -                | -                | -         |    -0.32 | calamity, cypress, intra, LEARSI, raw1  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
