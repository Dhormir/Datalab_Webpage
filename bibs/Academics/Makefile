CFLAGS = -d -s
SUFFIXES = .bib
SUBDIRS = Professors Students


INPUTS = *$(SUFFIXES)
OUPUTS = academics$(SUFFIXES)

.PHONY: subdirs $(SUBDIRS)
subdirs: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o ../$(OUPUTS)