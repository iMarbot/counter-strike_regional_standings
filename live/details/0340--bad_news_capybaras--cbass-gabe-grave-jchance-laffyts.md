### Roster Details<br />
Team Name: Bad News Capybaras<br />
Roster: cbass, Gabe, Grave, jchancE, LaffyTs<br />
Global Rank: [340](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [70]( ../standings_americas.md)<br />
<br />
Final Rank Value:  628.8<br />
<br />
Final Rank Value (628.8) = Starting Rank Value (667.7) + Head To Head Adjustments (-38.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.232[<sup>1</sup>](#table2)
- Bounty Collected: 0.215[<sup>2</sup>](#table1)
- Opponent Network: 0.009[<sup>2</sup>](#table1)
- LAN Wins: 0.079[<sup>2</sup>](#table1)

The average of these factors is 0.134<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 667.7
- 400 + ( ( 0.134 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 667.7


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           34 |      629 | 2025-02-09 | MCS Gaming           | L   | 1.000      | -            | -                | -                | -         |   -15.46 | cbass, Gabe, Grave, jchancE, LaffyTs |
|           33 |      685 | 2025-02-08 | M80                  | L   | 1.000      | -            | -                | -                | -         |    -4.54 | cbass, Gabe, Grave, jchancE, LaffyTs |
|           32 |     1613 | 2024-12-15 | SUPER EVIL GANG      | L   | 0.687      | -            | -                | -                | -         |    -8.41 | cbass, Champ, Grave, jchancE, z0mb1e |
|           31 |     1666 | 2024-12-14 | Undone               | L   | 0.681      | -            | -                | -                | -         |    -7.01 | cbass, Champ, Grave, jchancE, z0mb1e |
|           30 |     1756 | 2024-12-13 | LAG Gaming           | W   | 0.674      | 0.143        | 0.004 (0.000)    | 0.120 (0.012)    | 0 (0.000) |    13.28 | cbass, Champ, Grave, jchancE, z0mb1e |
|           29 |     1831 | 2024-12-12 | Chicken Coop Esports | W   | 0.667      | 0.143        | 0.006 (0.001)    | 0.187 (0.018)    | 0 (0.000) |    11.55 | cbass, Champ, Grave, jchancE, z0mb1e |
|           28 |     1872 | 2024-12-11 | Undone               | L   | 0.661      | -            | -                | -                | -         |    -6.69 | cbass, Champ, Grave, jchancE, z0mb1e |
|           27 |     1918 | 2024-12-10 | Chicken Coop Esports | W   | 0.654      | 0.143        | 0.006 (0.001)    | 0.187 (0.018)    | 0 (0.000) |    11.70 | cbass, Champ, Grave, jchancE, z0mb1e |
|           26 |     2062 | 2024-12-07 | FLUFFY AIMERS        | L   | 0.633      | -            | -                | -                | -         |    -5.87 | cbass, Champ, Grave, jchancE, z0mb1e |
|           25 |     2071 | 2024-12-07 | Sharks Esports       | L   | 0.633      | -            | -                | -                | -         |    -2.36 | cbass, Champ, Grave, jchancE, z0mb1e |
|           24 |     2125 | 2024-12-06 | Not Mythic           | W   | 0.627      | 0.384        | 0.000 (0.000)    | 0.012 (0.003)    | 1 (0.627) |     5.67 | cbass, Champ, Grave, jchancE, z0mb1e |
|           23 |     2946 | 2024-11-22 | Blahaj               | L   | 0.534      | -            | -                | -                | -         |   -11.30 | cbass, Champ, Grave, jchancE, z0mb1e |
|           22 |     5190 | 2024-10-12 | Not Mythic           | L   | 0.259      | -            | -                | -                | -         |    -5.94 | cbass, Champ, Grave, jchancE, z0mb1e |
|           21 |     5196 | 2024-10-12 | MCS Gaming           | L   | 0.258      | -            | -                | -                | -         |    -4.10 | cbass, Champ, Grave, jchancE, z0mb1e |
|           20 |     5313 | 2024-10-09 | LAG Gaming           | L   | 0.241      | -            | -                | -                | -         |    -2.87 | cbass, Champ, Grave, jchancE, z0mb1e |
|           19 |     5322 | 2024-10-09 | LAG Gaming           | W   | 0.240      | 0.477        | 0.004 (0.000)    | 0.120 (0.014)    | 0 (0.000) |     4.77 | cbass, Champ, Grave, jchancE, z0mb1e |
|           18 |     5385 | 2024-10-08 | Familia Maquininha   | L   | 0.234      | -            | -                | -                | -         |    -3.43 | cbass, Champ, Grave, jchancE, z0mb1e |
|           17 |     5391 | 2024-10-08 | Familia Maquininha   | L   | 0.233      | -            | -                | -                | -         |    -3.49 | cbass, Champ, Grave, jchancE, z0mb1e |
|           16 |     5707 | 2024-10-03 | Mythic               | W   | 0.200      | 0.477        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     1.93 | cbass, Champ, Grave, jchancE, z0mb1e |
|           15 |     5711 | 2024-10-03 | Mythic               | W   | 0.200      | 0.477        | 0.000 (0.000)    | 0.021 (0.002)    | 0 (0.000) |     1.96 | cbass, Champ, Grave, jchancE, z0mb1e |
|           14 |     5819 | 2024-10-01 | Vagrants             | L   | 0.187      | -            | -                | -                | -         |    -3.03 | cbass, Champ, Grave, jchancE, z0mb1e |
|           13 |     5824 | 2024-10-01 | Vagrants             | W   | 0.187      | 0.477        | 0.001 (0.000)    | 0.276 (0.025)    | 0 (0.000) |     2.90 | cbass, Champ, Grave, jchancE, z0mb1e |
|           12 |     6002 | 2024-09-28 | M80                  | L   | 0.167      | -            | -                | -                | -         |    -0.99 | cbass, Champ, Grave, jchancE, z0mb1e |
|           11 |     6005 | 2024-09-28 | M80                  | L   | 0.167      | -            | -                | -                | -         |    -1.00 | cbass, Champ, Grave, jchancE, z0mb1e |
|           10 |     6179 | 2024-09-26 | MarcaRegistrada      | L   | 0.153      | -            | -                | -                | -         |    -2.79 | cbass, Champ, Grave, jchancE, z0mb1e |
|            9 |     6253 | 2024-09-25 | Legacy               | L   | 0.147      | -            | -                | -                | -         |    -1.12 | cbass, Champ, Grave, jchancE, z0mb1e |
|            8 |     6258 | 2024-09-25 | Legacy               | L   | 0.147      | -            | -                | -                | -         |    -1.12 | cbass, Champ, Grave, jchancE, z0mb1e |
|            7 |     6730 | 2024-09-18 | NRG                  | L   | 0.100      | -            | -                | -                | -         |    -0.40 | cbass, Champ, Grave, jchancE, z0mb1e |
|            6 |     6737 | 2024-09-18 | NRG                  | L   | 0.100      | -            | -                | -                | -         |    -0.40 | cbass, Champ, Grave, jchancE, z0mb1e |
|            5 |     7341 | 2024-09-08 | Timbermen            | L   | 0.033      | -            | -                | -                | -         |    -0.53 | cbass, Grave, jchancE, serv0, z0mb1e |
|            4 |     7388 | 2024-09-07 | Wanted Goons         | W   | 0.027      | 0.333        | 0.000 (0.000)    | 0.001 (0.000)    | 1 (0.027) |     0.22 | cbass, Grave, jchancE, serv0, z0mb1e |
|            3 |     7419 | 2024-09-07 | Amped Esports Red    | W   | 0.025      | 0.333        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.025) |     0.14 | cbass, Grave, jchancE, serv0, z0mb1e |
|            2 |     7644 | 2024-09-04 | FLUFFY AIMERS        | L   | 0.007      | -            | -                | -                | -         |    -0.07 | cbass, Champ, Grave, jchancE, z0mb1e |
|            1 |     7645 | 2024-09-04 | FLUFFY AIMERS        | L   | 0.007      | -            | -                | -                | -         |    -0.07 | cbass, Champ, Grave, jchancE, z0mb1e |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($158.78)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-20 |      0.313 | $400.00        | $125.17         |
| 2024-09-08 |      0.034 | $1,000.00      | $33.61          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
