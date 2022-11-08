CFLAGS = -d -s
SUFFIXES = .bib
SUBDIRS = Academics

INPUTS = *$(SUFFIXES)
OUPUTS = pubs$(SUFFIXES)

.PHONY: subdirs $(SUBDIRS)
subdirs: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o $(OUPUTS)

clean:
	rm -f $(OUPUTS)