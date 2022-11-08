CFLAGS = -d -s
SUFFIXES = .txt

INPUTS = *$(SUFFIXES)
OUPUTS = undergraduate$(SUFFIXES)

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o ../$(OUPUTS)