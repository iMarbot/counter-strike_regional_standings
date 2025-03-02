### Roster Details<br />
Team Name: Team Norway<br />
Roster: Grus, sense, shyyne, SLY, Tapewaare<br />
Global Rank: [330](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [215]( ../standings_europe.md)<br />
<br />
Final Rank Value:  633.6<br />
<br />
Final Rank Value (633.6) = Starting Rank Value (607.2) + Head To Head Adjustments (26.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.016[<sup>2</sup>](#table1)
- LAN Wins: 0.170[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 607.2
- 400 + ( ( 0.104 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 607.2


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
|            5 |     3397 | 2024-11-15 | PCIFIC Espor                | W   | 0.492      | 0.617        | 0.004 (0.001)    | 0.254 (0.077)    | 1 (0.492) |    10.68 | Grus, sense, shyyne, SLY, Tapewaare |
|            4 |     3409 | 2024-11-15 | Metizport                   | L   | 0.491      | -            | -                | -                | -         |    -1.10 | Grus, sense, shyyne, SLY, Tapewaare |
|            3 |     3424 | 2024-11-14 | Homyno                      | W   | 0.487      | 0.617        | 0.008 (0.002)    | 0.192 (0.058)    | 1 (0.487) |     9.57 | Grus, sense, shyyne, SLY, Tapewaare |
|            2 |     3506 | 2024-11-13 | Mindfreak (Australian team) | W   | 0.479      | 0.617        | 0.002 (0.001)    | 0.093 (0.027)    | 1 (0.479) |     9.85 | Grus, sense, shyyne, SLY, Tapewaare |
|            1 |     3508 | 2024-11-13 | Los kogutos                 | L   | 0.479      | -            | -                | -                | -         |    -2.54 | Grus, sense, shyyne, SLY, Tapewaare |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
