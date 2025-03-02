### Roster Details<br />
Team Name: MarcaRegistrada<br />
Roster: amc, b1, Jardani, Majestic, spamzzy<br />
Global Rank: [398](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [84]( ../standings_americas.md)<br />
<br />
Final Rank Value:  597.7<br />
<br />
Final Rank Value (597.7) = Starting Rank Value (607.6) + Head To Head Adjustments (-9.9)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.226[<sup>1</sup>](#table2)
- Bounty Collected: 0.183[<sup>2</sup>](#table1)
- Opponent Network: 0.006[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.104<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 607.6
- 400 + ( ( 0.104 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 607.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent           | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                              |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           14 |      387 | 2025-02-15 | MCS Gaming         | L   | 1.000      | -            | -                | -                | -         |   -13.56 | amc, b1, Jardani, Majestic, spamzzy |
|           13 |      437 | 2025-02-14 | Team Aether        | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.093 (0.013)    | 0 (0.000) |    10.32 | amc, b1, Jardani, Majestic, spamzzy |
|           12 |      813 | 2025-02-06 | Akimbo Esports     | L   | 1.000      | -            | -                | -                | -         |   -13.06 | amc, b1, Jardani, Majestic, spamzzy |
|           11 |     1745 | 2024-12-13 | Vagrants           | L   | 0.682      | -            | -                | -                | -         |    -9.41 | amc, b1, Jardani, majestic, spamzzy |
|           10 |     1753 | 2024-12-13 | Immigrants Peek    | W   | 0.682      | 0.143        | 0.001 (0.000)    | 0.366 (0.036)    | 0 (0.000) |    11.38 | amc, b1, Jardani, majestic, spamzzy |
|            9 |     3220 | 2024-11-17 | APX Energy         | L   | 0.508      | -            | -                | -                | -         |    -8.25 | amc, b1, Jardani, Majestic, Medusa  |
|            8 |     3300 | 2024-11-16 | Angelicas BFS      | W   | 0.502      | 0.143        | 0.000 (0.000)    | 0.024 (0.002)    | 0 (0.000) |     7.07 | amc, b1, Jardani, Majestic, Medusa  |
|            7 |     5992 | 2024-09-28 | Nouns Esports      | L   | 0.175      | -            | -                | -                | -         |    -1.91 | 4TAYLOR, amc, b1, Jardani, Majestic |
|            6 |     5998 | 2024-09-28 | Wildcard           | L   | 0.174      | -            | -                | -                | -         |    -0.08 | 4TAYLOR, amc, b1, Jardani, Majestic |
|            5 |     6085 | 2024-09-27 | Party Astronauts   | W   | 0.168      | 0.143        | 0.008 (0.000)    | 0.385 (0.009)    | 0 (0.000) |     3.78 | 4TAYLOR, amc, b1, Jardani, Majestic |
|            4 |     6093 | 2024-09-27 | RazDva             | W   | 0.168      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     1.80 | 4TAYLOR, amc, b1, Jardani, Majestic |
|            3 |     6167 | 2024-09-26 | Bad News Capybaras | W   | 0.161      | 0.143        | 0.001 (0.000)    | 0.115 (0.003)    | 0 (0.000) |     2.92 | 4TAYLOR, amc, b1, Jardani, Majestic |
|            2 |     7373 | 2024-09-07 | Jahsdnmasjdm v2    | L   | 0.035      | -            | -                | -                | -         |    -0.73 | amc, b1, Jardani, kezz, majestic    |
|            1 |     7693 | 2024-09-03 | Exceritus          | L   | 0.008      | -            | -                | -                | -         |    -0.13 | amc, b1, Jardani, kezz, majestic    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($126.73)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-18 |      0.516 | $245.69        | $126.73         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
