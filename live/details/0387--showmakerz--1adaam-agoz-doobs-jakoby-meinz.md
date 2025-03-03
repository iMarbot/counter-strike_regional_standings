### Roster Details<br />
Team Name: Showmakerz<br />
Roster: 1Adaam, agoz, Doobs, jakoby, Meinz<br />
Global Rank: [387](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [243]( ../standings_europe.md)<br />
<br />
Final Rank Value:  604.7<br />
<br />
Final Rank Value (604.7) = Starting Rank Value (603.3) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.239[<sup>1</sup>](#table2)
- Bounty Collected: 0.167[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.102<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 603.3
- 400 + ( ( 0.102 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 603.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent      | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     3954 | 2024-11-05 | Johnny Speeds | L   | 0.418      | -            | -                | -                | -         |    -1.85 | 1Adaam, agoz, Doobs, jakoby, Meinz      |
|            7 |     4197 | 2024-11-01 | NIP Svea      | W   | 0.392      | 0.143        | 0.000 (0.000)    | 0.047 (0.003)    | 0 (0.000) |     3.08 | 1Adaam, agoz, Doobs, jakoby, Meinz      |
|            6 |     5861 | 2024-10-01 | Kario Mart    | W   | 0.184      | 0.143        | 0.004 (0.000)    | 0.062 (0.002)    | 0 (0.000) |     3.09 | 1Adaam, agoz, Doobs, jakoby, Meinz      |
|            5 |     6603 | 2024-09-21 | Deathsquad    | W   | 0.116      | 0.143        | 0.000 (0.000)    | 0.011 (0.000)    | 0 (0.000) |     0.90 | 1Adaam, agoz, Doobs, jakoby, Meinz      |
|            4 |     6756 | 2024-09-18 | Lemondogs     | L   | 0.098      | -            | -                | -                | -         |    -2.07 | bsover, Doobs, jakoby, Leon1das, meinz  |
|            3 |     6990 | 2024-09-14 | KILLBOX       | L   | 0.072      | -            | -                | -                | -         |    -1.53 | 1Adaam, agoz, Doobs, jakoby, Meinz      |
|            2 |     7247 | 2024-09-10 | Megoshort     | L   | 0.045      | -            | -                | -                | -         |    -0.95 | agoz, Doobs, jakoby, Leon1das, PornyBig |
|            1 |     7304 | 2024-09-09 | GODSENT       | W   | 0.038      | 0.143        | 0.001 (0.000)    | 0.269 (0.001)    | 0 (0.000) |     0.70 | agoz, Doobs, jakoby, Leon1das, PornyBig |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($216.18)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-13 |      0.472 | $458.19        | $216.18         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
