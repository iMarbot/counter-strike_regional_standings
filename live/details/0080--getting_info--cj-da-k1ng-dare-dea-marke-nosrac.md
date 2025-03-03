### Roster Details<br />
Team Name: Getting Info<br />
Roster: cJ-dA-K1nG, dare, dea, MarKE, nosraC<br />
Global Rank: [80](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [19]( ../standings_americas.md)<br />
<br />
Final Rank Value:  885.8<br />
<br />
Final Rank Value (885.8) = Starting Rank Value (850.5) + Head To Head Adjustments (35.4)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.340[<sup>1</sup>](#table2)
- Bounty Collected: 0.271[<sup>2</sup>](#table1)
- Opponent Network: 0.056[<sup>2</sup>](#table1)
- LAN Wins: 0.234[<sup>2</sup>](#table1)

The average of these factors is 0.225<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 850.5
- 400 + ( ( 0.225 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 850.5


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                               |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           12 |        1 | 2025-03-02 | Marsborne        | L   | 1.000      | -            | -                | -                | -         |   -15.21 | cJ-dA-K1nG, dare, dea, MarKE, nosraC |
|           11 |        4 | 2025-03-01 | Take Flyte       | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.189 (0.063)    | 1 (1.000) |     4.81 | cJ-dA-K1nG, dare, dea, MarKE, nosraC |
|           10 |        8 | 2025-03-01 | Blahaj           | W   | 1.000      | 0.333        | 0.000 (0.000)    | 0.144 (0.048)    | 1 (1.000) |     4.12 | cJ-dA-K1nG, dare, dea, MarKE, nosraC |
|            9 |      478 | 2025-02-14 | BLUEJAYS         | L   | 1.000      | -            | -                | -                | -         |    -8.91 | dea, MarKE, nosraC, rayxts, vanity   |
|            8 |      516 | 2025-02-13 | MIGHT            | W   | 1.000      | 0.143        | 0.002 (0.000)    | 0.489 (0.070)    | 0 (0.000) |    10.55 | dea, MarKE, nosraC, rayxts, vanity   |
|            7 |      666 | 2025-02-08 | Marsborne        | L   | 1.000      | -            | -                | -                | -         |   -15.18 | dea, MarKE, nosraC, slump, vanity    |
|            6 |      743 | 2025-02-07 | Fisher College   | W   | 1.000      | 0.143        | 0.008 (0.001)    | 0.324 (0.046)    | 0 (0.000) |     9.93 | dea, MarKE, nosraC, slump, vanity    |
|            5 |     1614 | 2024-12-15 | NRG              | W   | 0.687      | 0.303        | 0.049 (0.010)    | 0.446 (0.093)    | 0 (0.000) |    15.10 | dare, dea, nosraC, shane, snav       |
|            4 |     1618 | 2024-12-15 | Nouns Esports    | W   | 0.687      | 0.303        | 0.007 (0.001)    | 0.327 (0.068)    | 0 (0.000) |    11.04 | dare, dea, nosraC, shane, snav       |
|            3 |     1665 | 2024-12-14 | BLUEJAYS         | W   | 0.681      | 0.303        | 0.031 (0.006)    | 0.511 (0.105)    | 0 (0.000) |    17.03 | dare, dea, nosraC, shane, snav       |
|            2 |     2783 | 2024-11-24 | NRG              | L   | 0.546      | -            | -                | -                | -         |    -5.17 | dare, dea, nosraC, shane, snav       |
|            1 |     2834 | 2024-11-23 | Party Astronauts | W   | 0.540      | 0.303        | 0.008 (0.001)    | 0.382 (0.062)    | 0 (0.000) |     7.25 | dare, dea, nosraC, shane, snav       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($3,748.89)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.01) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2025-03-02 |      1.000 | $1,000.00      | $1,000.00       |
| 2024-12-15 |      0.687 | $4,000.00      | $2,748.89       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
