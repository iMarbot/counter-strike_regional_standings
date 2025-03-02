### Roster Details<br />
Team Name: Regnum4Games<br />
Roster: BlacKi, kinQ, MYS, Pictrucz, Spidergum<br />
Global Rank: [333](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [217]( ../standings_europe.md)<br />
<br />
Final Rank Value:  632.1<br />
<br />
Final Rank Value (632.1) = Starting Rank Value (630.5) + Head To Head Adjustments (1.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.5
- 400 + ( ( 0.115 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 630.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                     |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     2328 | 2024-12-02 | Ex-UHKA eSports      | L   | 0.607      | -            | -                | -                | -         |   -12.86 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           19 |     2483 | 2024-11-30 | POOHANK              | W   | 0.594      | 0.333        | 0.000 (0.000)    | 0.016 (0.003)    | 0 (0.000) |     7.43 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           18 |     2711 | 2024-11-26 | The Last Resort      | L   | 0.567      | -            | -                | -                | -         |    -7.02 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           17 |     4295 | 2024-10-30 | ESports Cologne      | W   | 0.387      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.42 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           16 |     4447 | 2024-10-27 | Wave Esports         | W   | 0.367      | 0.143        | 0.001 (0.000)    | 0.113 (0.006)    | 0 (0.000) |     5.80 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           15 |     4501 | 2024-10-26 | Wave Esports         | W   | 0.360      | 0.143        | 0.001 (0.000)    | 0.113 (0.006)    | 0 (0.000) |     5.78 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           14 |     4577 | 2024-10-25 | Reveal (German team) | W   | 0.353      | 0.143        | 0.001 (0.000)    | 0.192 (0.010)    | 0 (0.000) |     5.91 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           13 |     4697 | 2024-10-22 | Wave Esports         | L   | 0.333      | -            | -                | -                | -         |    -5.24 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           12 |     4733 | 2024-10-21 | MYinsanity           | W   | 0.326      | 0.143        | 0.002 (0.000)    | 0.086 (0.004)    | 0 (0.000) |     5.69 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           11 |     4768 | 2024-10-20 | Sissi State Punks    | W   | 0.320      | 0.143        | 0.000 (0.000)    | 0.068 (0.003)    | 0 (0.000) |     4.82 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           10 |     5103 | 2024-10-14 | XPERION NXT          | L   | 0.279      | -            | -                | -                | -         |    -4.12 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            9 |     5763 | 2024-10-02 | Permitta Esports     | L   | 0.200      | -            | -                | -                | -         |    -1.72 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            8 |     5839 | 2024-10-01 | MYinsanity           | L   | 0.193      | -            | -                | -                | -         |    -2.83 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            7 |     6455 | 2024-09-23 | ALTERNATE aTTaX      | L   | 0.140      | -            | -                | -                | -         |    -0.68 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            6 |     6740 | 2024-09-18 | Playing Ducks        | W   | 0.107      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.73 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            5 |     6878 | 2024-09-16 | Wave Esports         | L   | 0.093      | -            | -                | -                | -         |    -1.47 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            4 |     7185 | 2024-09-11 | Sissi State Punks    | L   | 0.059      | -            | -                | -                | -         |    -1.01 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            3 |     7234 | 2024-09-10 | Reveal (German team) | L   | 0.053      | -            | -                | -                | -         |    -0.84 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            2 |     7669 | 2024-09-04 | SNOGARD Dragons      | L   | 0.013      | -            | -                | -                | -         |    -0.22 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            1 |     7706 | 2024-09-03 | SNOGARD Dragons      | W   | 0.007      | 0.143        | 0.000 (0.000)    | 0.039 (0.000)    | 0 (0.000) |     0.09 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($792.63)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.367 | $2,159.94      | $792.63         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
