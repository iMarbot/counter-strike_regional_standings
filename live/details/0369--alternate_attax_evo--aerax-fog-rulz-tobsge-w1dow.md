### Roster Details<br />
Team Name: ALTERNATE aTTaX Evo<br />
Roster: aerax, FoG, Rulz, Tobsge, w1dow<br />
Global Rank: [369](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [234]( ../standings_europe.md)<br />
<br />
Final Rank Value:  611.6<br />
<br />
Final Rank Value (611.6) = Starting Rank Value (610.2) + Head To Head Adjustments (1.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.251[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.005[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.105<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 610.2
- 400 + ( ( 0.105 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 610.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                 | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                           |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           28 |     2498 | 2024-11-30 | Eternal premium          | L   | 0.586      | -            | -                | -                | -         |    -7.10 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           27 |     2726 | 2024-11-26 | SkyFury                  | L   | 0.559      | -            | -                | -                | -         |    -7.46 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           26 |     3666 | 2024-11-10 | Reveal (German team)     | L   | 0.452      | -            | -                | -                | -         |    -6.90 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           25 |     3711 | 2024-11-09 | Team Fragster            | W   | 0.445      | 0.143        | 0.000 (0.000)    | 0.097 (0.006)    | 0 (0.000) |     6.67 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           24 |     3990 | 2024-11-04 | AKA HERO                 | W   | 0.412      | 0.143        | 0.000 (0.000)    | 0.060 (0.004)    | 0 (0.000) |     5.86 | devils, FoG, Rulz, Tobsge, w1dow |
|           23 |     4050 | 2024-11-03 | RIZON                    | W   | 0.405      | -            | -                | -                | 0 (0.000) |     2.74 | devils, FoG, Rulz, Tobsge, w1dow |
|           22 |     4466 | 2024-10-27 | BIG SELECTA              | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.048 (0.002)    | 0 (0.000) |     4.87 | devils, FoG, Rulz, Tobsge, w1dow |
|           21 |     4658 | 2024-10-23 | Team Fragster            | W   | 0.332      | 0.143        | 0.000 (0.000)    | 0.097 (0.005)    | 0 (0.000) |     5.08 | devils, FoG, Rulz, Tobsge, w1dow |
|           20 |     4732 | 2024-10-21 | Sissi State Punks        | L   | 0.318      | -            | -                | -                | -         |    -5.18 | devils, FoG, Rulz, smaxy, w1dow  |
|           19 |     4774 | 2024-10-20 | Wave Esports             | L   | 0.312      | -            | -                | -                | -         |    -4.83 | devils, FoG, Rulz, smaxy, w1dow  |
|           18 |     4850 | 2024-10-19 | 777 Esports              | L   | 0.305      | -            | -                | -                | -         |    -4.15 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           17 |     4900 | 2024-10-18 | Ex-Dynamo Eclot Thunders | W   | 0.298      | 0.278        | 0.000 (0.000)    | 0.026 (0.002)    | 0 (0.000) |     4.45 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           16 |     4906 | 2024-10-18 | UNEVEN                   | W   | 0.297      | -            | -                | -                | 0 (0.000) |     2.81 | devils, FoG, Rulz, Tobsge, w1dow |
|           15 |     4950 | 2024-10-17 | 777 Esports              | L   | 0.290      | -            | -                | -                | -         |    -3.97 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           14 |     5004 | 2024-10-16 | Reveal (German team)     | L   | 0.285      | -            | -                | -                | -         |    -4.29 | devils, FoG, Rulz, smaxy, w1dow  |
|           13 |     5067 | 2024-10-15 | XI Esport                | W   | 0.278      | 0.278        | -                | 0.124 (0.010)    | 0 (0.000) |     3.17 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           12 |     5153 | 2024-10-13 | KUUSAMO.gg               | W   | 0.264      | 0.278        | -                | 0.162 (0.012)    | 0 (0.000) |     2.98 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           11 |     5266 | 2024-10-11 | Reveal (German team)     | L   | 0.251      | -            | -                | -                | -         |    -3.81 | devils, FoG, Rulz, Tobsge, w1dow |
|           10 |     5351 | 2024-10-09 | MYinsanity               | L   | 0.238      | -            | -                | -                | -         |    -3.47 | devils, FoG, Rulz, smaxy, w1dow  |
|            9 |     5360 | 2024-10-09 | Team Czech Republic      | W   | 0.237      | 0.278        | 0.000 (0.000)    | 0.092 (0.006)    | 0 (0.000) |     4.80 | aerax, FoG, Rulz, Tobsge, w1dow  |
|            8 |     5674 | 2024-10-04 | Sampi NEXT               | W   | 0.205      | 0.278        | -                | 0.022 (0.001)    | -         |     2.17 | aerax, FoG, Rulz, Tobsge, w1dow  |
|            7 |     6135 | 2024-09-27 | Entropy Gaming           | W   | 0.158      | 0.143        | 0.000 (0.000)    | 0.049 (0.001)    | -         |     2.20 | devils, FoG, Rulz, Smaxy, w1dow  |
|            6 |     6293 | 2024-09-25 | Playing Ducks            | W   | 0.145      | -            | -                | -                | -         |     1.05 | devils, FoG, Rulz, Tobsge, w1dow |
|            5 |     6524 | 2024-09-22 | Team NinjaParentz        | W   | 0.124      | 0.143        | 0.000 (0.000)    | -                | -         |     1.72 | devils, FoG, Rulz, Smaxy, w1dow  |
|            4 |     6699 | 2024-09-19 | SNOGARD Dragons          | W   | 0.105      | 0.143        | 0.000 (0.000)    | -                | -         |     1.57 | devils, FoG, Rulz, Tobsge, w1dow |
|            3 |     7092 | 2024-09-13 | Unorganized Five         | W   | 0.065      | 0.143        | 0.000 (0.000)    | -                | -         |     0.92 | devils, FoG, Rulz, Smaxy, w1dow  |
|            2 |     7407 | 2024-09-07 | GOOFYBOYZ                | L   | 0.025      | -            | -                | -                | -         |    -0.24 | devils, FoG, Rulz, Smaxy, w1dow  |
|            1 |     7576 | 2024-09-05 | Team Kosovo              | L   | 0.012      | -            | -                | -                | -         |    -0.20 | devils, FoG, Rulz, Smaxy, w1dow  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($337.44)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.452 | $241.26        | $109.00         |
| 2024-10-19 |      0.305 | $750.00        | $228.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
