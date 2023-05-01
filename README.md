Download Link: https://assignmentchef.com/product/solved-cda4203l-lab4-vending-machine-fsm
<br>
<strong>Objective:  </strong>To learn and practice synthesizable Finite State Machine construction to be tested on a FPGA board.

<strong>Description: </strong>Design an FSM for use as a controller for a vending machine. The system has five (5) inputs: quarter, nickel, dime, soda, and diet. The quarter input will go high, then go low when a 25¢ coin is added to the machine. The dime and nickel inputs work in a similar manner for the 10¢ and 5¢ coins. The sodas cost 45¢each. The user presses the soda button to select a regular soda, and the diet button to select a diet soda. The GiveSoda output will pulse high, then low when a regular soda is released. Similarly, the GiveDiet output will pulse high, then low when a diet soda is released. The Change output will pulse high, then low once for every 5¢ returned in change. Once the user has inserted enough money to buy a soda, the user cannot insert more money. You may wish to insert an additional output, status, to indicate whether the machine is currently accepting money. Choose a Moore or Mealy format as appropriate.

Your design must be a pure FSM. This means that there should be no complex operations (addition, subtraction) in your design. It must function solely on states and transitions.

The output pulses must stay high for a minimum of one-half of a clock cycle. The outputs will be directed to the bank of GPIO LEDs. You may select the exact mapping of outputs to LEDs. In your report, clearly list the input/button assignments.

The inputs will be taken from the Directional Buttons. These buttons will require a debounce circuit to operate correctly. You may select the exact mapping of inputs to buttons. In your report, clearly list the output/LED assignments.

<ol>

 <li> Design the vending machine FSM and verify it functionality using simulation.</li>

 <li> Synthesize the design and verify its functionality on the FPGA.</li>

</ol>

Submit a zipped archive consisting of: (a) A concise report that includes your Verilog code and simulation results; (b) Verilog Models and Testbench.  Include a README file. Organize your files in folders named Problem1 and Problem2.

<strong>Report Organization (A template is provided on Canvas):</strong>

<ul>

 <li>Cover sheet</li>

 <li>Problem 1: Your design details, Verilog Code, Test Bench, and Simulation Results (Waveforms)</li>

 <li>Problem 2: Pin mapping file and Synthesis report.</li>

 <li>Feedback: Hours spent, Exercise difficulty (Easy, Medium, Hard)</li>

</ul>

<strong> </strong>