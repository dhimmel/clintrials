# Extracting indications from clinicaltrials.gov

This repository extracts drug–disease relationships from [ClinicalTrials.gov](https://clinicaltrials.gov).

Diseases are mapped to the Disease Ontology and drugs are mapped to DrugBank. See [`data/DrugBank-DO.tsv`](data/DrugBank-DO.tsv) for the table of extracted relationships. The extracted drug–disease relationships are not physician curated. The automated extraction approach likely results in some erroneous relationships. Additionally, many relationships may represent symptomatic applications of a drug.

## License

All original content is licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/). See [`download/terms.md`](download/terms.md) for the terms and conditions of the ClinicalTrials.gov database.
