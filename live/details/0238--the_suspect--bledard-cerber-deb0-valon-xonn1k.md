### Roster Details<br />
Team Name: The Suspect<br />
Roster: BledarD, cerber, deb0, vAloN, xonn1k<br />
Global Rank: [238](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [167]( ../standings_europe.md)<br />
<br />
Final Rank Value:  682.6<br />
<br />
Final Rank Value (682.6) = Starting Rank Value (725.6) + Head To Head Adjustments (-43.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.279[<sup>1</sup>](#table2)
- Bounty Collected: 0.264[<sup>2</sup>](#table1)
- Opponent Network: 0.024[<sup>2</sup>](#table1)
- LAN Wins: 0.085[<sup>2</sup>](#table1)

The average of these factors is 0.163<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 725.6
- 400 + ( ( 0.163 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 725.6


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
|           31 |      140 | 2025-02-22 | ARCRED                 | L   | 1.000      | -            | -                | -                | -         |   -12.60 | BledarD, cerber, deb0, vAloN, xonn1k      |
|           30 |     1007 | 2025-02-04 | Aurora Gaming          | L   | 1.000      | -            | -                | -                | -         |   -11.23 | BledarD, deb0, Dementor, vAloN, xonn1k    |
|           29 |     1410 | 2024-12-22 | Kubix Esports          | L   | 0.738      | -            | -                | -                | -         |    -6.22 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           28 |     1450 | 2024-12-21 | MADNESS (Kosovar team) | W   | 0.733      | 0.143        | 0.003 (0.000)    | -                | 1 (0.733) |     6.24 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           27 |     1779 | 2024-12-13 | Ex-GODSENT             | L   | 0.680      | -            | -                | -                | -         |   -15.70 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           26 |     1784 | 2024-12-13 | RUSTEC                 | W   | 0.680      | 0.143        | -                | 0.217 (0.021)    | 0 (0.000) |     6.27 | BledarD, deb0, gulito, HYPERI1, vAloN     |
|           25 |     2874 | 2024-11-23 | HyperSpirit            | W   | 0.546      | 0.372        | 0.004 (0.001)    | 0.121 (0.025)    | 0 (0.000) |     7.31 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           24 |     2943 | 2024-11-22 | XP Academy             | L   | 0.540      | -            | -                | -                | -         |   -10.91 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           23 |     3009 | 2024-11-21 | HOTU                   | L   | 0.534      | -            | -                | -                | -         |    -8.63 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           22 |     3035 | 2024-11-21 | ROUNDS                 | W   | 0.532      | 0.372        | -                | 0.061 (0.012)    | 0 (0.000) |     3.61 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           21 |     3091 | 2024-11-20 | Ex-Soul's Heart Esport | W   | 0.527      | 0.372        | 0.000 (0.000)    | 0.082 (0.016)    | 0 (0.000) |     5.92 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           20 |     3986 | 2024-11-04 | Ex-9INE Academy        | W   | 0.420      | 0.372        | 0.000 (0.000)    | 0.035 (0.005)    | 0 (0.000) |     4.30 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           19 |     4291 | 2024-10-30 | PCIFIC Espor           | L   | 0.387      | -            | -                | -                | -         |    -5.27 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           18 |     4657 | 2024-10-23 | Anonymo Esports        | L   | 0.340      | -            | -                | -                | -         |    -7.91 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           17 |     4725 | 2024-10-21 | FAVBET Team            | L   | 0.326      | -            | -                | -                | -         |    -3.46 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           16 |     4763 | 2024-10-20 | ENJOY (Russian team)   | L   | 0.320      | -            | -                | -                | -         |    -7.91 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           15 |     4785 | 2024-10-20 | Lazer Cats             | W   | 0.319      | 0.143        | 0.005 (0.000)    | 0.387 (0.018)    | 0 (0.000) |     4.83 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           14 |     4999 | 2024-10-16 | GTZ.ESPORTS            | W   | 0.292      | 0.372        | 0.080 (0.009)    | 0.563 (0.061)    | 0 (0.000) |     8.63 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           13 |     5006 | 2024-10-16 | Los kogutos            | W   | 0.292      | 0.372        | 0.032 (0.003)    | 0.527 (0.057)    | 0 (0.000) |     7.48 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           12 |     5052 | 2024-10-15 | Underrated             | L   | 0.286      | -            | -                | -                | -         |    -4.95 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           11 |     5065 | 2024-10-15 | 500                    | L   | 0.286      | -            | -                | -                | -         |    -1.58 | BledarD, Caleyy, cerber, HYPERI1, vAloN   |
|           10 |     6046 | 2024-09-28 | Kubix Esports          | L   | 0.172      | -            | -                | -                | -         |    -1.28 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            9 |     6049 | 2024-09-28 | FLuffy Gangsters       | L   | 0.172      | -            | -                | -                | -         |    -2.19 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            8 |     6159 | 2024-09-27 | Dark Cloud Esports     | W   | 0.164      | 0.143        | 0.038 (0.001)    | 0.828 (0.019)    | 0 (0.000) |     3.32 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            7 |     6222 | 2024-09-26 | FLuffy Gangsters       | L   | 0.158      | -            | -                | -                | -         |    -2.02 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            6 |     6707 | 2024-09-19 | ALTERNATE aTTaX        | L   | 0.111      | -            | -                | -                | -         |    -0.84 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            5 |     6831 | 2024-09-17 | 9Pandas                | L   | 0.100      | -            | -                | -                | -         |    -0.62 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            4 |     6905 | 2024-09-16 | Insilio                | L   | 0.090      | -            | -                | -                | -         |    -1.56 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            3 |     7028 | 2024-09-14 | TALON                  | W   | 0.078      | -            | -                | -                | -         |     0.69 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            2 |     7126 | 2024-09-12 | Alliance               | W   | 0.066      | 0.143        | 0.015 (0.000)    | -                | -         |     1.51 | BledarD, cerber, Dementor, HYPERI1, vAloN |
|            1 |     7181 | 2024-09-11 | Nexus Gaming           | W   | 0.060      | 0.143        | 0.186 (0.002)    | 0.808 (0.007)    | -         |     1.75 | BledarD, cerber, Dementor, HYPERI1, vAloN |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($868.81)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-22 |      0.740 | $1,043.02      | $772.18         |
| 2024-09-28 |      0.173 | $558.41        | $96.64          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
