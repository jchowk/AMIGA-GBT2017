This repository contains the paper and data relevant to Howk et al. (2017):
_"Project AMIGA: A Minimal Covering Factor for Optically Thick Circumgalactic Gas Around the Andromeda Galaxy"_.

The paper is currently available via the arxiv: [Howk et al. 2017, arXiv:1706.01893](https://arxiv.org/abs/1706.01893).

*Contents*

The contents should be pretty self-evident:

* `Paper/` -- Figures and Latex files associated with the paper itself. The main Latex file is `coveringFactor.tex`.

* `Data/` -- Directory holding the data. This includes:

  * `pointing_list.dat` -- information on the pointing directions and their characteristics (similar to Table 1 of Howk et al. 2017).
  * `AMIGA-GBT_final.fits` -- HI 21-cm data for all of the sight lines in the _GBTIDL_ FITS format. Please see the documentation for [_GBTIDL_](http://gbtidl.nrao.edu) if you wish to use this file.
  * `*_GBT.dat` -- ASCII files of T_b[K] vs. v_LSR[km/s] for each sight line described in the paper.
