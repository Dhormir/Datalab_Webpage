CFLAGS = -d -s
SUFFIXES = .bib
SUBDIRS = Postgraduate Undergraduate


INPUTS = *$(SUFFIXES)
OUPUTS = students$(SUFFIXES)

.PHONY: subdirs $(SUBDIRS)
subdirs: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o ../$(OUPUTS)

clean:
	rm -f $(OUPUTS)