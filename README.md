# Pentaminos
This is my personal implementation of Pentamino's board game. 

Given a rectangular board format, the program needs to find out if there is a way to cover all spaces with pieces formed by 5 squares. For this implementation purpose, the following pieces are accepted. Changing pieces layout, however, is just a matter of few adjustments in the code. 

![Image containing 12 pieces in the format of capital letters. The letters are: F,I,L,N,P,T,U,V,W,X,Y,Z](https://github.com/pisn/Pentaminos/raw/master/images/PentaminosImage.png)

This is a very naive backtracking algorithm, developed only for computer science algorithms study purpose. It could be more easily written in another language. Nevertheless, C language provides a better understanding of structures internal implementation.

The program expects to receive through the standard input the board format. 

Boards should be described as a n x m binary matrix. First, inform <b>n</b> and <b>m</b> dimensions, then the matrix. 0s are translated as "empty space" in the board, while 1s as "occupied spaces", which  are inaccessible for the pieces.

## Input Example

6 10 <br>
0000000000<br>
0000000000<br>
0000000000<br>
0000000000<br>
0000000000<br>
0000000000<br>

## Output example
The algorithm returns the first possibility it finds for fitting all pieces. If no possibilities are found, return <b> Impossible </b>.

For the input example in the Input session, the expected output is this:<br>
![](https://github.com/pisn/Pentaminos/blob/master/images/output.png)


