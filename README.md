## VSD_SQUADRON_MINI_INTERNSHIP

### SOFTWARE:

#### UBUNTU : 
     * The Ubuntu software is used for the process.
     * The Ubuntu is a popular free and open-source Linux-based operating system .
     * Ubuntu was introduced in 2004 by a British company Canonical.
     * Ubuntu was based on Debian.

### TASK_1: 
Program to output the sum of numbers (Sample).

### STEPS INVOLVED:

#### COMMAND TO OPEN LEAFPAD:
         1. Initially the cd command is given in the terminal.
         2. After which the leafpad _filename_ & is given which is the command for opening the leafpad.
         3. Now the leafpad is opened in which the required code for the title is typed respectively.
#### PROGRAM:
         1. The required code for the given title is written in the leafpad.
         2. The code written has to be saved.
         3. It could be saved by clicking on to the file option on the top left of the leafpad opened.
#### OUTPUT COMMAND:
         1. The terminal is opened to obtain the output.
         2. The gcc _filename_.c is given with the extension of .c 
         3. After which the ouput is viewed through the command of ./a.out respectively.
#### OUTPUT OBTAINED:
         1. Thus the terminal window would display the output foe the code that is written in the leafpad respectively.
         2. The obtained output is the required output that could bbe obtained through the ubuntu software through the command ./a.out respectively.
#### OPENING RISC COMPILER:
         1. Initially the cat _filename_ is given to make the code to appear in the terminal window respectively.
         2. Then the required command of riscv64-unnown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o _filename_.o _filename_.c
         3. The next command to be given is of with ls -ltr _filename_.o
#### COMMAND TO VIEW ASSEMBLY CODE:
         1. The assembly code is viewed through the command of riscv64-unknown-elf-objdump -d _filename_.o.
         2. The line of code appeared would be too long as a result of which to reduce the code the following commnad is used.
         3. The command of riscv64-unknown-elf-objdump -d _filename_.o | less.
         4. The above command would thus result in a concised assembly level code.
#### OUTPUT:
         1. Thus the result is obtained for the required code given in the leafpad.

### TASK_2:
 Write a simple C program for Clock Cycle Divider: Crafting a Digital Clock Divider Circuit selected and compile with RISC-V GCC.
### CLOCK CYCLE DIVIDER:
A clock cycle divider is a digital circuit used to generate a clock signal that has a lower frequency than the original input clock. The divided clock signal can be used in various applications where a slower clock is needed, such as in microcontrollers, digital watches, or other timing-based applications.

### How a Clock Cycle Divider Works:
*Input Clock*: The original high-frequency clock signal that needs to be divided.
*Counter*: A digital counter that counts the number of input clock cycles.
*Divide Factor*: A predetermined value that specifies how many input clock cycles should elapse before toggling the output clock signal.

### Basic Operation:
*Counting Cycles*: The counter increments on each input clock cycle.
*Compare Counter to Divide Factor*: When the counter reaches the value specified by the divide factor, the output clock signal is toggled, and the counter is reset.
*Output Clock*: The resulting output clock signal has a frequency that is the input clock frequency divided by the divide factor.

### STEPS INVOLVED:
As mentioned in the above task_1 the similar steps are to be followed. The only difference is that the code involved in the program based on the topic chosen respectively.
### COMMAND TO OPEN LEAFPAD:


         
    
