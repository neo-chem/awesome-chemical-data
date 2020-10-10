# Awesome data in chemistry and materials science [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

We live in a data-driven age. To make use of all the data that is produced in chemistry and materials science, standards for collecting and sharing of data are needed.

| Symbol | Meaning                            |
| ------ | ---------------------------------- |
| 😴     | Currently not developed/maintained |
| 💰     | Proprietary product                |

## Electronic lab notebooks (ELN) / Laboratory infrastructure management systems (LIMS)

### Overviews

- [ELN comparison grid](https://datamanagement.hms.harvard.edu/electronic-lab-notebooks) by Harvard Biomedial Data.
- [ELN guidance](https://www.gurdon.cam.ac.uk/institute-life/computing/elnguidance) by the Gurdon institute of the University of Cambridge.
- [Comparison of ELNs](https://github.com/Labii/comparison-of-best-electronic-lab-notebook) by the Labii ELN.

### Open Source

- [c6h6](https://www.c6h6.org/): Developed by the [cheminfo organization](https://github.com/cheminfo), couchDB backend, modular frontend in JavaScript. [![Github Stars](https://img.shields.io/github/stars/cheminfo/roc-eln-docker?style=social)](https://github.com/cheminfo/roc-eln-docker) ![GitHub last commit](https://img.shields.io/github/last-commit/cheminfo/roc-eln-docker?style=social)
- [chemotion ELN](https://github.com/ComPlat/chemotion_ELN): Developed by Nicole Jung's group at KIT, with focus on organic chemistry. Written in JavaScript/Ruby. [![Github Stars](https://img.shields.io/github/stars/ComPlat/chemotion_ELN?style=social)](https://github.com/ComPlat/chemotion_ELN) ![GitHub last commit](https://img.shields.io/github/last-commit/ComPlat/chemotion_ELN?style=social)
- [openBIS](https://openbis.ch/): General purpose LIMS/ELN developed at ETH Zuerich, allows to add custom plugins and direct data analysis in Jupyter notebooks. Core written in Java.

### Commercial solutions

## Repositories

- [chemotion repository](https://www.chemotion-repository.net/welcome): Repository for molecules, reactions and research data.

## Schemas/Ontologies

### Overviews

- [Pachl, C.; Frank, N.; Breitbart, J.; Bräse, S. Overview of Chemical Ontologies. arXiv:2002.03842 [cs] 2020.](https://arxiv.org/pdf/2002.03842.pdf)

### Analytical methods

- [Chemical Methods Ontology](https://github.com/rsc-ontologies/rsc-cmo): Describes methods used to collect data in chemical experiments, based on the IUPAC Orange Book in ontology language (OBO and OWL).
- [Chemical Analysis Metadata Platform](http://champ-project.org/): Ontology, Vocabularies, Metadata for Chemical Analysis. 😴
- [Analytical Information Markup Language (AnIML)](https://animl.org/): American Society for Testing and Materials (ASTM) XML standard for analytical chemistry and biological data, with [regular meetings](https://animl.org/meetings).

### Organic reactions

- [RXNO: reaction ontologies](https://github.com/rsc-ontologies/rxno): Name reaction ontology. [![Github Stars](https://img.shields.io/github/stars/rsc-ontologies/rxno?style=social)](https://github.com/rsc-ontologies/rxno) ![GitHub last commit](https://img.shields.io/github/last-commit/rsc-ontologies/rxno?style=social)
- [Molecular process ontology (MOP)](https://www.ebi.ac.uk/ols/ontologies/mop): Molecular processes that underlie the name reaction ontology RXNO.
- [ord-schema](https://github.com/Open-Reaction-Database/ord-schema): Schema for organic reactions developed for the open reaction database. [![Github Stars](https://img.shields.io/github/stars/Open-Reaction-Database/ord-schema?style=social)](https://github.com/Open-Reaction-Database/ord-schema) ![GitHub last commit](https://img.shields.io/github/last-commit/Open-Reaction-Database/ord-schema?style=social)

## Standardization initiatives

Initiatives aiming to develop standard data formats.

- [NMReDATA](http://nmredata.org/): Proposing a format for storing NMR data.
