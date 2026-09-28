# Pedro Victor Freitas-Medrado, MD

Physician and clinical AI evaluation researcher. I build benchmarks that test whether frontier language models stay reliable when the deployment context diverges from their training: different formularies, levels of care, epidemiology.

## Current work

**[SUS-UncertaintyBench]** is a clinical uncertainty benchmark built on de-identified DATASUS emergency admissions from Brazilian federal university hospitals.

- 15 physician-authored archetypes and 91 controlled variations (cardiovascular, neurological, infectious disease), scored on five dimensions against a priori rubrics.
- Pre-pilot on 3 frontier models: 172 response pairs, 85 physician-scored. Independently trained models agree on which items are hard (Kendall's W = 0.58, p = 0.014).
- The pipeline and analysis are reproducible from one script and a fixed seed.

[Interactive leaderboard]([LEADERBOARD_LINK](https://gitpedro98.github.io/ClinicalUncertainty)) · [Repository]([REPO_LINK](https://github.com/GitPedro98/ClinicalUncertainty)) · 

## Background

- Seven years of field clinical research: 14 publications, 6 indexed, including two randomized trials where I led the data analysis.
- Clinical data engineering over Brazil's federal university hospital network (Python/SQL, ICD-10, DATASUS).
- Practicing physician in Brazil's public health system (SUS).

## Tools

Python (pandas, NumPy, SciPy, statsmodels, FastAPI), SQL, AWS.
Statistics: mixed-effects models, cluster bootstrap, permutation tests, power simulation, inter-rater reliability.

## Contact

pvfhealthtech@gmail.com · [LinkedIn]([LINKEDIN_LINK](https://www.linkedin.com/in/pedro-medrado-md-934813392/)) · [Google Scholar]([SCHOLAR_LINK](https://scholar.google.com/citations?user=w1DXfrEAAAAJ&hl=pt-BR))

## About my commit graph

The contribution graph on this profile is sparse, and it does not reflect my activity. Historically I have developed on a local machine and on cloud VMs, in private repositories, without pushing to GitHub. SUS-UncertaintyBench is my first public repository: it holds the archetypes, the pipeline, the analysis code and the raw outputs, so the work can be checked directly instead of inferred from a commit history.
