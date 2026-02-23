# Numerical Relativity Kyoto Initiative

The Kyoto initiative is a joint effort by several numerical relativity
groups to perform **blind** binary neutron star merger cross-code
comparisons. All groups will perform merger simulations starting from
common initial data. They will submit their waveforms, as well as their
estimated uncertainties, to the data analysis group, who will perform a
careful comparison between all models. The results will be documented in
a paper, with all participating groups listed as co-authors.

This comparison primarily focuses on gravitational-waves. However, groups
are encouraged to save ejecta data, remnant disk data, for a possible
follow up comparison.

At this time, we are in the planning phase for this effort.

## Timeline

This is a proposed timeline, details TBD

* February 5, 2026: initial conception of the project at the YITP workshop
  [Multi-Messenger Astrophysics in the Dynamic
  Universe](https://www2.yukawa.kyoto-u.ac.jp/~mm2026/).

* Mid March 2026: this document should be finalized. The project will
  be announced to the broader community and open to anyone who wants to join.

* By early summer 2026: deadline for groups to "pre-register" their submission.

* Early summer 2026: initial data will be made publicly available.

* Early summer 2027: deadline for submitting waveforms.

* End of 2027: paper submitted to arXiv and journal, all data and
  analysis scripts are immediately released on Zenodo.

### Note on Deadlines

The participation to a large scale code comparison effort is time and
resource intensive. In absence of strict deadlines, each group is
incentivized to be the last submitting. In the interest of fairness and
in recognition of the efforts of those involved, this project has a
strict deadline for submission. Failure to meet the deadline implies
exclusion from the project and from the paper.


## Initial Data

**Initial data lead:** Kenta Kiuchi <kenta.kiuchi@aei.mpg.de>

Low-eccentricity [FUKA](https://samueltootle.github.io/fuka/) initial
data corresponding to two neutron stars will be made available at a
pre-specified date, to give all groups, including those joining after the
YITP workshop, the same time to produce waveforms. 

### Initial data parameters

* **EOS:** [HS(DD2) from CompOSE](https://compose.obspm.fr/eos/18).
* **Masses:** TBD, target something like 1.4+1.2
* **Separation:** TBD, target ~10 orbits


## Simulations Parameters

Simulation codes should employ the CompOSE equation of state in tabular form.

To keep costs under control, simulations should employ a grid spacing
between 0.05 and 0.5 $M_\odot$.

Simulation groups will perform simulations at different resolutions, but
should only contribute a single waveform and its estimated uncertainty.
The latter could be estimated as the difference between the two highest
resolutions, or with Richardson extrapolation, or with any technique each
team prefers. The submission format will be determined by the data analysis team.


## Data Analysis

**Data analysis lead:** Jocelyn Read <jread@Fullerton.edu>

The data analysis group has the following tasks:

* Develop a specification for the data format (by mid March 2026)
* Propose a set of analysis diagnostics (by early summer 2026)
* Develop analysis scripts (by summer 2027)
* Analyze data, prepare figures (by end of summer 2027)

The results of the analysis should be blinded, meaning that code names
will be replaced by a unique anonymous identifier (e.g., a number). We
will unblind the analysis only after all project participants have
approved the draft of the final manuscript.


## Paper Writing

A publication describing the results of this project will be prepared by
a paper writing team. The draft will then be open to comments to all
participants. The paper writing team shall consist of

* One initial data representative: first author, discuss results
* David Radice: introduction, cleanup of the draft
* Kenta Kiuchi: initial data
* Code representatives: description of codes, methods, and approaches,
  authors 2-N in alphabetical order

Co-authorship will be offered to all active participants: code
representatives, developers, PIs, who have actually contributed to the
project. Each author should provide a brief, one sentence statement of
work done to be part of the paper. The participants will be listed in
alphabetical order after the code representatives.


## Participating Groups

Each group should appoint a representative. The representative will be
the main point of contact for each group.

We will try to keep telecons to a minimum. The representative of each
group agrees to participate in all of them. Occasionally, they may appoint a
substitute. Only the representative of each group joins the telecons (or
a substitute), as keeping the group small will improve our efficiency.
This also ensures that all groups are given the same space. 


### AthenaK

* **Spokesperson:** David Radice <dur566@psu.edu>
* **URL:** https://www.github.com/ias-astrophysics/athenak

### NANASI

* **Spokeperson:** Kenta Kiuchi <kenta.kiuchi@aei.mpg.de>
* **URL:** https://doi.org/10.1103/PhysRevD.106.124041

### SACRA-MPI

* **Spokeperson:** Kenta Kiuchi <kenta.kiuchi@aei.mpg.de>
* **URL:** https://doi.org/10.1103/zmdc-xkcm

### SpEC

* **Spokeperson:** Francois Foucart <francois.foucart@unh.edu>
* **URL:** https://www.black-holes.org/for-researchers/spec

## Policies

**Project coordinator:** David Radice <dur566@psu.edu>
