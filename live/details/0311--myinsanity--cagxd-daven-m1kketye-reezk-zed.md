### Roster Details<br />
Team Name: MYinsanity<br />
Roster: CagXD, DAVEN, m1kketye, reezk, zed<br />
Global Rank: [311](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [208]( ../standings_europe.md)<br />
<br />
Final Rank Value:  642.3<br />
<br />
Final Rank Value (642.3) = Starting Rank Value (656.0) + Head To Head Adjustments (-13.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.274[<sup>1</sup>](#table2)
- Bounty Collected: 0.175[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.062[<sup>2</sup>](#table1)

The average of these factors is 0.128<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 656.0
- 400 + ( ( 0.128 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 656.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                             |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           20 |     4307 | 2024-10-30 | BIG                     | L   | 0.386      | -            | -                | -                | -         |    -0.11 | CagXD, DAVEN, m1kketye, reezk, zed |
|           19 |     4520 | 2024-10-26 | Reveal (German team)    | L   | 0.359      | -            | -                | -                | -         |    -5.71 | CagXD, DAVEN, m1kketye, reezk, zed |
|           18 |     4593 | 2024-10-25 | Wave Esports            | L   | 0.352      | -            | -                | -                | -         |    -5.85 | CagXD, DAVEN, m1kketye, reezk, zed |
|           17 |     4658 | 2024-10-23 | Permitta Esports        | L   | 0.340      | -            | -                | -                | -         |    -3.48 | CagXD, DAVEN, m1kketye, reezk, zed |
|           16 |     4733 | 2024-10-21 | Regnum4Games            | L   | 0.326      | -            | -                | -                | -         |    -5.69 | CagXD, DAVEN, m1kketye, reezk, zed |
|           15 |     4779 | 2024-10-20 | Reveal (German team)    | W   | 0.319      | 0.143        | 0.001 (0.000)    | 0.192 (0.009)    | 0 (0.000) |     4.87 | CagXD, DAVEN, m1kketye, reezk, zed |
|           14 |     4984 | 2024-10-16 | ESports Cologne         | W   | 0.293      | 0.143        | 0.000 (0.000)    | 0.017 (0.001)    | 0 (0.000) |     2.39 | CagXD, DAVEN, m1kketye, reezk, zed |
|           13 |     5162 | 2024-10-12 | Los kogutos             | L   | 0.270      | -            | -                | -                | -         |    -1.20 | CagXD, DAVEN, m1kketye, reezk, zed |
|           12 |     5192 | 2024-10-12 | Team Solid (Swiss team) | W   | 0.266      | 0.143        | 0.000 (0.000)    | 0.012 (0.000)    | 1 (0.266) |     1.76 | CagXD, DAVEN, m1kketye, reezk, zed |
|           11 |     5215 | 2024-10-12 | Addicted Esports        | W   | 0.265      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 1 (0.265) |     1.61 | CagXD, DAVEN, m1kketye, reezk, zed |
|           10 |     5339 | 2024-10-09 | ALTERNATE aTTaX Evo     | W   | 0.246      | 0.143        | 0.001 (0.000)    | 0.184 (0.006)    | 0 (0.000) |     3.59 | CagXD, DAVEN, m1kketye, reezk, zed |
|            9 |     5479 | 2024-10-07 | SNOGARD Dragons         | L   | 0.233      | -            | -                | -                | -         |    -4.29 | CagXD, DAVEN, m1kketye, reezk, zed |
|            8 |     5839 | 2024-10-01 | Regnum4Games            | W   | 0.193      | 0.143        | 0.002 (0.000)    | 0.115 (0.003)    | 0 (0.000) |     2.83 | CagXD, DAVEN, m1kketye, reezk, zed |
|            7 |     5906 | 2024-09-30 | Wave Esports            | W   | 0.186      | 0.143        | 0.001 (0.000)    | 0.113 (0.003)    | 0 (0.000) |     2.77 | CagXD, DAVEN, m1kketye, reezk, zed |
|            6 |     6284 | 2024-09-25 | Sissi State Punks       | L   | 0.153      | -            | -                | -                | -         |    -2.76 | CagXD, DAVEN, m1kketye, reezk, zed |
|            5 |     6374 | 2024-09-24 | Sissi State Punks       | L   | 0.146      | -            | -                | -                | -         |    -2.67 | CagXD, DAVEN, m1kketye, reezk, zed |
|            4 |     6812 | 2024-09-17 | Wave Esports            | L   | 0.100      | -            | -                | -                | -         |    -1.69 | CagXD, DAVEN, m1kketye, reezk, zed |
|            3 |     7183 | 2024-09-11 | Playing Ducks           | W   | 0.059      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.36 | CagXD, DAVEN, m1kketye, reezk, zed |
|            2 |     7298 | 2024-09-09 | ALTERNATE aTTaX         | L   | 0.046      | -            | -                | -                | -         |    -0.25 | CagXD, DAVEN, m1kketye, reezk, zed |
|            1 |     7644 | 2024-09-04 | XPERION NXT             | L   | 0.013      | -            | -                | -                | -         |    -0.22 | CagXD, DAVEN, m1kketye, reezk, zed |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($742.73)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-14 |      0.686 | $105.05        | $72.11          |
| 2024-10-27 |      0.367 | $539.99        | $198.16         |
| 2024-10-12 |      0.270 | $1,749.84      | $472.46         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
