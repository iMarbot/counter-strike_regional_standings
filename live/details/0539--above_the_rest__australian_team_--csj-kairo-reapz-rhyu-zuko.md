### Roster Details<br />
Team Name: Above The Rest (Australian team)<br />
Roster: csJ, kairo, Reapz, Rhyu, Zuko<br />
Global Rank: [539](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [86]( ../standings_asia.md)<br />
<br />
Final Rank Value:  484.7<br />
<br />
Final Rank Value (484.7) = Starting Rank Value (479.3) + Head To Head Adjustments (5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.156[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 479.3
- 400 + ( ( 0.040 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 479.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |     1735 | 2024-12-14 | Underground Esports Club | L   | 0.676      | -            | -                | -                | -         |    -7.07 | csJ, kairo, Reapz, Rhyu, Zuko |
|            8 |     1825 | 2024-12-13 | MANTRA                   | L   | 0.669      | -            | -                | -                | -         |    -7.35 | csJ, kairo, Reapz, Rhyu, Zuko |
|            7 |     1862 | 2024-12-12 | Rebound                  | W   | 0.663      | 0.143        | 0.000 (0.000)    | 0.036 (0.003)    | 0 (0.000) |    10.62 | csJ, kairo, Reapz, Rhyu, Zuko |
|            6 |     1911 | 2024-12-11 | TALON                    | L   | 0.656      | -            | -                | -                | -         |    -8.02 | csJ, kairo, Reapz, Rhyu, Zuko |
|            5 |     1948 | 2024-12-10 | Rebound                  | W   | 0.649      | 0.143        | 0.000 (0.000)    | 0.036 (0.003)    | 0 (0.000) |    10.50 | csJ, kairo, Reapz, Rhyu, Zuko |
|            4 |     2106 | 2024-12-07 | Underground Esports Club | L   | 0.629      | -            | -                | -                | -         |    -6.26 | csJ, kairo, Reapz, Rhyu, Zuko |
|            3 |     2294 | 2024-12-03 | Vantage Esports          | L   | 0.603      | -            | -                | -                | -         |    -5.68 | csJ, kairo, Reapz, Rhyu, Zuko |
|            2 |     2369 | 2024-12-02 | Shanghai Sharks          | W   | 0.596      | 0.270        | 0.000 (0.000)    | 0.057 (0.009)    | 0 (0.000) |     9.60 | csJ, kairo, Reapz, Rhyu, Zuko |
|            1 |     2559 | 2024-11-30 | PrevailANZ               | W   | 0.583      | 0.270        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     9.04 | csJ, kairo, Reapz, Rhyu, Zuko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
