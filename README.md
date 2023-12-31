# Handling peptide-spectrum matches

`PSMatch` is a simple package to load, process and analyse PSMs
(Peptide-Spectrum Matches). The following references are a good way to
get started with the package:

- The [package manual
  package](https://rformassspectrometry.github.io/PSMatch/reference/PSMatch.html)
  for a general overview of the main concepts tackled by the `PSMatch`
  package.
- The [Working with PSM
  data](https://rformassspectrometry.github.io/PSMatch/articles/PSM.html)
  vignette to learn about the `PSM` to read and filter
  peptide-spectrum matches.
- The [Understanding protein groups with adjacency
  matrices](https://rformassspectrometry.github.io/PSMatch/articles/AdjacencyMatrix.html)
  vignette to learn about adjaceny matrices and connected components
  to explore and manage protein groups.
- The [MS2 fragment
  ions](https://rformassspectrometry.github.io/PSMatch/articles/Fragments.html)
  vignette to calculate and visualise MS2 fragment ions.

## Installation instructions

To install the package from Bioconductor, make sure you have the
`BiocManager` package, available from CRAN, and then run

```r
BiocManager::install("PSMatch")
```

## Credit

Code in this package is partly composed of functions ported from
[`MSnbase`](http://lgatto.github.io/MSnbase/) with the goal to (1)
make them more general and (2) integrate them with the [*R for Mass
Spectrometry*](https://github.com/rformassspectrometry)
infrastructure.
