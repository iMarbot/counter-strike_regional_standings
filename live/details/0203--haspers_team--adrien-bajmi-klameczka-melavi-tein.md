### Roster Details<br />
Team Name: Haspers Team<br />
Roster: AdrieN, bajmi, Klameczka, Melavi, tein<br />
Global Rank: [203](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [148]( ../standings_europe.md)<br />
<br />
Final Rank Value:  710.1<br />
<br />
Final Rank Value (710.1) = Starting Rank Value (709.9) + Head To Head Adjustments (0.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.348[<sup>1</sup>](#table2)
- Bounty Collected: 0.239[<sup>2</sup>](#table1)
- Opponent Network: 0.034[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.155<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 709.9
- 400 + ( ( 0.155 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 709.9


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                 |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           23 |     2891 | 2024-11-23 | K27                | W   | 0.545      | 0.372        | 0.008 (0.002)    | 0.776 (0.157)    | 0 (0.000) |    12.45 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           22 |     2895 | 2024-11-23 | Nexus Gaming       | L   | 0.545      | -            | -                | -                | -         |    -1.45 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           21 |     2903 | 2024-11-23 | 1win               | L   | 0.545      | -            | -                | -                | -         |    -7.27 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           20 |     2973 | 2024-11-22 | Endpoint           | W   | 0.539      | 0.372        | 0.009 (0.002)    | 0.385 (0.077)    | 0 (0.000) |     9.69 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           19 |     3044 | 2024-11-21 | Lilmix             | W   | 0.532      | 0.372        | 0.001 (0.000)    | 0.130 (0.026)    | 0 (0.000) |     6.35 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           18 |     3083 | 2024-11-20 | FAVBET Team        | L   | 0.527      | -            | -                | -                | -         |    -4.48 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           17 |     3108 | 2024-11-20 | GenOne             | L   | 0.526      | -            | -                | -                | -         |    -5.06 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           16 |     3121 | 2024-11-20 | Illuminar Gaming   | L   | 0.526      | -            | -                | -                | -         |    -5.78 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           15 |     3151 | 2024-11-19 | Permitta Esports   | L   | 0.520      | -            | -                | -                | -         |    -6.07 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           14 |     3154 | 2024-11-19 | 500                | L   | 0.519      | -            | -                | -                | -         |    -2.32 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           13 |     3157 | 2024-11-19 | Fire Flux Esports  | L   | 0.519      | -            | -                | -                | -         |    -3.85 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           12 |     3182 | 2024-11-18 | Nuclear TigeRES    | L   | 0.514      | -            | -                | -                | -         |    -6.19 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           11 |     3425 | 2024-11-14 | Ex-9INE Academy    | W   | 0.487      | 0.372        | 0.000 (0.000)    | 0.035 (0.006)    | 0 (0.000) |     4.40 | AdrieN, bajmi, Klameczka, Melavi, tein |
|           10 |     3460 | 2024-11-14 | HyperSpirit        | W   | 0.485      | 0.372        | 0.004 (0.001)    | 0.121 (0.022)    | 0 (0.000) |     6.45 | AdrieN, bajmi, Klameczka, Melavi, tein |
|            9 |     4000 | 2024-11-04 | Dark Cloud Esports | L   | 0.420      | -            | -                | -                | -         |    -4.54 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            8 |     4402 | 2024-10-28 | GOSTIVAR           | W   | 0.374      | 0.143        | 0.000 (0.000)    | 0.031 (0.002)    | 0 (0.000) |     2.80 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            7 |     4741 | 2024-10-21 | Los kogutos        | W   | 0.326      | 0.143        | 0.032 (0.001)    | 0.527 (0.025)    | 0 (0.000) |     8.39 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            6 |     5408 | 2024-10-08 | GOSTIVAR           | L   | 0.240      | -            | -                | -                | -         |    -5.77 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            5 |     6117 | 2024-09-27 | Dark Cloud Esports | W   | 0.166      | 0.143        | 0.038 (0.001)    | 0.828 (0.020)    | 0 (0.000) |     3.46 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            4 |     6369 | 2024-09-24 | Sampi NEXT         | W   | 0.146      | 0.143        | 0.000 (0.000)    | 0.024 (0.001)    | 0 (0.000) |     1.10 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            3 |     6380 | 2024-09-24 | UNiTY esports      | L   | 0.146      | -            | -                | -                | -         |    -1.46 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            2 |     6448 | 2024-09-23 | Illuminar Gaming   | L   | 0.140      | -            | -                | -                | -         |    -1.31 | AdrieN, bajmi, hfah, Klameczka, Markoś |
|            1 |     6557 | 2024-09-21 | Mollitiem          | W   | 0.127      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.60 | AdrieN, bajmi, hfah, Klameczka, Markoś |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,469.85)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-16 |      0.499 | $8,962.94      | $4,469.85       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
