### Roster Details<br />
Team Name: PrevailANZ<br />
Roster: Agera, Anima, Grubb, gunnlock, Jacktheaus<br />
Global Rank: [574](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [92]( ../standings_asia.md)<br />
<br />
Final Rank Value:  448.3<br />
<br />
Final Rank Value (448.3) = Starting Rank Value (478.9) + Head To Head Adjustments (-30.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.158[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.040<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 478.9
- 400 + ( ( 0.040 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 478.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     1069 | 2025-01-31 | SemperFi Esports                 | L   | 1.000      | -            | -                | -                | -         |   -10.49 | Agera, Anima, Grubb, gunnlock, Jacktheaus  |
|            4 |     1071 | 2025-01-31 | Canon Event                      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.025 (0.004)    | 0 (0.000) |    17.79 | Agera, Anima, Grubb, gunnlock, Jacktheaus  |
|            3 |     1076 | 2025-01-31 | BBBCBMBS                         | L   | 1.000      | -            | -                | -                | -         |   -17.53 | Agera, Anima, Grubb, gunnlock, Jacktheaus  |
|            2 |     2289 | 2024-12-03 | Gods Work                        | L   | 0.611      | -            | -                | -                | -         |   -11.26 | Agera, Grubb, gunnlock, Jacktheaus, shrine |
|            1 |     2547 | 2024-11-30 | Above The Rest (Australian team) | L   | 0.591      | -            | -                | -                | -         |    -9.15 | Agera, Grubb, gunnlock, Jacktheaus, shrine |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
