# One Extra Label Makes Multiclass Aggregation Mixable

## Abstract

Zero-one classification is not mixable. Aggregating $N$ multiclass experts therefore costs order $\sqrt{T\log N}$ regret in general. We show that one extra prediction slot changes the game discontinuously. If every expert predicts at most $r$ labels and a randomized learner predicts exactly $k>r$, then expected regret is independent of the horizon. We characterize the phenomenon exactly. For an unrestricted alphabet, the sharp resource-augmented mixability constant is the positive solution 

$$\frac{e^\eta-1}{\eta}=\frac{k}{r}.$$

 For a pool of $N$ experts, the sharper constant solves 

$$\frac N\eta\log\left(1+\frac{e^\eta-1}{N}\right)=\frac{k}{r},$$

 and becomes infinite once $k\ge Nr$. Exponential weights followed by an explicit exact-cardinality rounding rule then gives regret at most $\log N/\eta$. We prove matching lower bounds near the phase transition and for larger augmentation. The same geometry has two learning consequences. It gives a high-probability $1/n$ excess-risk rate for finite-class agnostic list learning, formalizing a recently identified hedging advantage. It also converts list Littlestone covers into $O(d\log T)$, rather than square-root-in-$T$, agnostic regret whenever the learner has more slots than the comparator. Thus a single additional answer changes both adversarial aggregation and stochastic model selection from nonmixable to fast-rate regimes.

## Contributions

- We define resource-augmented mixability and compute its exact finite-alphabet, finite-expert, and alphabet-uniform constants for list omission loss.
- We give an efficient aggregating algorithm with horizon-independent regret and a self-contained exact-list rounding rule.
- We prove lower bounds matching the augmentation dependence near $k=r$ and away from that threshold.
- We derive finite-class $1/n$ stochastic excess risk and logarithmic-in-$T$ agnostic regret from list Littlestone covers.

## Keywords

online learning, expert aggregation, mixability, multiclass prediction, regret bounds, resource augmentation, list prediction

## Files

- `main.pdf`
- `main.tex`
- `references.bib`
- `iclr2027_conference.sty`, `iclr2027_conference.bst`, `natbib.sty`, `fancyhdr.sty`
- `main.pdf.ots`, `README.md.ots` OpenTimestamps priority proofs
