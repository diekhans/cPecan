rootPath = ../
include ../include.mk

all: 
	cd lastz-distrib-1.03.54 && ${MAKE} install
	mv ${binPath}/lastz ${binPath}/cPecanLastz
	mv ${binPath}/lastz_D ${binPath}/cPecanLastz_D

clean: 
	cd lastz-distrib-1.03.54 && ${MAKE} clean 
	rm -rf ${binPath}/cPecanLastz ${binPath}/cPecanLastz_D

