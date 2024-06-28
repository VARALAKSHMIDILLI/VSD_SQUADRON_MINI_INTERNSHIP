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
#### PROGRAM:

#include <stdio.h>
#include <stdint.h>

#define DIVIDE_FACTOR 4 // Change this to the desired division factor

volatile uint32_t counter = 0;
volatile uint8_t divided_clock = 0;

void clock_divider(void) {
    counter++;
    if (counter >= DIVIDE_FACTOR) {
        counter = 0;
        divided_clock = !divided_clock; // Toggle the divided clock signal
    }
}

int main(void) {
    // Assuming some mechanism to call clock_divider() on each clock cycle
    // This could be an interrupt service routine (ISR) in a real embedded system

    printf("Starting clock divider simulation...\n");

    // Simulate 20 clock cycles
    for (int i = 0; i < 20; i++) {
        clock_divider();
        printf("Clock Cycle %d: Divided Clock = %d\n", i, divided_clock);
    }

    return 0;
}
##### Explanation of the Program:
##### Definitions and Variables:

######* DIVIDE_FACTOR:
          The factor by which you want to divide the clock frequency.
######* counter:
          A counter to keep track of the number of input clock cycles.
######* divided_clock:
          A variable representing the state of the divided clock signal.
######* clock_divider Function:
          This function increments the counter and checks if it has reached the DIVIDE_FACTOR.
When the counter reaches the DIVIDE_FACTOR, it resets the counter and toggles the divided_clock signal.
######* main Function:
          This function simulates the clock divider operation for 20 clock cycles.
It calls the clock_divider function on each simulated clock cycle and prints the state of the divided clock signal.


















         
    
