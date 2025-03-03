### Roster Details<br />
Team Name: Grindas<br />
Roster: AwwEzz, BaGyZ, fylzas, Sidivo, yakuza<br />
Global Rank: [453](../standings_global.md)<br />
<br />
Region: [Europe]( ../standings_europe.md)<br />
Regional Rank: [282]( ../standings_europe.md)<br />
<br />
Final Rank Value:  557.4<br />
<br />
Final Rank Value (557.4) = Starting Rank Value (524.7) + Head To Head Adjustments (32.6)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.232[<sup>2</sup>](#table1)
- Opponent Network: 0.017[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.062<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 524.7
- 400 + ( ( 0.062 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 524.7


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
|           11 |     3018 | 2024-11-21 | ALASKA                 | L   | 0.526      | -            | -                | -                | -         |    -1.52 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|           10 |     3089 | 2024-11-20 | Permitta Esports       | L   | 0.519      | -            | -                | -                | -         |    -3.11 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            9 |     3094 | 2024-11-20 | Lausanne-Sport Esports | W   | 0.519      | 0.372        | 0.000 (0.000)    | 0.124 (0.024)    | 0 (0.000) |     8.49 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            8 |     3203 | 2024-11-18 | Ex-9INE Academy        | W   | 0.505      | 0.372        | 0.000 (0.000)    | 0.033 (0.006)    | 0 (0.000) |     8.02 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            7 |     4248 | 2024-10-31 | FORZE Reload           | W   | 0.386      | 0.372        | 0.026 (0.004)    | 0.552 (0.079)    | 0 (0.000) |    10.44 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            6 |     4250 | 2024-10-31 | Kubix Esports          | L   | 0.385      | -            | -                | -                | -         |    -1.26 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            5 |     4372 | 2024-10-29 | Partizan Esports       | L   | 0.372      | -            | -                | -                | -         |    -0.54 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            4 |     4590 | 2024-10-25 | Lazer Cats             | W   | 0.345      | 0.372        | 0.005 (0.001)    | 0.378 (0.049)    | 0 (0.000) |     7.98 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            3 |     4665 | 2024-10-23 | TEAM NEXT LEVEL        | L   | 0.332      | -            | -                | -                | -         |    -1.52 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            2 |     4719 | 2024-10-22 | HyperSpirit            | W   | 0.324      | 0.372        | 0.004 (0.000)    | 0.119 (0.014)    | 0 (0.000) |     7.05 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |
|            1 |     4739 | 2024-10-21 | UNiTY esports          | L   | 0.318      | -            | -                | -                | -         |    -1.40 | AwwEzz, BaGyZ, fylzas, Sidivo, yakuza |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
