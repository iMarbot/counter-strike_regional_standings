### Roster Details<br />
Team Name: Eco Warriors<br />
Roster: Angelka, D7, juliano, kyossa, vicu<br />
Global Rank: [114](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [82]( ../standings_europe.md)<br />
<br />
Final Rank Value:  816.2<br />
<br />
Final Rank Value (816.2) = Starting Rank Value (794.2) + Head To Head Adjustments (22.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.377[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.014[<sup>2</sup>](#table1)
- LAN Wins: 0.126[<sup>2</sup>](#table1)

The average of these factors is 0.197<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 794.2
- 400 + ( ( 0.197 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 794.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           21 |      919 | 2025-02-05 | SAW                  | L   | 1.000      | -            | -                | -                | -         |    -2.40 | Angelka, D7, juliano, kyossa, vicu |
|           20 |      927 | 2025-02-05 | 500                  | L   | 1.000      | -            | -                | -                | -         |    -7.66 | Angelka, D7, juliano, kyossa, vicu |
|           19 |     1064 | 2025-02-01 | Prototype Blaze      | W   | 1.000      | 0.143        | 0.058 (0.008)    | 0.228 (0.033)    | 0 (0.000) |    18.30 | D7, juliano, kyossa, vicu, wieenN  |
|           18 |     1070 | 2025-02-01 | Forfunny             | W   | 1.000      | 0.143        | -                | 0.047 (0.007)    | 0 (0.000) |     3.14 | D7, juliano, kyossa, vicu, wieenN  |
|           17 |     1099 | 2025-01-31 | 95 Vikings Female    | W   | 0.999      | -            | -                | -                | 0 (0.000) |     2.96 | D7, juliano, kyossa, vicu, wieenN  |
|           16 |     2809 | 2024-11-24 | FURIA Esports Female | L   | 0.544      | -            | -                | -                | -         |    -5.87 | Angelka, ASTRA, D7, Hanka, vicu    |
|           15 |     2889 | 2024-11-23 | Fluxo Demons         | W   | 0.538      | 0.524        | 0.019 (0.005)    | 0.198 (0.056)    | 1 (0.538) |     8.09 | Angelka, ASTRA, D7, Hanka, vicu    |
|           14 |     2919 | 2024-11-23 | FlyQuest RED         | W   | 0.536      | 0.524        | 0.007 (0.002)    | 0.038 (0.011)    | 1 (0.536) |     5.40 | Angelka, ASTRA, D7, Hanka, vicu    |
|           13 |     3007 | 2024-11-22 | Imperial Female      | L   | 0.529      | -            | -                | -                | -         |    -3.62 | Angelka, ASTRA, D7, Hanka, vicu    |
|           12 |     4785 | 2024-10-20 | Let Her Cook         | W   | 0.311      | 0.328        | 0.002 (0.000)    | 0.030 (0.003)    | 0 (0.000) |     2.90 | Angelka, ASTRA, D7, Hanka, vicu    |
|           11 |     4847 | 2024-10-19 | K27 Female           | L   | 0.305      | -            | -                | -                | -         |    -5.95 | Angelka, ASTRA, D7, Hanka, vicu    |
|           10 |     4892 | 2024-10-18 | Ex-Astralis Women    | W   | 0.298      | 0.328        | 0.010 (0.001)    | 0.083 (0.008)    | 0 (0.000) |     4.10 | Angelka, ASTRA, D7, Hanka, vicu    |
|            9 |     5779 | 2024-10-02 | Take Flyte Female    | W   | 0.191      | 0.328        | 0.006 (0.000)    | 0.267 (0.017)    | 0 (0.000) |     1.98 | Angelka, ASTRA, D7, Hanka, vicu    |
|            8 |     6770 | 2024-09-18 | ENCE Athena          | W   | 0.098      | 0.328        | 0.001 (0.000)    | -                | 0 (0.000) |     0.56 | Angelka, ASTRA, D7, Hanka, vicu    |
|            7 |     6846 | 2024-09-17 | Eternal prem         | L   | 0.091      | -            | -                | -                | -         |    -2.15 | Angelka, ASTRA, D7, Hanka, vicu    |
|            6 |     6959 | 2024-09-15 | Imperial Female      | W   | 0.076      | 0.294        | 0.136 (0.003)    | 0.162 (0.004)    | 0 (0.000) |     1.89 | Angelka, ASTRA, D7, Hanka, vicu    |
|            5 |     7021 | 2024-09-14 | NIP Impact           | W   | 0.070      | 0.294        | 0.012 (0.000)    | -                | -         |     0.87 | Angelka, ASTRA, D7, Hanka, vicu    |
|            4 |     7050 | 2024-09-14 | Take Flyte Female    | W   | 0.070      | 0.294        | 0.006 (0.000)    | 0.267 (0.005)    | -         |     0.73 | Angelka, ASTRA, D7, Hanka, vicu    |
|            3 |     7200 | 2024-09-11 | NoLightGaming        | L   | 0.051      | -            | -                | -                | -         |    -1.19 | Angelka, ASTRA, D7, Hanka, vicu    |
|            2 |     7443 | 2024-09-07 | OneDay               | W   | 0.024      | 0.294        | -                | 0.148 (0.001)    | -         |     0.19 | Angelka, ASTRA, D7, Hanka, vicu    |
|            1 |     7595 | 2024-09-05 | NIP Impact           | L   | 0.011      | -            | -                | -                | -         |    -0.22 | Angelka, ASTRA, D7, Hanka, vicu    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($7,348.22)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-24 |      0.544 | $13,000.00     | $7,077.78       |
| 2024-09-21 |      0.118 | $350.00        | $41.42          |
| 2024-09-15 |      0.076 | $3,000.00      | $229.03         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
