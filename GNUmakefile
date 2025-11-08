.SUFFIXES:
.PHONY: all clean install check

PROJECT   =encoding-csv
VERSION   =1.0.0
PREFIX    =/usr/local
TOOLCHAINS=noarch
BUILDDIR ?=.build
UNAME_S  ?=$(shell uname -s)
EXE      ?=$(echo $(UNAME_S) | awk '/Windows/ || /MSYS/ || /CYG/ { print ".exe" }')

all:
clean:
install:
check:
	go test -v
## -- BLOCK:go --
## -- BLOCK:go --
