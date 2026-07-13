# Human liver ILC1s — single-cell analysis

Analysis of the **human liver type-1 innate lymphoid cell (ILC1)** single-cell dataset from
Kramer et al., characterising liver-resident ILC1 / NK-cell populations.

## Analysis
- `scripts/01_Dataset_overview.Rmd` — dataset overview, cell-type annotation and marker visualisation

## Data
Processed objects are kept outside version control (available from the original source).

---
Analysis by **Dillon Corvino** · [GitHub](https://github.com/Eomesodermin) · [dilloncorvino.com](https://dilloncorvino.com)

## Environment

Built in **R** with a Seurat-based single-cell stack — key packages: `Seurat`, `SeuratDisk`, `scCustomize`, `dplyr`, `ggplot2`, plus my helper package [`r-utility-functions`](https://github.com/Eomesodermin/r-utility-functions).

A pinned `renv.lock` is **not** committed for this repository. To capture an exact, reproducible
environment, run in the project root:

```r
install.packages("renv")
renv::init()        # discovers dependencies from the scripts
renv::snapshot()    # writes renv.lock pinning every package version
```
