### Roster Details<br />
Team Name: Bad News Capybaras<br />
Roster: cbass, Gabe, Grave, jchancE, LaffyTs<br />
Global Rank: [359](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [73]( ../standings_americas.md)<br />
<br />
Final Rank Value:  618.9<br />
<br />
Final Rank Value (618.9) = Starting Rank Value (665.1) + Head To Head Adjustments (-46.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.233[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.082[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 665.1
- 400 + ( ( 0.133 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 665.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      617 | 2025-02-09 | MCS Gaming           | L   | 1.000      | -            | -                | -                | -         |   -15.74 | cbass, Gabe, Grave, jchancE, LaffyTs |
|           33 |      673 | 2025-02-08 | M80                  | L   | 1.000      | -            | -                | -                | -         |    -4.43 | cbass, Gabe, Grave, jchancE, LaffyTs |
|           32 |     1601 | 2024-12-15 | Alter Iron Club      | L   | 0.696      | -            | -                | -                | -         |    -8.38 | cbass, Champ, Grave, jchancE, z0mb1e |
|           31 |     1654 | 2024-12-14 | Undone               | L   | 0.689      | -            | -                | -                | -         |    -6.94 | cbass, Champ, Grave, jchancE, z0mb1e |
|           30 |     1744 | 2024-12-13 | LAG Gaming           | W   | 0.682      | 0.143        | 0.001 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     9.26 | cbass, Champ, Grave, jchancE, z0mb1e |
|           29 |     1819 | 2024-12-12 | Chicken Coop Esports | W   | 0.676      | 0.143        | 0.006 (0.001)    | 0.189 (0.018)    | 0 (0.000) |    11.73 | cbass, Champ, Grave, jchancE, z0mb1e |
|           28 |     1860 | 2024-12-11 | Undone               | L   | 0.669      | -            | -                | -                | -         |    -6.73 | cbass, Champ, Grave, jchancE, z0mb1e |
|           27 |     1906 | 2024-12-10 | Chicken Coop Esports | W   | 0.662      | 0.143        | 0.006 (0.001)    | 0.189 (0.018)    | 0 (0.000) |    11.90 | cbass, Champ, Grave, jchancE, z0mb1e |
|           26 |     2050 | 2024-12-07 | FLUFFY AIMERS        | L   | 0.642      | -            | -                | -                | -         |    -6.01 | cbass, Champ, Grave, jchancE, z0mb1e |
|           25 |     2059 | 2024-12-07 | Sharks Esports       | L   | 0.641      | -            | -                | -                | -         |    -2.35 | cbass, Champ, Grave, jchancE, z0mb1e |
|           24 |     2113 | 2024-12-06 | Not Mythic           | W   | 0.635      | 0.384        | 0.000 (0.000)    | 0.012 (0.003)    | 1 (0.635) |     5.83 | cbass, Champ, Grave, jchancE, z0mb1e |
|           23 |     2934 | 2024-11-22 | Blahaj               | L   | 0.542      | -            | -                | -                | -         |   -11.29 | cbass, Champ, Grave, jchancE, z0mb1e |
|           22 |     5178 | 2024-10-12 | Not Mythic           | L   | 0.267      | -            | -                | -                | -         |    -6.09 | cbass, Champ, Grave, jchancE, z0mb1e |
|           21 |     5184 | 2024-10-12 | MCS Gaming           | L   | 0.267      | -            | -                | -                | -         |    -4.18 | cbass, Champ, Grave, jchancE, z0mb1e |
|           20 |     5301 | 2024-10-09 | LAG Gaming           | L   | 0.249      | -            | -                | -                | -         |    -4.56 | cbass, Champ, Grave, jchancE, z0mb1e |
|           19 |     5310 | 2024-10-09 | LAG Gaming           | W   | 0.248      | 0.477        | 0.001 (0.000)    | 0.027 (0.003)    | 0 (0.000) |     3.33 | cbass, Champ, Grave, jchancE, z0mb1e |
|           18 |     5373 | 2024-10-08 | Familia Maquininha   | L   | 0.242      | -            | -                | -                | -         |    -3.44 | cbass, Champ, Grave, jchancE, z0mb1e |
|           17 |     5379 | 2024-10-08 | Familia Maquininha   | L   | 0.242      | -            | -                | -                | -         |    -3.51 | cbass, Champ, Grave, jchancE, z0mb1e |
|           16 |     5695 | 2024-10-03 | Mythic               | W   | 0.209      | 0.477        | 0.000 (0.000)    | 0.023 (0.002)    | 0 (0.000) |     1.97 | cbass, Champ, Grave, jchancE, z0mb1e |
|           15 |     5699 | 2024-10-03 | Mythic               | W   | 0.208      | 0.477        | 0.000 (0.000)    | 0.023 (0.002)    | 0 (0.000) |     2.00 | cbass, Champ, Grave, jchancE, z0mb1e |
|           14 |     5807 | 2024-10-01 | Vagrants             | L   | 0.195      | -            | -                | -                | -         |    -3.14 | cbass, Champ, Grave, jchancE, z0mb1e |
|           13 |     5812 | 2024-10-01 | Vagrants             | W   | 0.195      | 0.477        | 0.001 (0.000)    | 0.278 (0.026)    | 0 (0.000) |     3.05 | cbass, Champ, Grave, jchancE, z0mb1e |
|           12 |     5990 | 2024-09-28 | M80                  | L   | 0.175      | -            | -                | -                | -         |    -1.01 | cbass, Champ, Grave, jchancE, z0mb1e |
|           11 |     5993 | 2024-09-28 | M80                  | L   | 0.175      | -            | -                | -                | -         |    -1.02 | cbass, Champ, Grave, jchancE, z0mb1e |
|           10 |     6167 | 2024-09-26 | MarcaRegistrada      | L   | 0.161      | -            | -                | -                | -         |    -2.92 | cbass, Champ, Grave, jchancE, z0mb1e |
|            9 |     6241 | 2024-09-25 | Legacy               | L   | 0.155      | -            | -                | -                | -         |    -1.16 | cbass, Champ, Grave, jchancE, z0mb1e |
|            8 |     6246 | 2024-09-25 | Legacy               | L   | 0.155      | -            | -                | -                | -         |    -1.17 | cbass, Champ, Grave, jchancE, z0mb1e |
|            7 |     6718 | 2024-09-18 | NRG                  | L   | 0.109      | -            | -                | -                | -         |    -0.43 | cbass, Champ, Grave, jchancE, z0mb1e |
|            6 |     6725 | 2024-09-18 | NRG                  | L   | 0.108      | -            | -                | -                | -         |    -0.43 | cbass, Champ, Grave, jchancE, z0mb1e |
|            5 |     7329 | 2024-09-08 | Timbermen            | L   | 0.041      | -            | -                | -                | -         |    -0.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     7376 | 2024-09-07 | Wanted Goons         | W   | 0.035      | 0.333        | 0.000 (0.000)    | 0.002 (0.000)    | 1 (0.035) |     0.29 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     7407 | 2024-09-07 | Amped Esports Red    | W   | 0.033      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.033) |     0.19 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     7632 | 2024-09-04 | FLUFFY AIMERS        | L   | 0.015      | -            | -                | -                | -         |    -0.15 | cbass, Champ, Grave, jchancE, z0mb1e |
|            1 |     7633 | 2024-09-04 | FLUFFY AIMERS        | L   | 0.015      | -            | -                | -                | -         |    -0.15 | cbass, Champ, Grave, jchancE, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($170.25)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.321 | $400.00        | $128.44         |
| 2024-09-08 |      0.042 | $1,000.00      | $41.81          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
