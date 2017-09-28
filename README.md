On Linux and Mac
cc -std=c99 -Wall lisp.c mpc.c -ledit -lm -o lisp


On Windows
cc -std=c99 -Wall lisp.c mpc.c -o lisp


mpc.c and mpc.h were obtained from
http://www.buildyourownlisp.com
