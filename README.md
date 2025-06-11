# cse231-lab-6-introduction-to-multiplexers-and-decoders-solved
**TO GET THIS SOLUTION VISIT:** [CSE231-Lab 6 Introduction to Multiplexers and Decoders Solved](https://mantutor.com/product/cse231-lab-6-introduction-to-multiplexers-and-decoders-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;62579&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE231-Lab 6 Introduction to Multiplexers and Decoders Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<ul>
<li>Understand the concept of multiplexing in the context of digital logic circuits.</li>
<li>Learn about the internal logic of digital multiplexers.</li>
<li>Implement digital logic functions using multiplexers.</li>
<li>Observe and analyze the operations of the 3 to 8 Line Decoder</li>
</ul>
<strong>Theory </strong>

&nbsp;

<strong>Multiplexers:</strong> A multiplexer is a combinational circuit that selects binary information from one of many input lines and directs it to a single output line. The selection of a particular input line is controlled by a set of selection lines. Normally, there are 2<sup>n</sup> input lines and n selection lines whose bit combinations determine which input is selected.

&nbsp;

A block diagram and truth table for a 4:1 Multiplexer (4 inputs and 1 output) is given below.

<strong>&nbsp; </strong>

&nbsp;

&nbsp;

<table width="348">
<tbody>
<tr>
<td width="115"><strong>S<sub>1</sub></strong></td>
<td width="115"><strong>S<sub>0</sub></strong></td>
<td width="53"></td>
<td width="64"><strong>Y </strong></td>
</tr>
<tr>
<td width="115">0</td>
<td width="115">0</td>
<td width="53"></td>
<td width="64">I0</td>
</tr>
<tr>
<td width="115">0</td>
<td width="115">1</td>
<td width="53"></td>
<td width="64">I1</td>
</tr>
<tr>
<td width="115">1</td>
<td width="115">0</td>
<td width="53"></td>
<td width="64">I2</td>
</tr>
<tr>
<td width="115">1</td>
<td width="115">1</td>
<td width="53"></td>
<td width="64">I3</td>
</tr>
<tr>
<td colspan="3" width="284">&nbsp; Output Equation:

<strong>&nbsp; Y= I<sub>0</sub>S<sub>1</sub>‘S<sub>0</sub>‘ + I<sub>1</sub>S<sub>1</sub>‘S<sub>2 </sub>+ I<sub>2</sub>S<sub>1</sub>S<sub>2</sub>‘ + I<sub>3</sub>S<sub>1</sub>S<sub>2</sub></strong>
</td>
<td width="64"></td>
</tr>
</tbody>
</table>
<h1>&nbsp;<strong>Table B1: </strong>Truth table for 4:1 Multiplexer &nbsp;&nbsp;&nbsp;&nbsp; <strong>Figure B1: </strong>Block diagram of &nbsp; 4:1 Multiplexer</h1>
&nbsp;

&nbsp;

&nbsp;

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Decoders:</strong> A decoder is a combinational circuit that converts binary information from n input lines to a maximum of 2<sup>n</sup> output lines.&nbsp; <strong>Figure B2</strong> shows the block diagram for a 3 to 8 line decoder. Here, x, y and z are the inputs and the combination of their values determines which output line becomes active. Setting all the input values to zero activates the first output line (0), setting x and y to zero and z to 1 activates the second output line (1) and this pattern continues till all the inputs are 1 at which point the eighth output line (7) is activated.

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h1><strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup>Figure B2: </strong>Block diagram of <strong><sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sup></strong>3 to 8 line decoder</h1>
<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>New Apparatus:</strong>

&nbsp;

<strong>IC 74151 (8:1 Multiplexer):</strong>

&nbsp;

The 74151 is a 16 pin IC which requires a Ground connection at pin 8 and V<sub>CC</sub> at pin 16. Pins 4, 3, 2, 1 and 15, 14, 13, 12 are the 8 inputs, pins 9, 10 and 11 are used to select a particular input and pin 5 is the output. Pin 6 is provides the inverse of the output at pin 5. An input at pin 7 is used to Enable the IC.

<strong>&nbsp;</strong>

<h1><strong><sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub>Figure B4: </strong>Pinout of IC74151</h1>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>IC 74138 (3 to 8 Line Decoder)</strong>:

&nbsp;

The 74138 is also a 16 pin IC which requires GND at pin 8 and VCC at pin 16. Pins 15, 14, 13, 12, 11, 10, 9 and 7 are used as the 8 outputs and pins 3, 2 and 1 are used to take input. A combination of the inputs at pins 6, 4 and 5 is used to enable the device. In order for the IC to function as intended, pin 6 (G1) must have a high value and both pins 4 and 5 (G2A and G2B) must have low values.

&nbsp;

Unlike some of the other ICs used so far, the outputs of the

74138 IC are ACTIVE-LOW which means that they provide a

0 or LOW output when they are activated and a 1 or High

output when they are inactive.

<strong>Figure B5: </strong>Pinout of IC74138

<h1><strong>Experiment 1: Constructing a 4:1 Multiplexer using basic Logic Gates </strong></h1>
<strong>&nbsp;</strong>

<strong>C.1 Apparatus </strong>

&nbsp;

<ul>
<li>Trainer board</li>
<li>1 x IC 7404 Hex Inverter (NOT gates)</li>
<li>2 x IC 7411 3-input AND gates</li>
<li>1 x IC 7432 2-input OR gates</li>
</ul>
&nbsp;

<strong>D.1 Procedure </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Figure D.1.1 </strong>4:1 Multiplexer

<strong>&nbsp;</strong>

<ol>
<li>Construct the circuit for the 4:1 MUX shown in <strong>Figure D.1.1</strong>.</li>
<li>Complete the Theoretical column of the truth table (<strong>Table F.1.1</strong>) for the following function:  F(A, B, C) = Σ (0, 1, 5, 7)</li>
<li>Now determine the inputs you need to provide to each data input line (I<sub>0</sub>, I<sub>1</sub>, I<sub>2</sub>, I<sub>3</sub>) of the MUX if you use A and B as the selection inputs, S<sub>1</sub> and S<sub>0</sub> Write down the values in the Data Inputs column.</li>
<li>Physically implement the function using the 4:1 MUX circuit you constructed.</li>
<li>Now complete the Practical column of the truth table.</li>
</ol>
&nbsp;

&nbsp;

<strong>E.1 Report </strong>

<strong>&nbsp;</strong>

<ol>
<li>Simulate the circuit you built for the 4:1 Multiplexer (<strong>Figure D.1.1</strong>) using Logisim. Include a screenshot of the circuit with your report.</li>
</ol>
&nbsp;

&nbsp;

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;</strong>

<h1><strong>Experiment 2: Using an 8:1 Multiplexer to implement a Boolean function </strong></h1>
&nbsp;

<strong>C.2 Apparatus </strong>

&nbsp;

<ul>
<li>Trainer board</li>
<li>1 x IC 74151 8:1 Multiplexer</li>
</ul>
&nbsp;

<strong>D.2 Procedure </strong>

&nbsp;

<ol>
<li>Complete the Theoretical column of the truth table (<strong>Table F.2.1</strong>) for the following function:</li>
</ol>
<h1> F(A, B, C, D) = Σ (0, 1, 3, 5, 8, 9, 14, 15)</h1>
<ol start="2">
<li>Now determine the inputs you need to provide to each data input line (I<sub>0</sub>, I<sub>1</sub>, I<sub>2</sub>, I<sub>3, </sub>I<sub>4</sub>, I<sub>5</sub>, I<sub>6</sub>, I<sub>7</sub>) of the MUX if you use A, B and C as the selection inputs, S<sub>2</sub>, S<sub>1</sub> and S<sub>0</sub> Write down the values in the Data Inputs column.</li>
<li>Draw the IC diagram (<strong>Figure F.2.1</strong>) for the implementation of the function using the provided 8:1 MUX (IC 74151).</li>
</ol>
Clearly label the inputs and outputs that you will use.

<ol start="4">
<li>Implement the function using the 8:1 MUX.</li>
<li>Now complete the Practical column of the truth table.</li>
</ol>
&nbsp;

<strong>E.2 Report </strong>

&nbsp;

<ol>
<li>Draw the IC diagram (with input values) for the implementation of the following function using IC 74151</li>
</ol>
 F(A, B, C, D) = Σ (1, 2, 4, 5, 10, 12, 13)

&nbsp;

&nbsp;

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<h2>Experiment 3: Implementing a 3 to 8 Line Decoder using IC 74138</h2>
&nbsp;

<strong>C.3 Apparatus </strong>

&nbsp;

<ul>
<li>Trainer board</li>
<li>1 x IC 74138</li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>D.3 Procedure </strong>

&nbsp;

<ol>
<li>Wire up the IC 74183 using the diagram in <strong>Figure B3 </strong>as your reference.
<ol>
<li>Set the Enable inputs to the appropriate values. G1 should be set to High and both G2A and G2B should be set to Low.</li>
<li>The 3 select inputs (<strong>C B A</strong>) should be connected to 3 binary switches and the 8 outputs should be connected to individual LEDs.</li>
</ol>
</li>
<li>Now change the values of the select inputs (<strong>C B A</strong>) to every combination from LLL to HHH and complete the truth table in <strong>Table F.3.1. </strong>In this table, use “<strong>L</strong>” to record a 0 and “<strong>H</strong>” to record a 1.</li>
</ol>
&nbsp;

&nbsp;

<strong>E.3 Report </strong>

<strong>&nbsp;</strong>

<ol>
<li>Explain the difference between an active-high and an active-low device.</li>
</ol>
&nbsp;

&nbsp;

&nbsp;

&nbsp;

<strong>F.1 Experimental Data: Implementing a Boolean function using a 4:1 MUX: </strong>

&nbsp;

<table width="438">
<tbody>
<tr>
<td width="38"><strong>A</strong></td>
<td width="38"><strong>B</strong></td>
<td width="38"><strong>C</strong></td>
<td width="118"><strong>F (Theoretical)</strong></td>
<td width="102"><strong>Data Inputs </strong></td>
<td width="102"><strong>F (Practical)</strong></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I0 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I1 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I2 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I3 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
</tbody>
</table>
<strong>Table F.1.1 </strong>

&nbsp;

<strong>&nbsp;</strong>

<strong>F.2 Experimental Data: Using an 8:1 MUX to implement a Boolean function: </strong>

&nbsp;

<table width="476">
<tbody>
<tr>
<td width="38"><strong>A</strong></td>
<td width="38"><strong>B</strong></td>
<td width="38"><strong>C</strong></td>
<td width="38"><strong>D </strong></td>
<td width="118"><strong>F (Theoretical)</strong></td>
<td width="102"><strong>Data Inputs </strong></td>
<td width="102"><strong>F (Practical)</strong></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I0 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I1 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I2 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I3 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I4 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I5 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I6 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">0</td>
<td width="118"></td>
<td rowspan="2" width="102">I7 =</td>
<td width="102"></td>
</tr>
<tr>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="38"></td>
<td width="118"></td>
<td width="102"></td>
</tr>
<tr>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="38">1</td>
<td width="118"></td>
<td width="102"></td>
<td width="102"></td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>Table F.2.1 </strong>

&nbsp;

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </strong><strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<table width="641">
<tbody>
<tr>
<td width="641"></td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>Figure F.2.1 </strong>

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>F.3 Experimental Data: 3 to 8 Line Decoder: </strong>

<strong>&nbsp;</strong>

<table width="624">
<tbody>
<tr>
<td colspan="2" width="96"><strong>Enable Inputs </strong></td>
<td colspan="3" width="144"><strong>Select Inputs </strong></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td colspan="2" width="96"><strong>Outputs </strong></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48"><strong>G1 </strong></td>
<td width="48"><strong>G2 </strong></td>
<td width="48"><strong>C </strong></td>
<td width="48"><strong>B </strong></td>
<td width="48"><strong>A </strong></td>
<td width="48"><strong>Y<sub>0</sub> </strong></td>
<td width="48"><strong>Y<sub>1</sub> </strong></td>
<td width="48"><strong>Y<sub>2</sub> </strong></td>
<td width="48"><strong>Y<sub>3</sub> </strong></td>
<td width="48"><strong>Y<sub>4</sub> </strong></td>
<td width="48"><strong>Y<sub>5</sub> </strong></td>
<td width="48"><strong>Y<sub>6</sub> </strong></td>
<td width="48"><strong>Y<sub>7</sub> </strong></td>
</tr>
<tr>
<td width="48">X</td>
<td width="48">H</td>
<td width="48">X</td>
<td width="48">X</td>
<td width="48">X</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
</tr>
<tr>
<td width="48">L</td>
<td width="48">X</td>
<td width="48">X</td>
<td width="48">X</td>
<td width="48">X</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">L</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">L</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">L</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
<tr>
<td width="48">H</td>
<td width="48">L</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48">H</td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
<td width="48"></td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

&nbsp;

<strong>Table F.3.1 </strong>

<strong>&nbsp;</strong>
