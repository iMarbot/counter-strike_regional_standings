### Roster Details<br />
Team Name: SNOGARD Dragons<br />
Roster: kryptoN, LapeX, mave, ND, Shairoe<br />
Global Rank: [417](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [258]( ../standings_europe.md)<br />
<br />
Final Rank Value:  583.8<br />
<br />
Final Rank Value (583.8) = Starting Rank Value (594.0) + Head To Head Adjustments (-10.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.223[<sup>1</sup>](#table2)
- Bounty Collected: 0.165[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.097<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 594.0
- 400 + ( ( 0.097 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 594.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                            |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |     4141 | 2024-11-02 | XPERION NXT          | L   | 0.406      | -            | -                | -                | -         |    -5.40 | kryptoN, LapeX, mave, ND, Shairoe |
|           14 |     4355 | 2024-10-29 | Wave Esports         | L   | 0.380      | -            | -                | -                | -         |    -5.37 | kryptoN, LapeX, mave, ND, Shairoe |
|           13 |     4368 | 2024-10-29 | BIG                  | L   | 0.380      | -            | -                | -                | -         |    -0.08 | kryptoN, LapeX, mave, ND, Shairoe |
|           12 |     4795 | 2024-10-20 | Reveal (German team) | L   | 0.319      | -            | -                | -                | -         |    -4.37 | kryptoN, LapeX, mave, ND, Shairoe |
|           11 |     4932 | 2024-10-17 | Playing Ducks        | W   | 0.299      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.31 | kryptoN, LapeX, mave, ND, Shairoe |
|           10 |     5098 | 2024-10-14 | Sissi State Punks    | W   | 0.280      | 0.143        | 0.000 (0.000)    | 0.068 (0.003)    | 0 (0.000) |     4.60 | kryptoN, LapeX, mave, ND, Shairoe |
|            9 |     5330 | 2024-10-09 | Wave Esports         | L   | 0.247      | -            | -                | -                | -         |    -3.52 | kryptoN, LapeX, mave, ND, Shairoe |
|            8 |     5479 | 2024-10-07 | MYinsanity           | W   | 0.233      | 0.143        | 0.002 (0.000)    | 0.086 (0.003)    | 0 (0.000) |     4.29 | kryptoN, LapeX, mave, ND, Shairoe |
|            7 |     5773 | 2024-10-02 | ALTERNATE aTTaX      | L   | 0.199      | -            | -                | -                | -         |    -0.86 | kryptoN, LapeX, mave, ND, Shairoe |
|            6 |     6687 | 2024-09-19 | ALTERNATE aTTaX Evo  | L   | 0.113      | -            | -                | -                | -         |    -1.70 | kryptoN, LapeX, mave, ND, Shairoe |
|            5 |     6752 | 2024-09-18 | XPERION NXT          | L   | 0.106      | -            | -                | -                | -         |    -1.45 | kryptoN, LapeX, mave, ND, Shairoe |
|            4 |     6833 | 2024-09-17 | Sissi State Punks    | W   | 0.099      | 0.143        | 0.000 (0.000)    | 0.068 (0.001)    | 0 (0.000) |     1.59 | kryptoN, LapeX, mave, ND, Shairoe |
|            3 |     7272 | 2024-09-09 | Permitta Esports     | L   | 0.047      | -            | -                | -                | -         |    -0.35 | kryptoN, LapeX, mave, ND, Shairoe |
|            2 |     7669 | 2024-09-04 | Regnum4Games         | W   | 0.013      | 0.143        | 0.002 (0.000)    | 0.115 (0.000)    | 0 (0.000) |     0.22 | kryptoN, LapeX, mave, ND, Shairoe |
|            1 |     7706 | 2024-09-03 | Regnum4Games         | L   | 0.007      | -            | -                | -                | -         |    -0.09 | kryptoN, LapeX, mave, ND, Shairoe |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($108.17)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.686 | $157.57        | $108.17         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
