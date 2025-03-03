### Roster Details<br />
Team Name: M80<br />
Roster: Lake, reck, s1n, slaxz-, Swisher<br />
Global Rank: [36](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [10]( ../standings_americas.md)<br />
<br />
Final Rank Value:  1039.0<br />
<br />
Final Rank Value (1039.0) = Starting Rank Value (913.6) + Head To Head Adjustments (125.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.413[<sup>1</sup>](#table2)
- Bounty Collected: 0.334[<sup>2</sup>](#table1)
- Opponent Network: 0.072[<sup>2</sup>](#table1)
- LAN Wins: 0.209[<sup>2</sup>](#table1)

The average of these factors is 0.257<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 913.6
- 400 + ( ( 0.257 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 913.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           46 |      466 | 2025-02-14 | BLUEJAYS           | W   | 1.000      | 0.143        | -                | 0.511 (0.073)    | 0 (0.000) |    16.98 | Lake, reck, s1n, slaxz-, Swisher |
|           45 |      488 | 2025-02-14 | NRG                | W   | 1.000      | 0.143        | 0.049 (0.007)    | 0.446 (0.064)    | 0 (0.000) |    17.66 | Lake, reck, s1n, slaxz-, Swisher |
|           44 |      519 | 2025-02-13 | Nouns Esports      | W   | 1.000      | -            | -                | -                | 0 (0.000) |    11.29 | Lake, reck, s1n, slaxz-, Swisher |
|           43 |      583 | 2025-02-10 | Marsborne          | W   | 1.000      | -            | -                | -                | -         |    12.76 | Lake, reck, s1n, slaxz-, Swisher |
|           42 |      624 | 2025-02-09 | Marsborne          | W   | 1.000      | -            | -                | -                | -         |    13.65 | Lake, reck, s1n, slaxz-, Swisher |
|           41 |      685 | 2025-02-08 | Bad News Capybaras | W   | 1.000      | -            | -                | -                | -         |     4.54 | Lake, reck, s1n, slaxz-, Swisher |
|           40 |      827 | 2025-02-06 | Zomblers           | W   | 1.000      | -            | -                | -                | -         |     1.32 | Lake, reck, s1n, slaxz-, Swisher |
|           39 |      832 | 2025-02-06 | Lumen              | W   | 1.000      | -            | -                | -                | -         |     1.29 | Lake, reck, s1n, slaxz-, Swisher |
|           38 |     1190 | 2025-01-16 | FaZe Clan          | L   | 0.898      | -            | -                | -                | -         |    -0.15 | k1to, Lake, s1n, slaxz-, Swisher |
|           37 |     3414 | 2024-11-15 | FURIA              | L   | 0.483      | -            | -                | -                | -         |    -0.99 | Lake, reck, s1n, slaxz-, Swisher |
|           36 |     3427 | 2024-11-14 | BESTIA             | W   | 0.481      | 0.143        | 0.069 (0.005)    | -                | 1 (0.481) |     7.63 | Lake, reck, s1n, slaxz-, Swisher |
|           35 |     3491 | 2024-11-13 | Complexity         | L   | 0.475      | -            | -                | -                | -         |    -3.58 | Lake, reck, s1n, slaxz-, Swisher |
|           34 |     3542 | 2024-11-12 | Legacy             | W   | 0.468      | -            | -                | -                | 1 (0.468) |     6.29 | Lake, reck, s1n, slaxz-, Swisher |
|           33 |     3566 | 2024-11-12 | RED Canids         | W   | 0.463      | -            | -                | -                | 1 (0.463) |     5.37 | Lake, reck, s1n, slaxz-, Swisher |
|           32 |     3587 | 2024-11-11 | BLUEJAYS           | L   | 0.462      | -            | -                | -                | -         |    -3.50 | Lake, reck, s1n, slaxz-, Swisher |
|           31 |     4588 | 2024-10-25 | BESTIA             | L   | 0.345      | -            | -                | -                | -         |    -5.56 | Lake, reck, s1n, slaxz-, Swisher |
|           30 |     4634 | 2024-10-24 | Aurora Gaming      | W   | 0.338      | 0.934        | 0.019 (0.006)    | 0.514 (0.162)    | -         |     3.31 | Lake, reck, s1n, slaxz-, Swisher |
|           29 |     4640 | 2024-10-24 | BESTIA             | L   | 0.337      | -            | -                | -                | -         |    -5.54 | Lake, reck, s1n, slaxz-, Swisher |
|           28 |     4771 | 2024-10-20 | NRG                | W   | 0.313      | 0.477        | 0.049 (0.007)    | 0.446 (0.066)    | -         |     5.70 | Lake, reck, s1n, slaxz-, Swisher |
|           27 |     4922 | 2024-10-17 | Legacy             | W   | 0.294      | 0.477        | 0.036 (0.005)    | 0.549 (0.077)    | -         |     4.06 | Lake, reck, s1n, slaxz-, Swisher |
|           26 |     4973 | 2024-10-16 | NRG                | W   | 0.287      | 0.477        | 0.049 (0.007)    | 0.446 (0.061)    | -         |     5.24 | Lake, reck, s1n, slaxz-, Swisher |
|           25 |     5314 | 2024-10-09 | BLUEJAYS           | W   | 0.240      | 0.477        | -                | 0.511 (0.059)    | -         |     5.88 | Lake, reck, s1n, slaxz-, Swisher |
|           24 |     5320 | 2024-10-09 | BLUEJAYS           | L   | 0.240      | -            | -                | -                | -         |    -1.70 | Lake, reck, s1n, slaxz-, Swisher |
|           23 |     5384 | 2024-10-08 | Legacy             | W   | 0.234      | 0.477        | -                | 0.549 (0.061)    | -         |     3.33 | Lake, reck, s1n, slaxz-, Swisher |
|           22 |     5390 | 2024-10-08 | Legacy             | L   | 0.233      | -            | -                | -                | -         |    -4.09 | Lake, reck, s1n, slaxz-, Swisher |
|           21 |     5397 | 2024-10-08 | Wildcard           | W   | 0.233      | 0.477        | 0.178 (0.020)    | 0.422 (0.047)    | -         |     6.67 | Lake, reck, s1n, slaxz-, Swisher |
|           20 |     5408 | 2024-10-08 | Wildcard           | W   | 0.233      | 0.477        | 0.178 (0.020)    | 0.422 (0.047)    | -         |     6.71 | Lake, reck, s1n, slaxz-, Swisher |
|           19 |     5590 | 2024-10-05 | Wildcard           | L   | 0.211      | -            | -                | -                | -         |    -0.54 | Lake, reck, s1n, slaxz-, Swisher |
|           18 |     5661 | 2024-10-04 | BIG                | L   | 0.206      | -            | -                | -                | -         |    -0.25 | Lake, reck, s1n, slaxz-, Swisher |
|           17 |     5668 | 2024-10-04 | Wildcard           | W   | 0.205      | 0.500        | 0.178 (0.018)    | -                | 1 (0.205) |     5.96 | Lake, reck, s1n, slaxz-, Swisher |
|           16 |     5822 | 2024-10-01 | Party Astronauts   | W   | 0.187      | -            | -                | -                | -         |     1.87 | Lake, reck, s1n, slaxz-, Swisher |
|           15 |     5828 | 2024-10-01 | Party Astronauts   | L   | 0.187      | -            | -                | -                | -         |    -4.07 | Lake, reck, s1n, slaxz-, Swisher |
|           14 |     5831 | 2024-10-01 | Nouns Esports      | W   | 0.186      | -            | -                | -                | -         |     1.55 | Lake, reck, s1n, slaxz-, Swisher |
|           13 |     5836 | 2024-10-01 | Nouns Esports      | L   | 0.186      | -            | -                | -                | -         |    -4.36 | Lake, reck, s1n, slaxz-, Swisher |
|           12 |     5896 | 2024-09-30 | Chill Guys         | W   | 0.180      | -            | -                | -                | -         |     1.08 | Lake, reck, s1n, slaxz-, Swisher |
|           11 |     5898 | 2024-09-30 | Chill Guys         | W   | 0.180      | -            | -                | -                | -         |     1.09 | Lake, reck, s1n, slaxz-, Swisher |
|           10 |     6002 | 2024-09-28 | Bad News Capybaras | W   | 0.167      | -            | -                | -                | -         |     0.99 | Lake, reck, s1n, slaxz-, Swisher |
|            9 |     6005 | 2024-09-28 | Bad News Capybaras | W   | 0.167      | -            | -                | -                | -         |     1.00 | Lake, reck, s1n, slaxz-, Swisher |
|            8 |     6175 | 2024-09-26 | Timbermen          | W   | 0.154      | -            | -                | -                | -         |     0.86 | Lake, reck, s1n, slaxz-, Swisher |
|            7 |     6176 | 2024-09-26 | Timbermen          | W   | 0.153      | -            | -                | -                | -         |     0.86 | Lake, reck, s1n, slaxz-, Swisher |
|            6 |     6254 | 2024-09-25 | NRG                | W   | 0.147      | -            | -                | -                | -         |     3.00 | Lake, reck, s1n, slaxz-, Swisher |
|            5 |     6259 | 2024-09-25 | NRG                | L   | 0.147      | -            | -                | -                | -         |    -1.64 | Lake, reck, s1n, slaxz-, Swisher |
|            4 |     6715 | 2024-09-19 | MIBR               | L   | 0.104      | -            | -                | -                | -         |    -0.15 | Lake, reck, s1n, slaxz-, Swisher |
|            3 |     6992 | 2024-09-14 | Imperial Esports   | W   | 0.072      | 0.889        | 0.092 (0.006)    | -                | 1 (0.072) |     1.35 | Lake, reck, s1n, slaxz-, Swisher |
|            2 |     7194 | 2024-09-11 | Fnatic             | W   | 0.051      | -            | -                | -                | 1 (0.051) |     1.13 | Lake, reck, s1n, slaxz-, Swisher |
|            1 |     7253 | 2024-09-10 | Complexity         | W   | 0.045      | -            | -                | -                | 1 (0.045) |     1.10 | Lake, reck, s1n, slaxz-, Swisher |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($12,449.10)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.04) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $25,000.00     | $7,822.92       |
| 2024-10-06 |      0.219 | $3,000.00      | $657.29         |
| 2024-09-22 |      0.124 | $32,000.00     | $3,968.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
