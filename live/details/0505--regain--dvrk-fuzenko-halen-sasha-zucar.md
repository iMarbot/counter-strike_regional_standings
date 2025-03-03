### Roster Details<br />
Team Name: Regain<br />
Roster: dvrk, Fuzenko, Halen, sasha, Zucar<br />
Global Rank: [505](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [114]( ../standings_americas.md)<br />
<br />
Final Rank Value:  509.1<br />
<br />
Final Rank Value (509.1) = Starting Rank Value (488.5) + Head To Head Adjustments (20.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.5
- 400 + ( ( 0.044 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 488.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      398 | 2025-02-15 | MCS Gaming         | L   | 1.000      | -            | -                | -                | -         |    -9.27 | dvrk, Fuzenko, Halen, sasha, Zucar    |
|           13 |      400 | 2025-02-15 | HbITuKu            | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |    11.33 | dvrk, Fuzenko, Halen, sasha, Zucar    |
|           12 |      451 | 2025-02-14 | Aetheris           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.141 (0.020)    | 0 (0.000) |    10.94 | dvrk, Fuzenko, Halen, sasha, Zucar    |
|           11 |     2325 | 2024-12-02 | Bad Boys           | L   | 0.601      | -            | -                | -                | -         |    -5.71 | dvrk, emothug, Halen, sasha, Zucar    |
|           10 |     2400 | 2024-12-01 | Guangdong Tigers   | W   | 0.594      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     6.76 | dvrk, emothug, Halen, sasha, Zucar    |
|            9 |     2580 | 2024-11-29 | MIGHT              | L   | 0.581      | -            | -                | -                | -         |    -2.94 | dvrk, emothug, Halen, sasha, Zucar    |
|            8 |     2697 | 2024-11-26 | VitaPLUR           | W   | 0.561      | 0.372        | 0.000 (0.000)    | 0.005 (0.001)    | 0 (0.000) |     8.91 | dvrk, emothug, Halen, sasha, Zucar    |
|            7 |     6618 | 2024-09-20 | InControl          | L   | 0.113      | -            | -                | -                | -         |    -1.12 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            6 |     6922 | 2024-09-15 | What's for Dinner  | W   | 0.080      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.95 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            5 |     7123 | 2024-09-12 | MIGHT              | L   | 0.060      | -            | -                | -                | -         |    -0.28 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            4 |     7229 | 2024-09-10 | SUPER EVIL GANG    | W   | 0.047      | 0.372        | 0.009 (0.000)    | 0.352 (0.006)    | 0 (0.000) |     1.12 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            3 |     7234 | 2024-09-10 | Familia Maquininha | L   | 0.046      | -            | -                | -                | -         |    -0.38 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            2 |     7339 | 2024-09-08 | LONG SEASON        | W   | 0.033      | 0.372        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.40 | dvrk, hunger, Pose1doNN, sasha, Zucar |
|            1 |     7554 | 2024-09-05 | Homyno             | L   | 0.014      | -            | -                | -                | -         |    -0.10 | dvrk, hunger, Pose1doNN, sasha, Zucar |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
