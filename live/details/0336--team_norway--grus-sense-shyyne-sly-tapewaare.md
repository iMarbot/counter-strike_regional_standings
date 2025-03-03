### Roster Details<br />
Team Name: Team Norway<br />
Roster: Grus, sense, shyyne, SLY, Tapewaare<br />
Global Rank: [336](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [217]( ../standings_europe.md)<br />
<br />
Final Rank Value:  632.0<br />
<br />
Final Rank Value (632.0) = Starting Rank Value (605.9) + Head To Head Adjustments (26.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.168[<sup>2</sup>](#table1)

The average of these factors is 0.103<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 605.9
- 400 + ( ( 0.103 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 605.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     3409 | 2024-11-15 | PCIFIC Espor                | W   | 0.484      | 0.617        | 0.004 (0.001)    | 0.251 (0.075)    | 1 (0.484) |    10.51 | Grus, sense, shyyne, SLY, Tapewaare |
|            4 |     3421 | 2024-11-15 | Metizport                   | L   | 0.483      | -            | -                | -                | -         |    -1.09 | Grus, sense, shyyne, SLY, Tapewaare |
|            3 |     3436 | 2024-11-14 | Homyno                      | W   | 0.479      | 0.617        | 0.008 (0.002)    | 0.189 (0.056)    | 1 (0.479) |     9.45 | Grus, sense, shyyne, SLY, Tapewaare |
|            2 |     3518 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.471      | 0.617        | 0.002 (0.001)    | 0.091 (0.026)    | 1 (0.471) |     9.68 | Grus, sense, shyyne, SLY, Tapewaare |
|            1 |     3520 | 2024-11-13 | Los kogutos                 | L   | 0.470      | -            | -                | -                | -         |    -2.49 | Grus, sense, shyyne, SLY, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
