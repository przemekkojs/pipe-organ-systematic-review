This repository contains supplementary materials for the paper:

**P. Kojs, M. Kopel, D. Król, *Identifying Research Trends and Key Gaps: A Systematic Review of Organ Pipe and Wind Instrument Simulation Research* (2026).**

The repository includes:

* VOSviewer map and network files located in the `VOSViewer/` directory,
* all figures used in the study located in the `Figures/` directory,
* all analyzed publications in PDF format located in the `Bibliography/` directory. File names correspond to the respective publications.

### Figure Naming Convention

Figure files follow the naming pattern:

`<BeginYear>-<EndYear>[-TA][-Density].png`

where:

* `-TA` indicates an analysis based on titles and abstracts,
* `-Density` indicates a density visualization (heat map),
* the absence of `-TA` indicates an analysis based on publication titles only.

### VOSviewer File Naming Convention

VOSviewer files follow the naming pattern:

`<BeginYear>-<EndYear>[-TA][-full]-<map|network>`

where:

* `-TA` indicates an analysis based on titles and abstracts,
* the absence of `-TA` indicates an analysis based on publication titles only,
* `-full` indicates full counting,
* the absence of `-full` indicates binary counting,
* `map` denotes a VOSviewer map file,
* `network` denotes a VOSviewer network file.
