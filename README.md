# Multiomics paper repo


We present a set of tools that, combined, provide the ability to store, visualize and leverage multiomics data to predict the outcome of bioengineering efforts. 

We show how to use: 
- [**ICE**](https://github.com/JBEI/ice) to store strain information
- [**OMG**](https://github.com/JBEI/OMG) to generate a mock dataset of omics data  
- [**EDD**](https://github.com/JBEI/EDD) to store experiment data and metadata
- [**ART**](https://github.com/JBEI/ART) to leverage these data to suggest new experiments that improve isoprenol production. 

By combining these tools with **Jupyter notebooks** we show how to pinpoint genetic modifications that improve production of  isoprenol, a potential biofuel, in a simulated data set. We expect the same procedures to be applicable in the case of real experimental data. 

- [Requirements](#requirements)
- [Installation Guide](#installation-guide)
- [Instructions for use](#instructions-for-use)
- [Reference](#reference)
- [License](#license)


## Requirements

Provided notebooks run on two different Jupyter lab kernels, for which we provide a set of requirements in the [`kernel_requirements`](https://github.com/AgileBioFoundry/multiomicspaper/tree/master/kernel_requirements) directory.

Running the notebooks requires the [ART](https://github.com/JBEI/ART) and [OMG](https://github.com/JBEI/OMG) libraries. In addition, OMG relies on a commercial package [CPLEX](https://www.ibm.com/products/ilog-cplex-optimization-studio?), for which academic licenses are available. 
Academic and commercial [licenses](https://github.com/JBEI/ART#license) for ART are available upon request.

## Installation Guide

Clone this repository to your local machine:

`git clone https://github.com/AgileBioFoundry/multiomicspaper.git`

## Instructions for use

Step-by-step instructions for guiding metabolic engineering via multiomics data and machine learning using a set of  [`notebooks`](https://github.com/AgileBioFoundry/multiomicspaper/tree/master/notebooks)  and screencasts are provided [here](https://sites.google.com/lbl.gov/esedataautomation/data-analysis/multiomics-tutorial?authuser=0).

## Reference

[Roy S., Radivojević T. et al., Multiomics Data Collection, Visualization, and Utilization for Guiding Metabolic Engineering, Front. Bioeng. Biotechnol. (2021)](https://www.frontiersin.org/articles/10.3389/fbioe.2021.612893/full)

## License

Code from this repository is available under the [BSD-3-Clause-LBNL license](https://github.com/AgileBioFoundry/multiomicspaper/blob/master/LICENSE.txt).

## Copyright Notice

Omics Mock Generator Library (OMG) Copyright (c) 2021, The 
Regents of the University of California, through Lawrence 
Berkeley National Laboratory (subject to receipt of any required 
approvals from the U.S. Dept. of Energy). All rights reserved.If you have questions about your rights to use or distribute this software,
please contact Berkeley Lab's Intellectual Property Office at
IPO@lbl.gov.

NOTICE.  This Software was developed under funding from the U.S. Department
of Energy and the U.S. Government consequently retains certain rights.  As
such, the U.S. Government has been granted for itself and others acting on
its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the
Software to reproduce, distribute copies to the public, prepare derivative 
works, and perform publicly and display publicly, and to permit others to do so.


