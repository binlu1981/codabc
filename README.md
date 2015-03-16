The package CodABC is computer framework to coestimate Recombination, Substitution and Molecular Adaptation (dN/dS) rates by approximate Bayesian computation from coding sequence alignments. The tool is based on a special version of the coalescent simulator CoalEvol that implements recombination (including intracodon recombination), a variety of migration models, demographics and user-specified populations/species trees. A total of 26 summary statistics can be computed from the coding alignments collecting information at all nucleotide, codon and amino acid levels. Then, CodABC can coestimate the three different parameters under approximate Bayesian computation (ABC) through rejection and regression methods. Thus, for example the tool can estimate dN/dS (nonsynonymous synonymous ratio rate) with the consideration of recombination and vice versa. In addition, the tool have already shown more accurate estimations of recombination than the commonly used likelihood-based methods.

The package is implemented in C, perl and R and can run on Linux and Mac OS and it includes a graphical user interface written in Java. Conveniently the simulations can, optionally, run in parallel on a user-specified number of processors.

Arenas, M.; Lopes, J.S.; Beaumont, M.A. and Posada, D. 2015. CodABC: A Computational Framework to Coestimate Recombination, Substitution and Molecular Adaptation rates by approximate Bayesian computation. Molecular Biology and Evolution. In press.
