This project demonstrates multivariate classification using neuromorphic hardware, 
in this case the SpiNNaker hardware platform [1].
The classifier neural model design is based on that published in [2,3] which is a 
bio-inspired design based on the insect olfactory system.

The core requirements to run these programs is Python 2.7 and a SpiNNaker board with 
the accompanying software suite made available from MAnchester Universtiy;
The work is demonstrated here in a series of Python/PynNN/sPyNNaker experiments of 
increasing complexity/difficulty.
In all these experiments, for those unable to run the program themselves, screenshot(s) of the 
relevant raster plots are made available in the "screenshots" subdirectory.

EXPERIMENT 1
This experiment demonstrates a basic ability to use synapse plasticity to learn to 
classify ("recognise") 10 digits taken from the standard MNIST dataset.

ACKNOWLEDGEMENTS
This work is supported by a grant from the Human Brain Project (HBP).
The SpiNNaker hardware platform is developed at Manchester University who supplied the board and software suite used in this work. 

CITING THIS WORK
To cite the work in this project please contact one of the Github collaborators based at the University of Sussex.

REFERENCES

[1] A. Diamond, T. Nowotny and M. Schmuker, "Comparing neuromorphic solutions in action: 
implementing a bio-inspired solution to a benchmark classification task on three parallel-computing platforms" in
Frontiers in Neuromorphic Engineering, 2016, Vol 9, No. 00491 doi:10.3389/fnins.2015.00491

[2] M. M. Khan, D. R. Lester, L. A. Plana, A. Rast, X. Jin, E. Painkras, and
S. B. Furber, “SpiNNaker: Mapping neural networks onto a massively-
parallel chip multiprocessor,” in Proceedings of the International Joint
Conference on Neural Networks, 2008, pp. 2849–2856

[3] M. Schmuker, T. Pfeil, and M. Nawrot, “A neuromorphic network for
generic multivariate data classification,” Proc. Natl. Acad. Sci., pp. 1–6,
Jan. 2014.

[4] A. Diamond, M. Schmuker, A.Z. Berna, S.Trowell and T. Nowotny
"Classifying chemical sensor data using GPU-accelerated bio-mimetic neuronal networks 
based on the insect olfactory system", BMC Neuroscience 2014, 15(Suppl 1):P77  
doi:10.1186/1471-2202-15-S1-P77


