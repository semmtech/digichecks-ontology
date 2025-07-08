# DigiChecks Permit Ontology

This repository contains the DigiChecks Permit Ontology, a top-level ontology for describing permitting processes, requirements, and verification activities. The ontology is based on the Semantic Modelling and Linking (SML, EN 17632) framework and provides core terminology for DigiChecks services to communicate unambiguously about permitting processes.

## Overview

- **Ontology file:** [`Top-level_permit_ontology_digichecks-internal-review_20240610_2025-04-29_1700.ttl`](Top-level_permit_ontology_digichecks-internal-review_20240610_2025-04-29_1700.ttl)
- **Documentation:** See the [`doc/`](doc/) folder for generated documentation, including HTML, JSON-LD, and OWL serializations.
- **Pilot projects:** Example SHACL rules and project-specific ontologies are available in [`Pilot projects/`](Pilot projects/).

## Features

- Core classes and properties for projects, permits, requirements, verifications, decisions, documents, and locations.
- SHACL shapes for data validation.
- Alignment with existing standards (SML, PROV, GeoSPARQL, SKOS, DC Terms, etc.).
- Example rules and project-specific extensions for Austria, Spain, United Kingdom, and IFC-based models.

## Getting Started

1. **Explore the ontology:**  
   Open the main ontology file or browse the documentation in [`doc/`](doc/).

2. **Use in your project:**  
   Import the ontology into your RDF/OWL tool or triple store.  
   Example (Turtle):
   ```
   @prefix checks: <https://data.digichecks.eu/def/> .
   @prefix sml: <https://w3id.org/sml/def#> .
   # ...other prefixes...
   ```

3. **Validate data:**  
   Use the SHACL shapes provided in the ontology to validate your data.

## Funding

This research has received funding from the European Union’s Horizon Research and Innovation Program under grant agreement no. 101058541.

## License

This ontology is licensed under [CC-BY](LICENSE).

## How to Cite

If you use this ontology, please cite as:

> To be announced.

## Contact

For questions or contributions, please open an issue or contact maintainers at coenvangruijthuijsen@semmtech.nl

---