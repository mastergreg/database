TARGET=ask2
$(TARGET).pdf: $(TARGET).tex title/* files/*
		xelatex -shell-escape $(TARGET).tex
spell:
		aspell -l el_gr --ignore-case=true -c $(TARGET).tex
clean:
	rm -f $(TARGET).{pdf,pyg,log,aux}
