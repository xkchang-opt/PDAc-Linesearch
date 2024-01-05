Xiaokai Chang, Junfeng Yang, Hongchao Zhang, A convex combination based primal-dual algorithm with linesearch for general convex-concave saddle point problems, 2024.

Using convex combination and linesearch techniques, we introduce a novel primal-dual algorithm for solving structured convex-concave saddle point problems with a generic smooth non-bilinear coupling term. Our adaptive linesearch strategy works under specific local smoothness conditions, allowing for potentially larger stepsizes. For an important class of structured convex optimization problems, the proposed algorithm reduces to a fully adaptive proximal gradient algorithm without linesearch, thereby representing an advancement over the golden ratio algorithm delineated in [Y. Malitsky, Math. Program. 2020].

Our numerical experiments on quadratically constrained quadratic programming and sparse logistic regression problems indicate the new algorithm is significantly faster than the comparison algorithms.

Code for QCQP  in Matlab and for SLR in Python.
