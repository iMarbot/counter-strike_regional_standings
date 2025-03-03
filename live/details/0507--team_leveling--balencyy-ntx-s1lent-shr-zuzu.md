### Roster Details<br />
Team Name: Team Leveling<br />
Roster: balencyy, ntx, s1lent, shr, zuzu<br />
Global Rank: [507](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [115]( ../standings_americas.md)<br />
<br />
Final Rank Value:  507.1<br />
<br />
Final Rank Value (507.1) = Starting Rank Value (483.6) + Head To Head Adjustments (23.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.160[<sup>2</sup>](#table1)
- Opponent Network: 0.007[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.042<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 483.6
- 400 + ( ( 0.042 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 483.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                    | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     2079 | 2024-12-07 | New Generation Academy      | L   | 0.632      | -            | -                | -                | -         |    -7.89 | balencyy, ntx, s1lent, shr, zuzu |
|           17 |     2405 | 2024-12-01 | 9z Academy                  | L   | 0.593      | -            | -                | -                | -         |    -5.95 | balencyy, ntx, s1lent, shr, zuzu |
|           16 |     2409 | 2024-12-01 | Sharks Youngsters           | W   | 0.592      | 0.143        | 0.000 (0.000)    | 0.095 (0.008)    | 0 (0.000) |    10.96 | balencyy, ntx, s1lent, shr, zuzu |
|           15 |     2480 | 2024-11-30 | LaChampionsLiga             | L   | 0.586      | -            | -                | -                | -         |    -6.13 | balencyy, ntx, s1lent, shr, zuzu |
|           14 |     2505 | 2024-11-30 | New Legacy (Brazilian team) | W   | 0.585      | 0.143        | 0.000 (0.000)    | 0.026 (0.002)    | 0 (0.000) |    10.92 | balencyy, ntx, s1lent, shr, zuzu |
|           13 |     3109 | 2024-11-20 | Nitro.GG                    | L   | 0.519      | -            | -                | -                | -         |    -4.83 | balencyy, ntx, s1lent, shr, zuzu |
|           12 |     3434 | 2024-11-14 | Yawara E-Sports             | L   | 0.479      | -            | -                | -                | -         |    -3.64 | balencyy, ntx, s1lent, shr, zuzu |
|           11 |     3594 | 2024-11-11 | América eSports             | W   | 0.460      | 0.143        | 0.000 (0.000)    | 0.426 (0.028)    | 0 (0.000) |     8.84 | balencyy, ntx, s1lent, shr, zuzu |
|           10 |     3657 | 2024-11-10 | INTERDIT                    | W   | 0.452      | 0.143        | 0.000 (0.000)    | 0.155 (0.010)    | 0 (0.000) |     9.34 | balencyy, ntx, s1lent, shr, zuzu |
|            9 |     3707 | 2024-11-09 | Sharks Youngsters           | L   | 0.446      | -            | -                | -                | -         |    -5.59 | balencyy, ntx, s1lent, shr, zuzu |
|            8 |     3717 | 2024-11-09 | BeBold.gg                   | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.020 (0.001)    | 0 (0.000) |     7.94 | balencyy, ntx, s1lent, shr, zuzu |
|            7 |     4410 | 2024-10-28 | Floripa Stars               | L   | 0.366      | -            | -                | -                | -         |    -3.32 | balencyy, ntx, s1lent, shr, zuzu |
|            6 |     4703 | 2024-10-22 | MIBR Academy                | L   | 0.325      | -            | -                | -                | -         |    -2.72 | balencyy, ntx, s1lent, shr, zuzu |
|            5 |     5053 | 2024-10-15 | DB Peek Esports             | W   | 0.279      | 0.143        | 0.000 (0.000)    | 0.236 (0.009)    | 0 (0.000) |     5.84 | balencyy, ntx, s1lent, shr, zuzu |
|            4 |     5059 | 2024-10-15 | SamuraiS (Brazilian team)   | W   | 0.278      | 0.143        | 0.000 (0.000)    | 0.154 (0.006)    | 0 (0.000) |     4.49 | balencyy, ntx, s1lent, shr, zuzu |
|            3 |     5518 | 2024-10-06 | Nitro.GG                    | L   | 0.219      | -            | -                | -                | -         |    -1.77 | balencyy, ntx, s1lent, shr, zuzu |
|            2 |     5570 | 2024-10-05 | INTERDIT                    | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.155 (0.005)    | 0 (0.000) |     4.50 | balencyy, ntx, s1lent, shr, zuzu |
|            1 |     5582 | 2024-10-05 | Smoke Academy               | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.56 | balencyy, ntx, s1lent, shr, zuzu |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
