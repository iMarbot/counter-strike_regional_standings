### Roster Details<br />
Team Name: Team Fragster<br />
Roster: DeadHog, dragoN, Peekay, PlebSter, Rabbi<br />
Global Rank: [386](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [242]( ../standings_europe.md)<br />
<br />
Final Rank Value:  605.4<br />
<br />
Final Rank Value (605.4) = Starting Rank Value (595.6) + Head To Head Adjustments (9.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.215[<sup>1</sup>](#table2)
- Bounty Collected: 0.174[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.098<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 595.6
- 400 + ( ( 0.098 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 595.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent             | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |     3599 | 2024-11-11 | Sissi State Punks    | L   | 0.459      | -            | -                | -                | -         |    -7.62 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|           12 |     3621 | 2024-11-11 | Wave Esports         | W   | 0.458      | 0.143        | 0.002 (0.000)    | 0.110 (0.007)    | 0 (0.000) |     7.77 | DeadHog, dragoN, Neru, Peekay, PlebSter  |
|           11 |     3711 | 2024-11-09 | ALTERNATE aTTaX Evo  | L   | 0.445      | -            | -                | -                | -         |    -6.67 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|           10 |     3741 | 2024-11-09 | Unorganized Five     | W   | 0.444      | 0.143        | 0.000 (0.000)    | 0.066 (0.004)    | 0 (0.000) |     6.42 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            9 |     4049 | 2024-11-03 | Reveal (German team) | W   | 0.405      | 0.143        | 0.001 (0.000)    | 0.187 (0.011)    | 0 (0.000) |     7.10 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            8 |     4467 | 2024-10-27 | UNEVEN               | W   | 0.358      | 0.143        | 0.000 (0.000)    | 0.008 (0.000)    | 0 (0.000) |     3.58 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            7 |     4658 | 2024-10-23 | ALTERNATE aTTaX Evo  | L   | 0.332      | -            | -                | -                | -         |    -5.08 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            6 |     4997 | 2024-10-16 | Team NinjaParentz    | W   | 0.285      | 0.143        | 0.000 (0.000)    | 0.035 (0.001)    | 0 (0.000) |     4.04 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            5 |     5672 | 2024-10-04 | Unorganized Five     | W   | 0.205      | 0.143        | 0.000 (0.000)    | 0.066 (0.002)    | 0 (0.000) |     3.02 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            4 |     5962 | 2024-09-29 | AKA HERO             | L   | 0.172      | -            | -                | -                | -         |    -2.75 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            3 |     6640 | 2024-09-20 | RIZON                | W   | 0.111      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     0.88 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            2 |     7090 | 2024-09-13 | BIG SELECTA          | L   | 0.065      | -            | -                | -                | -         |    -1.10 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |
|            1 |     7520 | 2024-09-06 | Entropy Gaming       | W   | 0.018      | 0.143        | 0.000 (0.000)    | 0.049 (0.000)    | 0 (0.000) |     0.26 | DeadHog, dragoN, Peekay, PlebSter, Rabbi |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($72.67)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-11-10 |      0.452 | $160.84        | $72.67          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
