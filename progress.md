---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Course progress
permalink: /teaching2025fall_progress.html
---

<style>
  #main {
    font-size: 85%; /* Adjust this percentage as you like */
  }
</style>

This is a not very detailed record on what happened in each course meeting. There should be course recordings in [北大教学网](https://course.pku.edu.cn).

### Sep 08

We discussed the definition of Teichmuller space, and the differentiable structure of $\mathrm{Teich}(T^2)$. 

Reference: [FM], pages 263-269. 


### Sep 10

We discussed the *algebraic topology* of $\mathrm{Teich}(S_g)$, by identifying it with $\mathrm{DF}(\pi_1(S_g),PSL(2,\mathbb R))/PGL(2,\mathbb R)$.

Then we show that $\mathrm{Teich}(S_0^3)\cong\mathbb R^3_+$, by considering the lengths of the three boundaries.

Any closed surface can be decomposed into pairs of pants. We defined twisting parameters using *seams*. 

Reference: [FM], pages 269-282.

### Sep 15

We discussed Fenchel-Nielson coordinates for Teichmuller space, and in particular, showed that $\mathrm{Teich}(S_g)\cong \mathbb R^{3g-3}_+\times \mathbb R^{3g-3}$.

Teichmuller space can be regarded as the space of *marked* hyperbolic surfaces, or as the space of *marked* complex structures. We introduced quasi-conformal maps, and stated Teichmuller's result on the Teichmuller metric using quasi-conformal maps.

Reference: [FM], pages 282-287, 294-300.

### Sep 22

We discussed *measured foliations* and *quadratic differentials* $\mathrm{QD}(X)$ on a Riemann surface, possibly bordered and punctured. These two concepts are closed related and essentially equivalent. We defined Teichmuller mappings based on the definition of quadratic differentials. We also computed $\mathrm{dim}_{\mathbb C} \mathrm{QD}(X)=3g-3$. 

Reference: [FM], pages 300-305, 309-312.

## Sep 24

As an example, we studied the Swiss Cross as a construction of a genus $2$ Riemann surface together with a quadratic differential. We stated the Teichmuller existence and uniquess theorem, and explained the diffeomorphism map between $\mathrm{QD}_1(X)$ and $\mathrm{Teich}(S)$. The Teichmuller metric is a complete metric defined by the dilatation of the Teichmuller map relating two conformal structures. 

Reference: [FM], pages 313-315, 320-323, 330-332, 337-341.

## Oct 15

We introducted *mapping class groups*, and discussed several examples (disk, annulus, torus with zero or $1$ marked points, $S_{0,3}$ and $S_{0,4}$.) We introduced the concept of the moduli space of (smooth) conformal/hyperbolic structures, and discussed the example of $\mathcal M(T^2)$.

Reference: [FM], Chapter 2, pages 342-349.

## Oct 19

We discussed Beltrami differentials and the Betlrami equation. In particular, by solving the Beltrami equation and restricted to *harmonic* Beltrami differentials, we get the tangent space of the Teichmuller space. We further discussed the *complex* structure on $\mathcal T_{g,n}$.

The quadratic differential is naturally identified with the *cotangent space* os the Teichmuller space. We discussed Weil-Pertersson metric as a hermitial metric given by the $L^2$ norm on Beltrami differentials. The Teichmuller metric is given by $L^\infty$-norm, or equivalently the $L^1$-norm on quadratic differentials discussed earlier.

References: [Hu] Ch 4 and 6, [IT] Ch 6. We did a very superficial survey to the deep analysis in this topic.

## Oct 22

The moduli space $\mathcal M_{g,n}=\mathcal T_{g,n}/\mathrm{PMod}_{g,n}$ is a complex orbifold from the properly discontinuous action.

We discussed the compactification of the moduli space: first we constructed a partial completion $\hat{\mathcal T}_{g,n}$ by allowing degeneration into a node, together with an extension of the action of the mapping class group. The Deligne-Mumford compactification $\overline{\mathcal M}_{g,n}$ is then defined by $\hat{\mathcal T}_{g,n}/\mathrm{PMod}_{g,n}$.

The construction is a priori not a compact space, or an orbifold. The compactness argument follows *Mumford's compactness criteria*, while the the orbifold structure at the boundary strata is given locally by the $xy=\epsilon$ near $\epsilon=0$: the boundary stratum is a normal crossing divisor. 




## Oct 28

We reviewed some basic notion of orbifolds, and discussed the universal property of moduli spaces. As an example, $\mathcal M_{1,1}$ has an *orbifold* universal curve of (smooth) genus $1$ curves with one marked points, but as a scheme (or topological space) the moduli space $M_{1,1}$ is too coarse.

The moduli space $\overline{\mathcal M}_{g,n}$ as an *orbifold* has a universal curve $\overline{\mathcal C}_{g,n}$. We discussed the example of $\overline{\mathcal M}_{0,4}$ and its universal curve.

The boundary of $\overline{\mathcal M}_{g,n}$ are stratified: they can be described by the dual graph of the topological type of the stable curves.  

References: [Zv], pages 671-681


---

- [FM] Farb, B., & Margalit, D. (2012), A Primer on Mapping Class Groups. Princeton University Press.

- [HM] Harris, J., & Morrison, I., Moduli of Curves. Springer

- [Hu] Hubbard, J. H., Teichmüller theory and applications to geometry, topology, and dynamics. Vol. 1.

- [IT] Imayoshi, Y., Taniguchi, M., An  introduction to Teichmuller space

- [Zv] Zvonkine, D., An introduction to moduli spaces of curves and their intersection theory (EMS published book Chapter 11, in Handbook of Teichmuller Theory vol III).