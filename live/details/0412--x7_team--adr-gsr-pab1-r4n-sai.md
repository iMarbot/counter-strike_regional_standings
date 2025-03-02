### Roster Details<br />
Team Name: X7 Team<br />
Roster: aDr, gsr, pab1, R4N, sai<br />
Global Rank: [412](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [91]( ../standings_americas.md)<br />
<br />
Final Rank Value:  587.3<br />
<br />
Final Rank Value (587.3) = Starting Rank Value (627.8) + Head To Head Adjustments (-40.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.209[<sup>1</sup>](#table2)
- Bounty Collected: 0.242[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.114<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 627.8
- 400 + ( ( 0.114 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 627.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           19 |     2071 | 2024-12-07 | ArtGamerz            | L   | 0.640      | -            | -                | -                | -         |   -13.45 | aDr, gsr, pab1, R4N, sai |
|           18 |     2248 | 2024-12-03 | Guará eSports        | L   | 0.615      | -            | -                | -                | -         |   -13.21 | aDr, gsr, pab1, R4N, sai |
|           17 |     2461 | 2024-11-30 | DB Peek Esports      | L   | 0.595      | -            | -                | -                | -         |    -9.06 | aDr, gsr, pab1, R4N, sai |
|           16 |     3924 | 2024-11-05 | Floripa Stars        | L   | 0.427      | -            | -                | -                | -         |    -6.01 | aDr, gsr, pab1, R4N, sai |
|           15 |     3977 | 2024-11-04 | Galorys Academy      | W   | 0.421      | 0.250        | 0.001 (0.000)    | 0.158 (0.017)    | 0 (0.000) |     6.58 | aDr, gsr, pab1, R4N, sai |
|           14 |     4118 | 2024-11-02 | FURIA Esports Female | L   | 0.407      | -            | -                | -                | -         |    -1.69 | aDr, gsr, pab1, R4N, sai |
|           13 |     4233 | 2024-10-31 | 9z Academy           | L   | 0.394      | -            | -                | -                | -         |    -5.67 | aDr, gsr, pab1, R4N, sai |
|           12 |     4611 | 2024-10-24 | Pugdesonesto         | W   | 0.348      | 0.250        | 0.000 (0.000)    | 0.101 (0.009)    | 0 (0.000) |     5.78 | aDr, gsr, pab1, R4N, sai |
|           11 |     4612 | 2024-10-24 | FURIA Esports Female | W   | 0.347      | 0.250        | 0.064 (0.006)    | 0.223 (0.019)    | 0 (0.000) |     9.73 | aDr, gsr, pab1, R4N, sai |
|           10 |     4918 | 2024-10-17 | Floripa Stars        | L   | 0.301      | -            | -                | -                | -         |    -4.19 | aDr, gsr, pab1, R4N, sai |
|            9 |     5651 | 2024-10-04 | Galorys Academy      | L   | 0.214      | -            | -                | -                | -         |    -3.13 | aDr, gsr, pab1, R4N, sai |
|            8 |     5710 | 2024-10-03 | 9z Academy           | L   | 0.207      | -            | -                | -                | -         |    -2.84 | aDr, gsr, pab1, R4N, sai |
|            7 |     6016 | 2024-09-28 | Dusty Roots          | L   | 0.173      | -            | -                | -                | -         |    -1.54 | aDr, gsr, pab1, R4N, sai |
|            6 |     6357 | 2024-09-24 | Pugdesonesto         | L   | 0.147      | -            | -                | -                | -         |    -2.27 | aDr, gsr, pab1, R4N, sai |
|            5 |     6666 | 2024-09-19 | TROPA DOS 7          | L   | 0.115      | -            | -                | -                | -         |    -2.47 | aDr, gsr, pab1, R4N, sai |
|            4 |     6806 | 2024-09-17 | FURIA Esports Female | W   | 0.100      | 0.250        | 0.064 (0.002)    | 0.223 (0.006)    | 0 (0.000) |     2.79 | aDr, gsr, pab1, R4N, sai |
|            3 |     7116 | 2024-09-12 | Yawara E-Sports      | W   | 0.068      | 0.250        | 0.002 (0.000)    | 0.454 (0.008)    | 0 (0.000) |     1.24 | aDr, gsr, pab1, R4N, sai |
|            2 |     7271 | 2024-09-09 | Galorys Academy      | L   | 0.047      | -            | -                | -                | -         |    -0.71 | aDr, gsr, pab1, R4N, sai |
|            1 |     7549 | 2024-09-05 | Floripa Stars        | L   | 0.021      | -            | -                | -                | -         |    -0.31 | aDr, gsr, pab1, R4N, sai |

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
