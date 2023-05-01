Download Link: https://assignmentchef.com/product/solved-cs2100-tutorial-9-sequential-circuits
<br>
D1. The state table on the right describes the state transition of a circuit with 4 states <em>A</em>, <em>B</em>, <em>C</em> and <em>D</em>, an input <em>x</em>, and an output <em>z</em>. For example, if the circuit is in state <em>A</em> and its input <em>x</em> is 0, then it moves into state <em>C</em> and generates the output 0 for <em>z</em>.




<ul>

 <li>Complete the state diagram below. The label of the arc indicates input/output, hence 1/1 means <em>x</em>=1 and <em>z</em>=1.</li>

</ul>

<strong><em>x</em></strong><strong>/<em>z</em> </strong>







<ul>

 <li>Assuming that the circuit starts in state <em>A</em>, find the output sequence and state sequence for the input sequence <em>x</em> = 100010 (read from left to right). (<em>x</em> = 100010 means that initially <em>x</em> is 1, then in the next clock <em>x</em> is 0, and so on.)</li>

</ul>




D2. Match the following state diagrams to the 4 flip-flops: <em>JK</em> flip-flop, <em>D</em> flip-flop, <em>RS</em> flipflop, and <em>T</em> flip-flop. Don’t-care value is indicated by “x”.

<ul>

 <li>(b)</li>

</ul>




<ul>

 <li>(d)</li>

</ul>

<strong>Tutorial Questions </strong>

<ol>

 <li>A four-state sequential circuit below consists of a <strong><em>T</em> flip-flop</strong> and a <strong><em>D</em> flip-flop</strong>. Analyze the circuit.</li>

</ol>




<ul>

 <li>Complete the state table and hence draw the state diagram.</li>

 <li>Assuming that the circuit is initially at state 0, what is the final state and the outputs generated after 3 clock cycles?</li>

</ul>

A state is called a <strong><em>sink</em></strong> if once the circuit enters this state, it never moves out of that state.

<ul>

 <li>How many sinks are there for this circuit?</li>

 <li>Which is likely to be an unused state in this circuit?</li>

</ul>




<table width="539">

 <tbody>

  <tr>

   <td rowspan="2" width="390">


    <table width="367">

     <tbody>

      <tr>

       <td colspan="2" rowspan="2" width="100"><strong>Present state </strong><strong><em>A</em></strong><strong>                 <em>B</em> </strong></td>

       <td rowspan="2" width="58"><strong>Output <em>p </em></strong></td>

       <td colspan="2" width="111"><strong>Flip-flop inputs </strong></td>

       <td rowspan="2" width="99"><strong>Next state </strong><strong><em>A</em></strong><strong>+              <em>B</em>+ </strong></td>

      </tr>

      <tr>

       <td width="55"><strong><em>TA</em></strong></td>

       <td width="56"><strong><em>DB</em></strong></td>

      </tr>

      <tr>

       <td width="46">0</td>

       <td width="54">0</td>

       <td width="58"><strong> </strong></td>

       <td width="55"><strong> </strong></td>

       <td width="56"><strong> </strong></td>

       <td width="99"><strong>                </strong></td>

      </tr>

      <tr>

       <td width="46">0</td>

       <td width="54">1</td>

       <td width="58"><strong> </strong></td>

       <td width="55"><strong> </strong></td>

       <td width="56"><strong> </strong></td>

       <td width="99"><strong>                </strong></td>

      </tr>

      <tr>

       <td width="46">1</td>

       <td width="54">0</td>

       <td width="58"><strong> </strong></td>

       <td width="55"><strong> </strong></td>

       <td width="56"><strong> </strong></td>

       <td width="99"><strong>                </strong></td>

      </tr>

      <tr>

       <td width="46">1</td>

       <td width="54">1</td>

       <td width="58"><strong> </strong></td>

       <td width="55"><strong> </strong></td>

       <td width="56"><strong> </strong></td>

       <td width="99"><strong>                </strong></td>

      </tr>

     </tbody>

    </table></td>

   <td rowspan="2" width="86"></td>

   <td width="63"></td>

  </tr>

  <tr>

   <td width="63"></td>

  </tr>

 </tbody>

</table>










<ol start="2">

 <li>Given the state transition diagram on the right with states <em>AB</em> and input <em>x</em>, implement the circuit using <strong><em>JK</em> flip-flop</strong>s and the fewest number of logic gates.</li>

</ol>

Fill in the state table below and draw the circuit. You do not need to follow the simplest SOP expression in your implementation as that might not give you a circuit with the fewest logic gates.




<table width="404">

 <tbody>

  <tr>

   <td rowspan="2" width="56"><strong>Present state <em>A </em></strong></td>

   <td rowspan="2" width="25"><strong> </strong><strong><em>B </em></strong></td>

   <td rowspan="2" width="53"><strong>Input <em>x </em></strong></td>

   <td rowspan="2" width="86"><strong>Next  state </strong><strong><em>A</em><sup>+</sup>       <em>B</em><sup>+</sup> </strong></td>

   <td width="91"><strong>Flip-flop <em>A</em> </strong></td>

   <td rowspan="2" width="61"><strong>Flip-flop </strong><strong><em>JB </em></strong></td>

   <td rowspan="2" width="32"><strong><em>B</em> </strong><strong><em>KB </em></strong></td>

  </tr>

  <tr>

   <td width="91">     <strong><em>JA        KA </em></strong></td>

  </tr>

  <tr>

   <td width="56">0</td>

   <td width="25">0</td>

   <td width="53">0</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">0</td>

   <td width="25">0</td>

   <td width="53">1</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">0</td>

   <td width="25">1</td>

   <td width="53">0</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">0</td>

   <td width="25">1</td>

   <td width="53">1</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">1</td>

   <td width="25">0</td>

   <td width="53">0</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">1</td>

   <td width="25">0</td>

   <td width="53">1</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">1</td>

   <td width="25">1</td>

   <td width="53">0</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

  <tr>

   <td width="56">1</td>

   <td width="25">1</td>

   <td width="53">1</td>

   <td width="86"><strong>            </strong></td>

   <td width="91"><strong>            </strong></td>

   <td width="61"><strong> </strong></td>

   <td width="32"><strong> </strong></td>

  </tr>

 </tbody>

</table>




State 3 is unused. Can you complete the following state diagram with the unused state?







A circuit is <strong>self-correcting</strong> if for some reason the circuit enters into any unused (invalid) state, it is able to transit to a valid state after a finite number of transitions. Is your circuit self-correcting, and why?




<ol start="3">

 <li>[AY2018/19 Semester 2 exam]</li>

</ol>

A sequential circuit goes through the following states, whose state values are shown in decimal:







The states are represented by 4-bit values <em>ABCD</em>. Implement the sequential circuit using a <em>D</em> flip-flop for <em>A</em>, <em>T</em> flip-flops for <em>B</em> and <em>C</em>, and a <em>JK</em> flip-flop for <em>D</em>.




<ul>

 <li>Write out the <strong>simplified SOP expressions</strong> for all the flip-flop inputs.</li>

</ul>




<ul>

 <li>Implement your circuit according to your simplified SOP expressions obtained in part (a). Complete the given state diagram, by indicating the next state for each of the five unused states.</li>

</ul>




<ul>

 <li>Is your circuit self-correcting? Why?</li>

</ul>






















Question 4 may be skipped if there is not enough time.




<ol start="4">

 <li>Pokemone Theme Park offers locker rental to its visitors. Visitors may purchase two types of token: Pokemoney $1 (P$1) and Pokemoney $2 (P$2). A locker’s rental costs P$3. When a visitor deposits P$3 into the locker’s token slot, its door will open.</li>

</ol>

Design a sequential circuit with states <em>AB</em> for the locker’s door using <em>D</em> flip-flops. The circuit consists of 4 states representing the amount a visitor has deposited: 0, 1, 2 and 3 (or, in binary, <em>AB</em> = 00, 01, 10 and 11). The visitor can deposit only one token at a time.  When the circuit reaches the final state 3, it remains in state 3 even if the visitor continues to put tokens into the slot. When the circuit is in state 2 and the visitor deposits a P$2 token, the circuit goes into state 3.

The partial state diagram is shown below. The inputs <em>x</em> and <em>y</em> represent the P$1 and P$2 tokens respectively. The label on each arrow represents <em>xy</em>.

<ul>

 <li>Draw and write the missing arrows and labels.</li>

</ul>




<ul>

 <li>Write the <strong>simplified SOP expressions</strong> for the flip-flop inputs <em>DA</em> and <em>DB</em>.</li>

</ul>


