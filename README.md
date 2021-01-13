# sudoku-solver-cpp

Problem statement: Write a Program to create a sudoku solver of 9 X 9 matix using CPP.

What is sudoku?
 ->  A puzzle in which players insert the numbers one to nine into a grid consisting of nine squares subdivided into a further nine smaller squares in such a way that every          number appears once in each horizontal line, vertical line, and square.

Scope of the Program: This sudoku solver can solves the sudoku puzzle of 9 X 9 order.

Language: C++

Platfrom required: 1. Visual Studio 2019 or
                   2. Code Block
How to get the platform:
 1.Go to visualstudio.microsoft.com and download the installer.
 2.Install the installer and then open it.
 3.Choose Visual studio 2019 community with the C++ desktop envirnoment kit.
 
Header files used:
   
 1. iostream
 2. vector
 3. array
 4. algorithm

Functions Used:
1. void print_grid
2. bool used_in_row
3. bool used_in_col
4. bool used_in_box
5. bool is_safe
6. bool solve_soduko
7. int main

Features of the code:
 1. Program contains a by default sudoku puzzle, and will solve that if the user Press 1.
 2. This program also allows the user to input thier own 9 x 9 sudoku puzzle and it will solve that.
 
 How to run this code:
  1. Go to any of the like visual studio or code block.
  2. write this code and compile it.
  3. Run the code.
  4. It will show two massages on the console screen.
     1. Use by deafult sudoku puzzle to check the code. Press 1.
     2. Or input your own sudoku puzzle. Press 2.
  5. If you Press 1, it will solve the inbuilt puzzle each time.
  6. If you Press 2, you have to enter the all elements of the sudoku puzzle and input zero at the empty places.
  
Ouput:
  You will get your puzzle totally solved.
