# CBIOMES-global

[![DOI](https://zenodo.org/badge/134205999.svg)](https://zenodo.org/badge/latestdoi/134205999)
[![Documentation Status](https://readthedocs.org/projects/cbiomes/badge/?version=latest)](https://cbiomes.readthedocs.io/en/latest/?badge=latest)

**Content:**

This repository contains the model configuration ([code/](code/), [input/](input/)) and documentation ([readthedocs](http://cbiomes.readthedocs.io/en/latest/)) that allow users to recompute or analyze CBIOMES-global solutions.

<!--- via on-premise cluster or via Amazon Web Services (see [example_scripts/](example_scripts/)). --->

<!--- **Citation for this repository:** --->

<!--- [![DOI](https://zenodo.org/badge/76184688.svg)](https://zenodo.org/badge/latestdoi/76184688) --->

[MIT general circulation model]: https://mitgcm.readthedocs.io/en/latest/
[Darwin Project model]: http://darwinproject.mit.edu/
[Amazon Web Services' cfncluster]: https://aws.amazon.com/hpc/cfncluster/
[gcmfaces]: http://gcmfaces.readthedocs.io/en/latest/
[MITprof]: https://github.com/gaelforget/MITprof

**CBIOMES-global (alpha version):** 

CBIOMES-global (alpha version) is a global ocean state estimate that covers the period from 1992 to 2011. It is based on Forget et al 2015 for ocean physics [MIT general circulation model][] and on Dutkiewicz et al 2015 for marine biogeochemistry and ecosystems [Darwin Project model][]. On the native model grid, it can be analyzed and manipulated using the [gcmfaces][] and [MITprof][] toolboxes. Interpolated fields in netcdf format are also available.

**References:**

Forget, G., J.-M. Campin, P. Heimbach, C. N. Hill, R. M. Ponte, and C. Wunsch, 2015: ECCO version 4: an integrated framework for non-linear inverse modeling and global ocean state estimation. Geoscientific Model Development, 8, 3071-3104, <http://dx.doi.org/10.5194/gmd-8-3071-2015> or [this URL](http://www.geosci-model-dev.net/8/3071/2015/)

Dutkiewicz, S., A.E. Hickman, O. Jahn, W.W. Gregg, C.B. Mouw, and M.J. Follows, 2015: Capturing optically important constituents and properties in a marine biogeochemical and ecosystem model. Biogeoscience, 12, 4447-4481, <http://dx.doi.org/10.5194/bg-12-4447-2015> or [this URL](https://www.biogeosciences.net/12/4447/2015/)
