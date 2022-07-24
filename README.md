# OrdinalMultinomialModels

| **Documentation** | **Build Status** | **Code Coverage**  |
|-------------------|------------------|--------------------|
| [![](https://img.shields.io/badge/docs-stable-blue.svg)](https://OpenMendel.github.io/OrdinalMultinomialModels.jl/stable) [![](https://img.shields.io/badge/docs-latest-blue.svg)](https://OpenMendel.github.io/OrdinalMultinomialModels.jl/latest) | [![Build Status](https://travis-ci.org/OpenMendel/OrdinalMultinomialModels.jl.svg?branch=master)](https://travis-ci.org/OpenMendel/OrdinalMultinomialModels.jl) [![Build status](https://ci.appveyor.com/api/projects/status/mj6mk3s8or9nb5oq/branch/master?svg=true)](https://ci.appveyor.com/project/Hua-Zhou/ordinalmultinomialmodels-jl/branch/master) | [![Coverage Status](https://coveralls.io/repos/github/OpenMendel/OrdinalMultinomialModels.jl/badge.svg?branch=master)](https://coveralls.io/github/OpenMendel/OrdinalMultinomialModels.jl?branch=master) [![codecov](https://codecov.io/gh/OpenMendel/OrdinalMultinomialModels.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/OpenMendel/OrdinalMultinomialModels.jl) |  


OrdinalMultinomialModels.jl provides Julia utilities to fit ordered multinomial models, including [proportional odds model](https://en.wikipedia.org/wiki/Ordered_logit) and [ordered Probit model](https://en.wikipedia.org/wiki/Ordered_probit) as special cases. 

OrdinalMultinomialModels.jl supports Julia v0.7 and later. See documentation for installation and usage.  
[![](https://img.shields.io/badge/docs-stable-blue.svg)](https://OpenMendel.github.io/OrdinalMultinomialModels.jl/stable) [![](https://img.shields.io/badge/docs-latest-blue.svg)](https://OpenMendel.github.io/OrdinalMultinomialModels.jl/latest)


This package is registered in the default Julia package registry, and can be installed through standard package installation procedure: e.g., running the following code in Julia REPL.
```julia
using Pkg
pkg"add OrdinalMultinomialModels"
```


## Citation

If you use [OpenMendel](https://openmendel.github.io) analysis packages in your research, please cite the following reference in the resulting publications:

*Zhou H, Sinsheimer JS, Bates DM, Chu BB, German CA, Ji SS, Keys KL, Kim J, Ko S, Mosher GD, Papp JC, Sobel EM, Zhai J, Zhou JJ, Lange K. OPENMENDEL: a cooperative programming project for statistical genetics. Hum Genet. 2020 Jan;139(1):61-71. doi: 10.1007/s00439-019-02001-z. Epub 2019 Mar 26. PMID: 30915546; PMCID: [PMC6763373](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6763373/).*

### Acknowledgments

This project has been supported by the National Institutes of Health under awards R01GM053275, R01HG006139, R25GM103774, and 1R25HG011845.
