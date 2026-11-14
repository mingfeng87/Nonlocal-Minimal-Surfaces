# Nonlocal Minimal Surfaces

This repository collects research manuscripts and drafts on nonlocal minimal surfaces and fractional perimeter, centered on two classical problems in the nonlocal setting: the Bernstein problem for entire minimizing graphs, and the stability of singular minimizing cones. The first manuscript constructs nonaffine entire nonlocal minimal graphs over $$\mathbb{R}^8$$ for every fractional exponent $$s \in (0,1)$$, providing the nonlocal counterpart of the Bombieri–De Giorgi–Giusti example. The second manuscript determines, for every $$m,n \ge 1$$ and every $$0<s<1$$, when stationary fractional Lawson cones in $$\mathbb{R}^m \times \mathbb{R}^n$$ are stable, uncovering the exponent thresholds at which stability transitions occur.

**Draft status:** Both manuscripts present candidate proofs. The team is continuing to verify every argument. The summaries below describe the statements and proofs as currently drafted.

* * *

## Manuscripts

### 1. Entire nonlocal minimal graphs over $$\mathbb{R}^8$$: an analytic construction for every fractional exponent

**[Read the PDF](https://github.com/mingfeng87/Nonlocal-Minimal-Surfaces/blob/main/Nonlocal_BDG_Graphs_All_s.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$8$$ (graph over $$\mathbb{R}^8$$, subgraph in $$\mathbb{R}^9$$) |
| **Range** | $$s \in (0,1)$$ |
| **Length** | 76 pages |

For every $$s \in (0,1)$$, the manuscript constructs a smooth nonaffine function $$f:\mathbb{R}^8 \to \mathbb{R}$$ whose subgraph locally minimizes the fractional $$s$$-perimeter against arbitrary measurable competitors in bounded open sets (Theorem 1.1). The function is invariant under $$O(4) \times O(4)$$, odd under interchange of the two factors, positive on $$\{ |u| > |v| \}$$, and has zero set equal to the balanced cone $$\Sigma = \{ |u| = |v| \}$$. As $$s \to 1$$, the indicators of the subgraphs converge locally in $$L^1$$ to the indicator of the classical BDG graph times $$\mathbb{R}$$. The proof reduces the curvature estimate for an explicit cap to a weighted fractional-Laplacian bound and a scalar inequality via a quaternionic change of variables. Comparing the negative cap curvature with a positive hyperboloid estimate places the smaller critical radial exponent of the Jacobi operator in $$(1, 5/2)$$. Two profiles of opposite curvature signs with the same leading decay are dilated at scales varying with height to produce ordered graph barriers; an angular kernel inequality gives comparison on $$\Sigma$$ and allows Dirichlet exhaustion between the barriers. The draft status note states that the candidate proof was obtained on November 4, 2026, through AI-assisted dialogue training and is currently under verification.

* * *

### 2. Stability and exponent transitions for fractional Lawson cones

**[Read the PDF](https://github.com/mingfeng87/Nonlocal-Minimal-Surfaces/blob/main/Nonlocal_Lawson_cone_stability.pdf)**

| Detail | Value |
|---|---|
| **Dimension** | $$N = m+n$$, for all $$m,n \ge 1$$ |
| **Range** | $$0 < s < 1$$ |
| **Length** | 56 pages |

The manuscript determines when stationary fractional Lawson cones in $$\mathbb{R}^m \times \mathbb{R}^n$$ are stable, for every $$m,n \ge 1$$ and every $$0<s<1$$, using smooth normal variations with compact support away from the vertex. The planar cross ($$N=2$$) has a unique threshold $$s_2 \in (0.9167, 0.9168)$$ and is stable exactly for $$s \ge s_2$$, with an explicit beta-function formula for its sharp weighted spectral gap. Every minimal Lawson cone is strictly unstable for $$3 \le N \le 6$$. In dimension $$N=7$$ there are three families up to interchange of the factors, each with a unique stability threshold at which the gap has a simple zero and changes sign; each cone is stable exactly below or at its threshold. For $$N \ge 8$$, every family is stable with a positive Hardy–curvature gap and weighted coercivity, including cones with a one-dimensional factor. The main step combines two radial terms before expanding, producing a gamma-moment series that keeps the cancellation in the gap and separates the exponent from the angular geometry; spherical moments then determine its sign. The draft status note states that the candidate proof was obtained on October 20, 2026, through AI-assisted dialogue training and is currently under verification.

* * *

## Citing a manuscript

Use the full manuscript title and the date printed in the PDF, use M. Zhao et al. as the author of PDF files. Include the
[repository URL](https://github.com/mingfeng87/Nonlocal-Minimal-Surfaces)
and the commit hash or a commit-specific PDF link for the version consulted,
so that the cited draft can be identified after revisions.

* * *

## Repository structure

| File | Description |
|---|---|
| [`Nonlocal_BDG_Graphs_All_s.pdf`](https://github.com/mingfeng87/Nonlocal-Minimal-Surfaces/blob/main/Nonlocal_BDG_Graphs_All_s.pdf) | Dimension 8, every $$s \in (0,1)$$, nonaffine entire minimizing graphs |
| [`Nonlocal_Lawson_cone_stability.pdf`](https://github.com/mingfeng87/Nonlocal-Minimal-Surfaces/blob/main/Nonlocal_Lawson_cone_stability.pdf) | All dimensions $$N=m+n$$, every $$0<s<1$$, stability thresholds for fractional Lawson cones |

* * *

## Keywords

Nonlocal minimal surface; fractional perimeter; Bernstein problem; Bombieri–De Giorgi–Giusti graph; Simons cone; balanced cone; Jacobi operator; geometric barrier; Lawson cone; stability; Hardy inequality; spherical moments; spectral gap; exponent transition.
