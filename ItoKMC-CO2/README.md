Publication
-----------

Title: A 3D kinetic Monte Carlo study of streamer discharges in CO2

Authors: Robert Marskar

DOI: ...


Simulation information
----------------------

Application: Physics/ItoKMC/

git hash: 540f105

Simulation was run on Betzy using up to 10,240 CPU cores.
Various variations of the input script was used, such as changing the amount of photoionization.
See corresponding paper for complete details.

Compilation instructions
------------------------

Compile using

```
make -s DIM=3 OPT=HIGH program
```

and run using

```
mpirun -np<num_cores> program3d.<bunch_of_options>.ex simulation.inputs
```

