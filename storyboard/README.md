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
1|	0|	0|	0|	0| 0|	0|	0|	0|	0|	0|	1|
1|	0	|0	|1	|0	|0	|0	|0|	0	|0|	1|	0|
1|0	|1|	0|	0	|0	|0|	0|	0|	1|	0|	0|
1	|0	|1	|1	|0|	0	|0	|0	|1|	0	|0	|0|
1	|1	|0	|0	|0|	0	|0	|1	|0|	0	|0|0|
1	|1	|0	|1	|0|	0	|1	|0|	0|	0	|0|	0|
1	|1	|1	|0|	0	|1	|0	|0	|0	|0|	0|	0
1	|1	|1	|1	|1	|0|	0|	0|	0	|0	|0|	0|


#### 2.1 Set the Visual Stage Description:
Describe here : (guide When a user lands up into a simulator, the visual stage is the first thing that user comes across. The visual stage should include all the elements to be seen by a user on an imaginary canvas.  (This should NOT include any drawings. ) )

#### 2.2 Set User Objectives & Goals:
Describe the objectives and goals in details here : (guide : The user should clearly understand the aims and objective of the experiment. ( how he will begin experiment. ?  in descriptive))

#### 2.3 Set the Pathway Activities:

Describe the pathway activites here : (Guide : Set the pathway activities in line with the learning objectives (LOs)  & with a view to achieve the goals set in round #0 & round#1.  (once he begins, how he will traverse through the entire experiment ? in descriptive))

##### 2.4 Set Challenges and Questions/Complexity/Variations in Questions:

Describe the challenges Here : (guide : Set Challenges and Questions/Complexity/variations in questions according to User’s level, so as to invoke the learners’ interest.  (while traversing, what challenges he will face? how he has to solve and overcome ? descriptive).)

##### 2.5 Allow pitfalls:
Describe the pitfalls here: (guide : (while traversing or while solving challenge, how will we bring a situation in front of him that he commits mistake if he is not attentive , or not following procedure , descriptive))

##### 2.6 Conclusion:
Describe conclusion here : (guide: This may include displaying: how much time did the user take to solve the questions/ How many questions were right?/ How many hints did the learner use. Based on this the evaluation/marking to be suggested to the user. (once he is towards the completion of the experiment, what LO he is taking along with him, what will be his probable, interpretation/conclusion , descriptive) )

##### 2.7 Equations/formulas: NA
Type equations here : (guide : ( a separate sheet having equations / programs for the lab exper3ment to be shared along with the Story submissions (1) . You can mark it as numerical reference numbers within the story narration (like we cite in the research papers) and then separately share these equations/programs sheets as a reference, do not include the equations as a whole in the narration))
Tool can be used to integrate formula in Markdown <b> [here](http://latex.codecogs.com/eqneditor/samples/example3.php) </b>


### 3. Flowchart 4
<img src="flowchart/flowchart.png"/><br>
link to flow chart Here : Store in the  /flowchart folder within Round2 folder in your repo
<br>
(guide :The lab proposer should extract logic from the story, prepare a flowchart from the story narration and write the algorithm to execute the black box.  use Google Drawings https://docs.google.com/drawings/ (send the link to your flowchart and also attach .png by exporting it )

### 4. Mindmap:
<img src="mindmap/mindmap.png"/>
 Link to mindmap here : Store the mindmap in both .mm & .png extension in the  /mindmap folder and include link of only .pdf verison here
 <br>
 (guide : An elaborate mind map (connecting all the points in the experiment flow ) should be prepared and submitted by the lab proposer. The mind map should be a clear and detailed document that takes into account all minute intri5acies involved in the development of virtual lab. The mindmap should be self-content and any developer across the globe should be able to code it with all those details. using only FreeMind http://freemind.sourceforge.net/wiki/index.php/Main_Page (send the .png file and also the original .mm extension project file. )

### 5. Storyboard :
Storyboard: <a href="Storyboard/carwiper.gif"> [here]</a>
Link to storybaord (.gif file ) here :
(guide: This document should include sketching and description scene wise (duration, action, description). Software to be used for storyboarding : https://wonderunit.com/storyboarder/ (Its a FOSS tool) . tutorial on how to use it https://www.youtube.com/watch?v=LAeCEpG0KX4
