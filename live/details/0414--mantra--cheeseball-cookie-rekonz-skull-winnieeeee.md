### Roster Details<br />
Team Name: MANTRA<br />
Roster: cheeseball, cookie, rekonz, SkulL, Winnieeeee<br />
Global Rank: [414](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [69]( ../standings_asia.md)<br />
<br />
Final Rank Value:  585.5<br />
<br />
Final Rank Value (585.5) = Starting Rank Value (616.0) + Head To Head Adjustments (-30.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.220[<sup>1</sup>](#table2)
- Bounty Collected: 0.203[<sup>2</sup>](#table1)
- Opponent Network: 0.010[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.108<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 616.0
- 400 + ( ( 0.108 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 616.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |       36 | 2025-02-25 | KZG                              | L   | 1.000      | -            | -                | -                | -         |   -14.66 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           17 |       54 | 2025-02-24 | Rooster                          | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.222 (0.032)    | 0 (0.000) |    19.71 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           16 |       75 | 2025-02-23 | TALON                            | L   | 1.000      | -            | -                | -                | -         |   -14.69 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           15 |      381 | 2025-02-15 | Justice For Tomorrow             | L   | 1.000      | -            | -                | -                | -         |   -12.14 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           14 |      385 | 2025-02-15 | BBBCBMBS                         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |     7.84 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           13 |      450 | 2025-02-14 | Vantage Esports                  | L   | 1.000      | -            | -                | -                | -         |   -13.47 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           12 |     1650 | 2024-12-15 | Underground Esports Club         | W   | 0.691      | 0.143        | 0.001 (0.000)    | 0.242 (0.024)    | 0 (0.000) |    11.16 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           11 |     1722 | 2024-12-14 | TALON                            | L   | 0.684      | -            | -                | -                | -         |   -11.14 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           10 |     1813 | 2024-12-13 | Above The Rest (Australian team) | W   | 0.677      | 0.143        | 0.000 (0.000)    | 0.087 (0.008)    | 0 (0.000) |     7.46 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|            9 |     5297 | 2024-10-10 | Rooster                          | L   | 0.251      | -            | -                | -                | -         |    -3.29 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            8 |     5298 | 2024-10-10 | Rooster                          | W   | 0.251      | 0.333        | 0.005 (0.000)    | 0.222 (0.019)    | 0 (0.000) |     4.69 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            7 |     5364 | 2024-10-09 | Only One Word                    | L   | 0.244      | -            | -                | -                | -         |    -3.45 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            6 |     5368 | 2024-10-09 | Only One Word                    | L   | 0.244      | -            | -                | -                | -         |    -3.52 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            5 |     5634 | 2024-10-04 | Vantage Esports                  | L   | 0.216      | -            | -                | -                | -         |    -3.06 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            4 |     5636 | 2024-10-04 | Above The Rest (Australian team) | W   | 0.216      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.58 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            3 |     5640 | 2024-10-04 | Housebets                        | L   | 0.215      | -            | -                | -                | -         |    -3.32 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            2 |     6316 | 2024-09-25 | DXA Esports                      | W   | 0.151      | 0.333        | 0.000 (0.000)    | 0.028 (0.001)    | 0 (0.000) |     2.29 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            1 |     6323 | 2024-09-25 | DXA Esports                      | L   | 0.151      | -            | -                | -                | -         |    -2.49 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($94.92)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.316 | $300.00        | $94.92          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
