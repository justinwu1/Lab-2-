# Lab-2
1.Process yacc grammar file, use -d flag to define tokens This will create y.tab.c and y.tab.h files
yacc -d calc.y

2.Process the lex specification file, this will create a lex.yy.c file
lex calc.l

3.Compile and link the two C source code files, output name using -o flag; name it calc this command will create y.tab.o, lex.yy.o, calc
cc y.tab.c lex.yy.c -o calc

y.tab.o is the object file for the y.tab.c source
lex.yy.o is the object file for the lex.yy.c source

4.Run calc program
./calc


Source: 80% of the code came from https://github.com/jengelsma/yacc-tutorial  I only done some modification to the code.

some commands to use this program:

a = 5 + 2; 
b = 5 - 2;
c = 5 * 2;
d = 5 / 2;
print a;
print b;
print c;
print d;
printBinary 1011;


