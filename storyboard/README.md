## Storyboard (Round 2)


Experiment 1: 3-8 Line Decoder

### 1. Story Outline:

In digital electronics, a decoder can take inputs in the form of 1 or 0. It has 3 bits inputs and 8 outputs. The coded 3x8 Decoder converts coded inputs into coded outputs, where the input and output codes are different e.g. n-to-2^n, binary-coded decimal decoders. 

### 2. Story:

A decoder is a n-to-2^n type binary decoders. The Decoder is a digital circuit which is a combinational circuit that convert coded binary information from 'n' coded inputs to a maximum of 2^n unique coded outputs. Few examples of Decoder are: 2-to-4 decoder, 3-to-8 decoder or 4-to-16 decoder.
Let us consider that a logic network has 3 inputs A, B and C. Their output will be as per the following 8 states as mentioned below. The truth table for this decoder is shown below:
Enable | A | B |C | O7 | O6 | O5 | O4 | O3 | O2 | O1 | O0
:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--|:--| 
0	|X|X|X|	0|	0|	0|	0|	0|	0|	0|	0|
1|	0|	0|	0|	0| 0|	0|	0|	0|	0|	0|<b>	1</b>|
1|	0	|0	|1	|0	|0	|0	|0|	0	|0|<b>	1</b>|	0|
1|0	|1|	0|	0	|0	|0|	0|	0|<b>	1</b>|	0|	0|
1	|0	|1	|1	|0|	0	|0	|0	|<b>	1</b>|	0	|0	|0|
1	|1	|0	|0	|0|	0	|0	|<b>	1</b>	|0|	0	|0|0|
1	|1	|0	|1	|0|	0	|<b>	1</b>	|0|	0|	0	|0|	0|
1	|1	|1	|0|	0	|<b>	1</b>	|0	|0	|0	|0|	0|	0
1	|1	|1	|1	|<b>	1</b>	|0|	0|	0|	0	|0	|0|	0|

<img src="https://github.com/avdheshgupta-ims/eb4_DS_DeadHeads_3-8LineDecoder/blob/master/storyboard/images/Decoder.jpg">
Fig1: Block Diagram of 3x8 Decoder
<img src="https://github.com/avdheshgupta-ims/eb4_DS_DeadHeads_3-8LineDecoder/blob/master/storyboard/images/FULL%20DECODER.jpg">
Fig2: Logic Diagram of 3x8 Decoder


#### 2.1 Set the Visual Stage Description:
A clear visualization of circuit diagram or logic diagram with block diagram on simulator page. It show the Logic diagram, Block diagram and truth table. The proper animation is ther to verify the truth table of 3x8 Decoder. 

#### 2.2 Set User Objectives & Goals:
Sr. No |	Learning Objective	| 
:--|:--|:--|:-:
1.| User will be able to understand the basic knowledge of logic gate and logic circuit.
2.| User will be able to apply to their learning of digital circuit.
2.| User will be able to design combinational circuit of Decoder.
3.| User will be able to evaluate the truth table of 3 x 8 Decoder.
<br>

Goals: <br>
•	Learn and understand of working od 3x8 Decoder.


#### 2.3 Set the Pathway Activities:

The simulator tab will follow:<br>
<br>1.	Logic diagram and block diagram with truth table
<br>2.	The user can input to logic diagram or can give binary input to block diagram
<br>3.	The diagram shows the output as per the truth table and highlight the input and output.
<br>4.	The user can clear the previous input/output to verify another combination of input/output



##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:

Q.1) How many input in a decoder, if there are 16 output:
<br><b>a.	4</b>
<br>b.	2
<br>c.	3
<br>d.	5

Q.2) Can a decoder design with NAND Gate:
<br><b>a.	Yes</b>
<br>b.	No

Q.3)	There is always n input and 2^n output in any decoder.
<br><b>a.	Yes</b>
<br>b.	No



##### 2.5 Allow pitfalls:
The user must have the basic knowledge of combinational circuit. The simulator is limited to show the verification of truth table.
##### 2.6 Conclusion:
Combinational logic circuits 3x8 Decoder has been designed and simulated using logic gates.

##### 2.7 Equations/formulas: NA
As the AND Gate out is depends on the input given to AND gate, and the output of AND Gate will be true if all inputs are 1. Therefore:<br>
O0 = A’B’C’
<br>O1 = A’B’C
<br>O2 = A’BC’
<br>O3 = A’BC
<br>O4 = AB’C’
<br>O5 = AB’C
<br>O6 = ABC’
<br>O7 = ABC


### 3. Flowchart
<img src="https://github.com/avdheshgupta-ims/eb4_DS_DeadHeads_3-8LineDecoder/blob/master/storyboard/images/WhatsApp%20Image%202020-09-13%20at%209.54.58%20PM.jpeg"/><br>
<br>

### 4. Mindmap:
<img src="https://github.com/avdheshgupta-ims/eb4_DS_DeadHeads_3-8LineDecoder/blob/master/storyboard/images/mmdecoder.png"/>


### 5. Storyboard :
Storyboard:
<br>
<img src="images/sbdecoder.png">
