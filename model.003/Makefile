#Time-stamp: <2018-10-23 19:20:22 hamada>

all:
	git log|grep commit |grep -v initial| tee log.txt
	./simulator.py |tee Estimations.md


install.gnuplot.macOS:
	brew install gnuplot --with-aquaterm --with-x11

install.tgif.ubuntu16.04.5:
	sudo apt update
	sudo apt install tgif
	sudo apt install xfonts-75dpi
	sudo apt install gsfonts-x11
	xset fp rehash

plot:
	./plot.sh

clean:
	rm -rf *~ .*~

c: clean
