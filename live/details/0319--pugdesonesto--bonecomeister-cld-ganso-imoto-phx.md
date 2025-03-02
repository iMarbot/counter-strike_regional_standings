### Roster Details<br />
Team Name: Pugdesonesto<br />
Roster: Bonecomeister, cLd, ganso, imoto, phx<br />
Global Rank: [319](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [61]( ../standings_americas.md)<br />
<br />
Final Rank Value:  639.8<br />
<br />
Final Rank Value (639.8) = Starting Rank Value (637.1) + Head To Head Adjustments (2.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.209[<sup>1</sup>](#table2)
- Bounty Collected: 0.258[<sup>2</sup>](#table1)
- Opponent Network: 0.008[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.119<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 637.1
- 400 + ( ( 0.119 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 637.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     3912 | 2024-11-05 | 9z Academy              | L   | 0.428      | -            | -                | -                | -         |    -5.95 | Bonecomeister, cLd, ganso, imoto, phx         |
|           19 |     3928 | 2024-11-05 | AMIGOS (Brazilian team) | L   | 0.427      | -            | -                | -                | -         |    -9.09 | Bonecomeister, cLd, ganso, imoto, phx         |
|           18 |     3976 | 2024-11-04 | FURIA Esports Female    | W   | 0.421      | 0.250        | 0.064 (0.007)    | 0.223 (0.023)    | 0 (0.000) |    11.19 | Bonecomeister, cLd, ganso, imoto, phx         |
|           17 |     4216 | 2024-10-31 | FURIA Esports Female    | W   | 0.395      | 0.250        | 0.064 (0.006)    | 0.223 (0.022)    | 0 (0.000) |    10.78 | Bonecomeister, cLd, ganso, imoto, phx         |
|           16 |     4405 | 2024-10-28 | VELOX Argentina         | L   | 0.374      | -            | -                | -                | -         |    -6.51 | Bonecomeister, cLd, ganso, imoto, phx         |
|           15 |     4611 | 2024-10-24 | X7 Team                 | L   | 0.348      | -            | -                | -                | -         |    -5.78 | Bonecomeister, cLd, ganso, imoto, phx         |
|           14 |     4685 | 2024-10-22 | Bad News Chickens       | W   | 0.334      | 0.143        | 0.003 (0.000)    | 0.239 (0.011)    | 0 (0.000) |     6.00 | Bonecomeister, cLd, ganso, imoto, phx         |
|           13 |     4872 | 2024-10-18 | Galorys Academy         | W   | 0.307      | 0.250        | 0.001 (0.000)    | 0.158 (0.012)    | 0 (0.000) |     4.96 | Bonecomeister, cLd, ganso, imoto, phx         |
|           12 |     4913 | 2024-10-17 | 9z Academy              | L   | 0.301      | -            | -                | -                | -         |    -4.20 | Bonecomeister, cLd, ganso, imoto, phx         |
|           11 |     4975 | 2024-10-16 | Martians Oldsters       | W   | 0.294      | 0.143        | 0.000 (0.000)    | 0.048 (0.002)    | 0 (0.000) |     2.72 | Bonecomeister, ganso, imoto, phx, Thuister    |
|           10 |     4977 | 2024-10-16 | DB Peek Esports         | W   | 0.293      | 0.143        | 0.000 (0.000)    | 0.240 (0.010)    | 0 (0.000) |     4.35 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            9 |     5044 | 2024-10-15 | SoJoga                  | W   | 0.287      | 0.143        | 0.000 (0.000)    | 0.032 (0.001)    | 0 (0.000) |     3.62 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            8 |     5048 | 2024-10-15 | Myth e-Sports           | L   | 0.287      | -            | -                | -                | -         |    -4.91 | Bonecomeister, ganso, imoto, phx, Thuister    |
|            7 |     5705 | 2024-10-03 | Floripa Stars           | L   | 0.208      | -            | -                | -                | -         |    -3.06 | Bonecomeister, cLd, ganso, imoto, phx         |
|            6 |     5707 | 2024-10-03 | FURIA Esports Female    | L   | 0.208      | -            | -                | -                | -         |    -0.78 | Bonecomeister, cLd, ganso, imoto, phx         |
|            5 |     6357 | 2024-09-24 | X7 Team                 | W   | 0.147      | 0.250        | 0.000 (0.000)    | 0.055 (0.002)    | 0 (0.000) |     2.27 | Bonecomeister, cLd, ganso, imoto, phx         |
|            4 |     6435 | 2024-09-23 | 9z Academy              | L   | 0.141      | -            | -                | -                | -         |    -1.99 | Bonecomeister, freitas, ganso, imoto, phx     |
|            3 |     6803 | 2024-09-17 | MIBR Academy            | L   | 0.101      | -            | -                | -                | -         |    -1.41 | Bonecomeister, freitas, ganso, imoto, Striker |
|            2 |     7332 | 2024-09-08 | Só os do JOB            | W   | 0.040      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.26 | Bonecomeister, freitas, ganso, imoto, Striker |
|            1 |     7387 | 2024-09-07 | Aura (Brazilian team)   | W   | 0.033      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.22 | Bonecomeister, freitas, ganso, imoto, Striker |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($54.24)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-06 |      0.434 | $125.00        | $54.24          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
