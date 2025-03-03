### Roster Details<br />
Team Name: Team PeeP<br />
Roster: bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN<br />
Global Rank: [528](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [327]( ../standings_europe.md)<br />
<br />
Final Rank Value:  490.0<br />
<br />
Final Rank Value (490.0) = Starting Rank Value (488.9) + Head To Head Adjustments (1.1)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.177[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.044<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 488.9
- 400 + ( ( 0.044 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 488.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     7314 | 2024-09-09 | Passion UA       | L   | 0.037      | -            | -                | -                | -         |    -0.05 | bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN |
|            4 |     7435 | 2024-09-07 | UNiTY esports    | W   | 0.024      | 0.372        | 0.025 (0.000)    | 0.403 (0.004)    | 0 (0.000) |     0.66 | bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN |
|            3 |     7502 | 2024-09-06 | FLuffy Gangsters | L   | 0.019      | -            | -                | -                | -         |    -0.09 | bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN |
|            2 |     7506 | 2024-09-06 | Flame Sharks     | W   | 0.018      | 0.221        | 0.000 (0.000)    | 0.167 (0.001)    | 0 (0.000) |     0.41 | bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN |
|            1 |     7514 | 2024-09-06 | GLADIATORS       | W   | 0.018      | 0.221        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.21 | bogemtdarf, Brilliance, GREATEST, la3euka, YumsaN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
