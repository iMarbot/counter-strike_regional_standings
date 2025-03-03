### Roster Details<br />
Team Name: FLUFFY AIMERS<br />
Roster: brett, den1ed, jason, slump, Wolffe<br />
Global Rank: [125](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [26]( ../standings_americas.md)<br />
<br />
Final Rank Value:  793.9<br />
<br />
Final Rank Value (793.9) = Starting Rank Value (803.6) + Head To Head Adjustments (-9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.302[<sup>1</sup>](#table2)
- Bounty Collected: 0.252[<sup>2</sup>](#table1)
- Opponent Network: 0.031[<sup>2</sup>](#table1)
- LAN Wins: 0.222[<sup>2</sup>](#table1)

The average of these factors is 0.202<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 803.6
- 400 + ( ( 0.202 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 803.6


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
|           35 |     1672 | 2024-12-14 | Party Astronauts   | L   | 0.680      | -            | -                | -                | -         |   -11.21 | brett, den1ed, jason, slump, Wolffe  |
|           34 |     2004 | 2024-12-08 | BLUEJAYS           | L   | 0.638      | -            | -                | -                | -         |    -3.09 | brett, jason, nooz, slump, Wolffe    |
|           33 |     2056 | 2024-12-07 | Party Astronauts   | W   | 0.634      | 0.384        | 0.008 (0.002)    | 0.382 (0.093)    | 1 (0.634) |     9.59 | brett, jason, nooz, slump, Wolffe    |
|           32 |     2062 | 2024-12-07 | Bad News Capybaras | W   | 0.633      | 0.384        | -                | 0.113 (0.027)    | 1 (0.633) |     5.87 | brett, jason, nooz, slump, Wolffe    |
|           31 |     2084 | 2024-12-07 | What's for Dinner  | W   | 0.632      | -            | -                | -                | 1 (0.632) |     1.96 | brett, jason, nooz, slump, Wolffe    |
|           30 |     2117 | 2024-12-06 | ROOMBA PEEK        | L   | 0.628      | -            | -                | -                | -         |   -15.97 | brett, jason, nooz, slump, Wolffe    |
|           29 |     5045 | 2024-10-15 | BLUEJAYS           | L   | 0.280      | -            | -                | -                | -         |    -1.11 | ayy, brett, jason, nooz, slump       |
|           28 |     5132 | 2024-10-13 | Fisher College     | L   | 0.266      | -            | -                | -                | -         |    -4.63 | brett, jason, nooz, slump, Wolffe    |
|           27 |     5133 | 2024-10-13 | InControl          | W   | 0.265      | -            | -                | -                | 0 (0.000) |     2.25 | brett, jason, nooz, slump, Wolffe    |
|           26 |     5181 | 2024-10-12 | Final Form         | W   | 0.260      | -            | -                | -                | 0 (0.000) |     2.07 | brett, jason, nooz, slump, Wolffe    |
|           25 |     5184 | 2024-10-12 | MCS Gaming         | W   | 0.259      | 0.262        | 0.003 (0.000)    | 0.343 (0.023)    | 0 (0.000) |     2.44 | brett, jason, nooz, slump, Wolffe    |
|           24 |     5186 | 2024-10-12 | Team Aether        | W   | 0.259      | -            | -                | -                | 0 (0.000) |     1.35 | brett, jason, nooz, slump, Wolffe    |
|           23 |     5189 | 2024-10-12 | Holly Molly        | W   | 0.259      | -            | -                | -                | 0 (0.000) |     0.77 | brett, jason, nooz, slump, Wolffe    |
|           22 |     5195 | 2024-10-12 | Final Form         | L   | 0.258      | -            | -                | -                | -         |    -6.13 | brett, jason, nooz, slump, Wolffe    |
|           21 |     5315 | 2024-10-09 | Chill Guys         | L   | 0.240      | -            | -                | -                | -         |    -5.27 | ayy, brett, jason, nooz, slump       |
|           20 |     5321 | 2024-10-09 | Chill Guys         | L   | 0.240      | -            | -                | -                | -         |    -5.36 | ayy, brett, jason, nooz, slump       |
|           19 |     5387 | 2024-10-08 | Timbermen          | L   | 0.234      | -            | -                | -                | -         |    -5.38 | ayy, brett, jason, nooz, slump       |
|           18 |     5393 | 2024-10-08 | Timbermen          | W   | 0.233      | 0.477        | 0.003 (0.000)    | -                | 0 (0.000) |     2.00 | ayy, brett, jason, nooz, slump       |
|           17 |     5458 | 2024-10-07 | BLUEJAYS           | L   | 0.227      | -            | -                | -                | -         |    -0.96 | ayy, brett, jason, nooz, slump       |
|           16 |     5460 | 2024-10-07 | BLUEJAYS           | W   | 0.227      | 0.477        | 0.031 (0.003)    | 0.511 (0.055)    | 0 (0.000) |     6.23 | ayy, brett, jason, nooz, slump       |
|           15 |     5563 | 2024-10-05 | BLUEJAYS           | L   | 0.214      | -            | -                | -                | -         |    -0.86 | brett, jason, nooz, slump, Wolffe    |
|           14 |     5567 | 2024-10-05 | Legacy             | W   | 0.213      | 0.371        | 0.036 (0.003)    | 0.549 (0.043)    | -         |     4.13 | brett, consti, jason, slump, Wolffe  |
|           13 |     5660 | 2024-10-04 | Timbermen          | W   | 0.206      | 0.371        | 0.003 (0.000)    | -                | -         |     1.85 | brett, jason, nooz, slump, Wolffe    |
|           12 |     5829 | 2024-10-01 | Chill Guys         | W   | 0.187      | 0.371        | 0.003 (0.000)    | 0.310 (0.021)    | -         |     1.76 | brett, jason, nooz, slump, Wolffe    |
|           11 |     6433 | 2024-09-23 | LAG Gaming         | W   | 0.134      | 0.477        | 0.004 (0.000)    | 0.120 (0.008)    | -         |     1.92 | ayy, brett, jason, nooz, slump       |
|           10 |     6437 | 2024-09-23 | LAG Gaming         | W   | 0.133      | 0.477        | 0.004 (0.000)    | 0.120 (0.008)    | -         |     1.94 | ayy, brett, jason, nooz, slump       |
|            9 |     6513 | 2024-09-22 | NRG                | L   | 0.125      | -            | -                | -                | -         |    -0.92 | brett, C4LLM3SU3, jason, nooz, slump |
|            8 |     6562 | 2024-09-21 | Legacy             | W   | 0.119      | 0.303        | 0.036 (0.001)    | 0.549 (0.020)    | -         |     2.19 | ayy, brett, jason, nooz, slump       |
|            7 |     6614 | 2024-09-20 | MIGHT              | W   | 0.114      | 0.143        | -                | 0.489 (0.008)    | -         |     1.78 | brett, C4LLM3SU3, jason, nooz, slump |
|            6 |     6616 | 2024-09-20 | VitaPLUR           | W   | 0.114      | -            | -                | -                | -         |     0.55 | brett, C4LLM3SU3, jason, nooz, slump |
|            5 |     6623 | 2024-09-20 | OutGoing eSports   | W   | 0.113      | -            | -                | -                | -         |     0.34 | brett, C4LLM3SU3, jason, nooz, slump |
|            4 |     7644 | 2024-09-04 | Bad News Capybaras | W   | 0.007      | -            | -                | -                | -         |     0.07 | ayy, brett, jason, nooz, slump       |
|            3 |     7645 | 2024-09-04 | Bad News Capybaras | W   | 0.007      | -            | -                | -                | -         |     0.07 | ayy, brett, jason, nooz, slump       |
|            2 |     7702 | 2024-09-03 | Legacy             | L   | 0.000      | -            | -                | -                | -         |    -0.01 | ayy, brett, jason, nooz, slump       |
|            1 |     7712 | 2024-09-03 | Legacy             | L   | 0.000      | -            | -                | -                | -         |    -0.00 | ayy, brett, jason, nooz, slump       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,600.06)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $2,000.00      | $625.83         |
| 2024-10-13 |      0.266 | $450.00        | $119.78         |
| 2024-10-05 |      0.214 | $4,000.00      | $854.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
