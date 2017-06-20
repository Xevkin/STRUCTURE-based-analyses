# Ohana

Github: https://github.com/jade-cheng/ohana

Paper: https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btx098

## QPAS
#on pg2
export LD_LIBRARY_PATH=/home/admin1/ohana/opt/OpenBLAS/lib:$LD_LIBRARY_PATH

Convert beagle .beagle.gz from ANGSD to .lgm format

`ohana-convert bgl2lgm sample.beagle sample.lgm`

`gunzip sample.beagle.gz`

#I found ohana-convert to run much faster on unzipped files rather than zcat pipping 

`/usr/local/bin/convert bgl2lgm sample.beagle sample.lgm`

`/usr/local/bin/qpas sample.lgm -k 2 -qo sample.qmatrix -fo sample.fmatrix -mi 5 -nt 12`
