### Roster Details<br />
Team Name: Pugdesonesto<br />
Roster: Bonecomeister, CaPiM, divin9, imoto, Royals<br />
Global Rank: [553](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [128]( ../standings_americas.md)<br />
<br />
Final Rank Value:  476.5<br />
<br />
Final Rank Value (476.5) = Starting Rank Value (485.8) + Head To Head Adjustments (-9.3)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.168[<sup>2</sup>](#table1)
- Opponent Network: 0.004[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.043<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 485.8
- 400 + ( ( 0.043 - 0.000 ) / ( 0.800 - 0.000 ) ) * 1600 = 485.8


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent                | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                      |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            5 |     2135 | 2024-12-06 | RED Canids Academy      | L   | 0.625      | -            | -                | -                | -         |    -3.96 | Bonecomeister, CaPiM, divin9, imoto, Royals |
|            4 |     2265 | 2024-12-03 | AMIGOS (Brazilian team) | L   | 0.606      | -            | -                | -                | -         |    -8.59 | Bonecomeister, CaPiM, divin9, imoto, Royals |
|            3 |     2958 | 2024-11-22 | Nitro.GG                | L   | 0.532      | -            | -                | -                | -         |    -4.37 | Bonecomeister, divin9, imoto, phx, Royals   |
|            2 |     3110 | 2024-11-20 | Yawara E-Sports         | L   | 0.519      | -            | -                | -                | -         |    -3.54 | Bonecomeister, divin9, imoto, phx, Royals   |
|            1 |     3379 | 2024-11-15 | Nitro.GG                | W   | 0.486      | 0.143        | 0.002 (0.000)    | 0.512 (0.036)    | 0 (0.000) |    11.18 | Bonecomeister, divin9, imoto, phx, Royals   |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($329,538.08)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
