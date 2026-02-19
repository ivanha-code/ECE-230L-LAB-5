# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Ivan Ha & Abigail Ames
## Lab Summary
We made the truth table from circuit A & B to POS and SOP
Assigned output of A to the input of B
What we Learned
- Learned how to connect two modules together
- Learned how to create a module in verilog
- Learned how to use wires in verilog
- Learned how to assign values to switches
- Learned how to analyze the contraints file to determine which line of code is needed for our circuits.
## Lab Questions

### 1 - Explain the role of the Top Level file.
The role of the top file is show which pin such as the switches and LED (inputs/outputs). That tells the file where to take the input equation then output them to the LEDs. Its also known as the starting point serving as the base for all the other files.
### 2 - Explain the function of the Constraints file.
The function of the contraints file is to tell that vivado acts as an interface between the user's logic and the physical board.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Yes because we had some trouble at first, due to the fact it was not optimized then we optitized it and was able to pass all testcases.
