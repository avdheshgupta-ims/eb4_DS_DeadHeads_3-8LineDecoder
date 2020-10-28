<h3><b>2.Theory</b></h3>
<p>Decode is an electronic combinational circuit which includes basic logic gates (AND, OR, NOT). The circuit take multiple decoded input in the form of n and provide multiple outputs in the form of 2^n. A decoder would be the n-to-2^n type binary decoders. The decoder converts binary information from 'n' coded inputs to 2^n outputs. 2-to-4 decoder, 3-to-8 decoder or 4-to-16 decoder are some examples of Decoder. Decoder is basically used to enable one of the circuit amoung multiple circuit.</p>
<br>
Here is a truth table for 3 to 8 Decoder.<br>

I2	| I1 | I0 |	D7 |	D6 |	D5 |	D4 |	D3 |	D2 |	D1 |	D0 |
:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|
0	|0	|0	|0	|0|	0|	0	|0|	0|	0	|1|
0	|0	|1	|0	|0|	0|	0	|0|	0|	1 |0|
0	|1	|0	|0	|0|	0|	0	|0|	1|	0	|0|
0	|1	|1	|0	|0|	0|	0	|1|	0|	0	|0|
1|0	|0	|0	|0|	0|	1	|0|	0|	0	|0|
1	|0	|1	|0	|0|	1|	0	|0|	0|	0	|0|
1	|1	|0	|0	|1|	0|	0	|0|	0|	0	|0|
1	|1	|1	|1	|0|	0|	0	|0|	0|	0	|0|
<br>
<img src="images/CDiagram.jpg">
