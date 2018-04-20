# Makefile for GTklos examples
#
#           Author: Erick Gallesio [eg@unice.fr]
#    Creation date: 19-Sep-2009 20:29 (eg)
# Last file update: 23-Oct-2010 13:00 (eg)

SRC=button.stk canvas1.stk canvas2.stk checkbutton.stk colorselector.stk \
    combobox.stk demos.stk dialog.stk entry1.stk entry2.stk entry3.stk \
    event.stk fileselector.stk fontselector.stk frame.stk gauge.stk \
    grid1.stk grid2.stk handle.stk image1.stk image2.stk \
    label.stk menu1.stk menu2.stk radiobutton.stk \
    scale.stk scroll1.stk scroll2.stk sedit.stk \
    separator.stk text.stk toolbar.stk

EXE=$(SRC:.stk=)

%: %.stk gtklos-demo.stk
	stklos-compile -c -o $* $<

all: 	$(EXE)
	@echo $(EXE) > all-demos

clean:
	/bin/rm -f $(EXE) *~ all-demos

distclean:
	/bin/rm -f stklos-gtklos.so

