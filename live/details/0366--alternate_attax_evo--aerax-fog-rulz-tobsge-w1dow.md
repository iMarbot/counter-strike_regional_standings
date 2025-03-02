### Roster Details<br />
Team Name: ALTERNATE aTTaX Evo<br />
Roster: aerax, FoG, Rulz, Tobsge, w1dow<br />
Global Rank: [366](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [234]( ../standings_europe.md)<br />
<br />
Final Rank Value:  611.9<br />
<br />
Final Rank Value (611.9) = Starting Rank Value (610.2) + Head To Head Adjustments (1.7)<br />

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
- 400 + ( ( 0.105 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 610.2


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
|           29 |     2486 | 2024-11-30 | Eternal premium          | L   | 0.594      | -            | -                | -                | -         |    -7.23 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           28 |     2714 | 2024-11-26 | SkyFury                  | L   | 0.567      | -            | -                | -                | -         |    -7.58 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           27 |     3654 | 2024-11-10 | Reveal (German team)     | L   | 0.460      | -            | -                | -                | -         |    -7.04 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           26 |     3699 | 2024-11-09 | Team Fragster            | W   | 0.454      | 0.143        | 0.000 (0.000)    | 0.100 (0.006)    | 0 (0.000) |     6.79 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           25 |     3978 | 2024-11-04 | AKA HERO                 | W   | 0.421      | 0.143        | 0.000 (0.000)    | 0.062 (0.004)    | 0 (0.000) |     5.97 | devils, FoG, Rulz, Tobsge, w1dow |
|           24 |     4038 | 2024-11-03 | RIZON                    | W   | 0.413      | -            | -                | -                | 0 (0.000) |     2.78 | devils, FoG, Rulz, Tobsge, w1dow |
|           23 |     4454 | 2024-10-27 | BIG SELECTA              | W   | 0.367      | 0.143        | 0.000 (0.000)    | 0.049 (0.003)    | 0 (0.000) |     4.97 | devils, FoG, Rulz, Tobsge, w1dow |
|           22 |     4646 | 2024-10-23 | Team Fragster            | W   | 0.340      | 0.143        | 0.000 (0.000)    | 0.100 (0.005)    | 0 (0.000) |     5.21 | devils, FoG, Rulz, Tobsge, w1dow |
|           21 |     4720 | 2024-10-21 | Sissi State Punks        | L   | 0.327      | -            | -                | -                | -         |    -5.32 | devils, FoG, Rulz, smaxy, w1dow  |
|           20 |     4762 | 2024-10-20 | Wave Esports             | L   | 0.320      | -            | -                | -                | -         |    -4.96 | devils, FoG, Rulz, smaxy, w1dow  |
|           19 |     4838 | 2024-10-19 | 777 Esports              | L   | 0.313      | -            | -                | -                | -         |    -4.26 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           18 |     4888 | 2024-10-18 | Ex-Dynamo Eclot Thunders | W   | 0.306      | 0.278        | 0.000 (0.000)    | 0.026 (0.002)    | 0 (0.000) |     4.57 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           17 |     4894 | 2024-10-18 | UNEVEN                   | W   | 0.306      | -            | -                | -                | 0 (0.000) |     2.88 | devils, FoG, Rulz, Tobsge, w1dow |
|           16 |     4938 | 2024-10-17 | 777 Esports              | L   | 0.299      | -            | -                | -                | -         |    -4.07 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           15 |     4992 | 2024-10-16 | Reveal (German team)     | L   | 0.293      | -            | -                | -                | -         |    -4.42 | devils, FoG, Rulz, smaxy, w1dow  |
|           14 |     5055 | 2024-10-15 | XI Esport                | W   | 0.286      | 0.278        | -                | 0.127 (0.010)    | 0 (0.000) |     3.27 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           13 |     5141 | 2024-10-13 | KUUSAMO.gg               | W   | 0.272      | 0.278        | -                | 0.164 (0.012)    | 0 (0.000) |     3.07 | aerax, FoG, Rulz, Tobsge, w1dow  |
|           12 |     5254 | 2024-10-11 | Reveal (German team)     | L   | 0.259      | -            | -                | -                | -         |    -3.94 | devils, FoG, Rulz, Tobsge, w1dow |
|           11 |     5339 | 2024-10-09 | MYinsanity               | L   | 0.246      | -            | -                | -                | -         |    -3.59 | devils, FoG, Rulz, smaxy, w1dow  |
|           10 |     5348 | 2024-10-09 | Team Czech Republic      | W   | 0.245      | 0.278        | 0.000 (0.000)    | 0.094 (0.006)    | 0 (0.000) |     4.97 | aerax, FoG, Rulz, Tobsge, w1dow  |
|            9 |     5662 | 2024-10-04 | Sampi NEXT               | W   | 0.213      | 0.278        | -                | 0.024 (0.001)    | -         |     2.25 | aerax, FoG, Rulz, Tobsge, w1dow  |
|            8 |     6123 | 2024-09-27 | Entropy Gaming           | W   | 0.166      | 0.143        | 0.000 (0.000)    | 0.051 (0.001)    | -         |     2.31 | devils, FoG, Rulz, Smaxy, w1dow  |
|            7 |     6281 | 2024-09-25 | Playing Ducks            | W   | 0.153      | -            | -                | -                | -         |     1.11 | devils, FoG, Rulz, Tobsge, w1dow |
|            6 |     6512 | 2024-09-22 | Team NinjaParentz        | W   | 0.133      | 0.143        | 0.000 (0.000)    | -                | -         |     1.83 | devils, FoG, Rulz, Smaxy, w1dow  |
|            5 |     6687 | 2024-09-19 | SNOGARD Dragons          | W   | 0.113      | 0.143        | 0.000 (0.000)    | -                | -         |     1.70 | devils, FoG, Rulz, Tobsge, w1dow |
|            4 |     7080 | 2024-09-13 | Unorganized Five         | W   | 0.073      | 0.143        | 0.000 (0.000)    | -                | -         |     1.03 | devils, FoG, Rulz, Smaxy, w1dow  |
|            3 |     7395 | 2024-09-07 | GOOFYBOYZ                | L   | 0.033      | -            | -                | -                | -         |    -0.31 | devils, FoG, Rulz, Smaxy, w1dow  |
|            2 |     7564 | 2024-09-05 | Team Kosovo              | L   | 0.020      | -            | -                | -                | -         |    -0.34 | devils, FoG, Rulz, Smaxy, w1dow  |
|            1 |     7710 | 2024-09-03 | Ex-DOSKI                 | W   | 0.007      | -            | -                | -                | -         |     0.05 | devils, FoG, Rulz, Smaxy, w1dow  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($345.56)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.460 | $241.26        | $110.98         |
| 2024-10-19 |      0.313 | $750.00        | $234.58         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
