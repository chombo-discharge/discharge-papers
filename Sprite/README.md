Publication
-----------

Title: Genesis of column sprites: formation mechanisms and optical structures

Authors: Robert Marskar

DOI: 10.1088/1361-6595/ad29c0
URL: https://iopscience.iop.org/article/10.1088/1361-6595/ad29c0


Simulation information
----------------------

Application: Physics/CdrPlasma/

git hash: 2456b1dd880

Simulation was run on Betzy using up to 25600 CPU cores for about a day, and generated approximately 50 TB of data.

Compilation instructions
------------------------

Compile using

```
make -s DIM=3 OPT=HIGH program
```

and run using

```
mpirun -np<num_cores> program3d.<bunch_of_options>.ex sprite3d.inputs
```



