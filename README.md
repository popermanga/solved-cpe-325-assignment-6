Download Link: https://assignmentchef.com/product/solved-cpe-325-assignment-6
<br>



<h1>Assignment</h1>

<ol>

 <li>Write an assembly program that interfaces switches, SW1 and SW2, and LEDs, LED1 and</li>

</ol>

LED2, as follows (You should use interrupts for both switches).

<ol>

 <li>Initially, both the LEDs should be turned off.</li>

 <li>When SW2 is pressed for the first time, LED2 should be turned on. The next time SW2 is pressed, LED2 is turned off, and so on. Hence each press changes the state of LED2.</li>

 <li>When SW1 is pressed, LED1 blinks 3 times at 1Hz and then toggles the state of LED2.</li>

 <li>What happens when SW2 is pressed while LED1 is blinking? Does that disrupt the blinking? Does SW2 function correctly? Explain.</li>

</ol>

<strong>*</strong>Be mindful of the <strong>Notes </strong>below*

<ol start="2">

 <li>Write a C program that interfaces switches SW1 and SW2, LEDs 1 and 2, and the clock frequency as follows (You should use interrupts for both switches):

  <ol>

   <li>Initially, LED1 is on and LED2 is off and the clock frequency is set to 1MHz.</li>

   <li>Both LEDs blink with a 50,000 loop iteration delay.</li>

   <li>Every time SW1 is pressed, the blinking frequency is increased by doubling the clock frequency and the clock frequency does not exceed 8MHz.</li>

   <li>Every time SW2 is pressed, the blinking frequency is decreased by halving the clock frequency and the clock frequency does not go below 1MHz.</li>

   <li>Calculate the LEDs blinking rate for each clock frequency and show your work.</li>

  </ol></li>

</ol>

<strong>Hint:</strong> The clock frequency should be either 1MHz, 2MHz, 4MHz, or 8MHz. You could use global variables to determine what the next value should be.

<strong>*</strong>Be mindful of the <strong>Notes </strong>below*

<ol start="3">

 <li> Rewrite the first question in C and extend it in the following manner:

  <ol>

   <li>While SW1 and SW2 are pressed together, both LEDs should be on and they should turn off when the switches are released.</li>

  </ol></li>

</ol>

<strong>Hint: </strong>In the ISR change the P1IES register accordingly.


