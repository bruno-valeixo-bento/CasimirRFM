# CasimirRFM

**CasimirRFM** is a Mathematica (Wolfram Language) package for studying of compactifications on Riemann-flat manifolds (RFMs) and computating one-loop Casimir energies in higher-dimensional field theories and supergravity models. The package provides tools for:

- constructing and analysing finite groups defining Riemann-flat manifolds;
- computing invariant metrics, cohomology forms, and compatible spin structures;
- evaluating lattice sums efficiently using Ewald summation;
- computing Casimir potentials and local Casimir energy densities; 
- evaluating group-element traces in the graviton, p-form, spinor, and Rarita–Schwinger representations.

The repository contains the package file `CasimirRFM.wl`, a template notebook with examples for all functions `CasimirRFM-Template.nb`, and detailed documentation `CasimirRFM.pdf`.

## Requirements

- Wolfram Mathematica 13.0 or later

## Installation

Download `CasimirRFM.wl` and place it in:

```text
$UserBaseDirectory/Applications/CasimirRFM/
```

The package can be loaded in a Mathematica notebook with:

```wolfram
<< CasimirRFM`
```

For parallel computations, launch the available kernels and load the package on each kernel with:

```wolfram
LaunchKernels[];
ParallelEvaluate[<< CasimirRFM`];
DistributedContexts = None;
```

## Documentation

Detailed documentation is provided in the accompanying package paper.

The repository also includes `CasimirRFM-Template.nb`, which contains descriptions and examples of the package's public functions.

## License

**CasimirRFM** is distributed under the LICENSE.

## Citation

If you use **CasimirRFM** in scientific work, please cite:

> B. Valeixo Bento,  
> *CasimirRFM: A Mathematica package for Riemann-flat compactifications with Casimir energies* (2026).

Please also cite the accompanying methodology paper:

> B. Valeixo Bento and M. Montero,  
> *An M-theory dS maximum from Casimir energies on Riemann-flat manifolds*,  
> JHEP **01** (2026) 099,  
> https://arxiv.org/abs/2507.02037.

## Author

**Bruno Valeixo Bento**

For questions, bug reports, or feature requests, please use the repository's issue tracker.
