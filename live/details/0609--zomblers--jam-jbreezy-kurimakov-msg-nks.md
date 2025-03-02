### Roster Details<br />
Team Name: Zomblers<br />
Roster: JAM, JBreezy, KURIMAKOV, MSG, Nks<br />
Global Rank: [609](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [140]( ../standings_americas.md)<br />
<br />
Final Rank Value:  396.8<br />
<br />
Final Rank Value (396.8) = Starting Rank Value (400.0) + Head To Head Adjustments (-3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |      814 | 2025-02-06 | MIGHT                | L   | 1.000      | -            | -                | -                | -         |    -4.89 | JAM, JBreezy, KURIMAKOV, MSG, Nks   |
|            5 |      815 | 2025-02-06 | M80                  | L   | 1.000      | -            | -                | -                | -         |    -1.35 | JAM, JBreezy, KURIMAKOV, MSG, Nks   |
|            4 |      826 | 2025-02-06 | Be Together Win      | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    15.62 | JAM, JBreezy, KURIMAKOV, MSG, Nks   |
|            3 |     1749 | 2024-12-13 | Final Form           | L   | 0.682      | -            | -                | -                | -         |    -4.75 | JAM, KURIMAKOV, MSG, Nks, ronin     |
|            2 |     2384 | 2024-12-01 | Vibe (American team) | L   | 0.602      | -            | -                | -                | -         |    -4.71 | Caffrey, KURIMAKOV, MSG, Nks, no1nx |
|            1 |     2689 | 2024-11-26 | Chicken Coop Esports | L   | 0.569      | -            | -                | -                | -         |    -3.16 | Caffrey, KURIMAKOV, MSG, Nks, no1nx |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
