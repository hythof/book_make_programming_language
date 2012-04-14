all:
	lex token.l
	yacc -dv mycalc.y
	cc -o mycalc y.tab.c lex.yy.c
	./mycalc

