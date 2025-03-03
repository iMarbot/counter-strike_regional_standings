### Roster Details<br />
Team Name: Regnum4Games<br />
Roster: BlacKi, kinQ, MYS, Pictrucz, Spidergum<br />
Global Rank: [334](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [216]( ../standings_europe.md)<br />
<br />
Final Rank Value:  632.3<br />
<br />
Final Rank Value (632.3) = Starting Rank Value (630.5) + Head To Head Adjustments (1.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.276[<sup>1</sup>](#table2)
- Bounty Collected: 0.182[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.115<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 630.5
- 400 + ( ( 0.115 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 630.5


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
|           19 |     2340 | 2024-12-02 | Ex-UHKA eSports      | L   | 0.599      | -            | -                | -                | -         |   -12.71 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           18 |     2495 | 2024-11-30 | POOHANK              | W   | 0.586      | 0.333        | 0.000 (0.000)    | 0.015 (0.003)    | 0 (0.000) |     7.32 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           17 |     2723 | 2024-11-26 | The Last Resort      | L   | 0.559      | -            | -                | -                | -         |    -6.93 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           16 |     4307 | 2024-10-30 | ESports Cologne      | W   | 0.379      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     3.35 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           15 |     4459 | 2024-10-27 | Wave Esports         | W   | 0.359      | 0.143        | 0.002 (0.000)    | 0.110 (0.006)    | 0 (0.000) |     5.66 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           14 |     4513 | 2024-10-26 | Wave Esports         | W   | 0.352      | 0.143        | 0.002 (0.000)    | 0.110 (0.006)    | 0 (0.000) |     5.63 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           13 |     4589 | 2024-10-25 | Reveal (German team) | W   | 0.345      | 0.143        | 0.001 (0.000)    | 0.187 (0.009)    | 0 (0.000) |     5.76 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           12 |     4709 | 2024-10-22 | Wave Esports         | L   | 0.325      | -            | -                | -                | -         |    -5.12 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|           11 |     4745 | 2024-10-21 | MYinsanity           | W   | 0.318      | 0.143        | 0.002 (0.000)    | 0.083 (0.004)    | 0 (0.000) |     5.53 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|           10 |     4780 | 2024-10-20 | Sissi State Punks    | W   | 0.312      | 0.143        | 0.000 (0.000)    | 0.066 (0.003)    | 0 (0.000) |     4.68 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            9 |     5115 | 2024-10-14 | XPERION NXT          | L   | 0.271      | -            | -                | -                | -         |    -4.01 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            8 |     5775 | 2024-10-02 | Permitta Esports     | L   | 0.192      | -            | -                | -                | -         |    -1.66 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            7 |     5851 | 2024-10-01 | MYinsanity           | L   | 0.185      | -            | -                | -                | -         |    -2.72 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            6 |     6467 | 2024-09-23 | ALTERNATE aTTaX      | L   | 0.132      | -            | -                | -                | -         |    -0.65 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            5 |     6752 | 2024-09-18 | Playing Ducks        | W   | 0.098      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.68 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            4 |     6890 | 2024-09-16 | Wave Esports         | L   | 0.085      | -            | -                | -                | -         |    -1.34 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            3 |     7197 | 2024-09-11 | Sissi State Punks    | L   | 0.051      | -            | -                | -                | -         |    -0.88 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |
|            2 |     7246 | 2024-09-10 | Reveal (German team) | L   | 0.045      | -            | -                | -                | -         |    -0.71 | BlacKi, catf1sh, kinQ, Pictrucz, Spidergum |
|            1 |     7681 | 2024-09-04 | SNOGARD Dragons      | L   | 0.004      | -            | -                | -                | -         |    -0.07 | BlacKi, kinQ, MYS, Pictrucz, Spidergum     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($774.93)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.359 | $2,159.94      | $774.93         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
