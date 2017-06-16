## QPAS

Convert beagle .beagle.gz from ANGSD to .lgm format

`ohana-convert bgl2lgm ./sample.beagle ./sample.lgm`

`? \cat ./sample.beagle.gz | ohana-convert bgl2lgm > ./sample.lgm`

`ohana-qpas ./sample.lgm -k 2 -qo ./sample.qmatrix -fo ./sample.fmatrix -mi 5 -nt 12`
