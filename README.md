Computer Exercise 4
===========

Introduction to assembly language

Computer Exercise 4 invloved simple programming exercises using the PRISM assembly language. The three programming tasks were:
  
    A) Store several data values in different memory locations
    B) Preform simple math operations and store it to a memory location
    C) Perform a decrementing loop on a value from the input port and write them to the three output ports
  
The programs are named Simple.psm, Math.psm, and Loops.psm respectively. 

The first program simply loaded the values into the assembler then wrote them to the specified memory locations. The program ended on an infinite loop

The second program loaded the requied value from the designated memory location. Performed the "Rotate Right" operation three times to perform a Rotate Left and double the value. The pogram then adds a C (two's compliment -4) directly into the accumulator, and then stored the 

The third and final program first loaded 1 into the register, negated it, then stored it in memory to be used in decrementing the inputs. The program then loaded the user input from the input ports into the accumulator and stored it to help the loop work. The loop then began and loaded the value stored in memory, wrote it to the first output, then decremented it, stored it in memory to be loaded later, and wrote it to the second output slot, and finally the accumulator was decremented once more and the value written to the third output. The loop then jumped the program back to where the value was loaded from memory and the decrementing process looped continuously.

Documentation None.
