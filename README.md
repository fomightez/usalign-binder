# usalign-binder

[![Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fomightez/usalign-binder/master?urlpath=lab/tree/index.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run command line-based [US-align](https://zhanggroup.org/US-align/) inside your browser.



------

[US-align](https://zhanggroup.org/US-align/)

>"US-align (Universal Structural alignment) is a unified protocol to compare 3D structures of different macromolecules (proteins, RNAs and DNAs) in different forms (monomers, oligomers and heterocomplexes) for both pairwise and multiple structure alignments. The core alogrithm of US-align is extended from TM-align and generates optimal structural alignments by maximizing TM-score of compared strucures through heuristic dynamic programming iterations. "

Because [the tm-align github page](https://github.com/kad-ecoli/TMalign) says:

>"This repo is outdated. Please use https://github.com/pylelab/USalign instead "

-------

Software
--------

The US-align software will be installed already in each active session launched from this repo. The US-align software is available directly from the authors at <a href="https://zhanggroup.org/US-align/">US-align (Universal Structural alignment) page at the Zhang Labhttps://anaconda.org/bioconda/tmalign  .

The US-align software is described in [this scientific article](https://pubmed.ncbi.nlm.nih.gov/36038728/).

Users should cite:

US-align: Universal Structure Alignment of Proteins, Nucleic Acids and Macromolecular Complexes.    
Chengxin Zhang, Morgan Shine, Anna Marie Pyle, Yang Zhang.   
Nature Methods, 19: 1109-1115 (2022)  [PMID: 36038728](https://pubmed.ncbi.nlm.nih.gov/36038728/)

The license information for the software is available [on the USalign GitHub Repository page](https://github.com/pylelab/USalign/blob/master/LICENSE).

***Clarifying Software Attribution: I, Wayne, am not involved in the US-algn or TM-align software at all. Those listed above are the developers and distributors of US-align and TM-align. See their materials. I simply set up this repository to make the software useable on the command line without installation headaches.***

I, Wayne, did code a Python-based utility for use with the results from command line US-align/TM-align; it is available [here](https://github.com/fomightez/sequencework/tree/master/tmalign-utilities/) and utilized in the notebooks in this repository to process the results and allow easily converting the results to other forms.

Usage
-----

This repository is set up to allow running the command line-based version of US-alig (evolved form of TM-align) after pressing the `launch binder` button above or below.  

The target use case is when you want to run structural alignments with several structures and can more quickly do it on the command line or with stitching together the pipeline in Python to make it easier. The Jupyter interface with the software already present makes a great environment for developing such approaces.  

In the notebooks that can be launched, I have added some examples illustrating how to use the program and process the data further to make images in PyMOL programmatically.


Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.


----
