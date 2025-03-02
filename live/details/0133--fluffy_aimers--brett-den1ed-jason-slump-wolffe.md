### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: brett, den1ed, jason, slump, Wolffe<br />
Global Rank: [133](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [25]( ../standings_americas.md)<br />
<br />
Final Rank Value:  781.3<br />
<br />
Final Rank Value (781.3) = Starting Rank Value (802.9) + Head To Head Adjustments (-21.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.302[<sup>1</sup>](#table2)
- Bounty Collected: 0.250[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.224[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 802.9
- 400 + ( ( 0.202 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 802.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           35 |     1660 | 2024-12-14 | Party Astronauts   | L   | 0.688      | -            | -                | -                | -         |   -11.13 | brett, den1ed, jason, slump, Wolffe  |
|           34 |     1992 | 2024-12-08 | BOSS               | L   | 0.647      | -            | -                | -                | -         |    -7.30 | brett, jason, nooz, slump, Wolffe    |
|           33 |     2044 | 2024-12-07 | Party Astronauts   | W   | 0.642      | 0.384        | 0.008 (0.002)    | 0.385 (0.095)    | 1 (0.642) |     9.80 | brett, jason, nooz, slump, Wolffe    |
|           32 |     2050 | 2024-12-07 | Bad News Capybaras | W   | 0.642      | 0.384        | 0.001 (0.000)    | 0.115 (0.028)    | 1 (0.642) |     6.01 | brett, jason, nooz, slump, Wolffe    |
|           31 |     2072 | 2024-12-07 | What's for Dinner  | W   | 0.640      | -            | -                | -                | 1 (0.640) |     2.06 | brett, jason, nooz, slump, Wolffe    |
|           30 |     2105 | 2024-12-06 | ROOMBA PEEK        | L   | 0.636      | -            | -                | -                | -         |   -16.01 | brett, jason, nooz, slump, Wolffe    |
|           29 |     5033 | 2024-10-15 | BOSS               | L   | 0.288      | -            | -                | -                | -         |    -3.21 | ayy, brett, jason, nooz, slump       |
|           28 |     5120 | 2024-10-13 | Fisher College     | L   | 0.274      | -            | -                | -                | -         |    -4.69 | brett, jason, nooz, slump, Wolffe    |
|           27 |     5121 | 2024-10-13 | InControl          | W   | 0.274      | 0.262        | 0.001 (0.000)    | 0.086 (0.006)    | 0 (0.000) |     2.38 | brett, jason, nooz, slump, Wolffe    |
|           26 |     5169 | 2024-10-12 | Final Form         | W   | 0.268      | -            | -                | -                | 0 (0.000) |     2.20 | brett, jason, nooz, slump, Wolffe    |
|           25 |     5172 | 2024-10-12 | MCS Gaming         | W   | 0.268      | 0.262        | 0.003 (0.000)    | 0.344 (0.024)    | 0 (0.000) |     2.58 | brett, jason, nooz, slump, Wolffe    |
|           24 |     5174 | 2024-10-12 | Team Aether        | W   | 0.267      | -            | -                | -                | 0 (0.000) |     1.44 | brett, jason, nooz, slump, Wolffe    |
|           23 |     5177 | 2024-10-12 | Holly Molly        | W   | 0.267      | -            | -                | -                | 0 (0.000) |     0.82 | brett, jason, nooz, slump, Wolffe    |
|           22 |     5183 | 2024-10-12 | Final Form         | L   | 0.267      | -            | -                | -                | -         |    -6.25 | brett, jason, nooz, slump, Wolffe    |
|           21 |     5303 | 2024-10-09 | Chill Guys         | L   | 0.249      | -            | -                | -                | -         |    -5.43 | ayy, brett, jason, nooz, slump       |
|           20 |     5309 | 2024-10-09 | Chill Guys         | L   | 0.248      | -            | -                | -                | -         |    -5.52 | ayy, brett, jason, nooz, slump       |
|           19 |     5375 | 2024-10-08 | Timbermen          | L   | 0.242      | -            | -                | -                | -         |    -4.87 | ayy, brett, jason, nooz, slump       |
|           18 |     5381 | 2024-10-08 | Timbermen          | W   | 0.242      | 0.477        | 0.011 (0.001)    | 0.160 (0.018)    | 0 (0.000) |     2.79 | ayy, brett, jason, nooz, slump       |
|           17 |     5446 | 2024-10-07 | BOSS               | L   | 0.235      | -            | -                | -                | -         |    -2.83 | ayy, brett, jason, nooz, slump       |
|           16 |     5448 | 2024-10-07 | BOSS               | W   | 0.235      | 0.477        | 0.014 (0.002)    | 0.327 (0.037)    | 0 (0.000) |     4.65 | ayy, brett, jason, nooz, slump       |
|           15 |     5551 | 2024-10-05 | BOSS               | L   | 0.222      | -            | -                | -                | -         |    -2.63 | brett, jason, nooz, slump, Wolffe    |
|           14 |     5555 | 2024-10-05 | Legacy             | W   | 0.221      | 0.371        | 0.036 (0.003)    | 0.554 (0.045)    | -         |     4.31 | brett, consti, jason, slump, Wolffe  |
|           13 |     5648 | 2024-10-04 | Timbermen          | W   | 0.214      | -            | -                | -                | -         |     1.08 | brett, jason, nooz, slump, Wolffe    |
|           12 |     5817 | 2024-10-01 | Chill Guys         | W   | 0.195      | 0.371        | 0.003 (0.000)    | 0.313 (0.023)    | -         |     1.83 | brett, jason, nooz, slump, Wolffe    |
|           11 |     6421 | 2024-09-23 | LAG Gaming         | W   | 0.142      | 0.477        | 0.001 (0.000)    | -                | -         |     1.14 | ayy, brett, jason, nooz, slump       |
|           10 |     6425 | 2024-09-23 | LAG Gaming         | W   | 0.142      | -            | -                | -                | -         |     1.15 | ayy, brett, jason, nooz, slump       |
|            9 |     6501 | 2024-09-22 | NRG                | L   | 0.133      | -            | -                | -                | -         |    -0.99 | brett, C4LLM3SU3, jason, nooz, slump |
|            8 |     6550 | 2024-09-21 | Legacy             | W   | 0.128      | 0.303        | 0.036 (0.001)    | 0.554 (0.021)    | -         |     2.35 | ayy, brett, jason, nooz, slump       |
|            7 |     6602 | 2024-09-20 | MIGHT              | W   | 0.122      | 0.143        | -                | 0.444 (0.008)    | -         |     1.60 | brett, C4LLM3SU3, jason, nooz, slump |
|            6 |     6604 | 2024-09-20 | VitaPLUR           | W   | 0.122      | -            | -                | -                | -         |     0.59 | brett, C4LLM3SU3, jason, nooz, slump |
|            5 |     6611 | 2024-09-20 | OutGoing eSports   | W   | 0.121      | -            | -                | -                | -         |     0.36 | brett, C4LLM3SU3, jason, nooz, slump |
|            4 |     7632 | 2024-09-04 | Bad News Capybaras | W   | 0.015      | -            | -                | -                | -         |     0.15 | ayy, brett, jason, nooz, slump       |
|            3 |     7633 | 2024-09-04 | Bad News Capybaras | W   | 0.015      | -            | -                | -                | -         |     0.15 | ayy, brett, jason, nooz, slump       |
|            2 |     7690 | 2024-09-03 | Legacy             | L   | 0.009      | -            | -                | -                | -         |    -0.11 | ayy, brett, jason, nooz, slump       |
|            1 |     7700 | 2024-09-03 | Legacy             | L   | 0.008      | -            | -                | -                | -         |    -0.11 | ayy, brett, jason, nooz, slump       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,652.91)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $2,000.00      | $642.22         |
| 2024-10-13 |      0.274 | $450.00        | $123.47         |
| 2024-10-05 |      0.222 | $4,000.00      | $887.22         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
