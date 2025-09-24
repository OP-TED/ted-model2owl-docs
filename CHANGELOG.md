# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]
### Added
- Description of a new `imports.xml` configuration file enabling fine-grained
  control of URIs included in `owl:imports` statements for each
  generated RDF artefact (TEDM2O-21).
- Description of a new `annotateShaclConceptsWithOntology` parameter, which
  enables the generation of rdfs:isDefinedBy statements in SHACL shapes
  (TEDM2O-18).
- Description of a new `nodeShapeURIsuffix` parameter, which specifies how URIs
  for SHACL node shapes are constructed (TEDM2O-19).

### Changed
- Transformation rules for cardinality constraints (TEDM2O-33).
- Description of the model2owl CLI for the import statements file (TEDM2O-21).

### Removed
- Documentation of the abandoned `R.18` transformation rule for disjointness
  among sibling classes in generalizations (TEDM2O-15).
