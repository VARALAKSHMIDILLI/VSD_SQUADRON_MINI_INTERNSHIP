### VSD_SQUADRON_MINI_INTERNSHIP

#### SOFTWARE:

##### UBUNTU : 
     * The Ubuntu software is used for the process.
     * The Ubuntu is a popular free and open-source Linux-based operating system .
     * Ubuntu was introduced in 2004 by a British company Canonical.
     * Ubuntu was based on Debian.

#### TASK_1: 
Program to output the sum of numbers (Sample).

#### STEPS INVOLVED:

##### COMMAND TO OPEN LEAFPAD:
         1. Initially the cd command is given in the terminal.
         2. After which the leafpad _filename_ & is given which is the command for opening the leafpad.
         3. Now the leafpad is opened in which the required code for the title is typed respectively.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/93e01f38-9ea3-44c1-a062-2b9e9810f0bd)         

##### PROGRAM:
         1. The required code for the given title is written in the leafpad.
         2. The code written has to be saved.
         3. It could be saved by clicking on to the file option on the top left of the leafpad opened.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/e7b39444-a27a-4113-af73-4bf500e2903b)
##### OUTPUT COMMAND:
         1. The terminal is opened to obtain the output.
         2. The gcc _filename_.c is given with the extension of .c 
         3. After which the ouput is viewed through the command of ./a.out respectively.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/e6d29330-dfa0-47ef-a714-8be9be57a433)

##### OUTPUT OBTAINED:
         1. Thus the terminal window would display the output foe the code that is written in the leafpad respectively.
         2. The obtained output is the required output that could bbe obtained through the ubuntu software through the command ./a.out respectively.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/91a172d6-239b-48e5-a596-a14e35edf74e)

##### OPENING RISC COMPILER:
         1. Initially the cat _filename_ is given to make the code to appear in the terminal window respectively.
         2. Then the required command of riscv64-unnown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o _filename_.o _filename_.c
         3. The next command to be given is of with ls -ltr _filename_.o
##### COMMAND TO VIEW ASSEMBLY CODE:
         1. The assembly code is viewed through the command of riscv64-unknown-elf-objdump -d _filename_.o.
         2. The line of code appeared would be too long as a result of which to reduce the code the following commnad is used.
         3. The command of riscv64-unknown-elf-objdump -d _filename_.o | less.
         4. The above command would thus result in a concised assembly level code.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/8598def7-1978-4891-9bce-1eb11f2fb463)

##### OUTPUT:
         1. Thus the result is obtained for the required code given in the leafpad.
![image](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/82dde3e0-2b21-4610-97d6-fee04abbec80)


#### TASK_2:
 Write a simple C program for Clock Cycle Divider: Crafting a Digital Clock Divider Circuit selected and compile with RISC-V GCC.
#### CLOCK CYCLE DIVIDER:
A clock cycle divider is a digital circuit used to generate a clock signal that has a lower frequency than the original input clock. The divided clock signal can be used in various applications where a slower clock is needed, such as in microcontrollers, digital watches, or other timing-based applications.

#### How a Clock Cycle Divider Works:
* *Input Clock*: The original high-frequency clock signal that needs to be divided.
* *Counter*: A digital counter that counts the number of input clock cycles.
* *Divide Factor*: A predetermined value that specifies how many input clock cycles should elapse before toggling the output clock signal.

#### Basic Operation:
* *Counting Cycles*: The counter increments on each input clock cycle.
* *Compare Counter to Divide Factor*: When the counter reaches the value specified by the divide factor, the output clock signal is toggled, and the counter is reset.
* *Output Clock*: The resulting output clock signal has a frequency that is the input clock frequency divided by the divide factor.

#### STEPS INVOLVED:
As mentioned in the above task_1 the similar steps are to be followed. The only difference is that the code involved in the program based on the topic chosen respectively.
#### COMMAND TO OPEN LEAFPAD:
         1. Initially the cd command is given in the terminal.
         2. Now the leafpad is opened in which the required code for the title is typed respectively
![1 Opening of leafpad cdp](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/e5535b04-718a-48e9-95ea-8169ad011a54)

#### PROGRAM FOR THE CLOCK DIVIDER:
         1. The required code for the given title is written in the leafpad.
         2. The code written has to be saved.
         3. It could be saved by clicking on to the file option on the top left of the leafpad opened.
![2 Clock Divider Program](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/5fc1de7c-787e-4171-b3b8-976158e920d8)

#### OUTPUT COMMAND:
         1. The terminal is opened to obtain the output.
         2. The gcc _filename_.c is given with the extension of .c 
         3. After which the ouput is viewed through the command of ./a.out respectively.
![3 Output Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/4029c8f3-b055-4f51-8953-80796eabf585)

#### OUTPUT OBTAINED:
         1. Thus the result is obtained for the required code given in the leafpad.
![4 Output for the cdp code](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/46f87afc-c9cc-4fa8-b36b-5d24329517f2)
#### FLOWCHART:
          Start
            |
            V
     Initialize counter to 0
            |
            V
    Initialize divided_clock to 0
            |
            V
    Print "Starting clock divider simulation..."
            |
            V
      Loop for 20 iterations
            |
            V
      [Inside Loop Iteration]
            |
            V
     Call clock_divider()
            |
            V
    Increment counter by 1
            |
            V
    Is counter >= DIVIDE_FACTOR?
         /     \
        /       \
      Yes       No
       |         |
       V         V
    Reset to 0  Continue     
       |         |
       V         V
    Toggle    divided_clock
       |         |
       V         V
     Print"Clock Cycle X: Divided Clock = Y"
            |
            V
         End Loop
            |
            V
           End
           
#### EXPLANATION:
* _Start_: The program begins execution.
* _Initialize counter to 0_: Set the counter variable to 0.
* _Initialize divided_clock to 0_: Set the divided clock signal to 0.
* _Print start message_: Print " Starting clock divider simulation ... " to the console.
* _Loop for 20 iterations_: Repeat the following steps 20 times.
* _Inside Loop Iteration_:
       * _Call clock_divider()_: Execute the clock_divider() function.
       * _Increment counter by 1_: Increase the counter value by 1.
       * _Is counter >= DIVIDE_FACTOR?_: Check if the counter has reached or exceeded the divide factor.
            * _Yes_: If true, proceed to reset the counter and toggle the divided clock signal.
                 * _Reset counter to 0_: Set the counter back to 0.
                 * _Toggle divided_clock_: Change the state of the divided clock signal (from 0 to 1 or from 1 to 0).
            * _No_: If false, continue without resetting the counter or toggling the clock.
      * _Print clock cycle status_: Print the current clock cycle number and the state of the divided clock.
* _End Loop_: Once all 20 iterations are complete, exit the loop.
* _End_: The program terminates.

This flowchart provides a visual representation of how the program executes, dividing the input clock signal and printing the state of the divided clock for each cycle.

#### TASK_3:
Write a simple C program for your project selected and compile with RISC-V GCC.

Compiling the C code with both GCC and RISCV confirms its compatibility with the Kit and the chip. Utilizing an AI tool to generate the cdp output streamlines the retrieval of the C code for the project cdp. This approach ensures precise implementation, speeds up development, and minimizes human errors, thus enhancing the clock divider's overall reliability and performance.

#### Steps to Compile with RISC-V GCC:
#### * Install RISC-V GCC Toolchain:
       Ensure you have the RISC-V GCC toolchain installed. If not, you can download and install it from the RISC-V 
       website or use a package manager if available for your OS.
#### * Save the Program:
       Save the provided C program in a file,
                E.g., cdp.c.
#### * Compile the Program:
       Open a terminal and navigate to the directory where clock_divider.c is saved. Run the following command to 
       compile the program with RISC-V GCC:
  
           riscv64-unknown-elf-gcc -o cdp.o cdp.c
  
       This command tells the RISC-V GCC compiler to compile the cdp.c source file and produce an executable named cdp.c.
#### GCC Output:
        Thus, the required gcc output is obtained by using the above command.
![1 GCC Output](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/a08f709b-a05f-4d52-b497-51df82f8c228)

#### * SPIKE Output:
       If you have a RISC-V simulator or hardware setup, you can run the compiled program on it. For a simulator, you 
       can use spike or any other RISC-V compatible simulator.
              For example:
                        spike pk cdp
       Thus, the output obtained is pictured as,
 ![2 SPIKE Output](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/3d7dcd82-6f7a-4908-b282-8b360c5b7604)
#### Assembly Code:
        The assembly code for the program is obtained to be vast initially.After which the less command is used to reduce the instructions respectively.
![3  Assembly Code with the command of less ](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/4a390620-0851-4d8e-b2f9-c899d91229c4)
#### Instructions and their Outputs:
         Certain instructions are put in the terminal to check their corresponding output generated by the spike in the terminal.Few instructions are given are pictured as follows.
![4 Instructions and their Outputs](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/065313fe-5192-4069-b34d-5e7692aeb06a) 

##### TASK_4:
Identify various RISC-V instruction type (R, I, S, B, U, J) and exact 32-bit instruction code in the instruction type format for below RISC-V instructions.
###### INSTRUCTIONS: 
         ADD r1, r2, r3
         SUB r3, r1, r2
         AND r2, r1, r3
         OR r8, r2, r5
         XOR r8, r1, r4
         SLT r10, r2, r4
         ADDI r12, r3, 5
         SW r3, r1, 4
         SRL r16, r11, r2
         BNE r0, r1, 20
         BEQ r0, r0, 15
         LW r13, r11, 2
         SLL r15, r11, r2
Upload the 32-bit pattern on Github.

RISC-V is an open standard Instruction Set Architecture (ISA) that uses a modular design, allowing for a simple and scalable instruction set. Here are the main instruction types in RISC-V:

##### 1. R-Type (Register Type)
      *_Purpose_: Used for arithmetic and logical operations.
      *_Format_: 31   25 24  20 19  15 14  12 11   7 6   0.
                 funct7 rs2 rs1 funct3 rd   opcode.
      *_opcode_: Operation code, specifies the operation to be performed.
      *_rs1, rs2_: Source registers.
      *_rd_: Destination register.
      *_funct3, funct7_: Function fields, provide more specificity for the operation.
      *_Efficiency_:*Uses only registers, which are faster to access compared to memory.
                    *Allows for complex arithmetic and logical operations without memory access overhead.
      *_Flexibility_:*Supports a wide range of operations (e.g., addition, subtraction, bitwise operations).
                     *Function fields (funct3, funct7) allow for many operations to be encoded in a compact format.

###### 2. I-Type (Immediate Type)
       *_Purpose_: Used for operations involving a constant (immediate) value and for load instructions.
       *_Format_: 31     20 19  15 14  12 11   7 6 0.
                  immediate rs1 funct3 rd   opcode.
       *_opcode_: Operation code.
       *_rs1_: Source register.
       *_rd_: Destination register.
       *_funct3: Function field.
       *_immediate_: 12-bit immediate value.
       *_Efficiency_:*Combines a register and an immediate value, reducing the need for additional instructions to load constants.
                     *Immediate values are embedded within the instruction, allowing quick access and reducing memory usage.
       *_Flexibility_:*Useful for arithmetic operations with constants and for load  instructions.
               *Supports operations like immediate addition, bit shifts, and load from memory.

##### 3. S-Type (Store Type)
      *_Purpose_: Used for store instructions.
      *_Format_:  31   25 24  20 19  15 14  12 11    7 6   0.
                  immediate[11:5] rs2 rs1 funct3 immediate[4:0] opcode.
      *_opcode_: Operation code.
      *_rs1_: Source register (address base).
      *_rs2_: Source register (data to store).
      *_funct3_: Function field.
      *_immediate_: 12-bit immediate value, split across two fields.
      *_Efficiency_:*Directly stores data from a register to memory, reducing the need for intermediate instructions.
                    *The immediate value allows for flexible addressing modes.
      *_Flexibility_:*Supports various store operations (e.g., store byte, store word).
                     *Immediate field allows for different offset addressing.

##### 4. B-Type (Branch Type)
      *_Purpose_: Used for conditional branch instructions.
      *_Format_:  31   25 24  20 19  15 14  12 11    7 6   0.
                  immediate[12,10:5] rs2 rs1 funct3 immediate[4:1,11] opcode.
      *_opcode_: Operation code.
      *_rs1, rs2_: Source registers.
      *_funct3_: Function field.
      *_immediate_: 13-bit immediate value, split across multiple fields.
      *_Efficiency_:*Enables conditional branching, which is essential for efficient control flow and loops.
                    *Immediate values allow for direct branching to nearby instructions,reducing the need for longer, more complex jump instructions.
      *_Flexibility_:*Supports a range of conditional branches (e.g., equal, not equal, less than).
               *Immediate field allows for efficient branch target encoding.

##### 5. U-Type (Upper Immediate Type)
      *_Purpose_: Used for instructions that set a 20-bit immediate in the upper 20 bits of a register.
      *_Format_: 31     12 11   7 6   0.
                 immediate[31:12] rd   opcode.
      *_opcode_: Operation code.
      *_rd_: Destination register.
      *_immediate_: 20-bit immediate value.
      *_Efficiency_:*Allows setting the upper 20 bits of a register, useful for large immediate values or addresses.
                    *Reduces the need for multiple instructions to construct large constants.
      *_Flexibility_:*Used in instructions like LUI (Load Upper Immediate) and AUIPC (Add *Upper Immediate to PC), enabling flexible manipulation of large values and 
               addresses.
              *Simplifies address calculations and large constant handling.

###### 6. J-Type (Jump Type)
       *_Purpose_: Used for jump instructions with a 20-bit immediate for the target address.
       *_Format_:  31      12 11 7 6   0.
                   immediate[20,10:1,11,19:12] rd   opcode.
       *_opcode_: Operation code.
       *_rd_: Destination register.
       *_immediate_: 20-bit immediate value, split across multiple fields.
       *_Efficiency_:*Provides a mechanism for long-distance jumps with a single instruction.
                     *Immediate value embedded in the instruction allows quick access to jump targets.
       *_Flexibility_:*Supports unconditional jumps, enabling functions and subroutine calls.
                      *The split immediate field allows for encoding larger jump distances.

To encode the provided RISC-V instructions into their 32-bit binary format, we need to follow the specific formats for each instruction type. Here are the 32-bit instruction codes for each instruction:

##### R-Type Instructions
###### ADD r1, r2, r3:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00011.
       *_rs1 (5 bits)_: 00010.
       *_funct3 (3 bits)_: 000.
       *_rd (5 bits)_: 00001.
       *_opcode (7 bits)_: 0110011.
       *_32 bit binary patterns_:
               0000000 00011 00010 000 00001 0110011.

###### SUB r3, r1, r2:
       *_funct7 (7 bits)_: 0100000.
       *_rs2 (5 bits)_: 00010.
       *_rs1 (5 bits)_: 00001.
       *_funct3 (3 bits)_: 000.
       *_rd (5 bits)_: 00011.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
               0100000 00010 00001 000 00011 0110011.

###### AND r2, r1, r3:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00011.
       *_rs1 (5 bits)_: 00001.
       *_funct3 (3 bits)_: 111.
       *_rd (5 bits)_: 00010.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
               0000000 00011 00001 111 00010 0110011.

###### OR r8, r2, r5:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00101.
       *_rs1 (5 bits)_: 00010.
       *_funct3 (3 bits)_: 110.
       *_rd (5 bits)_: 01000.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
                0000000 00101 00010 110 01000 0110011.

###### XOR r8, r1, r4:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00100.
       *_rs1 (5 bits)_: 00001.
       *_funct3 (3 bits)_: 100.
       *_rd (5 bits)_: 01000.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
                0000000 00100 00001 100 01000 0110011.

###### SLT r10, r2, r4:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00100.
       *_rs1 (5 bits)_: 00010.
       *_funct3 (3 bits)_: 000.
       *_rd (5 bits)_: 01010.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
                0000000 00100 00010 010 01010 0110011.

##### I-Type Instructions:
###### ADDI r12, r3, 5
       *_immediate (12 bits)_: 000000000101.
       *_rs1 (5 bits)_: 00011.
       *_funct3 (3 bits)_: 000.
       *_rd (5 bits)_: 01100.
       *_opcode (7 bits)_: 0010011.
       *_32-bit binary patterns_:
                000000000101 00011 000 01100 0010011.

###### LW r13, r11, 2:
       *_immediate (12 bits)_: 000000000010.
       *_rs1 (5 bits)_: 01011.
       *_funct3 (3 bits)_: 010.
       *_rd (5 bits)_: 01101.
       *_opcode (7 bits)_: 0000011.
       *_32-bit binary patterns_:
                000000000010 01011 010 01101 0000011.

##### S-Type Instructions:
###### SW r3, r1, 4
      *_immediate (12 bits)_: 000000000100 (split as 7 and 5 bits).
      *_rs2 (5 bits)_: 00011.
      *_rs1 (5 bits)_: 00001.
      *_funct3 (3 bits)_: 010.
      *_opcode (7 bits)_: 0100011.
      *_32-bit binary patterns_:
               0000000 00011 00001 010 00010 0100011.

##### B-Type Instructions:
###### BNE r0, r1, 20
       *_immediate (13 bits)_: 000000010100 (split across multiple fields).
       *_rs2 (5 bits)_: 00001.
       *_rs1 (5 bits)_: 00000.
       *_funct3 (3 bits)_: 001.
       *_opcode (7 bits)_: 1100011.
       *_32-bit binary patterns_:
               000000 00001 00000 001 00101 1100011.

###### BEQ r0, r0, 15
      *_immediate (13 bits)_: 00000001111 (split across multiple fields)
      *_rs2 (5 bits)_: 00000
      *_rs1 (5 bits)_: 00000
      *_funct3 (3 bits)_: 000
      *_opcode (7 bits_): 1100011
      *_32-bit binary patterns_:
               000000 00000 00000 000 01111 1100011

##### R-Type Instructions :
###### SRL r16, r11, r2
      *_funct7 (7 bits)_: 0000000.
      *_rs2 (5 bits)_: 00010.
      *_rs1 (5 bits)_: 01011.
      *_funct3 (3 bits)_: 101.
      *_rd (5 bits)_: 10000.
      *_opcode (7 bits)_: 0110011.
      *_32-bit binary patterns_:
               0000000 00010 01011 101 10000 0110011.

###### SLL r15, r11, r2:
       *_funct7 (7 bits)_: 0000000.
       *_rs2 (5 bits)_: 00010.
       *_rs1 (5 bits)_: 01011.
       *_funct3 (3 bits)_: 001.
       *_rd (5 bits_): 01111.
       *_opcode (7 bits)_: 0110011.
       *_32-bit binary patterns_:
                0000000 00010 01011 001 01111 0110011.

Let's now combine these instructions into their 32-bit binary patterns:.
##### 32-bit binary patterns:
      *_ADD  r1, r2, r3_: 00000000001100010000000010110011.
      *_SUB  r3, r1, r2_: 01000000001000001000000110110011.
      *_AND  r2, r1, r3_: 00000000001100001111000010010011.
      *_OR   r8, r2, r5_: 00000000010100010110000100010011.
      *_XOR  r8, r1, r4_: 00000000010000001100000100010011.
      *_SLT  r10, r2, r4_: 00000000010000010101000101010011.
      *_ADDI r12, r3, 5_: 00000000010100010000001100010011.
      *_SW   r3, r1, 4_: 00000000001100001010001000110011.
      *_SRL  r16, r11, r2_: 00000000001001011101000000110011.
      *_BNE  r0, r1, 20_: 00000000001000000000100101100011.
      *_BEQ  r0, r0, 15_: 00000000000000000000011111100011.
      *_LW   r13, r11, 2_: 00000000001001011010001100100011.
      *_SLL  r15, r11, r2_: 00000000001001011000001111010011.
These binary patterns represent the 32-bit encoded instructions for each of the specified RISC-V instructions.

#####TASK_5:
Use this RISC-V Core Verilog netlist and testbench for functional simulation experiment.
Certainly! Here's a step-by-step guide to proceed with running the RISC-V core Verilog code and its testbench on Ubuntu:

Step 1:A directory is created with the folowing command:
             $ mkdir squadron_vsdmini (squadron_vsdmini- any name)
 ![1 Directory](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/093bdc9a-8a1e-4efb-9a2b-f6323f3a3d87)
            

Step 2:Create the verilog code and testbench file:
             $ cd
             $ leafpad squadron_vsdmini.v
             $ leafpad squadron_vsdmini_tb .v
![2 Testbench creation](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/66e07e01-576d-4a3b-a627-b5c65a38b3de)
             
Step 3: Compile the Verilog Code:
Use Icarus Verilog to compile the Verilog files:
            iverilog -o squadron_vsdminisquadron_vsdmini.v squadron_vsdmini_tb.v
            $ ./squadron_vsdmini
This command compiles the Verilog files and creates an executable called squadron_vsdmini.
![4 Gtk wave](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/8ee97f06-83fa-48c7-bb3d-7fe762e24ed3)


Step 5: View Waveforms:
To view the waveforms, you need to generate a Value Change Dump (VCD) file from the simulation. Modify the testbench file (tb_rv32i_core.v) to include VCD dump commands:
![3 Netlist Dump command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/8470798d-db09-4664-adb3-34484546c9db)

Step 6: Open Waveforms with GTKWave:
Use GTKWave to view the waveforms:
           gtkwave simulation.vcd
In GTKWave, you can add the signals you want to observe and analyze the waveform.
![4 Gtk wave](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/b3b95151-c914-41f8-93d3-fc174299197d)

GTK WAVEFORMS:
1.ADD:
![7 ADD Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/d9ef6dff-1483-4bf9-8038-9d560f87d941)

2.AND:
![8 AND Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/8385db42-54fa-4836-930c-98a6d7c01c1a)

3.BEQ:
![9 BEQ Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/c3b82992-6f4b-4525-97f2-f87bb550c865)

4.BNE:
![10 BNE Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/e41d0731-d8b9-4d57-8384-770b9aa542ab)

5.OR:
![11 OR Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/1bd73488-8c42-4744-a884-d330a002cecd)

6.SLL:
![12 SLL Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/642a1a68-f17d-4390-ad1d-47443b5e4daf)

7.SLT:
![13 SLT Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/cb8714f7-08bb-4bf0-8e6c-5daf4c84b1c8)

8.SUB:
![14 SUB Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/9b0304c8-50c2-4f8e-a00c-88a60b1b93b3)

9.XOR:
![15 XOR Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/f5ade277-9814-45b3-b9f8-4887d5387210)

10.ADDI:
![16 ADDI Command](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/a9391109-c347-4f9d-97cf-d43e2a2b05ea)

TASK_6:

Update the repo with,
* Project Name
* Overview
* Components Required
* Circuit Connection
* Pinout Diagram (using a PowerPoint presentation)
* Table for Pin Connection
 
1. Project Name:
Clock Cycle Divider: Crafting a Digital Clock Divider Circuit

2. Overview:
The Clock Cycle Divider: Crafting a Digital Clock Divider Circuit project aims to design a clock divider using a RISC-V processor. This clock divider will allow users to set a programmable division ratio, enabling precise control over the output clock frequency. The system uses a CH32V003 RISC-V processor to manage the clock signals and interfaces with other digital components for clock signal generation and division.

3. Components Required:
* CH32V003 RISC-V processor.
* Oscillator/Clock source.
* Breadboard.
* Jumper wire.s
* Power supply.
* Resistors and capacitors (as needed for the clock circuit).
* Programming interface (e.g., USB to UART converter).

5. Circuit Connection:
The circuit connection involves interfacing the CH32V003 RISC-V processor with an oscillator to generate the clock signal. The processor will divide the clock signal based on the programmable ratio set by the user. Connections include power and ground connections, clock input to the processor, and output connections to observe the divided clock signal.

6. Pinout Diagram:

![Pinout Diagram](https://github.com/VARALAKSHMIDILLI/VSD_SQUADRON_MINI_INTERNSHIP/assets/173541966/9e76eb1f-e0b6-4ed3-a849-4fdd84d7ba8a)

7. Table for Pin Connection:

Component	        CH32V003 RISC-V Pin        	Description
Oscillator VCC	    VCC	                        Power supply to the oscillator
Oscillator GND	    GND	                        Ground connection
Oscillator OUT	    CLK_IN	                    Clock signal input to the processor
Processor OUT	    CLK_OUT	                    Divided clock signal output
Power Supply VCC	VCC	                        Power supply to the processor
Power Supply GND	GND	                        Ground connection

8. Sample Code:

  #include <stdio.h>
  #include <stdint.h>
  #include <unistd.h>     // For sleep function
  #include <gpio.h>       // Example GPIO library, replace with your actual GPIO library

  #define GPIO_INPUT_PIN  0   // Example input GPIO pin number
  #define GPIO_OUTPUT_PIN 1   // Example output GPIO pin number

  #define DIVISION_RATIO  2   // Example division ratio

  int main() 
  {
    gpio_setup();   // Setup GPIO pins for input and output

    int input_state = 0;
    int output_state = 0;
    
    while (1) 
    {
        // Read input GPIO pin (assuming it's connected to a button or switch)
        input_state = gpio_read(GPIO_INPUT_PIN);

        // Check input condition to adjust division ratio (example: button press)
        // This part would depend on your specific input mechanism

        // Perform clock division logic
        if (output_state == 0) {
            // Toggle output state every DIVISION_RATIO cycles
            output_state = 1;
            gpio_write(GPIO_OUTPUT_PIN, output_state);
        } else {
            output_state = 0;
            gpio_write(GPIO_OUTPUT_PIN, output_state);
        }

        // Delay to slow down operation (adjust as needed)
        usleep(500000);  // Example delay of 500 ms (500,000 microseconds)
    }

    return 0;
  }
