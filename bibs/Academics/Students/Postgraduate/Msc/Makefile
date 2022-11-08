CFLAGS = -d -s
SUFFIXES = .txt

INPUTS = *$(SUFFIXES)
OUPUTS = pubs$(SUFFIXES)

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o ../$(OUPUTS)