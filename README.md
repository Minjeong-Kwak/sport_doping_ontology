# Sport Doping Ontology

This repository provides the OWL ontology file developed for the manuscript:

**An Ontology Study for the Structuring of Doping Regulatory Information and Query-Based Analysis**

## Repository contents

- `sport_doping_ontology.owl`  
  The final OWL ontology file used in the manuscript.

- `competency_questions.sparql`  
  SPARQL queries corresponding to the competency questions reported in the manuscript.

## Ontology scope

The ontology represents structured anti-doping regulatory information, including:

- anti-doping rule violation categories
- prohibited substances and prohibited methods
- violation case records
- sanctions and results management information
- testing and monitoring information
- therapeutic use exemption-related information
- pharmaceutical products and herbal medicine-related doping risk information

## Ontology metrics

The final ontology contains:

- 67 classes
- 39 object properties
- 77 data properties
- 1,777 named individuals

## Competency questions

The ontology was validated using competency question-based SPARQL queries.  
The queries support retrieval of:

1. prohibited substance categories associated with doping violations
2. sanctions imposed in violation cases
3. ADRV provisions and detected substances in Russia-related cases
4. sanction-period distributions for S1-related violations
5. substance and method patterns in athletics cases
6. long-term ineligibility cases of 48 months or more

## Availability

This ontology file corresponds to the submitted manuscript and was used to execute the competency questions reported in the paper.

## License

This repository is released under the Creative Commons Zero v1.0 Universal license.
