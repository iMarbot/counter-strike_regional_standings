### Roster Details<br />
Team Name: SUPER EVIL GANG<br />
Roster: arias, clipzera, flow, Misha, Talen<br />
Global Rank: [226](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [45]( ../standings_americas.md)<br />
<br />
Final Rank Value:  694.6<br />
<br />
Final Rank Value (694.6) = Starting Rank Value (693.2) + Head To Head Adjustments (1.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.328[<sup>1</sup>](#table2)
- Bounty Collected: 0.228[<sup>2</sup>](#table1)
- Opponent Network: 0.030[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.147<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 693.2
- 400 + ( ( 0.147 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 693.2


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                         |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           24 |        9 | 2025-03-01 | Marsborne            | L   | 1.000      | -            | -                | -                | -         |    -8.07 | arias, clipzera, flow, Misha, Talen            |
|           23 |      589 | 2025-02-10 | Immigrants Peek      | L   | 1.000      | -            | -                | -                | -         |   -18.63 | arias, clipzera, flow, Misha, Talen            |
|           22 |      628 | 2025-02-09 | Vagrants             | L   | 1.000      | -            | -                | -                | -         |   -16.89 | arias, clipzera, flow, Misha, Talen            |
|           21 |      664 | 2025-02-08 | Mythic               | W   | 1.000      | 0.143        | -                | 0.021 (0.003)    | 0 (0.000) |     6.57 | arias, clipzera, flow, Misha, Talen            |
|           20 |      742 | 2025-02-07 | Marsborne            | L   | 1.000      | -            | -                | -                | -         |    -9.25 | arias, clipzera, Flow, Misha, Talen            |
|           19 |     1613 | 2024-12-15 | Bad News Capybaras   | W   | 0.687      | 0.143        | 0.000 (0.000)    | 0.113 (0.011)    | 0 (0.000) |     8.41 | arias, clipzera, Keiti, Misha, Talen           |
|           18 |     1667 | 2024-12-14 | LAG Gaming           | W   | 0.681      | 0.143        | 0.004 (0.000)    | 0.120 (0.012)    | 0 (0.000) |    11.00 | arias, clipzera, Keiti, Misha, Talen           |
|           17 |     1749 | 2024-12-13 | Undone               | L   | 0.675      | -            | -                | -                | -         |    -9.01 | arias, clipzera, Keiti, Misha, Talen           |
|           16 |     1978 | 2024-12-08 | Make Your Mind       | L   | 0.641      | -            | -                | -                | -         |    -9.98 | arias, clipzera, flow, Misha, Talen            |
|           15 |     2057 | 2024-12-07 | Chicken Coop Esports | W   | 0.634      | 0.372        | 0.006 (0.002)    | 0.187 (0.044)    | 0 (0.000) |     8.95 | arias, clipzera, flow, Misha, Talen            |
|           14 |     2122 | 2024-12-06 | Bad Boys             | W   | 0.627      | 0.372        | 0.004 (0.001)    | 0.142 (0.033)    | 0 (0.000) |     8.45 | arias, clipzera, flow, Misha, Talen            |
|           13 |     2164 | 2024-12-05 | Undone               | W   | 0.621      | 0.372        | 0.002 (0.001)    | 0.282 (0.065)    | 0 (0.000) |    11.26 | arias, clipzera, flow, Misha, Talen            |
|           12 |     2204 | 2024-12-04 | Immigrants Peek      | W   | 0.614      | 0.372        | 0.001 (0.000)    | 0.366 (0.084)    | 0 (0.000) |     8.14 | arias, clipzera, flow, Misha, Talen            |
|           11 |     2255 | 2024-12-03 | StandOnBusiness      | W   | 0.608      | 0.372        | -                | 0.054 (0.012)    | 0 (0.000) |     3.18 | arias, clipzera, flow, Misha, Talen            |
|           10 |     2323 | 2024-12-02 | Vibe (American team) | W   | 0.601      | 0.372        | 0.000 (0.000)    | 0.069 (0.016)    | 0 (0.000) |     6.83 | arias, clipzera, flow, Misha, Talen            |
|            9 |     2397 | 2024-12-01 | VitaPLUR             | W   | 0.594      | 0.372        | 0.000 (0.000)    | -                | 0 (0.000) |     4.53 | arias, clipzera, flow, Misha, Talen            |
|            8 |     2583 | 2024-11-29 | OutGoing eSports     | L   | 0.580      | -            | -                | -                | -         |   -10.47 | arias, clipzera, flow, Misha, Talen            |
|            7 |     2698 | 2024-11-26 | Guangdong Tigers     | W   | 0.561      | -            | -                | -                | -         |     2.80 | arias, clipzera, flow, Misha, Talen            |
|            6 |     5180 | 2024-10-12 | Akimbo Esports       | W   | 0.260      | 0.259        | 0.003 (0.000)    | 0.327 (0.022)    | -         |     3.66 | arias, clipzera, Lambchoppington, misha, Talen |
|            5 |     5512 | 2024-10-06 | VitaPLUR             | W   | 0.220      | 0.259        | 0.000 (0.000)    | -                | -         |     1.76 | arias, clipzera, Lambchoppington, misha, Talen |
|            4 |     7229 | 2024-09-10 | Regain               | L   | 0.047      | -            | -                | -                | -         |    -1.12 | arias, clipzera, Li4m, misha, Talen            |
|            3 |     7387 | 2024-09-07 | Lycus Empire         | W   | 0.027      | -            | -                | -                | -         |     0.14 | arias, clipzera, Li4m, misha, Talen            |
|            2 |     7418 | 2024-09-07 | Wanted Goons         | L   | 0.025      | -            | -                | -                | -         |    -0.60 | arias, Lambchoppington, Locke, misha, Talen    |
|            1 |     7553 | 2024-09-05 | Exceritus            | L   | 0.014      | -            | -                | -                | -         |    -0.26 | arias, clipzera, Li4m, misha, Talen            |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($2,963.69)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-12-08 |      0.641 | $4,300.00      | $2,755.58       |
| 2024-10-12 |      0.260 | $800.00        | $208.11         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
