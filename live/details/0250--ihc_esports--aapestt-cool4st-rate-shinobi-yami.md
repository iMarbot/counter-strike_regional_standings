### Roster Details<br />
Team Name: IHC Esports<br />
Roster: Aapestt, cool4st, rate, shinobi, yAmi<br />
Global Rank: [250](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [32]( ../standings_asia.md)<br />
<br />
Final Rank Value:  678.9<br />
<br />
Final Rank Value (678.9) = Starting Rank Value (693.9) + Head To Head Adjustments (-15.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.275[<sup>1</sup>](#table2)
- Bounty Collected: 0.272[<sup>2</sup>](#table1)
- Opponent Network: 0.041[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.9
- 400 + ( ( 0.147 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 693.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |      361 | 2025-02-16 | ShamanKings               | L   | 1.000      | -            | -                | -                | -         |   -22.68 | Aapestt, cool4st, rate, shinobi, yAmi |
|           17 |      371 | 2025-02-16 | Ego accendent             | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.050 (0.007)    | 0 (0.000) |    12.97 | Aapestt, cool4st, rate, shinobi, yAmi |
|           16 |      494 | 2025-02-14 | HOTU                      | L   | 1.000      | -            | -                | -                | -         |   -14.19 | cool4st, me1o, rate, shinobi, yAmi    |
|           15 |      714 | 2025-02-08 | The Huns Esports          | L   | 1.000      | -            | -                | -                | -         |    -8.69 | clouden, cool4st, me1o, rate, yAmi    |
|           14 |      721 | 2025-02-08 | Nomads (Mongolian team)   | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.407 (0.058)    | 0 (0.000) |     9.08 | clouden, cool4st, me1o, rate, yAmi    |
|           13 |      801 | 2025-02-07 | Unsettled Resentment      | W   | 1.000      | 0.143        | 0.013 (0.002)    | 0.259 (0.037)    | 0 (0.000) |    18.21 | clouden, cool4st, me1o, rate, yAmi    |
|           12 |      923 | 2025-02-05 | Eruption                  | L   | 1.000      | -            | -                | -                | -         |    -7.51 | clouden, cool4st, me1o, rate, yAmi    |
|           11 |     1314 | 2024-12-27 | Steel Helmet              | L   | 0.777      | -            | -                | -                | -         |   -17.61 | clouden, cool4st, me1o, rate, yAmi    |
|           10 |     1319 | 2024-12-27 | The Huns Esports          | L   | 0.776      | -            | -                | -                | -         |    -7.48 | clouden, cool4st, me1o, rate, yAmi    |
|            9 |     1334 | 2024-12-27 | ATOX Esports              | L   | 0.771      | -            | -                | -                | -         |    -2.72 | clouden, cool4st, me1o, rate, yAmi    |
|            8 |     1342 | 2024-12-26 | Eruption                  | L   | 0.769      | -            | -                | -                | -         |    -7.80 | clouden, cool4st, me1o, rate, yAmi    |
|            7 |     2137 | 2024-12-06 | Chinggis Warriors         | L   | 0.631      | -            | -                | -                | -         |    -5.90 | clouden, cool4st, me1o, rate, yAmi    |
|            6 |     2234 | 2024-12-04 | Just Swing (Chinese team) | W   | 0.617      | 0.333        | 0.005 (0.001)    | 0.351 (0.072)    | 0 (0.000) |    10.82 | clouden, cool4st, me1o, rate, yAmi    |
|            5 |     2236 | 2024-12-03 | ATOX Esports              | W   | 0.617      | 0.333        | 0.064 (0.013)    | 0.604 (0.124)    | 0 (0.000) |    17.52 | clouden, cool4st, me1o, rate, yAmi    |
|            4 |     2910 | 2024-11-22 | Just Swing (Chinese team) | L   | 0.544      | -            | -                | -                | -         |    -7.72 | cool4st, hasteka, me1o, rate, yAmi    |
|            3 |     2991 | 2024-11-22 | The Huns Esports          | W   | 0.538      | 0.333        | 0.025 (0.004)    | 0.557 (0.100)    | 0 (0.000) |    12.82 | cool4st, hasteka, me1o, rate, yAmi    |
|            2 |     3132 | 2024-11-19 | ATOX Esports              | L   | 0.524      | -            | -                | -                | -         |    -1.54 | cool4st, hasteka, me1o, rate, yAmi    |
|            1 |     3134 | 2024-11-19 | CatEvil                   | W   | 0.523      | 0.333        | 0.000 (0.000)    | 0.093 (0.016)    | 0 (0.000) |     7.41 | cool4st, hasteka, me1o, rate, yAmi    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($784.03)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-29 |      0.784 | $1,000.00      | $784.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
