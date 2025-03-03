### Roster Details<br />
Team Name: Galorys Academy<br />
Roster: bacc, insan1ty, Kadzz, prisma, triande<br />
Global Rank: [424](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [97]( ../standings_americas.md)<br />
<br />
Final Rank Value:  580.5<br />
<br />
Final Rank Value (580.5) = Starting Rank Value (639.8) + Head To Head Adjustments (-59.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.247[<sup>1</sup>](#table2)
- Bounty Collected: 0.209[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.120<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 639.8
- 400 + ( ( 0.120 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 639.8


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
|           38 |     1547 | 2024-12-19 | Nitro.GG             | L   | 0.711      | -            | -                | -                | -         |    -8.72 | bacc, insan1ty, Kadzz, prisma, triande    |
|           37 |     1579 | 2024-12-17 | América eSports      | W   | 0.698      | 0.384        | 0.000 (0.000)    | 0.426 (0.114)    | 0 (0.000) |    11.72 | bacc, insan1ty, Kadzz, prisma, triande    |
|           36 |     1638 | 2024-12-15 | Patins da Ferrari    | L   | 0.684      | -            | -                | -                | -         |   -12.46 | bacc, insan1ty, Kadzz, prisma, triande    |
|           35 |     1771 | 2024-12-13 | UNO MILLE            | L   | 0.673      | -            | -                | -                | -         |    -5.77 | bacc, insan1ty, Kadzz, prisma, triande    |
|           34 |     2136 | 2024-12-06 | PaiN Gaming Academy  | L   | 0.625      | -            | -                | -                | -         |   -12.62 | bacc, insan1ty, Kadzz, prisma, triande    |
|           33 |     2269 | 2024-12-03 | América eSports      | L   | 0.606      | -            | -                | -                | -         |    -9.54 | bacc, insan1ty, Kadzz, prisma, triande    |
|           32 |     2590 | 2024-11-29 | RED Canids Academy   | L   | 0.579      | -            | -                | -                | -         |    -6.67 | bacc, insan1ty, Kadzz, prisma, triande    |
|           31 |     2669 | 2024-11-27 | Yawara E-Sports      | W   | 0.565      | 0.143        | 0.002 (0.000)    | 0.448 (0.036)    | 0 (0.000) |    11.40 | bacc, insan1ty, Kadzz, prisma, triande    |
|           30 |     2706 | 2024-11-26 | Floripa Stars        | W   | 0.560      | 0.143        | 0.001 (0.000)    | 0.296 (0.024)    | 0 (0.000) |     9.51 | bacc, insan1ty, Kadzz, prisma, triande    |
|           29 |     3431 | 2024-11-14 | Floripa Stars        | L   | 0.479      | -            | -                | -                | -         |    -6.49 | bacc, insan1ty, Kadzz, prisma, triande    |
|           28 |     3921 | 2024-11-05 | UNO MILLE            | L   | 0.421      | -            | -                | -                | -         |    -4.10 | bacc, insan1ty, Kadzz, prisma, triande    |
|           27 |     3977 | 2024-11-04 | Fluxo                | L   | 0.413      | -            | -                | -                | -         |    -1.85 | bacc, insan1ty, Kadzz, prisma, triande    |
|           26 |     3989 | 2024-11-04 | X7 Team              | L   | 0.412      | -            | -                | -                | -         |    -6.45 | bacc, insan1ty, Kadzz, prisma, triande    |
|           25 |     4001 | 2024-11-04 | 20/70                | L   | 0.412      | -            | -                | -                | -         |    -6.28 | bacc, insan1ty, Kadzz, prisma, triande    |
|           24 |     4038 | 2024-11-03 | Intense Game         | L   | 0.407      | -            | -                | -                | -         |    -5.55 | bacc, insan1ty, Kadzz, prisma, triande    |
|           23 |     4107 | 2024-11-02 | América eSports      | W   | 0.400      | 0.143        | 0.000 (0.000)    | 0.426 (0.024)    | 0 (0.000) |     5.89 | bacc, insan1ty, Kadzz, prisma, reg1no.O   |
|           22 |     4184 | 2024-11-01 | ODDIK                | L   | 0.393      | -            | -                | -                | -         |    -3.07 | bacc, insan1ty, Kadzz, prisma, triande    |
|           21 |     4231 | 2024-10-31 | AdalYamigos          | W   | 0.387      | 0.143        | 0.004 (0.000)    | 0.193 (0.011)    | 0 (0.000) |     8.30 | bacc, insan1ty, Kadzz, prisma, triande    |
|           20 |     4235 | 2024-10-31 | Floripa Stars        | L   | 0.387      | -            | -                | -                | -         |    -5.20 | bacc, insan1ty, Kadzz, prisma, triande    |
|           19 |     4241 | 2024-10-31 | 9z Academy           | L   | 0.386      | -            | -                | -                | -         |    -5.54 | bacc, insan1ty, Kadzz, prisma, triande    |
|           18 |     4321 | 2024-10-30 | Team Solid           | L   | 0.378      | -            | -                | -                | -         |    -2.93 | bacc, insan1ty, Kadzz, prisma, triande    |
|           17 |     4356 | 2024-10-29 | Sharks Esports       | L   | 0.373      | -            | -                | -                | -         |    -1.25 | bacc, insan1ty, Kadzz, prisma, triande    |
|           16 |     4434 | 2024-10-28 | RED Canids Academy   | L   | 0.365      | -            | -                | -                | -         |    -4.80 | bacc, insan1ty, Kadzz, prisma, triande    |
|           15 |     4701 | 2024-10-22 | Sharks Youngsters    | W   | 0.325      | 0.143        | -                | 0.095 (0.004)    | 0 (0.000) |     4.35 | bacc, insan1ty, Kadzz, prisma, triande    |
|           14 |     4884 | 2024-10-18 | Pugdesonesto         | L   | 0.299      | -            | -                | -                | -         |    -4.81 | bacc, insan1ty, prisma, reg1no.O, triande |
|           13 |     4931 | 2024-10-17 | FURIA Esports Female | L   | 0.292      | -            | -                | -                | -         |    -1.14 | bacc, insan1ty, prisma, reg1no.O, triande |
|           12 |     5580 | 2024-10-05 | Bad News Chickens    | L   | 0.212      | -            | -                | -                | -         |    -2.99 | bacc, insan1ty, Kadzz, prisma, triande    |
|           11 |     5663 | 2024-10-04 | X7 Team              | W   | 0.205      | 0.250        | 0.000 (0.000)    | -                | 0 (0.000) |     3.02 | bacc, insan1ty, Kadzz, prisma, triande    |
|           10 |     5721 | 2024-10-03 | RED Canids Academy   | W   | 0.199      | 0.143        | 0.005 (0.000)    | 0.236 (0.007)    | 0 (0.000) |     3.60 | bacc, insan1ty, Kadzz, prisma, triande    |
|            9 |     5723 | 2024-10-03 | Floripa Stars        | L   | 0.199      | -            | -                | -                | -         |    -3.04 | bacc, insan1ty, Kadzz, prisma, triande    |
|            8 |     5847 | 2024-10-01 | 9z Academy           | W   | 0.185      | 0.143        | 0.001 (0.000)    | 0.384 (0.010)    | 0 (0.000) |     3.18 | bacc, insan1ty, Kadzz, prisma, triande    |
|            7 |     6450 | 2024-09-23 | MIBR Academy         | L   | 0.132      | -            | -                | -                | -         |    -1.89 | bacc, insan1ty, Kadzz, prisma, triande    |
|            6 |     6675 | 2024-09-19 | 9z Academy           | L   | 0.107      | -            | -                | -                | -         |    -1.56 | bacc, insan1ty, Kadzz, prisma, triande    |
|            5 |     6688 | 2024-09-19 | TROPA DOS 7          | W   | 0.106      | -            | -                | -                | 0 (0.000) |     0.99 | bacc, insan1ty, Kadzz, prisma, triande    |
|            4 |     6879 | 2024-09-16 | 9z Academy           | W   | 0.085      | 0.143        | 0.001 (0.000)    | 0.384 (0.005)    | -         |     1.45 | bacc, insan1ty, Kadzz, prisma, triande    |
|            3 |     7131 | 2024-09-12 | FURIA Esports Female | W   | 0.059      | 0.250        | 0.064 (0.001)    | 0.218 (0.003)    | -         |     1.63 | bacc, Kadzz, prisma, reg1no.O, triande    |
|            2 |     7283 | 2024-09-09 | X7 Team              | W   | 0.039      | -            | -                | -                | -         |     0.59 | bacc, insan1ty, Kadzz, prisma, triande    |
|            1 |     7567 | 2024-09-05 | Yawara E-Sports      | L   | 0.012      | -            | -                | -                | -         |    -0.17 | bacc, insan1ty, Kadzz, prisma, triande    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($290.48)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-05 |      0.421 | $690.60        | $290.48         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
