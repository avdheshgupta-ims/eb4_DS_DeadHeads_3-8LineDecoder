## Storyboard (Round 2)


Experiment 1: 3-8 Line Decoder

### 1. Story Outline:

In digital electronics, a decoder can take the form of a multiple-input, multiple-output logic circuit that converts coded inputs into coded outputs, where the input and output codes are different e.g. n-to-2n, binary-coded decimal decoders. 

### 2. Story:

A decoder would be the n-to-2n type binary decoders. These types of decoders are combinational circuits that convert binary information from 'n' coded inputs to a maximum of 2n unique outputs. In case the 'n' bit coded information has unused bit combinations, the decoder may have less than 2n outputs. 2-to-4 decoder, 3-to-8 decoder or 4-to-16 decoder are other examples.
Let us suppose that a logic network has 3 inputs A, B and C. They will give rise to 8 states as mentioned below. The truth table for this decoder is shown below:
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
There will be one enable input, if this enable input is 0, the circuit will be in high impedance state, if it is 1, then the circuit will work. There will be 3 input and 8 output. 
If enable input = 1
The output will be depend on inputs for example, if A=0, B=1, C=0, then as per the decoder circuit, O2 will be high.

#### 2.2 Set User Objectives & Goals:
User will be able to apply to their learning of digital circuit<br>
User will be able to design combinational circuit of Decoder<br>
User will be able to evaluate the truth table of 3 x 8 Decoder<br>

Goals: <br>
•	Learn and Design of combination circuit of 3x8 Decoder.


#### 2.3 Set the Pathway Activities:

1. Understand Logic gates
2. Understand Combination circuit
3. learn to design and simulate 3x8 Decoder


##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:

Q.1) Which of the following is a decoder IC?<br>
a) 7890<br>
<b>b) 8870</b><br>
c) 4047<br>
d) 4041<br>

Q.2) Which of the following represents a number of output lines for a decoder with 4 input lines?<br>
a) 15<br>
<b>b) 16</b><br>
c) 17<br>
d) 18<br>
Q.3) Which gate is best used as a basic comparator?<br>

a)	NOR<br>
b)	OR<br>
<b>c)	Exclusive-OR</b><br>
d)	AND<br>


##### 2.5 Allow pitfalls:
NA

##### 2.6 Conclusion:
Combinational logic circuits 3x8 Decoder has been designed and simulated using logic gates.

##### 2.7 Equations/formulas: NA
As the AND Gate out is depends on the input given to AND gate, and the output of AND Gate will be true if all inputs are 1. Therefore:
O0 = A’B’C’
O1 = A’B’C
O2 = A’BC’
O3 = A’BC
O4 = AB’C’
O5 = AB’C
O6 = ABC’
O7 = ABC


### 3. Flowchart 4
<img src="https://github.com/avdheshgupta-ims/eb4_DS_DeadHeads_3-8LineDecoder/blob/master/storyboard/images/WhatsApp%20Image%202020-09-13%20at%209.54.58%20PM.jpeg"/><br>
<br>

### 4. Mindmap:
<img src="mindmap/mindmap.png"/>
 Link to mindmap here : Store the mindmap in both .mm & .png extension in the  /mindmap folder and include link of only .pdf verison here
 <br>
 (guide : An elaborate mind map (connecting all the points in the experiment flow ) should be prepared and submitted by the lab proposer. The mind map should be a clear and detailed document that takes into account all minute intri5acies involved in the development of virtual lab. The mindmap should be self-content and any developer across the globe should be able to code it with all those details. using only FreeMind http://freemind.sourceforge.net/wiki/index.php/Main_Page (send the .png file and also the original .mm extension project file. )

### 5. Storyboard :
Storyboard: <a href="Storyboard/carwiper.gif"> [here]</a>
Link to storybaord (.gif file ) here :
(guide: This document should include sketching and description scene wise (duration, action, description). Software to be used for storyboarding : https://wonderunit.com/storyboarder/ (Its a FOSS tool) . tutorial on how to use it https://www.youtube.com/watch?v=LAeCEpG0KX4
