1) a. The C stack will set aside memeory locations for the variables that are used in the function. The main function will then fill in   the values of the variables, starting from the top of the stack. It will decrement by 4 for each variable. In this case, I have 2 int variables and 2 int pointers, so the C stack will have 4 memory locations starting from the top of the stack, and decrement it by 4, 4 times. The main function will then put in the values I set for those variables into the memory addresses.

   Essentially, the main function is setting up the inputs for the function that will be called.

   b. R0 is the value of the first argurment in my function, which is the address of my XPtr, and R1 is the value of the second argument, the address of my yPtr.
   
   c.
   
   ![Locals View](https://github.com/Thisisme125/embsys100/blob/feature/assignment05/images/1c.PNG)
   
2) 

   ![sqrAsm Output](https://github.com/Thisisme125/embsys100/blob/feature/assignment05/images/2.PNG)


3) The middle part shows the divide by 2 output.

4) The bottom shows the initial values of Char1 and Char2, and after calling the function, the values are swapped.


![Divby2 and swapChar outputs](https://github.com/Thisisme125/embsys100/blob/feature/assignment05/images/3_and_4.PNG)
