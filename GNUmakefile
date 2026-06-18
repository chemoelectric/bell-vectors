.DEFAULT_GOAL := bell-vectors.html

.DELETE_ON_ERROR:

%.html: %.adoc
	asciidoctor --safe $(<) -o $(@)

.PHONY: clean
clean:
	-rm -f bell-vectors.html
