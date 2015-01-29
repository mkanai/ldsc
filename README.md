
LDSC (LD SCore)
===============

`v1.0.0`

`ldsc` is a command line tool for estimating heritability and genetic correlation from GWAS summary statistics. `ldsc` also computes LD Scores.

How Do I Use This?
--------------------

First, you will need to install python as well as the packages listed under the requirements header below. Once you have downloaded all requirements, you can check that you have everything you need by running 
```
$ python ldsc.py -h
```
which will print a list of command-line options. Short tutorials describing the four basic functions of `ldsc` (estimating LD Scores, h2 and partitioned h2, genetic correlation, the LD Score regression intercept) can be found in the [tutorial](tutorial/) subdirectory.

Support
-------

Before contacting us, please try the following:

1. The [tutorials](tutorials/) have basic advice on running `ldsc` and interpreting the output
2. Common issues are described in the [FAQ](docs/FAQ)
2. The methods are described in the papers (citations below)
3. Search the [issue tracker](https://github.com/bulik/ldsc/issues)

Please report bugs on the [issue tracker](https://github.com/bulik/ldsc/issues). 

Citation
--------

If you use the software or the LD Score regression intercept, please cite

Bulik-Sullivan, et al. LD Score Regression Distinguishes Confounding from Polygenicity in Genome-Wide Association Studies.
Nature Genetics, 2015. ([Director's cut](http://biorxiv.org/content/early/2014/02/21/002931))

For genetic correlation, please also cite

Bulik-Sullivan, et al. An Atlas of Genetic Correlations across Human Diseases and Traits. bioRxiv doi: http://dx.doi.org/10.1101/014498

For partitioned heritability, please also cite

Finucane, HK, et al. Partitioning Heritability by Functional Category using GWAS Summary Statistics. bioRxiv doi: http://dx.doi.org/10.1101/014241


Requirements
------------

1. `Python 2.7`
2. `argparse 1.2.1`
3. `bitarray 0.8.1`
4. `numpy 1.8.0`
5. `pandas 0.15.0`
6. `scipy 0.10.1`

License
-------

This project is licensed under GNU GPL v3.


Authors
-------

Brendan Bulik-Sullivan (Broad Institute of MIT and Harvard)

Hilary Finucane (MIT Department of Mathematics)
