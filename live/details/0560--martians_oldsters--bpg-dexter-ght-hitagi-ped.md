### Roster Details<br />
Team Name: Martians Oldsters<br />
Roster: bpg, DexteR, ght, hitagi, ped<br />
Global Rank: [560](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [130]( ../standings_americas.md)<br />
<br />
Final Rank Value:  471.2<br />
<br />
Final Rank Value (471.2) = Starting Rank Value (468.1) + Head To Head Adjustments (3.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.135[<sup>2</sup>](#table1)
- Opponent Network: 0.001[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.034<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 468.1
- 400 + ( ( 0.034 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 468.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                   | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                        |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |     2861 | 2024-11-23 | América eSports            | L   | 0.538      | -            | -                | -                | -         |    -6.03 | bpg, DexteR, ght, hitagi, ped |
|            7 |     4987 | 2024-10-16 | Pugdesonesto               | L   | 0.286      | -            | -                | -                | -         |    -2.64 | bpg, DexteR, ght, hitagi, ped |
|            6 |     4988 | 2024-10-16 | Myth e-Sports              | W   | 0.285      | 0.143        | 0.000 (0.000)    | 0.078 (0.003)    | 0 (0.000) |     5.99 | bpg, DexteR, ght, hitagi, ped |
|            5 |     5055 | 2024-10-15 | SamuraiS (Brazilian team)  | W   | 0.279      | 0.143        | 0.000 (0.000)    | 0.154 (0.006)    | 0 (0.000) |     4.68 | bpg, DexteR, ght, hitagi, ped |
|            4 |     5058 | 2024-10-15 | DB Peek Esports            | L   | 0.278      | -            | -                | -                | -         |    -2.71 | bpg, DexteR, ght, hitagi, ped |
|            3 |     5519 | 2024-10-06 | DB Peek Esports            | L   | 0.219      | -            | -                | -                | -         |    -2.14 | bpg, DexteR, gaard, ght, ped  |
|            2 |     5569 | 2024-10-05 | Formula 1 (Brazilian team) | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.010 (0.000)    | 0 (0.000) |     2.71 | bpg, DexteR, gaard, ght, ped  |
|            1 |     5587 | 2024-10-05 | URI Sailor                 | W   | 0.212      | 0.143        | 0.000 (0.000)    | 0.053 (0.002)    | 0 (0.000) |     3.31 | bpg, DexteR, gaard, ght, ped  |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
