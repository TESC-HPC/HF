.. Hirsch-Fye documentation master file, created by
   sphinx-quickstart on Thu Mar  6 08:51:55 2014.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Code Overview
==============

.. toctree::
   :maxdepth: 2

Code Overview

DCA-HFQMC is a massively parallel (MPI+OpenMP) Fortran code originally built 
by Mark Jarrell and his collaborators at University of Cincinnati. 
The code can be used to solve the Hubbard model for 1D, 2D and 3D cases
at different fillings. And it can be easily adapted to simulate the 
Anderson lattice model. The code focuses on the square lattice where
the so-called Betts clusters in addition to the usual cubic clusters
are used. It should be straightforward to generalize to the triangular
or honeycomb lattices. 

To speed up the computation within the nowadays high-performance hardware
structure, parts of the code have being rewritten in cuda.

