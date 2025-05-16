# COS30045_project
# Interactive Road Safety Enforcement Dashboard

This project visualises police enforcement data from the Bureau of Infrastructure and Transport Research Economics (BITRE), focusing on the newly expanded datasets available from 2023 onward. The dashboard provides users with tools to explore enforcement activity by location, age group, and violation type.

## 🚀 Purpose

The goal is to create an interactive web-based tool that improves public understanding of road safety enforcement in Australia, and supports data-driven policy insights.

## 📊 Datasets Used

We use four main datasets:
1. `police_enforcement_2023_fines.csv`
2. `police_enforcement_2023_positive_breath_tests.csv`
3. `police_enforcement_2023_positive_drug_tests.csv`
4. `police_enforcement_2023_alcohol_drug_tests.csv`

All data is sourced from BITRE and reflects legal actions, tests conducted, and violations recorded by police and other agencies.

## 📘 Key Data Fields

- `YEAR`, `START_DATE`, `END_DATE`
- `JURISDICTION` — state or territory
- `AGE_GROUP` — life stage brackets (e.g., 18–25)
- `METRIC` — type of enforcement (e.g., speeding, drug test)
- `DETECTION_METHOD` — camera, police-issued, or unspecified
- `FINES`, `ARRESTS`, `CHARGES` — enforcement outcomes
- `BEST_DETECTION_METHOD` — used to isolate valid drug test results

## 📁 Repository Structure

<pre> ## 📁 Repository Structure ``` /data ├── cleaned_datasets/ ├── raw/ ├── KNIME_workflows/ └── data_dictionary.pdf /src ├── charts/ ├── components/ ├── styles/ └── utils/ /docs ├── project_design_book_draft.pdf └── standup_presentation.pptx index.html README.md ``` </pre>

## 🧠 AI Assistance Declaration

This project used ChatGPT to:
- Summarise data dictionaries
- Generate README templates
- Draft Design Book sections
All outputs were reviewed and edited to maintain academic integrity.

## 👥 Authors
Nguyen Quang Nguyen Phan

