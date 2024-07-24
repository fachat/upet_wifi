
FILES=wificfg



$(FILES): % : %.a65 *.a65 *.i65
	xa -XMASM -XCA65 -O PETSCII -o $@ $<


clean:
	rm -f $(FILES)

