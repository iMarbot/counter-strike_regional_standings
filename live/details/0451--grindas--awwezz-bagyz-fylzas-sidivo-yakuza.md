### Roster Details<br />
Team Name: Grindas<br />
Roster: AwwEzz, BaGyZ, fylzas, Sidivo, yakuza<br />
Global Rank: [451](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [283]( ../standings_europe.md)<br />
<br />
Final Rank Value:  558.5<br />
<br />
Final Rank Value (558.5) = Starting Rank Value (525.1) + Head To Head Adjustments (33.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.233[<sup>2</sup>](#table1)
- Opponent Network: 0.018[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.063<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 525.1
- 400 + ( ( 0.063 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 525.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent               | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           11 |     3006 | 2024-11-21 | ALASKA                 | L   | 0.534      | -            | -                | -                | -         |    -1.58 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|           10 |     3077 | 2024-11-20 | Permitta Esports       | L   | 0.527      | -            | -                | -                | -         |    -3.14 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            9 |     3082 | 2024-11-20 | Lausanne-Sport Esports | W   | 0.527      | 0.372        | 0.000 (0.000)    | 0.126 (0.025)    | 0 (0.000) |     8.62 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            8 |     3191 | 2024-11-18 | Ex-9INE Academy        | W   | 0.514      | 0.372        | 0.000 (0.000)    | 0.035 (0.007)    | 0 (0.000) |     8.19 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            7 |     4236 | 2024-10-31 | FORZE Reload           | W   | 0.394      | 0.372        | 0.026 (0.004)    | 0.559 (0.082)    | 0 (0.000) |    10.67 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            6 |     4238 | 2024-10-31 | Kubix Esports          | L   | 0.394      | -            | -                | -                | -         |    -1.28 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            5 |     4360 | 2024-10-29 | Partizan Esports       | L   | 0.380      | -            | -                | -                | -         |    -0.55 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            4 |     4578 | 2024-10-25 | Lazer Cats             | W   | 0.353      | 0.372        | 0.005 (0.001)    | 0.387 (0.051)    | 0 (0.000) |     8.18 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            3 |     4653 | 2024-10-23 | TEAM NEXT LEVEL        | L   | 0.340      | -            | -                | -                | -         |    -1.56 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            2 |     4707 | 2024-10-22 | HyperSpirit            | W   | 0.332      | 0.372        | 0.004 (0.000)    | 0.121 (0.015)    | 0 (0.000) |     7.23 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            1 |     4727 | 2024-10-21 | UNiTY esports          | L   | 0.326      | -            | -                | -                | -         |    -1.42 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
