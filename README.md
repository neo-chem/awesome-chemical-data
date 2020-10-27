# Awesome data in (experimental) chemistry and materials science [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

We live in a data-driven age. To make use of all the data that is produced in (experimental) chemistry and materials science, standards for collecting and sharing of data are needed. Once the community agrees on standard schemas, they can be implemented in ELNs and the data can be re-used if shared via repositories.

| Symbol | Meaning                            |
| ------ | ---------------------------------- |
| 😴     | Currently not developed/maintained |
| 🔓     | Closed source                      |
| 📄     | Link to a paper                    |

## Contents

- [Electronic lab notebooks (ELN) / Laboratory infrastructure management systems (LIMS)](#electronic-lab-notebooks-eln--laboratory-infrastructure-management-systems-lims)
- [Repositories](#repositories)
- [Schemas/Ontologies](#schemasontologies)
- [Related compilations](#related-compilations)

## Electronic lab notebooks (ELN) / Laboratory infrastructure management systems (LIMS)

### Overviews

- [ELN comparison grid](https://datamanagement.hms.harvard.edu/electronic-lab-notebooks) by Harvard Biomedical Data.
- [ELN guidance](https://www.gurdon.cam.ac.uk/institute-life/computing/elnguidance) by the Gurdon institute of the University of Cambridge.
- [Comparison of ELNs](https://github.com/Labii/comparison-of-best-electronic-lab-notebook) by the Labii ELN.
- [List of ELNs](https://en.wikipedia.org/wiki/List_of_electronic_laboratory_notebook_software_packages) on Wikipedia.

### ELNs

- [c6h6](https://www.c6h6.org/): Developed by the [cheminfo organization](https://github.com/cheminfo), couchDB backend, modular frontend in JavaScript. [![Github Stars](https://img.shields.io/github/stars/cheminfo/roc-eln-docker?style=social)](https://github.com/cheminfo/roc-eln-docker) ![GitHub last commit](https://img.shields.io/github/last-commit/cheminfo/roc-eln-docker?style=social) [📄](https://onlinelibrary.wiley.com/doi/abs/10.1002/mrc.4669)
- [chemotion ELN](https://github.com/ComPlat/chemotion_ELN): Developed by Nicole Jung's group at KIT, with focus on organic chemistry. Written in JavaScript/Ruby. [![Github Stars](https://img.shields.io/github/stars/ComPlat/chemotion_ELN?style=social)](https://github.com/ComPlat/chemotion_ELN) ![GitHub last commit](https://img.shields.io/github/last-commit/ComPlat/chemotion_ELN?style=social) [📄](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5612905/pdf/13321_2017_Article_240.pdf)
- [openBIS](https://openbis.ch/): General purpose LIMS/ELN developed at ETH Zuerich, allows to add custom plugins and direct data analysis in Jupyter notebooks. Core written in Java. [📄](https://academic.oup.com/bioinformatics/article/32/4/638/1743839).
- [LabTrove](http://labtrove.org/): The ELN used for the [Open Source Malaria](http://malaria.ourexperiment.org/triazolopyrazine_se) project.

## Repositories

- [chemotion repository](https://www.chemotion-repository.net/welcome): Repository for molecules, reactions and research data.

- [Materials Commons](https://github.com/materials-commons/materialscommons.org): A site for Materials Scientists to collaborate, store and publish research. [![Github Stars](https://img.shields.io/github/stars/materials-commons/materialscommons.org?style=social)](https://github.com/materials-commons/materialscommons.org). ![GitHub last commit](https://img.shields.io/github/last-commit/materials-commons/materialscommons.org?style=social) [📄](https://link.springer.com/article/10.1007%2Fs11837-016-1998-7)

- [nmrshiftdb2](https://nmrshiftdb.nmr.uni-koeln.de/) Repository for NMR data. A major rework of the software is pending. Use of NMReDATA is central. Can include raw data and processed data (currently the case for some entries, mostly peak lists). Integration in workflows is possible (e. g. prediction usedin chemotion).

## Schemas/Ontologies

### Overviews

- [Pachl, C.; Frank, N.; Breitbart, J.; Bräse, S. Overview of Chemical Ontologies. arXiv:2002.03842 [cs] 2020.](https://arxiv.org/pdf/2002.03842.pdf)

### Generic

- [SciData](https://github.com/stuchalk/scidata): Scientific data model (SDM) and related ontology (SDMO). [![Github Stars](https://img.shields.io/github/stars/stuchalk/scidata?style=social)](https://github.com/stuchalk/scidata) ![GitHub last commit](https://img.shields.io/github/last-commit/stuchalk/scidata?style=social)

- [oreChem](https://www.openarchives.org/oreChem/2010/05/24-orechem-ns): Its goal was to create an ontology for scientific experiments, was funded by Microsoft research. "The oreChem s Ontology [eo] describes (a) the planned method of a scientific experiment; (b) the enactment of plans and (c) the provenance of objects realised during enactments." [📄](https://eprints.soton.ac.uk/179619/1/05693933.pdf). 😴

- [elnItemManifest](https://sourceforge.net/p/labtrove/code/HEAD/tree/trunk/schemas/): Describes core metadata for ELNs (like title, keywords, identifiers, contact, license information, related items, contributors, content, source). [📄](https://link.springer.com/article/10.1186/1758-2946-5-52#Sec3). 😴

- [autoprotocol](https://autoprotocol.org/): Language for specifying experimental protocols. Has with [Autoprotocol standard changes](https://autoprotocol.org/ascs/) a mechanism similar to Python enhancement proposals for changes in the standard. [![Github Stars](https://img.shields.io/github/stars/autoprotocol/autoprotocol-python?style=social)](https://github.com/autoprotocol/autoprotocol-python) ![GitHub last commit](https://img.shields.io/github/last-commit/autoprotocol/autoprotocol-python?style=social)

- [Chemical Markup Language (CML)](http://www.xml-cml.org/): XML for most chemistry, especially molecules, compounds, reactions, spectra, crystals and computational chemistry, developed by Peter Murray-Rust and Henry Rzepa. [📄](https://dx.doi.org/10.1186/1758-2946-3-44) 😴 ([Last Update: 2013-04-22](https://sourceforge.net/projects/cml/))

- [European Materials and Modelling Ontology (EMMO)](https://emmc.info/emmo-info/): An ontology designed to represent the "complex multiscale nature of chemicals and materials" with varying analytical philosophical interpretations. Available from the [emmo-repo](https://github.com/emmo-repo/) organisation on GitHub. [![Github Stars](https://img.shields.io/github/stars/emmo-repo/EMMO?style=social)](https://github.com/emmo-repo/EMMO) ![GitHub last commit](https://img.shields.io/github/last-commit/emmo-repo/EMMO?style=social)

- [Materials Genome Initiative JSON](https://github.com/usnistgov/mgi-json-schema): JSON schema for materials science and engineering. [![Github Stars](https://img.shields.io/github/stars/usnistgov/mgi-json-schema?style=social)](https://github.com/usnistgov/mgi-json-schema) ![GitHub last commit](https://img.shields.io/github/last-commit/usnistgov/mgi-json-schema?style=social)

### Analytical methods

- [Chemical Methods Ontology](https://github.com/rsc-ontologies/rsc-cmo): Describes methods used to collect data in chemical experiments, based on the IUPAC Orange Book in ontology language (OBO and OWL).[![Github Stars](https://img.shields.io/github/stars/rsc-ontologies/rsc-cmo?style=social)](https://github.com/rsc-ontologies/rsc-cmo) ![GitHub last commit](https://img.shields.io/github/last-commit/rsc-ontologies/rsc-cmo?style=social)
- [Chemical Analysis Metadata Platform](http://champ-project.org/): Ontology, Vocabularies, Metadata for Chemical Analysis. 😴
- [Analytical Information Markup Language (AnIML)](https://animl.org/): American Society for Testing and Materials (ASTM) XML standard for analytical chemistry and biological data, with [regular meetings](https://animl.org/meetings).

### Organic reactions

- [RXNO: reaction ontologies](https://github.com/rsc-ontologies/rxno): Name reaction ontology. [![Github Stars](https://img.shields.io/github/stars/rsc-ontologies/rxno?style=social)](https://github.com/rsc-ontologies/rxno) ![GitHub last commit](https://img.shields.io/github/last-commit/rsc-ontologies/rxno?style=social)
- [Molecular process ontology (MOP)](https://www.ebi.ac.uk/ols/ontologies/mop): Molecular processes that underlie the name reaction ontology RXNO.
- [ord-schema](https://github.com/Open-Reaction-Database/ord-schema): Schema for organic reactions developed for the open reaction database. [![Github Stars](https://img.shields.io/github/stars/Open-Reaction-Database/ord-schema?style=social)](https://github.com/Open-Reaction-Database/ord-schema) ![GitHub last commit](https://img.shields.io/github/last-commit/Open-Reaction-Database/ord-schema?style=social)

### Biology

- [SD2E/opil](https://github.com/SD2E/opil) Synthetic biology experiment description effort intended to standardize the interface between human-generated experimental requests and lab-automated protocol. [![Github Stars](https://img.shields.io/github/stars/SD2E/opil?style=social)](https://github.com/Open-Reaction-Database/ord-schema) ![GitHub last commit](https://img.shields.io/github/last-commit/SD2E/opil?style=social)

### Materials synthesis

### Materials properties

- [MatML](https://www.matml.org/): XML format for the interchange of materials information. 😴

- [Physical information file (PIF)](https://citrineinformatics.github.io/pif-documentation/index.html): Schema for information about physical systems, maintained by Citrine informatics. [![Github Stars](https://img.shields.io/github/stars/CitrineInformatics/pypif?style=social)](https://github.com/CitrineInformatics/pypif) ![GitHub last commit](https://img.shields.io/github/last-commit/CitrineInformatics/pypif?style=social)

### Spectral data

- [NMReDATA](http://nmredata.org/): Proposing a format for storing NMR data. [![Github Stars](https://img.shields.io/github/stars/NMReDATAInitiative/javatools?style=social)](https://github.com/NMReDATAInitiative/javatools) ![GitHub last commit](https://img.shields.io/github/last-commit/NMReDATAInitiative/javatools?style=social)

- [JCAMP-DX](http://www.jcamp-dx.org/): Joint Committee on Atomic and Molecular Physical Data (JCAMP) data extension file for spectral data. Used by the [c6h6 eln](https://www.c6h6.org/).

- [nmrML](https://github.com/nmrML/nmrML): Open mark-up language for NMR raw and spectral data. [![Github Stars](https://img.shields.io/github/stars/nmrML/nmrML?style=social)](https://github.com/nmrML/nmrML) ![GitHub last commit](https://img.shields.io/github/last-commit/nmrML/nmrML?style=social) [📄](https://pubs.acs.org/doi/10.1021/acs.analchem.7b02795).

- [CMLSpect](https://sourceforge.net/projects/cml/): XML Vocabulary for Spectral Data (extension of CML). [📄](https://pubs.acs.org/doi/10.1021/ci600531a) 😴 ([Last Update: 2013-04-22](https://sourceforge.net/projects/cml/)).

## Initiatives/Consortia

- [NFDI4Chem](https://www.nfdi4chem.de/): Initiative to build an open and FAIR infrastructure for research data management in chemistry.

- [Blue Obelisk](https://blueobelisk.github.io/): Internet group promoting reusable chemistry via open source software development. [📄](https://pubs.acs.org/doi/10.1021/ci050400b) [📄](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-3-37)

- [GO FAIR Chemistry Implementation Network](https://www.go-fair.org/implementation-networks/overview/chemistryin/): Goals are "to enhance the open, FAIR and effective communication of chemical knowledge within the chemical sciences and between chemistry and other disciplines" and "to enable chemists and chemistry to contribute to the achievement of the UN Global Sustainable Development goals" (direct quotes from the website). [📄](https://www.mitpressjournals.org/doi/full/10.1162/dint_a_00035)

- [Chemistry Research Data IG](https://www.rd-alliance.org/groups/chemistry-research-data-interest-group.html): Interest Group of the Research Data Alliance (RDA) that aims to foster exchange on chemical data.

- [RDA/CODATA Materials Data, Infrastructure & Interoperability IG](https://www.rd-alliance.org/groups/rdacodata-materials-data-infrastructure-interoperability-ig.html): Interest Group of the Research Data Alliance (RDA) that aims to foster exchange on material data.

## Related compilations

- [Awesome Materials Informatics](https://github.com/tilde-lab/awesome-materials-informatics): In contrast to this compilation, [Awesome Materials Informatics](https://github.com/tilde-lab/awesome-materials-informatics) focuses more on computational materials science.

- [FAIRsharing.org](https://fairsharing.org) domain collections for [Chemistry](https://fairsharing.org/collection/Chemistry) and [Semantic Assets for Materials Science](https://fairsharing.org/collection/SemanticAssetsMatSci).
