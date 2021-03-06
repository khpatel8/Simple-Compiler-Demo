# Simple-Compiler-Demo

# Disclamer
Due to class project confidentiality no code or implementation details is shared publically. The details below only describe the project and share the results. 

# Polynomial-Calculator
This project is intended to use c++ programing language to create a compiler that can calculate polynomial functions. The set of symbols are defined using a context free grammer in the first image below. The compiler checked for syntax as well as sematics error. If there are no errors, then the program will output the correct computed value of the polynomial.

<img width="545" alt="Screen Shot 2020-03-04 at 7 07 08 PM" src="https://user-images.githubusercontent.com/56375328/75941501-24233000-5e4d-11ea-84ce-8dfed276edce.png">

There are three parts to the language defined in Grammar:

1) The lines that start with POLY which means this is the statement where the polynomial to be evaluated is declared. These lines are followed by a START sybmol which tells the program to start the evaluation.

2) These are the line(s) that start with either declared polynomail name or INPUT which means it is asking for user's input as an argument to the polynomial declared. They are seen after START symbol.

3) This the the line(s) with numbers which will be fed to the program during compilation.

All the line have to be followed by a SEMICOLON except the last line.

Some images of the test cases with the output generated by the program.

As you can see here there is no semicolon at the end of lines 1 and 4 resulting in syntax error.
<img width="1233" alt="Screen Shot 2020-03-04 at 7 18 33 PM" src="https://user-images.githubusercontent.com/56375328/75941508-27b6b700-5e4d-11ea-9664-0d1a68c6c49b.png">

Incorrect arguments are supplied for evaluation resulting in sematics error at lines 6 and 11.
<img width="1237" alt="Screen Shot 2020-03-04 at 7 19 12 PM" src="https://user-images.githubusercontent.com/56375328/75941511-29807a80-5e4d-11ea-9f61-d3988be19a0a.png">

No syntax or semantics errors found. Program executes and calculates the ouput.
<img width="1242" alt="Screen Shot 2020-03-04 at 7 16 10 PM" src="https://user-images.githubusercontent.com/56375328/75941523-2d140180-5e4d-11ea-8a12-741af26a5fd0.png">


Program was able to pass all the test cases (hidden or visible) provided by the instructor. 
