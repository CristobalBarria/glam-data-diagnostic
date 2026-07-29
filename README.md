# Diagnostic Questionnaire on GLAM Heritage Data

This questionnaire serves as a diagnostic instrument to assess the structure, curation state, and legal and ethical considerations of heritage datasets held by GLAM institutions (Galleries, Libraries, Archives, and Museums). Designed to be flexible and adaptable to different institutional contexts, it is intended to be applied prior to data integration processes, providing insights to support decisions regarding interoperability, semantic modeling, and publication priorities. By producing standardized diagnostic results, it also enables comparative analyses of curation practices across institutions.

## Context

Developed as part of a Master's thesis in Museology (University of Neuchâtel), using as a case study the federated heritage collections platform project currently under development at the City of Geneva.

## Repository Structure

- **`index.html`** — the questionnaire (see [Access](#access) below)
- **`Memoire_Cristobal_Barria.pdf`** — the associated Master's thesis
- **`survey/`** — licenses and reference files for the questionnaire

## Themes Assessed

| # | Theme |
|---|-------|
| 1 | Respondent information |
| 2 | Dataset themes |
| 3 | Data management systems and models |
| 4 | Entity inventory |
| 5 | Attribute inventory |
| 6 | Duplicate assessment |
| 7 | Uncertainty management |
| 8 | Ambiguity management |
| 9 | Data normalization status |
| 10 | Update practices and identifier stability |
| 11 | Rights and licensing |
| 12 | Sensitive data and deontological strategies |
| 13 | Publishability assessment |

## Results

**CSV export** (four files):
- General information (respondent, institution, and dataset theme)
- Entities (inventory, including declared duplicates)
- Attributes (full curation profile — e.g., data type, vocabularies, uncertainty handling, rights, normalization issues)
- Attribute groups (semantic relationships)

**Graphical visualization** of entities and their attributes, with a curation indicator (**% NC** — non-curated data) per attribute.

## Technologies

- [SurveyJS](https://surveyjs.io/) (survey-jquery)
- [D3.js](https://d3js.org/) v7
- [Google Apps Script](https://developers.google.com/apps-script)

## Access

The questionnaire is available online via GitHub Pages: https://cristobalbarria.github.io/glam-data-diagnostic/

It is intended to be completed by GLAM institution staff responsible for data and collections management, ideally with the support of a data or metadata specialist.

## License

- **Code** (`index.html`): [MIT](LICENSE)
- **Content** (questionnaire, methodology): [CC BY 4.0](survey/LICENSE-CONTENT.md)

## Contact

[cristobal.barria@geneve.ch](mailto:cristobal.barria@geneve.ch)
