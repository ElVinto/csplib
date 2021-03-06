###
Note on instance results

These results were achieved using this algorithms described by Burke et al. (see reference 1 on the references page). This technique uses aggregations to simplify the problem, and so the solutions are not guaranteed to be optimal.
The instance results consist of three parts:

Best cost: the cost of the best solution found
Delivery schedules: details of the number of batches of a product delivered per period between pairs of agents: product-name (agent-sender-name->agent-receiver-name).
Production schedules: details of the number of each product produced by each agent in each period: agent-name,product-name.

### Instance 1

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 288644
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>



<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 41 </td><td> 69 </td><td> 66 </td><td> 0 </td><td> 75 </td><td> 0 </td><td> 0 </td><td> 74 </td><td> 0 </td><td> 41 </td><td> 65 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 128 </td><td> 0 </td><td> 0 </td><td> 127 </td><td> 0 </td><td> 0 </td><td> 64 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 61 </td><td> 53 </td><td> 59 </td><td> 67 </td><td> 60 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 91 </td><td> 83 </td><td> 93 </td><td> 79 </td><td> 88 </td><td> 0 </td><td> 18 </td><td> 81 </td><td> 80 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 0 </td><td> 26 </td><td> 66 </td><td> 47 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>


### Instance 2

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 595879
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 3 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>



<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 0 </td><td> 33 </td><td> 61 </td><td> 0 </td><td> 35 </td><td> 0 </td><td> 92 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 38 </td><td> 0 </td><td> 0 </td><td> 89 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 53 </td><td> 41 </td><td> 94 </td><td> 30 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 32 </td><td> 0 </td><td> 43 </td><td> 37 </td><td> 0 </td><td> 34 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 75 </td><td> 60 </td><td> 71 </td><td> 76 </td><td> 82 </td><td> 65 </td><td> 61 </td><td> 47 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 17 </td><td> 33 </td><td> 32 </td><td> 42 </td><td> 27 </td><td> 22 </td><td> 28 </td><td> 26 </td><td> 45 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>

### Instance 3

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 587171
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 3 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P5 (A5-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P6 (A6-&gt;A3) </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P7 (A7-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>

<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 78 </td><td> 0 </td><td> 0 </td><td> 91 </td><td> 0 </td><td> 0 </td><td> 67 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 0 </td><td> 0 </td><td> 82 </td><td> 0 </td><td> 97 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 0 </td><td> 0 </td><td> 43 </td><td> 0 </td><td> 0 </td><td> 25 </td><td> 33 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 31 </td><td> 23 </td><td> 43 </td><td> 33 </td><td> 43 </td><td> 34 </td><td> 32 </td><td> 35 </td><td> 0 </td><td> 13 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 12 </td><td> 39 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A5, P5 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A6, P6 </td><td> 31 </td><td> 28 </td><td> 33 </td><td> 23 </td><td> 44 </td><td> 21 </td><td> 35 </td><td> 29 </td><td> 21 </td><td> 22 </td><td> 41 </td><td> 0
</td></tr><tr>
<td> A7, P7 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>


### Instance 4

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 599203
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 3 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 2 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P5 (A5-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P6 (A6-&gt;A3) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P7 (A7-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>

<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 0 </td><td> 77 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 79 </td><td> 47 </td><td> 57 </td><td> 15 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 56 </td><td> 53 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 28 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 0 </td><td> 14 </td><td> 53 </td><td> 44 </td><td> 48 </td><td> 0 </td><td> 0 </td><td> 61 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 63 </td><td> 0 </td><td> 51 </td><td> 58 </td><td> 27 </td><td> 0 </td><td> 68 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 0 </td><td> 19 </td><td> 56 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A5, P5 </td><td> 0 </td><td> 53 </td><td> 0 </td><td> 69 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A6, P6 </td><td> 0 </td><td> 50 </td><td> 0 </td><td> 0 </td><td> 68 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A7, P7 </td><td> 0 </td><td> 0 </td><td> 35 </td><td> 40 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>




### Instance 5

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 1156312
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P5 (A5-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P6 (A6-&gt;A3) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 3 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P7 (A7-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P8 (A8-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P9 (A9-&gt;A3) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P10 (A10-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>



<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 84 </td><td> 0 </td><td> 98 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 84 </td><td> 0 </td><td> 0 </td><td> 73 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 42 </td><td> 0 </td><td> 45 </td><td> 33 </td><td> 0 </td><td> 0 </td><td> 46 </td><td> 24 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 0 </td><td> 0 </td><td> 62 </td><td> 63 </td><td> 0 </td><td> 0 </td><td> 79 </td><td> 0 </td><td> 51 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 76 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A5, P5 </td><td> 0 </td><td> 75 </td><td> 82 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A6, P6 </td><td> 41 </td><td> 74 </td><td> 66 </td><td> 67 </td><td> 57 </td><td> 79 </td><td> 65 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A7, P7 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A8, P8 </td><td> 60 </td><td> 93 </td><td> 83 </td><td> 89 </td><td> 65 </td><td> 53 </td><td> 80 </td><td> 44 </td><td> 74 </td><td> 54 </td><td> 82 </td><td> 51
</td></tr><tr>
<td> A9, P9 </td><td> 30 </td><td> 0 </td><td> 22 </td><td> 26 </td><td> 33 </td><td> 5 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A10, P10 </td><td> 49 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>


### Instance 6

<table border="">
<tbody><tr>
<td></td><th>Best Cost</th><td> 1351505
</td></tr><tr>
</tr></tbody></table>


<table border="">
<caption>Delivery Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of batches delivered per period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> P2 (A2-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P3 (A3-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P4 (A4-&gt;A1) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P5 (A5-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P6 (A6-&gt;A3) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P7 (A7-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P8 (A8-&gt;A2) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P9 (A9-&gt;A3) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> P10 (A10-&gt;A4) </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>
</tt><tt>


<table border="">
<caption>Production Schedules</caption>
<tbody><tr>
<td></td><th colspan="12">Number of each product manufactured in each period</th>	
</tr><tr>
<td> Period </td><td> 1 </td><td> 2 </td><td> 3 </td><td> 4 </td><td> 5 </td><td> 6 </td><td> 7 </td><td> 8 </td><td> 9 </td><td> 10 </td><td> 11 </td><td> 12
</td></tr><tr>
<td> A1, P0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 77 </td><td> 0 </td><td> 0 </td><td> 60 </td><td> 0 </td><td> 0 </td><td> 60 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A1, P1 </td><td> 23 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A2, P2 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 38 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A3, P3 </td><td> 0 </td><td> 39 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 60 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A4, P4 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A5, P5 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A6, P6 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 14 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A7, P7 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A8, P8 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 28 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A9, P9 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 1 </td><td> 89 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
<td> A10, P10 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0 </td><td> 0
</td></tr><tr>
</tr><tr>
</tr></tbody></table>


</tt>

<hr>

<ul>
