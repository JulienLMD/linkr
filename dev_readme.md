# Linkr Developer Guide - Visualization Module

## Repository References

- Initial repo by Jean Cupe: [JCupe17/linkr](https://github.com/JCupe17/linkr)
- Personal fork: [JulienLMD/linkr](https://github.com/JulienLMD/linkr)

## Project Installation

Install the project using Poetry as explained in the project's `README.md`.
You will retrieve in your `./data/` folder the [MIMIC](https://physionet.org/files/mimic-iv-demo-omop/0.9/1_omop_data_csv/)(Medical Information Mart for Intensive Care)

## Creating an ATHENA Account

1. Create an ATHENA account: [ATHENA](https://athena.ohdsi.org/search-terms/start)
2. Download the `CONCEPT.csv` and `DRUG_STRENGTH.csv` files with the column CODE = RxNorm.
3. Put the two files inside `./data/vocabulary_download_v5_all/`

## OMOP Documentation

- Explanation of the Common Data Model OMOP: [Common Data Model OMOP](https://ohdsi.github.io/CommonDataModel/cdm54.html#drug_exposure)
- How to calculate drug dosages: [Calculating Drug Dosages](https://ohdsi.github.io/CommonDataModel/drug_dose.html)

## Relationship Between OMOP and MIMIC

MIMIC (Medical Information Mart for Intensive Care) is a freely accessible database containing de-identified health data associated with approximately sixty thousand intensive care unit admissions. While MIMIC is not a native component of the OMOP (Observational Medical Outcomes Partnership) Common Data Model (CDM), it is often used in medical research, especially for analyzing intensive care data.

### Integrating MIMIC with OMOP CDM

Although MIMIC is not inherently part of the OMOP CDM, its data can be mapped to the OMOP CDM. This mapping allows for broader integration and analysis within the OHDSI (Observational Health Data Sciences and Informatics) community.

## Creating a Framagit Account

Create a Framagit account (a fork of GitLab) to access the LinkR repo and push plugins: [Framagit - Interhop Linkr](https://framagit.org/interhop/linkr)

## Implementing the Plugin

Implement the developed plugin live: [LinkR Live](https://linkr.interhop.org/)
