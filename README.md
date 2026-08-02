# ESCO Data Scientist: 63 Essential Concepts

A small, reproducible data project that explores the **63 essential knowledge,
skill and competence concepts** connected to the `data scientist` occupation in
**ESCO v1.2.1**.

The project separates the concepts into the two ESCO skill types:

- `skill/competence`
- `knowledge`

It also provides an interactive treemap and a searchable table containing every
concept and its official ESCO description.

> Important: this is not a checklist for deciding who is a “real” data scientist.
> ESCO is an occupational classification. Its handbook defines essential concepts
> as concepts that are usually relevant to an occupation across work contexts,
> employers and countries. Actual roles still differ.

## Main question

**What knowledge, skills and competences does ESCO classify as essential for a
data scientist?**

## Repository structure

```text
esco-data-scientist-skills/
├── data/
│   ├── README.md
│   ├── esco_v1_2_1_data_scientist_essential_relations.csv
│   └── esco_v1_2_1_data_scientist_skill_descriptions.csv
├── outputs/
│   └── README.md
├── esco_data_scientist_essential_skills.ipynb
├── requirements.txt
├── .gitignore
└── COPYRIGHT.md
```

## How to run the project

1. Download or clone this repository.
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook and use **Run All**.

The two small data files required by the notebook are already included. They are
adapted subsets of the official ESCO v1.2.1 English CSV files.

## Outputs

After the notebook runs, the `outputs` folder will contain:

- A clean CSV containing all essential concepts and descriptions.
- An interactive HTML treemap.
- A 1080 × 1350 LinkedIn infographic.

## What the notebook demonstrates

- Loading official open data with Python.
- Filtering occupation–skill relationships.
- Joining tables with stable ESCO URIs.
- Checking duplicates and missing descriptions.
- Creating interactive Plotly visualizations.
- Building a searchable ITables table.
- Communicating a result without overstating what the data proves.

## Limitations

- ESCO is a classification, not a survey of job vacancies.
- The concepts are not ranked by importance.
- “Essential” does not mean that every employer expects all concepts at the same
  level.
- Results can change in later ESCO versions.

## Data provenance and reuse

**This publication uses the ESCO classification of the European Commission.**

The two CSV files in `data` are adapted subsets created from ESCO v1.2.1. They
contain only the 63 essential data scientist relations and their descriptions.
The complete ESCO dataset is not included. It can be downloaded from the
[official ESCO download page](https://esco.ec.europa.eu/en/use-esco/download).

## Ethics and responsible use

- Do not use the 63 concepts as a gatekeeping checklist.
- Do not treat a missing skill as proof that a person is unsuitable for a job.
- ESCO reflects a general European occupational profile and may not represent
  every industry, country, employer or career path equally.
- A skill taxonomy can support human judgement, but it should not make an
  automatic hiring decision by itself.
- Recruitment tools should be transparent, checked for unfair outcomes and
  supported by meaningful human review.
- If a future system processes CVs or candidate profiles, privacy and data
  protection must be considered from the beginning.

## Sources

- [What is ESCO?](https://esco.ec.europa.eu/en/about-esco/what-esco)
- [ESCO skills and competences](https://esco.ec.europa.eu/en/classification/skill_main)
- [Download ESCO](https://esco.ec.europa.eu/en/use-esco/download)
- [ESCO handbook](https://esco.ec.europa.eu/system/files/2021-07/Handbook.pdf)
- [EU AI Act overview](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
- [General Data Protection Regulation](https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng)

## Author

Adel Sahli

## Copyright

Copyright © 2026 Adel Sahli. All rights reserved. The original code, notebook
structure, analysis, visual design and written content are published for
portfolio review. ESCO-derived data remains subject to the European Commission's
reuse conditions described above.
