SUFFIXES = .bib
SUBDIRS = Postdoc Phd Msc


INPUTS = *$(SUFFIXES)
OUPUTS = postgraduate$(SUFFIXES)

.PHONY: subdirs $(SUBDIRS)

subdirs: $(SUBDIRS)

$(SUBDIRS):
	$(MAKE) -C $@

pubs: *$(SUFFIXES)
	bibtool $(CFLAGS) $(INPUTS) -o ../$(OUPUTS)

clean:
	rm -f $(OUPUTS)