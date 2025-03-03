### Roster Details<br />
Team Name: MANTRA<br />
Roster: cheeseball, cookie, rekonz, SkulL, Winnieeeee<br />
Global Rank: [418](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [69]( ../standings_asia.md)<br />
<br />
Final Rank Value:  585.6<br />
<br />
Final Rank Value (585.6) = Starting Rank Value (616.0) + Head To Head Adjustments (-30.4)<br />

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
- 400 + ( ( 0.108 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 616.0


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
|           18 |       51 | 2025-02-25 | KZG                              | L   | 1.000      | -            | -                | -                | -         |   -14.66 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           17 |       69 | 2025-02-24 | Rooster                          | W   | 1.000      | 0.143        | 0.005 (0.001)    | 0.220 (0.031)    | 0 (0.000) |    19.68 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           16 |       90 | 2025-02-23 | TALON                            | L   | 1.000      | -            | -                | -                | -         |   -14.75 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           15 |      393 | 2025-02-15 | Justice For Tomorrow             | L   | 1.000      | -            | -                | -                | -         |   -12.16 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           14 |      397 | 2025-02-15 | BBBCBMBS                         | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.094 (0.013)    | 0 (0.000) |     7.84 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           13 |      462 | 2025-02-14 | Vantage Esports                  | L   | 1.000      | -            | -                | -                | -         |   -13.48 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           12 |     1662 | 2024-12-15 | Underground Esports Club         | W   | 0.683      | 0.143        | 0.001 (0.000)    | 0.240 (0.023)    | 0 (0.000) |    11.03 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           11 |     1734 | 2024-12-14 | TALON                            | L   | 0.676      | -            | -                | -                | -         |   -11.05 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|           10 |     1825 | 2024-12-13 | Above The Rest (Australian team) | W   | 0.669      | 0.143        | 0.000 (0.000)    | 0.086 (0.008)    | 0 (0.000) |     7.35 | cheeseball, cookie, rekonz, SkulL, Winnieeeee |
|            9 |     5309 | 2024-10-10 | Rooster                          | L   | 0.243      | -            | -                | -                | -         |    -3.18 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            8 |     5310 | 2024-10-10 | Rooster                          | W   | 0.242      | 0.333        | 0.005 (0.000)    | 0.220 (0.018)    | 0 (0.000) |     4.53 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            7 |     5376 | 2024-10-09 | Only One Word                    | L   | 0.236      | -            | -                | -                | -         |    -3.34 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            6 |     5380 | 2024-10-09 | Only One Word                    | L   | 0.236      | -            | -                | -                | -         |    -3.41 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            5 |     5646 | 2024-10-04 | Vantage Esports                  | L   | 0.208      | -            | -                | -                | -         |    -2.94 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            4 |     5648 | 2024-10-04 | Above The Rest (Australian team) | W   | 0.208      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.52 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            3 |     5652 | 2024-10-04 | Housebets                        | L   | 0.207      | -            | -                | -                | -         |    -3.20 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            2 |     6328 | 2024-09-25 | DXA Esports                      | W   | 0.143      | 0.333        | 0.000 (0.000)    | 0.027 (0.001)    | 0 (0.000) |     2.16 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |
|            1 |     6335 | 2024-09-25 | DXA Esports                      | L   | 0.142      | -            | -                | -                | -         |    -2.35 | cheeseball, cookie, Reapz, rekonz, Winnieeeee |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92.46)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-19 |      0.308 | $300.00        | $92.46          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
