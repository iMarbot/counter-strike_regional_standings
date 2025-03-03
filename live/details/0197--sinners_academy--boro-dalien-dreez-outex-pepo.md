### Roster Details<br />
Team Name: SINNERS Academy<br />
Roster: BORO, DALIEN, dreez, outex, Pepo<br />
Global Rank: [197](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [141]( ../standings_europe.md)<br />
<br />
Final Rank Value:  712.7<br />
<br />
Final Rank Value (712.7) = Starting Rank Value (736.1) + Head To Head Adjustments (-23.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.250[<sup>1</sup>](#table2)
- Bounty Collected: 0.278[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.113[<sup>2</sup>](#table1)

The average of these factors is 0.168<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 736.1
- 400 + ( ( 0.168 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 736.1


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
|           17 |     1988 | 2024-12-08 | NEVERMORE (Ukrainian team) | L   | 0.639      | -            | -                | -                | -         |    -7.66 | BORO, DALIEN, dreez, outex, Pepo   |
|           16 |     2354 | 2024-12-02 | LEON Esports               | L   | 0.598      | -            | -                | -                | -         |    -8.26 | BORO, DALIEN, dreez, outex, Pepo   |
|           15 |     2521 | 2024-11-30 | Metizport X                | W   | 0.585      | 0.333        | 0.001 (0.000)    | 0.218 (0.042)    | 0 (0.000) |     7.99 | BORO, DALIEN, dreez, outex, Pepo   |
|           14 |     2619 | 2024-11-28 | SkyFury                    | W   | 0.572      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.58 | BORO, DALIEN, dreez, outex, Pepo   |
|           13 |     2999 | 2024-11-22 | BRUTE                      | L   | 0.530      | -            | -                | -                | -         |    -8.85 | BORO, DALIEN, dreez, outex, Pepo   |
|           12 |     3412 | 2024-11-15 | Dusty Roots                | L   | 0.484      | -            | -                | -                | -         |    -7.16 | BORO, DALIEN, outex, Pepo, STYKO   |
|           11 |     3419 | 2024-11-15 | Partizan Esports           | W   | 0.483      | 0.617        | 0.083 (0.025)    | 0.757 (0.226)    | 1 (0.483) |    13.33 | BORO, DALIEN, outex, Pepo, STYKO   |
|           10 |     3429 | 2024-11-14 | Kitsune Esports            | W   | 0.480      | 0.617        | 0.001 (0.000)    | 0.096 (0.028)    | 1 (0.480) |     5.15 | BORO, DALIEN, outex, Pepo, STYKO   |
|            9 |     3501 | 2024-11-13 | Team Czech Republic        | L   | 0.472      | -            | -                | -                | -         |    -7.30 | BORO, DALIEN, outex, Pepo, STYKO   |
|            8 |     3510 | 2024-11-13 | The Huns Esports           | L   | 0.471      | -            | -                | -                | -         |    -3.61 | BORO, DALIEN, outex, Pepo, STYKO   |
|            7 |     5352 | 2024-10-09 | ENTERPRISE Genesis         | L   | 0.238      | -            | -                | -                | -         |    -4.65 | BORO, DALIEN, dreez, outex, Pepo   |
|            6 |     5610 | 2024-10-05 | 777 Esports                | L   | 0.210      | -            | -                | -                | -         |    -4.07 | BORO, DALIEN, dreez, outex, Pepo   |
|            5 |     6830 | 2024-09-17 | Kubix Esports              | L   | 0.092      | -            | -                | -                | -         |    -0.73 | BORO, DALIEN, dreez, pandi7o, Pepo |
|            4 |     7273 | 2024-09-10 | Dynamo Eclot               | L   | 0.043      | -            | -                | -                | -         |    -0.17 | BORO, DALIEN, dreez, outex, Pepo   |
|            3 |     7372 | 2024-09-08 | Dark Cloud Esports         | W   | 0.030      | 0.333        | 0.039 (0.000)    | 0.819 (0.008)    | 0 (0.000) |     0.60 | BORO, DALIEN, dreez, outex, Pepo   |
|            2 |     7408 | 2024-09-07 | Madagaskar                 | L   | 0.025      | -            | -                | -                | -         |    -0.64 | BORO, DALIEN, dreez, outex, Pepo   |
|            1 |     7700 | 2024-09-04 | Dynamo Eclot               | L   | 0.002      | -            | -                | -                | -         |    -0.01 | BORO, DALIEN, dreez, outex, Pepo   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($335.20)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $616.62        | $335.20         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
