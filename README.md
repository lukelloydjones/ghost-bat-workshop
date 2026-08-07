# 🦇 Close-Kin Mark-Recapture for Ghost Bats

### A 2-Day Workshop

Close-Kin Mark-Recapture (CKMR) uses genetic relatedness — identifying parent-offspring pairs, half-siblings, and other kin — to estimate population abundance and demographic parameters without the need for physical recaptures. This workshop introduces the theory, tools, and practical design considerations for applying CKMR to ghost bat (*Macroderma gigas*) populations.

---

## About the Workshop

Ghost bats are Australia's only false vampire bat and one of the continent's most elusive mammals. Traditional mark-recapture is difficult given their ecology and conservation sensitivity. CKMR offers a powerful, minimally invasive alternative — all we need is a tissue sample and the right statistical framework.

This workshop is designed for ecologists, conservation geneticists, and wildlife managers who want to understand how CKMR works and how to apply it in practice. No prior experience with CKMR is required, though familiarity with R and basic population genetics will be helpful.

---

## Schedule

### Day 1 — Foundations

| Session | Topic | Description |
|---------|-------|-------------|
| **1.1** | Introduction to CKMR | Core concepts: kinship probabilities, how kin pairs encode population size, and the statistical basis of CKMR estimation. |
| **1.2** | Running a Basic Model | Hands-on walkthrough of a CKMR model from simulated data — setting up inputs, fitting the model, and interpreting outputs. |
| **1.3** | Kinference | Introduction to the [Kinference](https://github.com/) package for kin-finding and inference. Practical exercises on pairwise kinship classification and integrating results into CKMR estimation. |

### Day 2 — Design & Application

| Session | Topic | Description |
|---------|-------|-------------|
| **2.1** | Study Design for CKMR | Sampling considerations: how many samples, over what time frame, and from which age/sex classes? Power, precision, and common pitfalls. |
| **2.2** | Ghost Bat Case Study | Applying design principles to ghost bat populations — spatial structure, colony dynamics, life history, and what we know (and don't know) about *Macroderma gigas*. |
| **2.3** | Discussion & Next Steps | Open session to discuss project-specific applications, limitations, extensions (e.g., spatial CKMR, integrated models), and future directions. |

---

## Getting Started

### Prerequisites

- [R](https://cran.r-project.org/) (≥ 4.2)
- [RStudio](https://posit.co/download/rstudio-desktop/) (recommended)
- R packages (install before the workshop):

```r
install.packages(c("tidyverse", "kinference", "TMB"))
```

### Setup

```bash
# Clone this repository
git clone https://github.com/your-username/ckmr-ghost-bats-workshop.git
cd ckmr-ghost-bats-workshop
```

Open `ckmr-ghost-bats-workshop.Rproj` in RStudio to get started.

---

## Repository Structure

```
ckmr-ghost-bats-workshop/
├── day1/
│   ├── 01_intro-to-ckmr/
│   ├── 02_basic-model/
│   └── 03_kinference/
├── day2/
│   ├── 01_study-design/
│   ├── 02_ghost-bat-case-study/
│   └── 03_discussion-notes/
├── data/
│   ├── simulated/
│   └── examples/
├── slides/
├── README.md
└── ckmr-ghost-bats-workshop.Rproj
```

---

## Key References

- Bravington, M.V., Skaug, H.J., & Anderson, E.C. (2016). Close-kin mark-recapture. *Statistical Science*, 31(2), 259–274.
- Hillary, R.M., Bravington, M.V., Patterson, T.A., et al. (2018). Genetic relatedness reveals total population size of white sharks in eastern Australia and New Zealand. *Scientific Reports*, 8, 2661.
- Lentini, P.E., Milne, D.J., & Lumsden, L.F. (2022). Ghost bat ecology and conservation — a review. *Australian Mammalogy*.

---

## Acknowledgements

We acknowledge the Traditional Owners of the lands on which this workshop is held and on which ghost bats live. We pay our respects to Elders past, present, and emerging.

---

## Contact

For questions about the workshop materials, please [open an issue](https://github.com/your-username/ckmr-ghost-bats-workshop/issues) or contact the workshop organisers.

---

## Licence

Workshop materials are released under the [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) licence unless otherwise noted.
