### Roster Details<br />
Team Name: Chinggis Warriors<br />
Roster: ctrlmad, fury5k, melo, NEUZ, xerolte<br />
Global Rank: [325](../standings_global.md)<br />
<br />
Region: [Asia]( ../standings_asia.md)<br />
Regional Rank: [50]( ../standings_asia.md)<br />
<br />
Final Rank Value:  636.7<br />
<br />
Final Rank Value (636.7) = Starting Rank Value (632.1) + Head To Head Adjustments (4.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.210[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.039[<sup>2</sup>](#table1)

The average of these factors is 0.116<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 632.1
- 400 + ( ( 0.116 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 632.1


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
|           10 |     5807 | 2024-10-02 | ATOX Esports              | W   | 0.189      | 0.143        | 0.064 (0.002)    | 0.601 (0.016)    | 1 (0.189) |     5.56 | ctrlmad, fury5k, melo, NEUZ, xerolte           |
|            9 |     5816 | 2024-10-02 | Clutch Gaming             | L   | 0.189      | -            | -                | -                | -         |    -3.69 | ctrlmad, fury5k, melo, NEUZ, xerolte           |
|            8 |     6161 | 2024-09-27 | Chinggis Warriors         | L   | 0.156      | -            | -                | -                | -         |    -0.78 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            7 |     6327 | 2024-09-25 | Chinggis Warriors         | L   | 0.143      | -            | -                | -                | -         |    -0.73 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            6 |     6344 | 2024-09-24 | Nomads (Mongolian team)   | W   | 0.141      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.141) |     0.94 | fury5k, NEUZ, sergelen19k, xerolte, Zilkenberg |
|            5 |     6600 | 2024-09-21 | Alter Ego                 | W   | 0.117      | 0.250        | 0.000 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     1.50 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            4 |     6716 | 2024-09-19 | Just Swing (Chinese team) | W   | 0.103      | 0.250        | 0.005 (0.000)    | 0.346 (0.009)    | 0 (0.000) |     1.94 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            3 |     7208 | 2024-09-11 | Alter Ego                 | L   | 0.050      | -            | -                | -                | -         |    -0.93 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            2 |     7323 | 2024-09-09 | Just Swing (Chinese team) | W   | 0.037      | 0.250        | 0.005 (0.000)    | 0.346 (0.003)    | 0 (0.000) |     0.69 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |
|            1 |     7498 | 2024-09-06 | Vizora Esports            | W   | 0.022      | 0.250        | 0.000 (0.000)    | 0.002 (0.000)    | 0 (0.000) |     0.15 | fury5k, NEUZ, Stormrage, xerolte, Zilkenberg   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($58.33)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-09-21 |      0.117 | $500.00        | $58.33          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
