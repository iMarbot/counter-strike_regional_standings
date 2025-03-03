### Roster Details<br />
Team Name: InControl<br />
Roster: Beast, DYLAN, jsfeltner, milo, TyRa<br />
Global Rank: [363](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [77]( ../standings_americas.md)<br />
<br />
Final Rank Value:  618.4<br />
<br />
Final Rank Value (618.4) = Starting Rank Value (632.0) + Head To Head Adjustments (-13.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.258[<sup>1</sup>](#table2)
- Bounty Collected: 0.202[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.0
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           16 |      588 | 2025-02-10 | Exceritus                  | L   | 1.000      | -            | -                | -                | -         |   -15.16 | Beast, DYLAN, jsfeltner, milo, TyRa   |
|           15 |      626 | 2025-02-09 | Chill Guys                 | L   | 1.000      | -            | -                | -                | -         |   -12.47 | Beast, DYLAN, jsfeltner, milo, TyRa   |
|           14 |      682 | 2025-02-08 | FlyQuest RED               | W   | 1.000      | 0.143        | 0.007 (0.001)    | 0.038 (0.005)    | 0 (0.000) |    16.24 | Beast, DYLAN, jsfeltner, milo, TyRa   |
|           13 |     5133 | 2024-10-13 | FLUFFY AIMERS              | L   | 0.265      | -            | -                | -                | -         |    -2.25 | Andrew, DYLAN, jsfeltner, mason, TyRa |
|           12 |     5182 | 2024-10-12 | Fisher College             | L   | 0.260      | -            | -                | -                | -         |    -2.59 | Andrew, DYLAN, jsfeltner, mason, TyRa |
|           11 |     5193 | 2024-10-12 | MCS Gaming                 | W   | 0.259      | 0.262        | 0.003 (0.000)    | 0.343 (0.023)    | 0 (0.000) |     4.38 | Andrew, DYLAN, jsfeltner, mason, TyRa |
|           10 |     5197 | 2024-10-12 | LONG SEASON                | W   | 0.258      | 0.262        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.77 | Andrew, DYLAN, jsfeltner, mason, TyRa |
|            9 |     6436 | 2024-09-23 | Chill Guys                 | L   | 0.134      | -            | -                | -                | -         |    -1.89 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            8 |     6618 | 2024-09-20 | Regain                     | W   | 0.113      | 0.371        | 0.000 (0.000)    | 0.155 (0.007)    | 0 (0.000) |     1.12 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            7 |     6668 | 2024-09-19 | Undefined (American team)  | L   | 0.107      | -            | -                | -                | -         |    -1.72 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            6 |     6875 | 2024-09-16 | Mythic                     | L   | 0.087      | -            | -                | -                | -         |    -1.84 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            5 |     7070 | 2024-09-13 | Dangerous (Ukrainian team) | W   | 0.066      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.45 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            4 |     7230 | 2024-09-10 | Akimbo Esports             | L   | 0.047      | -            | -                | -                | -         |    -0.71 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            3 |     7280 | 2024-09-09 | Final Form                 | W   | 0.040      | 0.372        | 0.001 (0.000)    | 0.073 (0.001)    | 0 (0.000) |     0.60 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            2 |     7340 | 2024-09-08 | Straykids                  | W   | 0.033      | 0.372        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.35 | DYLAN, FIEND, jsfeltner, mason, TyRa  |
|            1 |     7557 | 2024-09-05 | Creeps                     | W   | 0.014      | 0.372        | 0.000 (0.000)    | 0.001 (0.000)    | 0 (0.000) |     0.09 | DYLAN, FIEND, jsfeltner, mason, TyRa  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($436.84)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-13 |      0.266 | $150.00        | $39.93          |
| 2024-09-21 |      0.120 | $3,300.00      | $396.92         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
