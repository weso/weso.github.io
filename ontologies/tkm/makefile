INDIR		= .
NS		= http://purl.org/weso/ontologies/tkm\#
PREFIX  	= tkm
ONTOFILE	= tkm.owl
HTMLFILE	= tkm.html
SCRIPT		= specgen6.py

all	:	$(HTMLFILE)

$(HTMLFILE)	:	$(ONTOFILE) $(INDIR)/template.html
	$(SCRIPT) --indir=$(INDIR) --ns=$(NS) --prefix=$(PREFIX) --templatedir=$(TEMPLATEDIR) --outfile=$(HTMLFILE) --ontofile=$(ONTOFILE)
	
clean	:	
	rm $(HTMLFILE)