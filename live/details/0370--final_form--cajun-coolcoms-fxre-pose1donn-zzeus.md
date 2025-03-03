### Roster Details<br />
Team Name: Final Form<br />
Roster: CAJUN, CoolComs, FxRE, Pose1doNN, Zzeus<br />
Global Rank: [370](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [80]( ../standings_americas.md)<br />
<br />
Final Rank Value:  611.1<br />
<br />
Final Rank Value (611.1) = Starting Rank Value (610.9) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.236[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.105<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.9
- 400 + ( ( 0.105 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 610.9


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
|           16 |     1758 | 2024-12-13 | Make Your Mind            | L   | 0.674      | -            | -                | -                | -         |    -6.72 | CAJUN, CoolComs, FxRE, Pose1doNN, Zzeus |
|           15 |     1761 | 2024-12-13 | Zomblers                  | W   | 0.674      | 0.143        | 0.000 (0.000)    | 0.047 (0.005)    | 0 (0.000) |     4.71 | CAJUN, CoolComs, FxRE, Pose1doNN, Zzeus |
|           14 |     5181 | 2024-10-12 | FLUFFY AIMERS             | L   | 0.260      | -            | -                | -                | -         |    -2.07 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|           13 |     5183 | 2024-10-12 | After Hours               | W   | 0.260      | 0.262        | 0.000 (0.000)    | 0.024 (0.002)    | 0 (0.000) |     1.97 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|           12 |     5187 | 2024-10-12 | Fisher College            | L   | 0.259      | -            | -                | -                | -         |    -2.42 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|           11 |     5195 | 2024-10-12 | FLUFFY AIMERS             | W   | 0.258      | 0.262        | 0.005 (0.000)    | 0.213 (0.014)    | 0 (0.000) |     6.13 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|           10 |     5841 | 2024-10-01 | NRG                       | L   | 0.186      | -            | -                | -                | -         |    -0.54 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|            9 |     6360 | 2024-09-24 | Jahsdnmasjdm v2           | W   | 0.139      | 0.371        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     1.49 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|            8 |     6505 | 2024-09-22 | Familia Maquininha        | L   | 0.127      | -            | -                | -                | -         |    -1.64 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|            7 |     6630 | 2024-09-20 | Penance (American Team)   | W   | 0.113      | 0.371        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.84 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|            6 |     6920 | 2024-09-15 | Undefined (American team) | L   | 0.080      | -            | -                | -                | -         |    -1.23 | CAJUN, CoolComs, Drop, FxRE, Zzeus      |
|            5 |     6972 | 2024-09-14 | Lore Gaming               | W   | 0.073      | 0.371        | 0.000 (0.000)    | 0.017 (0.000)    | 0 (0.000) |     0.55 | CAJUN, CoolComs, Drop, FxRE, YNGHunter  |
|            4 |     7228 | 2024-09-10 | Mythic                    | L   | 0.047      | -            | -                | -                | -         |    -0.96 | CAJUN, CoolComs, Drop, FxRE, Zzeus      |
|            3 |     7280 | 2024-09-09 | InControl                 | L   | 0.040      | -            | -                | -                | -         |    -0.60 | CAJUN, CoolComs, Drop, FxRE, Zzeus      |
|            2 |     7382 | 2024-09-07 | MIGHT                     | W   | 0.027      | 0.372        | 0.002 (0.000)    | 0.489 (0.005)    | 0 (0.000) |     0.63 | CAJUN, CoolComs, Drop, FxRE, Zzeus      |
|            1 |     7556 | 2024-09-05 | Eefsports                 | W   | 0.014      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.10 | CAJUN, CoolComs, Drop, FxRE, Zzeus      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($190.27)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-13 |      0.266 | $150.00        | $39.93          |
| 2024-09-21 |      0.120 | $1,250.00      | $150.35         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
