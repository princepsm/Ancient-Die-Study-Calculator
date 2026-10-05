# Ancient Die Study Calculator

A single-page tool for ancient numismatists. Enter the counts from a die study (coins, dies observed, singletons, and optionally doubletons and tripletons) to estimate how many dies originally struck an issue, how much of the coinage the sample covers, and how many coins and how much metal that implies.

**Live version:** [sarahprince.net/tools/die-study-calculator](https://sarahprince.net/tools/die-study-calculator)

## What it calculates

- **Esty (2011)**, the recommended standard: D = n·d / (n − d)
- **Carter (1983)**
- **Coverage** and the coverage-based estimate (Good; Esty 1984, 1986, 2006)
- **Lyon–Chao1 (1989) Formula 2** and **Lyon (1989) Formula 3**, with Lyon's published confidence limits
- **Bayesian comparison** under five die-output models, including the two-population model of Albarède et al. (2021)
- **Coin output**: coins struck, metal coined, silver equivalent and survival rate, for an adjustable output per die

A **Simple** mode shows only the Esty estimate, its interval and coverage.

## Using it

Open `index.html` in any modern browser. It needs no installation, server or account; everything runs in the page. Fonts load from Google Fonts.

## References

- G. F. Carter, "A simplified method for calculating the original number of dies from die link statistics", *ANS Museum Notes* 28 (1983), 195–206.
- W. W. Esty, "Estimation of the size of a coinage: a survey and comparison of methods", *Numismatic Chronicle* 146 (1986), 185–215.
- W. W. Esty, "How to estimate the original number of dies and the coverage of a sample", *Numismatic Chronicle* 166 (2006), 359–364.
- W. W. Esty, "The geometric model for estimating the number of dies", in F. de Callataÿ (ed.), *Quantifying Monetary Supplies in Greco-Roman Times* (Bari 2011), 43–58.
- S. Lyon, "Die estimation: some experiments with simulated samples of a coinage", *British Numismatic Journal* 59 (1989), 1–12.
- F. Albarède, F. de Callataÿ, P. Debernardi and J. Blichert-Toft, "Model for ancient Greek and Roman coinage production", *Journal of Archaeological Science* 131 (2021), 105406.

Example data for Naxos staters: SILVER database, Royal Library of Belgium (KBR), CC BY 4.0.

The Bayesian estimates, including the use of the Albarède et al. model within them, are this tool's own construction rather than methods proposed in those papers.

## Licence

MIT. See `LICENSE`.
