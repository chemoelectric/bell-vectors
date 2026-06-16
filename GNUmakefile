.DEFAULT_GOAL := bell-vectors.html

.DELETE_ON_ERROR:

%.html: %.adoc
	asciidoctor $(<)

.PHONY: clean
clean:
	-rm -f bell-vectors.html
