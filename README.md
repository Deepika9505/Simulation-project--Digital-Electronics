# TITTLE:

Minimise the function using K map F(A,B,C)=A′BC+A′BC′+AB′C′+AB′C and simulate the logic diagram using verilog

# THEORY:

The K-map is a systematic way of simplifying Boolean expressions. With the help of the K-map method, we can find the simplest POS and SOP expression, which is known as the minimum expression. The K-map provides a cookbook for simplification.

Just like the truth table, a K-map contains all the possible values of input variables and their corresponding output values. However, in K-map, the values are stored in cells of the array. In each cell, a binary value of each input variable is stored.

The K-map method is used for expressions containing 2, 3, 4, and 5 variables. For a higher number of variables, there is another method used for simplification called the Quine-McClusky method. In K-map, the number of cells is similar to the total number of variable input combinations. For example, if the number of variables is three, the number of cells is 23=8, and if the number of variables is four, the number of cells is 24. The K-map takes the SOP and POS forms. The K-map grid is filled using 0's and 1's. The K-map is solved by making groups. There are the following steps used to solve the expressions using K-map:


# LOGIC DIAGRAM:

![WhatsApp Image 2023-06-04 at 9 17 00 PM](https://github.com/Deepika9505/Simulation-project--Digital-Electronics/assets/128984662/d1c714f9-dbe0-41cd-816a-0ce8b9087fd3)


# NETLIST DIAGRAM:

![WhatsApp Image 2023-06-04 at 9 17 00 PM (1)](https://github.com/Deepika9505/Simulation-project--Digital-Electronics/assets/128984662/a9361ea5-2896-4415-b4c3-bf4a1d6beed5)


# TIMING DIAGRAM:

![WhatsApp Image 2023-06-04 at 9 17 01 PM](https://github.com/Deepika9505/Simulation-project--Digital-Electronics/assets/128984662/9780cc7b-48fb-4dde-a823-0c99772685b4)


# PROGRAM:

module assignment(A,B,F);
input A,B;
output F;
xor(F,A,B);
endmodule

# REFERENCE:

https://www.javatpoint.com/karnaugh-map-in-digital-electronics
