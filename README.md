# OEB-ontologies
We want to do the validation that do mongo with collections with two ontologies. One about formats (FASTA, JSON, TAR,...) linked to ontology EDAM, and other ontology with datasets importing the other ontology and linked to that. 

## dataFormats ontology
Based on [EDAM](http://edamontology.org/EDAM.owl), **dataFormats** imports it with some extra data formats (classes) and properties

- New classes: TAR, Log, ERR
- New properties: file_extension

## OEBdatasets ontology
Describes the different types of datasets involved in OpenEBench platform. **OEBdatasets** imports dataFormats' ontology to better define dataset's files adding 'file_type' properties.


