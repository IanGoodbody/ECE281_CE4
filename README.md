Computer Exercise 4
===========

Introduction to assembly language

Computer Exercise 4 involved simple programming exercises using the PRISM assembly language. The three programming tasks were:
  
    A) Store several data values in different memory locations
    B) Preform simple math operations and store it to a memory location
    C) Perform a decrementing loop on a value from the input port and write them to the three output ports
  
The programs are named Simple.psm, Math.psm, and Loops.psm respectively. 

The first program simply loaded the values into the assembler then wrote them to the specified memory locations. The program ended on an infinite loop

The first program was tested by running it step by step, ensuring that the values on the animation acted as expected, then ensured that the values were stored in the proper places in the memory window.

The second program loaded the required value from the designated memory location. Performed the "Rotate Right" operation three times to perform a Rotate Left and double the value. The program then adds a C (two's compliment -4) directly into the accumulator, and then output the value to output port 2. The program ended in an infinite loop.

The second program was tested by placing an arbitrary value in memory location B0, and ensuring that they produced the correct output. The two values tested were 4 and 3 which produced the correct outputs of 4 and 2 respectively

The third and final program first begins by loading the value from the third input port. The loop begins where the program writes the accumulator value to the first output port, the program then adds F (two's compliment -1) to the accumulator value and wrties that value to the second output port. The decrementing process is repeated once more and the output sent to the third output port. The program then adds one the the accumulator value, so it represents the decremented initial value, and loops back to the point where the program writes the accumulator value to the first output port.

The final program was tested by selecting an arbitrary value for the input port, running the program then ensuring that the values decremented as expected.

Documentation None.
