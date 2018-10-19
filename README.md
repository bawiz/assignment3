# assignment3
Scientific programming course. Assignment 3 parallel computing

Copywright This project is part of Scientific programming assignment developed by authors below which is released under MIT license. © 2011 Dara Akdag All Rights Reserved

# Authors list
Dara Sevkan Akdag. 
Maastricht university Systems Biology M.Sc. 

# Compile and execution suggestions
The jupyter notebook can be executed in your web browser after jupyter notebook has been succesfully installed. Installation guide can be found at: http://jupyter.org/install
The kernel used to execute the notebook is based on an anaconda distribution of python 3. 
Anaconda is a package handler which is great for installing libraries. https://conda.io/docs/user-guide/install/index.html# 

# Data
The descriptors matrix was computed based on variables from PubChemAid 624202. The study is called "QHTS Assay To Identify Small Molecule Activators Of BRCA1 Expression". Reference:
National Center for Biotechnology Information. PubChem BioAssay Database; AID=624202, https://pubchem.ncbi.nlm.nih.gov/bioassay/624202 (accessed Oct. 19, 2018).

The smiles data files can be downloaded on the link above as well. More details are available in the jupyter notebook

# Expected output
The expected output can be viewed the the jupyter notebook which is uploaded. 
Depending on the amount of cores available on your computer you will have to run the runParallelProcessing method with a number that does not exceed the cores in your computer. Python usually splits each core into two so if you have a quad core processer it will show 8 cores available. Apart from that the multiprocessing module also utilises threading. Each core runs 4 threads. Thus if the descriptors where calculated with only one thread, you would have different times. 

# Libraries
Pandas http://pandas.pydata.org/pandas-docs/stable/api.html
Numpy  http://www.numpy.org/
Rdkit  https://www.rdkit.org/docs/GettingStartedInPython.html
Matplotlib https://matplotlib.org/
Multiprocessing https://docs.python.org/2/library/multiprocessing.html

