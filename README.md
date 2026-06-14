<!--
  GitHub profile README for dipanwitabose11.
  Save this file as README.md inside a repository named exactly dipanwitabose11
  (github.com/dipanwitabose11/dipanwitabose11). That special repo renders
  on your profile page.
-->

## Hi, I am Dipanwita Bose

I am a Ph.D. candidate in the Department of Mathematics at the University of Houston,
working with Dr. Bernhard Bodmann. I expect to graduate in August 2026 and I am on
the job market this year.

My research builds operator-theoretic tools to learn the dynamics of continuous-time
Markov chains on graphs from censored data, the hard case where you only observe the
start X(0) and the end X(T) of each path and never the trajectory in between. I care
about two things at once: a rigorous framework with identifiability, stability, and
uncertainty bounds for the generator Q, and algorithms that inherit those guarantees
and still run on real data.

The repositories pinned here are the computational side of that program. They share a
single idea: represent the generator in a basis built from the graph's incidence
Dirac (and Laplacian) structure, regularize so the learned flow follows the network
geometry instead of fighting it, and reconstruct the hidden path segments with Doob
bridges inside an EM loop.

### Projects

These four repositories take the same framework from a fully controlled test case all
the way to noisy real-world data.

| Project | System | What it shows |
|---------|--------|---------------|
| [dirac-logistic-growth](https://github.com/dipanwitabose11/dirac-logistic-growth) | Logistic birth-death CTMC | Clean synthetic validation with known parameters |
| [dirac-predator-prey](https://github.com/dipanwitabose11/dirac-predator-prey) | Algae and rotifer ecology | Real data, Doob and Schrodinger bridges, error bounds |
| [dirac-rotational-vector-field](https://github.com/dipanwitabose11/dirac-rotational-vector-field) | The field b(x,y) = (-y, x) | Analytic ground truth, recovery to machine precision |
| [dirac-yellow-cab-dynamics](https://github.com/dipanwitabose11/dirac-yellow-cab-dynamics) | NYC yellow taxi, 30 zones | Real mobility data with no known generator |

The predator-prey and yellow taxi studies feed directly into a paper I am preparing,
"Inferring hidden trajectories in endpoint-only Markov jump processes: regularized
likelihood with applications to the NYC yellow taxi graph and predator-prey model."

### What I work with

Time-frequency and harmonic analysis, functional analysis and operator algebras,
probability and Bayesian statistics, dynamical systems and ODEs, optimization, and
numerical analysis. On the computational side I mostly use Python with NumPy, SciPy,
pandas, NetworkX, scikit-learn, Matplotlib, and Jupyter.

### Outside the math

When I am not working I am usually painting, stargazing, swimming, or playing
badminton. I also love teaching and any excuse to get someone else excited about
mathematics.

### Reach me

Email: dbose2@cougarnet.uh.edu
Website: https://sites.google.com/view/dipanwita-bose/home
Office: PGH 609, University of Houston
