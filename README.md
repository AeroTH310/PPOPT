<p>
<h1>
<img valign="middle" src="mp_plot.png" height="50" height="50" alt="PPOPT_LOGO"/></a>
PPOPT
</h1>
</p>

**P**ython **P**arametric **OP**timization **T**oolbox (**PPOPT**) is a software platform for solving and manipulating multiparametric programs in Python. This package is still in development but the following features are complete and are in full working order.

#### Completed Features
* Solver interface for mpLPs and mpQP with the following algorithms
  1. Serial and Parallel Combinatorial Algorithm
  2. Serial and Parallel Geometrical Algorithm
  3.  Serial and Parallel Graph based algorithm
* Multiparametric solution export to C++, Javacript, Matlab, and Python
* Plotting utilities
* Presolver and Conditioning for Multiparametric Programs

## Key Applications

* Explicit Model Predictive Control
* Multilevel Optimization 
* Integrated Design, Control, and Scheduling
* Robust Optimization

For more information about Multiparametric programming and it's applications, [this paper](https://www.frontiersin.org/articles/10.3389/fceng.2020.620168/full) is a good jumping point.

## Installation

Currently PPOPT requires Python 3.7 or higher and can be installed with the following commands.

```bash
pip install -e git+https://github.com/mmihaltz/pysettrie.git#egg=pysettrie
pip install git+https://github.com/TamuParametric/ppopt.git#egg=ppopt
```
