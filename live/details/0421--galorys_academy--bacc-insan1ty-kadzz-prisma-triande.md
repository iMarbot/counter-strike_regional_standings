### Roster Details<br />
Team Name: Galorys Academy<br />
Roster: bacc, insan1ty, Kadzz, prisma, triande<br />
Global Rank: [421](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [93]( ../standings_americas.md)<br />
<br />
Final Rank Value:  580.8<br />
<br />
Final Rank Value (580.8) = Starting Rank Value (640.5) + Head To Head Adjustments (-59.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.211[<sup>2</sup>](#table1)
- Opponent Network: 0.025[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 640.5
- 400 + ( ( 0.120 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 640.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           38 |     1535 | 2024-12-19 | Nitro.GG             | L   | 0.719      | -            | -                | -                | -         |    -8.80 | bacc, insan1ty, Kadzz, prisma, triande    |
|           37 |     1567 | 2024-12-17 | América eSports      | W   | 0.706      | 0.384        | 0.000 (0.000)    | 0.429 (0.116)    | 0 (0.000) |    11.85 | bacc, insan1ty, Kadzz, prisma, triande    |
|           36 |     1626 | 2024-12-15 | Patins da Ferrari    | L   | 0.692      | -            | -                | -                | -         |   -12.61 | bacc, insan1ty, Kadzz, prisma, triande    |
|           35 |     1759 | 2024-12-13 | UNO MILLE            | L   | 0.681      | -            | -                | -                | -         |    -5.81 | bacc, insan1ty, Kadzz, prisma, triande    |
|           34 |     2124 | 2024-12-06 | PaiN Gaming Academy  | L   | 0.634      | -            | -                | -                | -         |   -12.68 | bacc, insan1ty, Kadzz, prisma, triande    |
|           33 |     2257 | 2024-12-03 | América eSports      | L   | 0.614      | -            | -                | -                | -         |    -9.68 | bacc, insan1ty, Kadzz, prisma, triande    |
|           32 |     2578 | 2024-11-29 | RED Canids Academy   | L   | 0.587      | -            | -                | -                | -         |    -6.75 | bacc, insan1ty, Kadzz, prisma, triande    |
|           31 |     2657 | 2024-11-27 | Yawara E-Sports      | W   | 0.574      | 0.143        | 0.002 (0.000)    | 0.454 (0.037)    | 0 (0.000) |    11.59 | bacc, insan1ty, Kadzz, prisma, triande    |
|           30 |     2694 | 2024-11-26 | Floripa Stars        | W   | 0.568      | 0.143        | 0.001 (0.000)    | 0.302 (0.024)    | 0 (0.000) |     9.69 | bacc, insan1ty, Kadzz, prisma, triande    |
|           29 |     3419 | 2024-11-14 | Floripa Stars        | L   | 0.487      | -            | -                | -                | -         |    -6.59 | bacc, insan1ty, Kadzz, prisma, triande    |
|           28 |     3909 | 2024-11-05 | UNO MILLE            | L   | 0.429      | -            | -                | -                | -         |    -4.16 | bacc, insan1ty, Kadzz, prisma, triande    |
|           27 |     3965 | 2024-11-04 | Fluxo                | L   | 0.422      | -            | -                | -                | -         |    -1.86 | bacc, insan1ty, Kadzz, prisma, triande    |
|           26 |     3977 | 2024-11-04 | X7 Team              | L   | 0.421      | -            | -                | -                | -         |    -6.58 | bacc, insan1ty, Kadzz, prisma, triande    |
|           25 |     3989 | 2024-11-04 | 20/70                | L   | 0.420      | -            | -                | -                | -         |    -6.42 | bacc, insan1ty, Kadzz, prisma, triande    |
|           24 |     4026 | 2024-11-03 | Intense Game         | L   | 0.415      | -            | -                | -                | -         |    -5.67 | bacc, insan1ty, Kadzz, prisma, triande    |
|           23 |     4095 | 2024-11-02 | América eSports      | W   | 0.409      | 0.143        | 0.000 (0.000)    | 0.429 (0.025)    | 0 (0.000) |     5.99 | bacc, insan1ty, Kadzz, prisma, reg1no.O   |
|           22 |     4172 | 2024-11-01 | ODDIK                | L   | 0.401      | -            | -                | -                | -         |    -3.13 | bacc, insan1ty, Kadzz, prisma, triande    |
|           21 |     4219 | 2024-10-31 | AdalYamigos          | W   | 0.395      | 0.143        | 0.004 (0.000)    | 0.194 (0.011)    | 0 (0.000) |     8.49 | bacc, insan1ty, Kadzz, prisma, triande    |
|           20 |     4223 | 2024-10-31 | Floripa Stars        | L   | 0.395      | -            | -                | -                | -         |    -5.30 | bacc, insan1ty, Kadzz, prisma, triande    |
|           19 |     4229 | 2024-10-31 | 9z Academy           | L   | 0.395      | -            | -                | -                | -         |    -5.66 | bacc, insan1ty, Kadzz, prisma, triande    |
|           18 |     4309 | 2024-10-30 | Team Solid           | L   | 0.386      | -            | -                | -                | -         |    -2.98 | bacc, insan1ty, Kadzz, prisma, triande    |
|           17 |     4344 | 2024-10-29 | Sharks Esports       | L   | 0.381      | -            | -                | -                | -         |    -1.29 | bacc, insan1ty, Kadzz, prisma, triande    |
|           16 |     4422 | 2024-10-28 | RED Canids Academy   | L   | 0.373      | -            | -                | -                | -         |    -4.91 | bacc, insan1ty, Kadzz, prisma, triande    |
|           15 |     4689 | 2024-10-22 | Sharks Youngsters    | W   | 0.334      | 0.143        | -                | 0.097 (0.005)    | 0 (0.000) |     4.44 | bacc, insan1ty, Kadzz, prisma, triande    |
|           14 |     4872 | 2024-10-18 | Pugdesonesto         | L   | 0.307      | -            | -                | -                | -         |    -4.96 | bacc, insan1ty, prisma, reg1no.O, triande |
|           13 |     4919 | 2024-10-17 | FURIA Esports Female | L   | 0.300      | -            | -                | -                | -         |    -1.17 | bacc, insan1ty, prisma, reg1no.O, triande |
|           12 |     5568 | 2024-10-05 | Bad News Chickens    | L   | 0.220      | -            | -                | -                | -         |    -3.10 | bacc, insan1ty, Kadzz, prisma, triande    |
|           11 |     5651 | 2024-10-04 | X7 Team              | W   | 0.214      | 0.250        | 0.000 (0.000)    | -                | 0 (0.000) |     3.13 | bacc, insan1ty, Kadzz, prisma, triande    |
|           10 |     5709 | 2024-10-03 | RED Canids Academy   | W   | 0.207      | 0.143        | 0.005 (0.000)    | 0.240 (0.007)    | 0 (0.000) |     3.75 | bacc, insan1ty, Kadzz, prisma, triande    |
|            9 |     5711 | 2024-10-03 | Floripa Stars        | L   | 0.207      | -            | -                | -                | -         |    -3.17 | bacc, insan1ty, Kadzz, prisma, triande    |
|            8 |     5835 | 2024-10-01 | 9z Academy           | W   | 0.194      | 0.143        | 0.001 (0.000)    | 0.388 (0.011)    | 0 (0.000) |     3.32 | bacc, insan1ty, Kadzz, prisma, triande    |
|            7 |     6438 | 2024-09-23 | MIBR Academy         | L   | 0.140      | -            | -                | -                | -         |    -2.00 | bacc, insan1ty, Kadzz, prisma, triande    |
|            6 |     6663 | 2024-09-19 | 9z Academy           | L   | 0.115      | -            | -                | -                | -         |    -1.69 | bacc, insan1ty, Kadzz, prisma, triande    |
|            5 |     6676 | 2024-09-19 | TROPA DOS 7          | W   | 0.114      | -            | -                | -                | 0 (0.000) |     1.08 | bacc, insan1ty, Kadzz, prisma, triande    |
|            4 |     6867 | 2024-09-16 | 9z Academy           | W   | 0.094      | 0.143        | 0.001 (0.000)    | 0.388 (0.005)    | -         |     1.58 | bacc, insan1ty, Kadzz, prisma, triande    |
|            3 |     7119 | 2024-09-12 | FURIA Esports Female | W   | 0.067      | 0.250        | 0.064 (0.001)    | 0.223 (0.004)    | -         |     1.86 | bacc, Kadzz, prisma, reg1no.O, triande    |
|            2 |     7271 | 2024-09-09 | X7 Team              | W   | 0.047      | -            | -                | -                | -         |     0.71 | bacc, insan1ty, Kadzz, prisma, triande    |
|            1 |     7555 | 2024-09-05 | Yawara E-Sports      | L   | 0.021      | -            | -                | -                | -         |    -0.28 | bacc, insan1ty, Kadzz, prisma, triande    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($296.14)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.429 | $690.60        | $296.14         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
