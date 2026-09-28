# Pedro Victor Freitas-Medrado, MD

[![Interactive leaderboard](https://img.shields.io/badge/Interactive_leaderboard-open-9E1F33?style=for-the-badge)](https://gitpedro98.github.io/ClinicalUncertainty) [![Repository](https://img.shields.io/badge/Repository-ClinicalUncertainty-1B2331?style=for-the-badge&logo=github)](https://github.com/GitPedro98/ClinicalUncertainty) [![Google Scholar](https://img.shields.io/badge/Google_Scholar-profile-4A5466?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=w1DXfrEAAAAJ&hl=pt-BR) [![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-4A5466?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pedro-medrado-md-934813392/)

I'm a physician who also writes and understands code. Over seven years I built experience in field clinical research and in clinical data engineering over Brazil's federal university hospitals, and these days I spend my time on one question: what happens when a frontier language model is deployed into a health system it was not trained on, with different formularies, different levels of care, different epidemiology?

## Current work

**[SUS-UncertaintyBench](https://github.com/GitPedro98/ClinicalUncertainty)** is the benchmark I'm building to answer it. It is anchored in de-identified DATASUS emergency admissions, and each case keeps a physician-written clinical core fixed while one controlled variable changes between two prompts.

- 15 archetypes with physician-authored clinical cores and 91 controlled variations (cardiovascular, neurological, infectious disease), scored on five dimensions against a priori rubrics.
- I ran a pre-pilot unfunded: 3 frontier models, 172 response pairs, 85 scored by me. Independently trained models agree on which items are hard (Kendall's W = 0.58, p = 0.014), but at this sample size they cannot be ranked, and the results page says so.
- The pipeline and analysis are reproducible from one script and a fixed seed.

## Background

- Seven years of field clinical research: 14 publications, 6 indexed, including two randomized trials where I led the data analysis.
- Clinical data engineering over Brazil's federal university hospital network (Python/SQL, ICD-10, DATASUS).
- Practicing physician in Brazil's public health system (SUS).

## Tools

Python (pandas, NumPy, SciPy, statsmodels, FastAPI), SQL, AWS.
Statistics: mixed-effects models, cluster bootstrap, permutation tests, power simulation, inter-rater reliability.

## About my commit graph

You'll notice my contribution graph is nearly empty. That's not because I'm not building. Until now I have developed on my local machine and on cloud VMs, in private repositories, and I never pushed to GitHub. SUS-UncertaintyBench is my first public repository, so the work can be checked directly instead of inferred from a commit history.

## Contact

pvfhealthtech@gmail.com
