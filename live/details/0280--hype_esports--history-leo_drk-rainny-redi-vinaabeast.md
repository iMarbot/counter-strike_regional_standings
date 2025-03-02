### Roster Details<br />
Team Name: Hype Esports<br />
Roster: history, leo_drk, rainny, redi, vinaabEAST<br />
Global Rank: [280](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [52]( ../standings_americas.md)<br />
<br />
Final Rank Value:  661.7<br />
<br />
Final Rank Value (661.7) = Starting Rank Value (666.7) + Head To Head Adjustments (-4.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.257[<sup>1</sup>](#table2)
- Bounty Collected: 0.256[<sup>2</sup>](#table1)
- Opponent Network: 0.021[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.133<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 666.7
- 400 + ( ( 0.133 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 666.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     1666 | 2024-12-14 | Game Hunters           | L   | 0.688      | -            | -                | -                | -         |    -9.31 | history, leo_drk, rainny, redi, vinaabEAST   |
|           19 |     1757 | 2024-12-13 | Bounty Hunters Esports | L   | 0.681      | -            | -                | -                | -         |    -9.26 | history, leo_drk, rainny, redi, vinaabEAST   |
|           18 |     3799 | 2024-11-08 | Team Solid             | L   | 0.446      | -            | -                | -                | -         |    -3.77 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           17 |     3862 | 2024-11-06 | ShindeN                | W   | 0.435      | 0.371        | 0.005 (0.001)    | 0.310 (0.050)    | 0 (0.000) |     7.92 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           16 |     5318 | 2024-10-09 | Case Esports           | L   | 0.248      | -            | -                | -                | -         |    -3.83 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           15 |     5326 | 2024-10-09 | Case Esports           | W   | 0.247      | 0.450        | 0.001 (0.000)    | 0.064 (0.007)    | 0 (0.000) |     4.04 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           14 |     5390 | 2024-10-08 | Team Solid             | W   | 0.241      | 0.450        | 0.023 (0.002)    | 0.561 (0.061)    | 0 (0.000) |     5.54 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           13 |     5401 | 2024-10-08 | Team Solid             | L   | 0.241      | -            | -                | -                | -         |    -2.07 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           12 |     5747 | 2024-10-02 | Imperial Esports       | L   | 0.201      | -            | -                | -                | -         |    -0.93 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           11 |     5753 | 2024-10-02 | Imperial Esports       | L   | 0.201      | -            | -                | -                | -         |    -0.94 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|           10 |     5823 | 2024-10-01 | PaiN Gaming            | L   | 0.194      | -            | -                | -                | -         |    -0.03 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            9 |     5828 | 2024-10-01 | PaiN Gaming            | L   | 0.194      | -            | -                | -                | -         |    -0.03 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            8 |     6092 | 2024-09-27 | Fluxo                  | L   | 0.168      | -            | -                | -                | -         |    -1.05 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            7 |     6175 | 2024-09-26 | Galorys                | W   | 0.161      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     1.34 | history, leo_drk, MaLLby, rainny, vinaabEAST |
|            6 |     6254 | 2024-09-25 | Sharks Esports         | W   | 0.154      | 0.450        | 0.054 (0.004)    | 0.629 (0.044)    | 0 (0.000) |     4.29 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            5 |     6260 | 2024-09-25 | Sharks Esports         | L   | 0.154      | -            | -                | -                | -         |    -0.58 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            4 |     6347 | 2024-09-24 | BESTIA                 | L   | 0.148      | -            | -                | -                | -         |    -0.97 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            3 |     6353 | 2024-09-24 | BESTIA                 | W   | 0.147      | 0.450        | 0.069 (0.005)    | 0.478 (0.032)    | 0 (0.000) |     3.71 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            2 |     6800 | 2024-09-17 | Dusty Roots            | L   | 0.101      | -            | -                | -                | -         |    -1.08 | history, leo_drk, MaLLby, redi, vinaabEAST   |
|            1 |     6805 | 2024-09-17 | Dusty Roots            | W   | 0.101      | 0.450        | 0.008 (0.000)    | 0.371 (0.017)    | 0 (0.000) |     2.11 | history, leo_drk, MaLLby, redi, vinaabEAST   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($437.17)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-09 |      0.455 | $750.00        | $341.13         |
| 2024-10-20 |      0.320 | $300.00        | $96.04          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
