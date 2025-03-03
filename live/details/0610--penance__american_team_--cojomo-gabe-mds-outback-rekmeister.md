### Roster Details<br />
Team Name: Penance (American Team)<br />
Roster: CoJoMo, Gabe, mds, Outback, REKMEISTER<br />
Global Rank: [610](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [142]( ../standings_americas.md)<br />
<br />
Final Rank Value:  396.9<br />
<br />
Final Rank Value (396.9) = Starting Rank Value (400.0) + Head To Head Adjustments (-3.1)<br />

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
- 400 + ( ( 0.000 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     4838 | 2024-10-19 | Fisher College    | L   | 0.307      | -            | -                | -                | -         |    -1.02 | CoJoMo, Gabe, mds, Outback, REKMEISTER |
|            4 |     6512 | 2024-09-22 | Lore Gaming       | L   | 0.125      | -            | -                | -                | -         |    -1.97 | CoJoMo, Gabe, Louie, mds, shutout      |
|            3 |     6630 | 2024-09-20 | Final Form        | L   | 0.113      | -            | -                | -                | -         |    -0.84 | CoJoMo, Gabe, Louie, mds, shutout      |
|            2 |     6876 | 2024-09-16 | Undone            | L   | 0.086      | -            | -                | -                | -         |    -0.29 | CoJoMo, Gabe, Louie, mds, shutout      |
|            1 |     7069 | 2024-09-13 | What's for Dinner | W   | 0.067      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.05 | CoJoMo, Gabe, Louie, mds, shutout      |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
