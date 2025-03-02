### Roster Details<br />
Team Name: Kario Mart<br />
Roster: delle, Fabbelit0, pulan, Simpan, tvs<br />
Global Rank: [346](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [225]( ../standings_europe.md)<br />
<br />
Final Rank Value:  625.9<br />
<br />
Final Rank Value (625.9) = Starting Rank Value (625.6) + Head To Head Adjustments (0.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.291[<sup>1</sup>](#table2)
- Bounty Collected: 0.158[<sup>2</sup>](#table1)
- Opponent Network: 0.002[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 625.6
- 400 + ( ( 0.113 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 625.6


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
|            9 |     2990 | 2024-11-22 | Alliance             | L   | 0.538      | -            | -                | -                | -         |    -3.38 | delle, Fabbelit0, pulan, Simpan, tvs |
|            8 |     3054 | 2024-11-21 | Kappa Bar            | L   | 0.531      | -            | -                | -                | -         |    -6.38 | delle, Fabbelit0, pulan, Simpan, tvs |
|            7 |     3934 | 2024-11-05 | GODSENT              | W   | 0.427      | 0.143        | 0.001 (0.000)    | 0.275 (0.017)    | 0 (0.000) |     7.65 | delle, Fabbelit0, pulan, Simpan, tvs |
|            6 |     4363 | 2024-10-29 | Lemondogs            | W   | 0.380      | 0.143        | 0.000 (0.000)    | 0.041 (0.002)    | 0 (0.000) |     2.71 | delle, Fabbelit0, pulan, Simpan, tvs |
|            5 |     4890 | 2024-10-18 | Deathsquad           | W   | 0.306      | 0.143        | 0.000 (0.000)    | 0.012 (0.001)    | 0 (0.000) |     2.16 | delle, Fabbelit0, pulan, Simpan, tvs |
|            4 |     5419 | 2024-10-08 | Venom (Swedish team) | W   | 0.239      | 0.143        | 0.000 (0.000)    | 0.063 (0.002)    | 0 (0.000) |     2.55 | delle, Fabbelit0, pulan, Simpan, tvs |
|            3 |     5849 | 2024-10-01 | Showmakerz           | L   | 0.193      | -            | -                | -                | -         |    -3.23 | delle, Fabbelit0, pulan, Simpan, tvs |
|            2 |     6192 | 2024-09-26 | Kappa Bar            | L   | 0.159      | -            | -                | -                | -         |    -1.91 | delle, Fabbelit0, pulan, Simpan, tvs |
|            1 |     7587 | 2024-09-05 | NIP Svea             | W   | 0.019      | 0.143        | 0.000 (0.000)    | 0.048 (0.000)    | 0 (0.000) |     0.14 | delle, Fabbelit0, pulan, Simpan, tvs |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($1,237.56)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-23 |      0.546 | $2,265.27      | $1,237.56       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
