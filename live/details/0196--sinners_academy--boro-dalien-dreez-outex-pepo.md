### Roster Details<br />
Team Name: SINNERS Academy<br />
Roster: BORO, DALIEN, dreez, outex, Pepo<br />
Global Rank: [196](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [142]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.9<br />
<br />
Final Rank Value (712.9) = Starting Rank Value (737.1) + Head To Head Adjustments (-24.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.279[<sup>2</sup>](#table1)
- Opponent Network: 0.032[<sup>2</sup>](#table1)
- LAN Wins: 0.114[<sup>2</sup>](#table1)

The average of these factors is 0.169<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 737.1
- 400 + ( ( 0.169 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 737.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           18 |     1976 | 2024-12-08 | NEVERMORE (Ukrainian team) | L   | 0.647      | -            | -                | -                | -         |    -7.74 | BORO, DALIEN, dreez, outex, Pepo   |
|           17 |     2342 | 2024-12-02 | LEON Esports               | L   | 0.606      | -            | -                | -                | -         |    -8.38 | BORO, DALIEN, dreez, outex, Pepo   |
|           16 |     2509 | 2024-11-30 | Metizport X                | W   | 0.593      | 0.333        | 0.001 (0.000)    | 0.221 (0.044)    | 0 (0.000) |     8.11 | BORO, DALIEN, dreez, outex, Pepo   |
|           15 |     2607 | 2024-11-28 | SkyFury                    | W   | 0.581      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.61 | BORO, DALIEN, dreez, outex, Pepo   |
|           14 |     2987 | 2024-11-22 | BRUTE                      | L   | 0.538      | -            | -                | -                | -         |    -8.99 | BORO, DALIEN, dreez, outex, Pepo   |
|           13 |     3400 | 2024-11-15 | Dusty Roots                | L   | 0.492      | -            | -                | -                | -         |    -7.30 | BORO, DALIEN, outex, Pepo, STYKO   |
|           12 |     3407 | 2024-11-15 | Partizan Esports           | W   | 0.491      | 0.617        | 0.082 (0.025)    | 0.768 (0.233)    | 1 (0.491) |    13.57 | BORO, DALIEN, outex, Pepo, STYKO   |
|           11 |     3417 | 2024-11-14 | Kitsune Esports            | W   | 0.488      | 0.617        | 0.001 (0.000)    | 0.098 (0.029)    | 1 (0.488) |     5.24 | BORO, DALIEN, outex, Pepo, STYKO   |
|           10 |     3489 | 2024-11-13 | Team Czech Republic        | L   | 0.480      | -            | -                | -                | -         |    -7.40 | BORO, DALIEN, outex, Pepo, STYKO   |
|            9 |     3498 | 2024-11-13 | The Huns Esports           | L   | 0.480      | -            | -                | -                | -         |    -3.66 | BORO, DALIEN, outex, Pepo, STYKO   |
|            8 |     5340 | 2024-10-09 | ENTERPRISE Genesis         | L   | 0.246      | -            | -                | -                | -         |    -4.81 | BORO, DALIEN, dreez, outex, Pepo   |
|            7 |     5602 | 2024-10-05 | 777 Esports                | L   | 0.219      | -            | -                | -                | -         |    -4.23 | BORO, DALIEN, dreez, outex, Pepo   |
|            6 |     6818 | 2024-09-17 | Kubix Esports              | L   | 0.100      | -            | -                | -                | -         |    -0.79 | BORO, DALIEN, dreez, pandi7o, Pepo |
|            5 |     7261 | 2024-09-10 | Dynamo Eclot               | L   | 0.051      | -            | -                | -                | -         |    -0.20 | BORO, DALIEN, dreez, outex, Pepo   |
|            4 |     7360 | 2024-09-08 | Dark Cloud Esports         | W   | 0.038      | 0.333        | 0.038 (0.000)    | 0.828 (0.010)    | 0 (0.000) |     0.76 | BORO, DALIEN, dreez, outex, Pepo   |
|            3 |     7396 | 2024-09-07 | Madagaskar                 | L   | 0.033      | -            | -                | -                | -         |    -0.85 | BORO, DALIEN, dreez, outex, Pepo   |
|            2 |     7688 | 2024-09-04 | Dynamo Eclot               | L   | 0.010      | -            | -                | -                | -         |    -0.04 | BORO, DALIEN, dreez, outex, Pepo   |
|            1 |     7747 | 2024-09-03 | Dragon Esports Club        | L   | 0.005      | -            | -                | -                | -         |    -0.11 | BORO, DALIEN, dreez, outex, Pepo   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($340.25)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.552 | $616.62        | $340.25         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
