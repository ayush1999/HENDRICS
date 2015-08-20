# MaLTPyNT - Matteo's Libraries and Tools in Python for NuSTAR Timing.

| **Master** | [![Build Status Master](https://travis-ci.org/matteobachetti/MaLTPyNT.svg?branch=master)](https://travis-ci.org/matteobachetti/MaLTPyNT) | [![Coverage Status Master](https://coveralls.io/repos/matteobachetti/MaLTPyNT/badge.svg?branch=master&service=github)](https://coveralls.io/github/matteobachetti/MaLTPyNT?branch=master) | [![Documentation Status Master](https://readthedocs.org/projects/maltpynt/badge/?version=master)](https://readthedocs.org/projects/maltpynt/badge/?version=master) |
| ------------- | ----------- | ------------- | ----------- |
| **Devel** |  [![Build Status Unstable](https://travis-ci.org/matteobachetti/MaLTPyNT.svg?branch=unstable)](https://travis-ci.org/matteobachetti/MaLTPyNT) | [![Coverage Status Unstable](https://coveralls.io/repos/matteobachetti/MaLTPyNT/badge.svg?branch=unstable&service=github)](https://coveralls.io/github/matteobachetti/MaLTPyNT?branch=unstable) | [![Documentation Status](https://readthedocs.org/projects/maltpynt/badge/?version=unstable)](https://readthedocs.org/projects/maltpynt/badge/?version=unstable) |


This software is designed to do correctly and fairly easily a **quick-look timing analysis** of NuSTAR data, treating properly orbital gaps and exploiting the presence of two independent detectors by using the **cospectrum** as a proxy for the power density spectrum (for an explanation of why this is important, look at Bachetti et al., _ApJ_, 800, 109 -[arXiv:1409.3248](http://arxiv.org/abs/1409.3248)). The output of the analysis is a cospectrum, or a power density spectrum, that can be fitted with [Xspec](http://heasarc.gsfc.nasa.gov/xanadu/xspec/) or [Isis](http://space.mit.edu/home/mnowak/isis_vs_xspec/mod.html). Also, one can calculate in the same easy way **time lags** (still under testing, help is welcome).
Despite its main focus on NuSTAR, the software can be used to make standard aperiodic timing analysis on X-ray data from, in principle, any other satellite (for sure XMM-Newton and RXTE).

The **documentation** can be found [here](http://maltpynt.readthedocs.org).

A **tutorial** is also available [here](http://maltpynt.readthedocs.org/en/stable/tutorial.html)
