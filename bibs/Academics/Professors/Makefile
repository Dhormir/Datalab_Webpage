CFLAGS = -d -s
SUFFIXES = .txt

INPUTS = *$(SUFFIXES)
OUPUTS = professors$(SUFFIXES)

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) *$(SUFFIXES) -o ../$(OUPUTS)