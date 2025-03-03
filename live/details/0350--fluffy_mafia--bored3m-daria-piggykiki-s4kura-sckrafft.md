### Roster Details<br />
Team Name: FLUFFY MAFIA<br />
Roster: bored3m, daria, PiggyKiki, s4kUra, sckrafft<br />
Global Rank: [350](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [224]( ../standings_europe.md)<br />
<br />
Final Rank Value:  625.5<br />
<br />
Final Rank Value (625.5) = Starting Rank Value (626.3) + Head To Head Adjustments (-0.7)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.267[<sup>1</sup>](#table2)
- Bounty Collected: 0.184[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.113<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 626.3
- 400 + ( ( 0.113 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 626.3


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            7 |     4882 | 2024-10-18 | TSM Impact       | L   | 0.300      | -            | -                | -                | -         |    -4.89 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            6 |     5566 | 2024-10-05 | Imp Pact         | L   | 0.213      | -            | -                | -                | -         |    -3.78 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            5 |     5718 | 2024-10-03 | Aware Impact     | W   | 0.200      | 0.333        | 0.001 (0.000)    | 0.007 (0.000)    | 0 (0.000) |     2.91 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            4 |     6262 | 2024-09-25 | Blue Otter Karma | W   | 0.146      | 0.333        | 0.001 (0.000)    | 0.005 (0.000)    | 0 (0.000) |     2.15 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            3 |     6741 | 2024-09-18 | Lotus            | W   | 0.100      | 0.333        | 0.001 (0.000)    | 0.003 (0.000)    | 0 (0.000) |     1.45 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            2 |     7126 | 2024-09-12 | Supernova Comets | W   | 0.060      | 0.333        | 0.011 (0.000)    | 0.263 (0.005)    | 0 (0.000) |     1.22 | bored3m, daria, PiggyKiki, s4kUra, sckrafft |
|            1 |     7560 | 2024-09-05 | Nouns.fe         | W   | 0.013      | 0.333        | 0.001 (0.000)    | 0.070 (0.000)    | 0 (0.000) |     0.20 | bored3m, mira, PiggyKiki, s4kUra, sckrafft  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($599.44)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-18 |      0.300 | $2,000.00      | $599.44         |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
