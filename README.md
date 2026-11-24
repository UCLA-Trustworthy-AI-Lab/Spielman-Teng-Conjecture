# The Smallest Singular Value of a Random Sign Matrix: The Spielman–Teng Conjecture

**Hengzhi He and Guang Cheng**  
Working Paper · November 23, 2026

[Read the paper (PDF)](Spielman-Teng.pdf) · [November 23 manuscript and citation](preprints/Spielman-Teng-2026-11-23/)

## Main results

How likely is a square random sign matrix to be nearly singular? Let $A$ be an $n\times n$ matrix whose entries are independently and uniformly chosen from $\{-1,1\}$, and let $s_{\min}(A)$ be its smallest singular value. We prove the bound conjectured by Spielman and Teng in 2002. For some absolute constant $c>0$, every $n\ge 1$, and every $t\ge 0$,

```math
\Pr\left(\sqrt{n} s_{\min}(A)\le t\right)\le t+e^{-cn}.
```

The coefficient of $t$ is one. The exponential term allows for the positive probability that a sign matrix is exactly singular.

We also obtain a finite-dimensional improvement. There are absolute constants $c,\theta,C>0$ such that, for all sufficiently large $n$ and all $e^{-cn}\le t\le n^{-\theta}$,

```math
\Pr\left(\sqrt{n} s_{\min}(A)\le t\right)
\le t\left(1-\frac{1}{2n}+Cn^{-1.02}\right).
```

The proof compares the sign matrix with a matrix whose rows are independent and uniform on a sphere. An arithmetic small-ball estimate transfers the comparison to exponentially small thresholds. At polynomial thresholds, a coordinate of the least left singular vector supplies the weight in a crossing argument.

## How to cite

He, H., and Cheng, G. (2026). *The Smallest Singular Value of a Random Sign Matrix: The Spielman–Teng Conjecture*. Working paper, revision R4, November 23, 2026. [Version cited](https://github.com/UCLA-Trustworthy-AI-Lab/Spielman-Teng-Conjecture/blob/a0ba1f0a5c2c24a1b411620a4729a5055eaa0a8b/Spielman-Teng.pdf).

```bibtex
@unpublished{hecheng2026spielmanteng,
  author = {He, Hengzhi and Cheng, Guang},
  title  = {The Smallest Singular Value of a Random Sign Matrix: The {Spielman--Teng} Conjecture},
  year   = {2026},
  month  = nov,
  note   = {Working paper, revision R4, November 23, 2026},
  url    = {https://github.com/UCLA-Trustworthy-AI-Lab/Spielman-Teng-Conjecture/blob/a0ba1f0a5c2c24a1b411620a4729a5055eaa0a8b/Spielman-Teng.pdf}
}
```
