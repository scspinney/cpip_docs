# Phenotyping

Phenotyping data for the C-PIP project includes demographic information, clinical scores, genetic data, and tabular measures derived from MRI processing.

## Data types

Phenotyping data may include information such as:

* participant demographics
* clinical and behavioral scores
* genetic data
* processed MRI-derived measures stored in tabular files, such as regional volumes

## Data management

Processed phenotyping data is intended to be stored in a relational database. This allows efficient querying, retrieval, and integration with other project data.

## Combining with MRI data

Phenotyping data can be combined with raw or processed MRI data for comprehensive analysis across imaging, clinical, demographic, and behavioral measures.

## Subject IDs in REDCap

For multi-site studies, subject IDs should be unique across all sites. A practical approach is to combine a site-specific code with a sequential participant number.

Example IDs:

* `SITE1-001`
* `SITE1-002`
* `SITE2-001`
* `SITE2-002`

Recruitment IDs and consented participant IDs should be tracked separately when possible. Recruitment records can store pre-consent information, while consented records can use the main study subject ID.

For studies involving families or parent-child pairs, a shared family ID can be used to link related participants.

## New heading!!!
