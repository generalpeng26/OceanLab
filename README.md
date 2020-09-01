# OceanLab

Package of Python scripts for Oceanography  (Python 3.6)

## Synopsis

This lib was made by **Iury T. Simoes-Sousa** (<mailto:simoesiury@gmail.com>).

Now this package have this subpackages below:

- **OA**
- **DYN**
- **EOF**

## Code Example

TODO*

## Installation

`pip install oceanlab`


## Documentation

- **OA**
  - *vectoa()*: Objective analysis for vectorial fields (Adaption on Filipe Fernandes function);
  - *scaloa()*: Objective analysis for scalar fields;
  - *Functions to calculate the correlation length*;
- **DYN**
  - *dyn_amp()*: Makes the projection of every dynamical mode to velocity to obtain its amplitude;
  - *zeta()*: Calculates the vorticity field by velocity field;
  - *psi2uv()*: Calculates the velocity field by stream function scalar field;
  - *eqmodes()*: Calculates the equatorial dynamical pressure and vertical velocity modes;
- **EOF**
  - *eoft()*: Calculates the Empirical Orthogonal Functions;
  - *my_eof_interp()*: Fillgaps on matrix based on EOFs (translated by Cesar Rocha Matlab version);

## Contributors

Everyone can contribute to this code. Some of functions was based on Filipe Fernandes or Cesar Rocha functions and some of them was created with help of Hélio Almeida and Wandrey Watanabe at Laboratório de Dinâmica Oceânica of University of São Paulo (USP).