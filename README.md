### Market Mechanisms as Convex Optimization problems

These notebooks demonstrate some basic implementations of market mechanisms using a convex optimization framework. The implementations are formulated as [Disciplined Convex Programming](http://dcp.stanford.edu/home) problems, and solved with the [splitting conic solver](https://github.com/cvxgrp/scs).

The [cpcam.ipynb](https://github.com/cdetrio/convex-market-mechanisms/blob/master/cpcam.ipynb) notebook implements a Convex Parimutuel Call Auction Mechanism (CPCAM). The [lmsr-convex-max-entropy.ipynb](https://github.com/cdetrio/convex-market-mechanisms/blob/master/lmsr-convex-max-entropy.ipynb) notebook implements the Logarithmic Market Scoring Rule (LMSR) as a convex optimization problem. The [LCMM-olympic-medals-example.ipynb](https://github.com/cdetrio/convex-market-mechanisms/blob/master/LCMM-olympic-medals-example.ipynb) notebook implements a Linearly-Constrained Market Maker (LCMM).

These notebooks are a follow-up to my paper [Smart Markets for Stablecoins](http://github.com/cdetrio/smart-markets/).
