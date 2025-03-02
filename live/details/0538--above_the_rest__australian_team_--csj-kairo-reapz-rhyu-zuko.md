### Roster Details<br />
Team Name: Above The Rest (Australian team)<br />
Roster: csJ, kairo, Reapz, Rhyu, Zuko<br />
Global Rank: [538](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [86]( ../standings_asia.md)<br />
<br />
Final Rank Value:  484.9<br />
<br />
Final Rank Value (484.9) = Starting Rank Value (479.5) + Head To Head Adjustments (5.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.157[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 479.5
- 400 + ( ( 0.040 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 479.5


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
|            9 |     1723 | 2024-12-14 | Underground Esports Club | L   | 0.684      | -            | -                | -                | -         |    -7.17 | csJ, kairo, Reapz, Rhyu, Zuko |
|            8 |     1813 | 2024-12-13 | MANTRA                   | L   | 0.677      | -            | -                | -                | -         |    -7.46 | csJ, kairo, Reapz, Rhyu, Zuko |
|            7 |     1850 | 2024-12-12 | Rebound                  | W   | 0.671      | 0.143        | 0.000 (0.000)    | 0.037 (0.004)    | 0 (0.000) |    10.75 | csJ, kairo, Reapz, Rhyu, Zuko |
|            6 |     1899 | 2024-12-11 | TALON                    | L   | 0.664      | -            | -                | -                | -         |    -8.10 | csJ, kairo, Reapz, Rhyu, Zuko |
|            5 |     1936 | 2024-12-10 | Rebound                  | W   | 0.657      | 0.143        | 0.000 (0.000)    | 0.037 (0.004)    | 0 (0.000) |    10.63 | csJ, kairo, Reapz, Rhyu, Zuko |
|            4 |     2094 | 2024-12-07 | Underground Esports Club | L   | 0.638      | -            | -                | -                | -         |    -6.35 | csJ, kairo, Reapz, Rhyu, Zuko |
|            3 |     2282 | 2024-12-03 | Vantage Esports          | L   | 0.611      | -            | -                | -                | -         |    -5.78 | csJ, kairo, Reapz, Rhyu, Zuko |
|            2 |     2357 | 2024-12-02 | Shanghai Sharks          | W   | 0.604      | 0.270        | 0.000 (0.000)    | 0.057 (0.009)    | 0 (0.000) |     9.72 | csJ, kairo, Reapz, Rhyu, Zuko |
|            1 |     2547 | 2024-11-30 | PrevailANZ               | W   | 0.591      | 0.270        | 0.000 (0.000)    | 0.047 (0.007)    | 0 (0.000) |     9.15 | csJ, kairo, Reapz, Rhyu, Zuko |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
