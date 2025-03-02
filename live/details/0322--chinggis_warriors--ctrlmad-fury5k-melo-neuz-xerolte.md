### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: ctrlmad, fury5k, melo, NEUZ, xerolte<br />
Global Rank: [322](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [49]( ../standings_asia.md)<br />
<br />
Final Rank Value:  638.6<br />
<br />
Final Rank Value (638.6) = Starting Rank Value (633.6) + Head To Head Adjustments (5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.211[<sup>1</sup>](#table2)
- Bounty Collected: 0.213[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.040[<sup>2</sup>](#table1)

The average of these factors is 0.117<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 633.6
- 400 + ( ( 0.117 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 633.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           10 |     5795 | 2024-10-02 | ATOX Esports              | W   | 0.198      | 0.143        | 0.064 (0.002)    | 0.604 (0.017)    | 1 (0.198) |     5.81 | ctrlmad, fury5k, melo, NEUZ, xerolte           |
|            9 |     5804 | 2024-10-02 | Clutch Gaming             | L   | 0.197      | -            | -                | -                | -         |    -3.85 | ctrlmad, fury5k, melo, NEUZ, xerolte           |
|            8 |     6149 | 2024-09-27 | Chinggis Warriors         | L   | 0.164      | -            | -                | -                | -         |    -0.82 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            7 |     6315 | 2024-09-25 | Chinggis Warriors         | L   | 0.151      | -            | -                | -                | -         |    -0.77 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            6 |     6332 | 2024-09-24 | Nomads (Mongolian team)   | W   | 0.149      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.149) |     0.98 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            5 |     6588 | 2024-09-21 | Alter Ego                 | W   | 0.125      | 0.250        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     1.60 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            4 |     6704 | 2024-09-19 | Just Swing (Chinese team) | W   | 0.112      | 0.250        | 0.005 (0.000)    | 0.351 (0.010)    | 0 (0.000) |     2.09 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            3 |     7196 | 2024-09-11 | Alter Ego                 | L   | 0.058      | -            | -                | -                | -         |    -1.08 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            2 |     7311 | 2024-09-09 | Just Swing (Chinese team) | W   | 0.045      | 0.250        | 0.005 (0.000)    | 0.351 (0.004)    | 0 (0.000) |     0.84 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            1 |     7486 | 2024-09-06 | Vizora Esports            | W   | 0.030      | 0.250        | 0.000 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     0.20 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($62.43)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.125 | $500.00        | $62.43          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
