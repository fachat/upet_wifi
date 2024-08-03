
FILES=wificfg proghelper sendbrk


all: $(FILES)

$(FILES): % : %.a65 *.a65 *.i65
	xa -E -XMASM -XCA65 -O PETSCII -o $@ $<


clean:
	rm -f $(FILES)

