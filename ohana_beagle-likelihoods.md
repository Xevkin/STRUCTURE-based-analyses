# Ohana

Github: https://github.com/jade-cheng/ohana

Paper: https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btx098

## QPAS

Convert beagle .beagle.gz from ANGSD to .lgm format

`ohana-convert bgl2lgm ./sample.beagle ./sample.lgm`

`? \cat ./sample.beagle.gz | ohana-convert bgl2lgm > ./sample.lgm`

`ohana-qpas ./sample.lgm -k 2 -qo ./sample.qmatrix -fo ./sample.fmatrix -mi 5 -nt 12`
