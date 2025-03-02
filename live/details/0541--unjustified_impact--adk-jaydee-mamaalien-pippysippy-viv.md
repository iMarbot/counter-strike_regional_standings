### Roster Details<br />
Team Name: Unjustified Impact<br />
Roster: ADK, Jaydee, MamaAlien, PippySippy, Viv<br />
Global Rank: [541](../standings_global.md)<br />
<br />
Region: [Americas]( ../standings_americas.md)<br />
Regional Rank: [122]( ../standings_americas.md)<br />
<br />
Final Rank Value:  483.7<br />
<br />
Final Rank Value (483.7) = Starting Rank Value (509.4) + Head To Head Adjustments (-25.8)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.219[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.055<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 509.4
- 400 + ( ( 0.055 - 0.000 ) / ( 0.801 - 0.000 ) ) * 1600 = 509.4


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent         | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                       |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            8 |      816 | 2025-02-06 | The Little Bocks | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |    11.49 | ADK, Jaydee, MamaAlien, PippySippy, Viv      |
|            7 |      870 | 2025-02-05 | Black mold       | L   | 1.000      | -            | -                | -                | -         |   -15.48 | ADK, Jaydee, MamaAlien, PippySippy, Viv      |
|            6 |     1662 | 2024-12-14 | Lotus            | L   | 0.688      | -            | -                | -                | -         |    -7.20 | ADK, Bouchard, Jaydee, MamaAlien, PippySippy |
|            5 |     2052 | 2024-12-07 | GIRLYPOPS        | L   | 0.641      | -            | -                | -                | -         |    -7.74 | ADK, Jaydee, Kimmy, MamaAlien, PippySippy    |
|            4 |     2456 | 2024-11-30 | Lotus            | L   | 0.595      | -            | -                | -                | -         |    -6.58 | ADK, Jaydee, Knopk@, MamaAlien, PippySippy   |
|            3 |     4446 | 2024-10-27 | Supernova Comets | L   | 0.368      | -            | -                | -                | -         |    -3.24 | ADK, Jaydee, Knopk@, MamaAlien, PippySippy   |
|            2 |     4497 | 2024-10-26 | Equity Gaming    | W   | 0.361      | 0.250        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     3.99 | ADK, Jaydee, Knopk@, MamaAlien, PippySippy   |
|            1 |     6961 | 2024-09-14 | Arf Squad        | L   | 0.081      | -            | -                | -                | -         |    -0.99 | ADK, Chowdzz, jaydee, Knopk@, PippySippy     |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($92.01)
- Divide that value by the 5th highest value among all rosters ($336,474.68)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-10-27 |      0.368 | $250.00        | $92.01          |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by Liquipedia.net_<br />
