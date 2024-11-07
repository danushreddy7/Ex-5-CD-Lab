# Ex-5-RECOGNITION-OF-THE-GRAMMAR-anb-where-n-10-USING-YACC
RECOGNITION OF THE GRAMMAR(anb where n>=10) USING YACC
# Date:
# Aim:
To write a YACC program to recognize the grammar anb where n>=10.
# ALGORITHM
1.	Start the program.
2.	Write a program in the vi editor and save it with .l extension.
3.	In the lex program, write the translation rules for the variables a and b.
4.	Write a program in the vi editor and save it with .y extension.
5.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l
6.	Compile the yacc program with yacc compiler to produce output file as y.tab.c. eg $ yacc –d arith_id.y
7.	Compile these with the C compiler as gcc lex.yy.c y.tab.c
8.	Enter a string as input and it is identified as valid or invalid.
# PROGRAM:
# GAMMAR.I
![image](https://github.com/user-attachments/assets/76741009-c29a-4ac0-908c-d56cfc19db59)
# GAMMAR.Y
![image](https://github.com/user-attachments/assets/07e4b03d-d1b2-48f4-a117-e902b6317882)

# OUTPUT:
![image](https://github.com/user-attachments/assets/de760239-60ba-4ec0-b685-d63b8b59a6b1)

# RESULT:
The YACC program to recognize the grammar anb where n>=10 is executed successfully and the output is verified.
