Submitted by: 
Fekry Mohamed    ID: 900192372
Mario Ghaly	 ID: 900202178
Freedy Amgad     ID: 900203088

Our implementation supported all the instructions correctly, and there is no errors. 

In the BNE instruction the user should consider that the PC is actually incremented by 1 each clock cycle, so if he wants to branch to the previous instruction, he should make 
the offset = -2 because at the execution time the PC will be in the next instruction and not the BNE instruction.

We verified the functionallity of the processor by writing three test cases that cover all instructions supported and inst2.txt file have a loop.

Bonus features:
The program supports variable hardware organization. The user should specify the number of
reservation stations for each class of instructions. Additionally, the user will specify the number
of cycles needed by each functional unit type. (counted as two features)

Note: I submitted the source code with the test cases because they should be in the same folder while running the program