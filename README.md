# Mapping UK Biobank to the Experimental Factor Ontology (EFO)
UK Biobank is a massive datasource for population health data used extensively in research. Some of the clinical data is mapped to ICD-10, but coverage is incomplete, as are mappings from existing ICD-10 codes to public ontologies. Here, we describe a pipeline to map 1,552 UK Biobank traits to public ontology terms via the Experimental Factor Ontolo- gy. Our approach uses ontology mapping services and man- ual curation to provide almost complete coverage (97%), thus increasing interoperability of UK Biobank with public datasets. Both mappings and services described are freely available for use and the mapping pipeline represents a typi- cal curation workflow that can be adopted for other domains.

## This repository contains:

- The mapping masterfile TSV containing all up to date mappings of UK Biobank and ICD10 to EFO mappings.
- The [Zooma](https://www.ebi.ac.uk/spot/zooma/) dataset CSV, containing all mappings in the Zooma format. The mappings are available in Zooma.
- The ISMB ECCB 2019 paper outlining our mapping process and results.