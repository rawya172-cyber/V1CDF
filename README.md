
Asymmetry in Spacing Statistics of Real and Imaginary Crossings of the Riemann Zeta Function


Abstract

We investigate the local spacing statistics of crossing points of the Riemann zeta function along the critical line, distinguishing between zeros of the real and imaginary parts of ζ(1/2 + it). Using numerical computations up to T = 200, we extract crossing sequences and analyze their normalized nearest-neighbor spacings.

Kolmogorov–Smirnov (KS) tests show that real crossings are closer to Poisson statistics (KS ≈ 0.131) than to GUE-type predictions (KS ≈ 0.361), while imaginary crossings exhibit the opposite trend, being closer to GUE (KS ≈ 0.178) than to Poisson (KS ≈ 0.269).

Anderson–Darling (AD) statistics further support this asymmetry: real crossings show moderate deviation from Poisson behavior (AD ≈ 3.44), whereas imaginary crossings exhibit strong deviation (AD ≈ 21.82), indicating significant suppression of small spacings.

The distinction is most pronounced in the small-spacing regime and appears stable across increasing ranges. These findings suggest a structural difference between the real and imaginary components of ζ(1/2 + it), reflected in their spacing statistics.


1. Introduction

The statistical properties of the nontrivial zeros of the Riemann zeta function have been extensively studied and are known to exhibit strong connections with random matrix theory, particularly the Gaussian Unitary Ensemble (GUE). Classical results, beginning with Montgomery’s pair correlation conjecture and supported by extensive computations by Odlyzko, indicate that zeros of ζ(1/2 + it) display level repulsion consistent with GUE statistics.

In this work, we examine a related but distinct object: the spacing distribution of points where either the real or imaginary part of ζ(1/2 + it) vanishes. While zeros correspond to simultaneous vanishing of both components, the individual crossing sequences of the real and imaginary parts have received comparatively little attention.

Our goal is to investigate whether these crossing sequences exhibit statistical behavior similar to that of the zeros, and whether differences between them reveal structural features of the zeta function.


2. Methodology

We numerically evaluate ζ(1/2 + it) along the critical line and detect crossing points of the real and imaginary parts using sign changes combined with root-finding methods.

Let {t_n} denote the sequence of crossings. We define the nearest-neighbor spacing as:

s = (t_{n+1} − t_n) * log(t_n) / (2π)

and normalize all spacings to have unit mean.

We emphasize that this normalization is borrowed from the theory of zeta zeros, where it is justified by the asymptotic density of zeros. Its application to crossing sequences is heuristic and does not currently have a rigorous theoretical justification.

We compare empirical spacing distributions with:

Poisson statistics (uncorrelated spacings)
GUE-type statistics (level repulsion)
using:

Kolmogorov–Smirnov (KS) test
Anderson–Darling (AD) test (with respect to Poisson behavior)

3. Results

3.1 Sample Sizes

At T = 150:

Real crossings: 104
Imaginary crossings: 106
At T = 200:

Real crossings: 157
Imaginary crossings: 158

3.2 Kolmogorov–Smirnov Statistics

At T = 200:

Real crossings:
KS vs Poisson ≈ 0.131
KS vs GUE ≈ 0.361
Imaginary crossings:
KS vs Poisson ≈ 0.269
KS vs GUE ≈ 0.178
These results indicate that real crossings are closer to Poisson behavior, while imaginary crossings are closer to GUE-type statistics.


3.3 Anderson–Darling Statistics

At T = 200:

Real crossings:
AD vs Poisson ≈ 3.44
Imaginary crossings:
AD vs Poisson ≈ 21.82
The large AD value for imaginary crossings indicates strong deviation from Poisson behavior, consistent with significant suppression of small spacings.


3.4 Distribution Behavior

Empirical cumulative distribution functions (CDFs) show that:

Real crossings allow a relatively large number of small spacings
Imaginary crossings strongly suppress small spacings
The difference is most pronounced in the region s < 0.5.


4. Discussion

The results reveal a clear asymmetry between real and imaginary crossings.

Imaginary crossings exhibit strong level repulsion and deviate significantly from Poisson statistics. This behavior is qualitatively consistent with GUE-type statistics, though not in exact quantitative agreement.

In contrast, real crossings lie in an intermediate regime: they are closer to Poisson behavior but do not fully match it, indicating the presence of weak correlations.

A natural interpretation can be based on the representation:

ζ(1/2 + it) = R(t) * exp(i θ(t))

Imaginary crossings are more directly associated with phase alignment (θ(t) ≈ kπ), while real crossings involve a phase shift and may be more sensitive to amplitude fluctuations. This difference may explain the stronger rigidity observed in imaginary crossings.

We stress that the observed agreement with GUE is qualitative rather than exact, and the results should be interpreted as numerical evidence rather than a rigorous characterization.


5. Limitations

Several limitations must be noted:

The data range (T ≤ 200) is relatively small compared to large-scale computations in the literature.
The normalization used is heuristic and not theoretically justified for crossing sequences.
No error analysis (e.g., bootstrap or confidence intervals) is included.
The extraction of crossings depends on numerical resolution and root-finding accuracy.
These limitations suggest that further work is required before drawing stronger conclusions.


6. Conclusion

We have demonstrated a consistent asymmetry in the spacing statistics of real and imaginary crossings of the Riemann zeta function.

Imaginary crossings exhibit stronger level repulsion and significant deviation from Poisson statistics, while real crossings remain closer to weakly correlated behavior.

The effect appears stable across increasing ranges and is most pronounced in the small-spacing regime.

These findings provide numerical evidence for a structural difference between the real and imaginary components of ζ(1/2 + it), though further theoretical and computational investigation is needed.


References

Montgomery, H. L. (1973). The pair correlation of zeros of the zeta function.

Odlyzko, A. M. (1987). On the distribution of spacings between zeros of the zeta function.

Mehta, M. L. (2004). Random Matrices.

