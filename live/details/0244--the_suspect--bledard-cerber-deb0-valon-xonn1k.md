### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, cerber, deb0, vAloN, xonn1k<br />
Global Rank: [244](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [169]( ../standings_europe.md)<br />
<br />
Final Rank Value:  681.7<br />
<br />
Final Rank Value (681.7) = Starting Rank Value (724.7) + Head To Head Adjustments (-43.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.263[<sup>2</sup>](#table1)
- Opponent Network: 0.023[<sup>2</sup>](#table1)
- LAN Wins: 0.085[<sup>2</sup>](#table1)

The average of these factors is 0.162<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 724.7
- 400 + ( ( 0.162 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 724.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                    |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           31 |      155 | 2025-02-22 | ARCRED                 | L   | 1.000      | -            | -                | -                | -         |   -12.61 | BledarD, cerber, deb0, vAloN, xonn1k      |
|           30 |     1019 | 2025-02-04 | Aurora Gaming          | L   | 1.000      | -            | -                | -                | -         |   -11.25 | BledarD, deb0, Dementor, vAloN, xonn1k    |
|           29 |     1422 | 2024-12-22 | Kubix Esports          | L   | 0.730      | -            | -                | -                | -         |    -6.17 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           28 |     1462 | 2024-12-21 | MADNESS (Kosovar team) | W   | 0.724      | 0.143        | 0.003 (0.000)    | -                | 1 (0.724) |     6.21 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           27 |     1791 | 2024-12-13 | Ex-GODSENT             | L   | 0.672      | -            | -                | -                | -         |   -15.49 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           26 |     1796 | 2024-12-13 | RUSTEC                 | W   | 0.671      | 0.143        | -                | 0.216 (0.021)    | 0 (0.000) |     6.19 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           25 |     2886 | 2024-11-23 | HyperSpirit            | W   | 0.538      | 0.372        | 0.004 (0.001)    | 0.119 (0.024)    | 0 (0.000) |     7.20 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           24 |     2955 | 2024-11-22 | XP Academy             | L   | 0.532      | -            | -                | -                | -         |   -10.79 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           23 |     3021 | 2024-11-21 | HOTU                   | L   | 0.525      | -            | -                | -                | -         |    -8.49 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           22 |     3047 | 2024-11-21 | ROUNDS                 | W   | 0.524      | 0.372        | -                | 0.060 (0.012)    | 0 (0.000) |     3.55 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           21 |     3103 | 2024-11-20 | Ex-Soul's Heart Esport | W   | 0.519      | 0.372        | 0.000 (0.000)    | 0.078 (0.015)    | 0 (0.000) |     5.83 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           20 |     3998 | 2024-11-04 | Ex-9INE Academy        | W   | 0.412      | 0.372        | 0.000 (0.000)    | 0.033 (0.005)    | 0 (0.000) |     4.18 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           19 |     4303 | 2024-10-30 | PCIFIC Espor           | L   | 0.379      | -            | -                | -                | -         |    -5.16 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           18 |     4669 | 2024-10-23 | Anonymo Esports        | L   | 0.332      | -            | -                | -                | -         |    -7.71 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           17 |     4737 | 2024-10-21 | FAVBET Team            | L   | 0.318      | -            | -                | -                | -         |    -3.38 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           16 |     4775 | 2024-10-20 | ENJOY (Russian team)   | L   | 0.312      | -            | -                | -                | -         |    -7.70 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           15 |     4797 | 2024-10-20 | Lazer Cats             | W   | 0.311      | 0.143        | 0.005 (0.000)    | 0.378 (0.017)    | 0 (0.000) |     4.71 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           14 |     5011 | 2024-10-16 | GTZ.ESPORTS            | W   | 0.284      | 0.372        | 0.080 (0.008)    | 0.557 (0.059)    | 0 (0.000) |     8.39 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           13 |     5018 | 2024-10-16 | Los kogutos            | W   | 0.284      | 0.372        | 0.032 (0.003)    | 0.515 (0.054)    | 0 (0.000) |     7.25 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           12 |     5064 | 2024-10-15 | Underrated             | L   | 0.278      | -            | -                | -                | -         |    -4.81 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           11 |     5077 | 2024-10-15 | 500                    | L   | 0.278      | -            | -                | -                | -         |    -1.52 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           10 |     6058 | 2024-09-28 | Kubix Esports          | L   | 0.164      | -            | -                | -                | -         |    -1.22 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            9 |     6061 | 2024-09-28 | FLuffy Gangsters       | L   | 0.164      | -            | -                | -                | -         |    -2.09 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            8 |     6171 | 2024-09-27 | Dark Cloud Esports     | W   | 0.155      | 0.143        | 0.039 (0.001)    | 0.819 (0.018)    | 0 (0.000) |     3.16 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            7 |     6234 | 2024-09-26 | FLuffy Gangsters       | L   | 0.150      | -            | -                | -                | -         |    -1.92 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            6 |     6719 | 2024-09-19 | ALTERNATE aTTaX        | L   | 0.103      | -            | -                | -                | -         |    -0.78 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            5 |     6843 | 2024-09-17 | 9Pandas                | L   | 0.091      | -            | -                | -                | -         |    -0.57 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            4 |     6917 | 2024-09-16 | Insilio                | L   | 0.082      | -            | -                | -                | -         |    -1.43 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            3 |     7040 | 2024-09-14 | TALON                  | W   | 0.070      | -            | -                | -                | -         |     0.61 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            2 |     7138 | 2024-09-12 | Alliance               | W   | 0.058      | 0.143        | 0.015 (0.000)    | -                | -         |     1.32 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            1 |     7193 | 2024-09-11 | Nexus Gaming           | W   | 0.051      | 0.143        | 0.187 (0.001)    | 0.795 (0.006)    | -         |     1.51 | BledarD, cerber, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($855.69)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.732 | $1,043.02      | $763.63         |
| 2024-09-28 |      0.165 | $558.41        | $92.06          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
