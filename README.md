RIVER AND LAKE SYNCHRONY IN THE CANADIAN PRAIRIES
Reproduction files for Figures 3 and 4

Extract the complete ZIP into one directory. Open a terminal in the directory
containing run_all.R. In R, install ggplot2 (>= 3.5.0) and ragg once. Then run:

    Rscript --vanilla run_all.R

In an R session with the repository root as its working directory, run:

    source("run_all.R")

The scripts read the bundled data and write PDFs and PNGs to figures/ and CSV
results to results/. The README.md file describes units, station IDs, sources
and methods. It can be opened in a text editor or viewed on GitHub.

Figure 4 has two outputs. The manuscript reconstruction preserves the plotted
hydroclimate estimates. The recalculated output uses available monthly station
measurements. See the comparison in README.md and the numerical values in
results/figure_4_hydroclimate_audit.csv.

Data and code for "Comparison of river and lake synchrony using the Energy-mass
flux framework", by Chenxi Mi and colleagues.
