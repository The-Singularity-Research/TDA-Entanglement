# TDA-Entanglement
---
## A project using persistent homology to study the structure of entanglement
---
Reference [Entanglement-Distance](https://github.com/The-Singularity-Research/Entanglement-Distance). 
As an application of the theory developed thus far we propose a way of defining a Hamilton-
ian Ansatz for arbitrary materials by defining a multiscale, multiparameter Hamiltonian Ansatz
for an arbitrary material via persistence homology given by a dynamic DB-Scan algorithm re-
lated to a proposal presented in [WXZ] and [AJLMWX]. This method will work for a useful
scale-dependent definition of a Hamiltonian and a definition of entanglement that can be ad-
justed for emergent topological, structural, and dynamic patterns, properties, and features of the
material at different scales. We can also use varying frequencies of light for ”measurements”
(i.e. entanglement of the object generating the light with the material to be studied via operators
corresponding to electromagnetic radiation, represented by an interaction Hamiltonian). Defin-
ing a multi-frequency Hamiltonian provides additional adjustable parameters and for each fixed
value of this frequency parameter we may perform the persistent homology analysis. This will
give an ”energy-scale” parameter for our topological analysis. Having ”energy scale windows”
will be useful in analyzing phase transitions in topologically ordered materials in materials sci-
ence and condensed matter. We may study interesting materials such as ”solid hydrogen” using
these methods and provide quantum circuits that reproduce such materials given a precursor
material with a Hamiltonian within a certain error range determined by the material and target
properties to be achieved (for example transforming a gas to a solid). Since information the-
oretically any such process can be written as a (hybrid qudit) quantum circuit with potentially
modified entanglement (to include p-adic physics), exotic materials such as solid state hydrogen
can be achieved. The physical consequences of constructing such a material are conjectural and
likely context dependent. Proceed at your own risk.

The Reverse Direction: Using Entanglement to Model Distance, Multiscale
Topological Structures, and Emergent Space-Time
---
Using arbitrary controlled-U gates in place of controlled-X (CNOT) gates to entangle qubits
we get a more complex variety of entangled states. If we also allow the controlled-U gates
to be dynamic (learnable parameters in a uantum neural network) we can make entanglement
between qudits a dynamic parameter.
This parameter can be interpreted as a form of distance between qudits. Using energy level
of qudits as a second parameter and using a dynamic DB-scan with these two parameters gives
a way of computing 2-parameter persistent homology. The persistent homology allows us to
understand emergent geometric and topological properties of the quantum system.
We can define maps between surface code states that model conformal maps of conformal
field theories on some Riemann surface. The idea is to think of the surface code (corresponding
to the gentle surface algebra) as a bundle of operators over a Riemann surface. A conformal
map of Riemann surfaces with a conformal field theory correspond to a map of bundles, which
should be defined by some local qudit gates or a generalized version of qudit gates according to
surface algebra theory.

## To-Do:
---
1. Modify [DB-scan](https://scikit-learn.org/stable/auto_examples/cluster/plot_dbscan.html#sphx-glr-auto-examples-cluster-plot-dbscan-py)
for two parammemeters rather than one, or use [Rivet](https://rivet.readthedocs.io/en/latest/about.html)

2. Reference [Entanglement-Distance](https://github.com/The-Singularity-Research/Entanglement-Distance) to use
as a distance metric for persistent homology. 

## Resources
---
-[Topological Analysis of Syntactic Structures](https://github.com/The-Singularity-Research/TDA-Entanglement/blob/main/1903.05181.pdf)

-[Persistent Homology of Syntax](https://github.com/The-Singularity-Research/TDA-Entanglement/blob/main/PersistentTopologySyntax.pdf)

-[Persistent Homology Tutorial for R](https://cran.r-project.org/web/packages/TDA/vignettes/article.pdf)

-[Persistent Homology in R](https://cran.r-project.org/web/packages/TDA/vignettes/article.pdf)

-[Giotto-TDA](https://giotto-ai.github.io/gtda-docs/0.5.1/library.html)

-[Gravitational Wave Detection](https://giotto-ai.github.io/gtda-docs/0.5.1/notebooks/gravitational_waves_detection.html#) (transform gravitational waves into conformal mappings in an AdS/CFT type correspondence after reduction from Minkowski spacetime in $\mathbb{R}^{3+1}$ to a conformal region in one complex spacial dimension and one time dimension, and then into quantum gates via [conformal-gates](https://github.com/The-Singularity-Research/conformal-gates)



