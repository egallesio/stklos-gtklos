# Makefile for GTklos examples
#
#           Author: Erick Gallesio [eg@unice.fr]
#    Creation date: 19-Sep-2009 20:29 (eg)
# Last file update: 19-Sep-2009 20:50 (eg)

SRC=$(wildcard *.stk)
EXE=$(SRC:.stk=)

%: %.stk gtklos-demo.stk
	stklos-compile -c -o $* $<

all: 	$(EXE)
	@echo $(EXE) > all-demos

clean:
	/bin/rm -f $(EXE) *~ all-demos
