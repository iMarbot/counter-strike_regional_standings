### Roster Details<br />
Team Name: Nova holanda<br />
Roster: bks, dudinho, fP1, kirill, t9mpest<br />
Global Rank: [417](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [96]( ../standings_americas.md)<br />
<br />
Final Rank Value:  587.2<br />
<br />
Final Rank Value (587.2) = Starting Rank Value (596.7) + Head To Head Adjustments (-9.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.217[<sup>1</sup>](#table2)
- Bounty Collected: 0.172[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 596.7
- 400 + ( ( 0.098 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 596.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            9 |      947 | 2025-02-04 | Elevate                  | L   | 1.000      | -            | -                | -                | -         |   -17.91 | bks, dudinho, fP1, kirill, t9mpest  |
|            8 |     1689 | 2024-12-14 | SixBullets               | W   | 0.679      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     7.61 | bks, fP1, kirill, predict, t9mpest  |
|            7 |     3708 | 2024-11-09 | INTERDIT                 | L   | 0.446      | -            | -                | -                | -         |    -6.89 | bks, fP1, kirill, predict, Straafer |
|            6 |     3715 | 2024-11-09 | DB Peek Esports          | L   | 0.445      | -            | -                | -                | -         |    -6.74 | bks, fP1, kirill, predict, Straafer |
|            5 |     3875 | 2024-11-06 | Players (Brazilian team) | L   | 0.426      | -            | -                | -                | -         |    -4.20 | bks, fP1, kirill, predict, Straafer |
|            4 |     3982 | 2024-11-04 | INTERDIT                 | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.155 (0.009)    | 0 (0.000) |     6.72 | bks, fP1, kirill, predict, Straafer |
|            3 |     4120 | 2024-11-02 | DB Peek Esports          | W   | 0.399      | 0.143        | 0.000 (0.000)    | 0.236 (0.013)    | 0 (0.000) |     6.39 | bks, fP1, kirill, predict, Straafer |
|            2 |     4127 | 2024-11-02 | Game Hunters             | W   | 0.398      | 0.143        | 0.003 (0.000)    | 0.392 (0.022)    | 0 (0.000) |     8.16 | bks, fP1, kirill, predict, Straafer |
|            1 |     5583 | 2024-10-05 | Nitro.GG                 | L   | 0.212      | -            | -                | -                | -         |    -2.60 | bks, fP1, leozik4, predict, t9mpest |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($79.28)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.679 | $82.75         | $56.17          |
| 2024-11-08 |      0.439 | $52.69         | $23.11          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
