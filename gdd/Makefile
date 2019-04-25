#
# General purpose Makefile for Latex
# 
# The Makefile is licensed under MIT
# and is part of the Pinit project.
#
# Author: Preben Vangberg
# Since: 23.02.2019 
#

OS = Linux

VERSION = 1.0.0
CC	= pdflatex

PARAM :=

SRCDIR := src
OUTDIR := out

FILE := gdd

#.PHONY: clean

#clean: 
#	rm -f $(OUTDIR)/*
#	echo $(SRCS)


target:
	@mkdir -p out
	$(CC) $(PARAM) -output-directory $(OUTDIR) $(SRCDIR)/$(FILE).tex


