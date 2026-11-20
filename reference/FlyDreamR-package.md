# FlyDreamR: Runs the Ghosh-Harbison Hidden Markov Model on Activity Counts to Infer Sleep/Wake States

The FlyDreamR package implements the Ghosh-Harbison hidden Markov model.
It is designed to take activity count data as input and subsequently
infer sleep and wake states.

## Key Functions

Important functions in this package:

- [`HMMDataPrep`](https://nhlbi.github.io/FlyDreamR/reference/HMMDataPrep.md):
  This is the function to prepare DAM data for running the HMMs.

- [`HMMbehavr`](https://nhlbi.github.io/FlyDreamR/reference/HMMbehavr.md):
  The main function of the package to run HMMs for sleep state
  inference.

- [`HMMbehavrFast`](https://nhlbi.github.io/FlyDreamR/reference/HMMbehavrFast.md):
  Parallelized version of `HMMbehavr`.

## See also

Useful links:

- <https://nhlbi.github.io/FlyDreamR>

- Report bugs at <https://github.com/NHLBI/FlyDreamR/issues>

## Author

Arijit Ghosh <arijitghosh2009@gmail.com> (ORCID: 0000-0002-7910-3170)
