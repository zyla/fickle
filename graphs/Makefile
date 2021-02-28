# Makefile for pretty graphs.
# Requires graphviz.

all: d1.dot.png d2.dot.png d3.dot.png

%.dot.png: %.dot
	dot -Tpng $^ > $^.png

%.dot.svg: %.dot
	dot -Tsvg $^ > $^.svg
