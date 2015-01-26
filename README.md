# RandomTestMatrices

A small module providing random test matrices. These are for testing and debugging purposes, for random matrix ensembles with known limiting distributions, see the package RandomMatrices.jl . 

randsym(d)
	Gaussian random symmetric matrix of dimension ``d``.

randantisym(d)
    Gaussian antisymmetric matrix

randposdef(d, n = d)
	Random positive definite matrix of dimension ``d`` from the Laguerre ensemble ``n``. 

randstable(d)
	Random stable matrix (matrix with eigenvalues with negative real part) with dimension ``d``.

randunitary(d)
	Random unitary matrix of dimension ``d``.

randorth(d)
	Orthogonal matrix drawn according to the Haar measure on the group of orthogonal matrices.

randnormal(d) 
	Random normal matrix of dimension ``d``.



