# Changelog

All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]
### Added
- New category of transformation rules for JSON-LD context generation
  (TEDM2O-7).
- New _ReSpec documentation_ page for the ReSpec generation feature (TEDM2O-11).
- New section describing existing and new metadata stored in the `metadata.json`
  (TEDM2O-11).
- Description of a new `imports.xml` configuration file enabling fine-grained
  control of URIs included in `owl:imports` statements for each
  generated RDF artefact (TEDM2O-21).
- Description of a new `annotateShaclConceptsWithOntology` parameter, which
  enables the generation of rdfs:isDefinedBy statements in SHACL shapes
  (TEDM2O-18).
- Description of a new `nodeShapeURIsuffix` parameter, which specifies how URIs
  for SHACL node shapes are constructed (TEDM2O-19).

### Changed
- Updates on the _Configuration parameters_ page reflecting move of metadata
  from from `config-parameters.xml` to `metadata.json` file (TEDM2O-11).
- Transformation rules for cardinality constraints (TEDM2O-33).
- Description of the model2owl CLI for the import statements file (TEDM2O-21).

### Removed
- Documentation of the abandoned `R.18` transformation rule for disjointness
  among sibling classes in generalizations (TEDM2O-15).


## [3.0.0] — 2025-03-21
### Added
- Documentation of new transformation rules and conventions for controlled
  vocabularies ([Task 2: Export of controlled vocabulary
  restrictions](https://github.com/OP-TED/model2owl/issues/228)) by @gkostkowski
  in https://github.com/OP-TED/ted-model2owl-docs/pull/6
- Documentation of new transformation rules and conventions for tags and
  comments ([Task 3: Export of metadata about
  concepts](https://github.com/OP-TED/model2owl/issues/229)) by @gkostkowski in
  https://github.com/OP-TED/ted-model2owl-docs/pull/7
- User guide providing general instructions and documenting new features ([Task
  1: Status-based filtering](https://github.com/OP-TED/model2owl/issues/226),
  [Task 2: Export of controlled vocabulary
  restrictions](https://github.com/OP-TED/model2owl/issues/228), [Task 3: Export
  of metadata about concepts](https://github.com/OP-TED/model2owl/issues/229))
  by @Dragos0000 in https://github.com/OP-TED/ted-model2owl-docs/pull/9
- Documentation of conventions and checkers for property inheritance
  (https://github.com/OP-TED/model2owl/issues/205) by @gkostkowski in
  https://github.com/OP-TED/ted-model2owl-docs/pull/10


## [2.3.0-rc.1] — 2024-12-06
### Changed
- Cleaned-up the documentation structure
- Fixed documentation version
- Changed version number to correspond to the relevant [model2owl
  version](https://github.com/OP-TED/model2owl/releases/tag/2.3.0-rc.2)
