# DiSSCo openDS Vocabulary Repository


## Introduction
This repository (code-named **orpheus**) manages terms and controlled vocabularies used in the DiSSCo openDS schema. It supports standardisation and interoperability by defining terms and their values in a structured format. 
The openDS Terms are available at: [https://terms.dissco.tech/](https://terms.dissco.tech/).

## Background

This repository follows the TDWG guidance on vocabulary management ([TDWG Maintenance Specification](https://github.com/tdwg/vocab/blob/master/vms/maintenance-specification.md)).

### Key Definitions
Borrowing the definitions from TDWG: 

**term** - an entity representing a class, property, or concept. A term is identified by an Internationalised Resource Identifier (IRI), may have one or more human-readable labels, and is defined by a series of properties that include a human-readable definition. Terms and their values are used to communicate information about a subject resource.

**vocabulary** - a collection of standardised terms and their definitions.


Vocabularies can be enhanced by building upon this basic term layer. Added features may include:

- constraining the use of literal-value terms through data types
- establishing relationships among class terms by applying a domain model
- introducing additional term properties that generate entailments that can be materialized through machine reasoning

## Structure
This repository includes:
- **Terms**: High-level categories that define a concept (e.g., `ods:topicOrigin`, `ods:topicDiscipline`).
- **Controlled Vocabularies**: Predefined values associated with a term, each with a PID and SKOS-based definition.


### Example 1: `ods:topicOrigin` (Term)
- **Definition**: Describes the origin of a topic in the DiSSCo schema.
- **Controlled Vocabulary Values**:
  - `Natural`
  - `Human-made`
  - `Mixed origin`
  - `Unclassified`

Each value is represented as with a JSON Schema. 


### Example 2: `ods:topicDiscipline` (Term)
- **Definition**: A controlled vocabulary for disciplines associated with topics in the DiSSCo schema.
- **Controlled Vocabulary Values**:
  - `Anthropology`
  - `Botany`
  - `Astrogeology`
  - `Geology`
  - `Microbiology`
  - `Palaeontology`
  - `Zoology`
  - `Ecology`
  - `Other Biodiversity`
  - `Other Geodiversity`
  - `Unclassified`

## Contributing
We welcome feedback from the community to improve these terms and vocabularies.


Thank you for contributing to the development of the DiSSCo openDS vocabulary. 

