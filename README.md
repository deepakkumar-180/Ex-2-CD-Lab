# Ex-2-GENERATION OF LEXICAL TOKENS LEX FLEX TOOL
# NAME : DEEPAKKUMARS 
# REG NO : 212225230042
# AIM
## To write a lex program to implement lexical analyzer to recognize a few patterns.
# ALGORITHM

1.	Start the program.

2.	Lex program consists of three parts.

     a.	Declaration %%

     b.	Translation rules %%

     c.	Auxilary procedure.

3.	The declaration section includes declaration of variables, maintest, constants and regular definitions.
4.	Translation rule of lex program are statements of the form

    a.	P1 {action}

    b.	P2 {action}

    c.	…

    d.	…

    e.	Pn {action}

5.	Write a program in the vi editor and save it with .l extension.

6.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l $ cc lex.yy.c
7.	Compile that file with C compiler and verify the output.

# INPUT
```a=b+c*d```
# OUTPUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6440fe03-2f32-465c-9468-87a7a72ae7a8" />

# RESULT
## The lexical analyzer is implemented using lex and the output is verified.
