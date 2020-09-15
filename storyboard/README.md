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
A clear visualization of circuit diagram or logic diagram with block diagram on simulator page. It show the Logic diagram, Block diagram and truth table. The proper animation is ther to verify the truth table of 3x8 Decoder. 

#### 2.2 Set User Objectives & Goals:
Sr. No |	Learning Objective	| Cognitive Level | Action Verb
:--|:--|:--|:-:
1.| User will be able to understand the basic knowledge of logic gate and logic circuit |Understand| understand
2.| User will be able to apply to their learning of digital circuit | Applying | apply
2.| User will be able to design combinational circuit of Decoder | Create| design
3.| User will be able to evaluate the truth table of 3 x 8 Decoder | Evaluate |evaluate
<br>

Goals: <br>
•	Learn and Design of combination circuit of 3x8 Decoder.


#### 2.3 Set the Pathway Activities:

The simulator tab will follow:<br>
<br>1.	Logic diagram and block diagram with truth table
<br>2.	The user can input to logic diagram or can give binary input to block diagram
<br>3.	The diagram shows the output as per the truth table and highlight the input and output.
<br>4.	Click on clear, to verify another combination of input/output



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
The user must have the basic knowledge of combinational circuit.
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
