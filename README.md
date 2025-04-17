# A metadata schema to standardize non-thermal plasma decontamination parameters in food-related applications

> **Repository:** `plasma-food-metadata-schema`  
> *Forked from [`plasma-mds/plasma-metadata-schema`](https://github.com/plasma-mds/plasma-metadata-schema) to extend Plasma-MDS for food-related decontamination applications.*

## About this repository
This repository accompanies the manuscript **“A metadata schema to standardize non-thermal plasma decontamination parameters in food-related applications.”** It contains two JSON files that implement a metadata schema designed to promote FAIR (findable, accessible, interoperable, and reusable) data principles in non-thermal plasma decontamination experiments in food-related applications.

The metadata schema was developed using [Adamant](https://plasma-mds.github.io/adamant/), a JSON schema-based metadata editor for research data management workflows. By providing a structured way to describe the relevant parameters, the repository aims to support reproducibility, comparability, and broader data integration across studies.

## Files Overview

1. **Full metadata schema**
   - **Filename:** `plasma-food-metadata-schema.json`  
   - **Description:** A single, integrated JSON schema that includes all relevant parameter categories (e.g., plasma source, plasma medium, plasma target, and plasma diagnostics) for describing non-thermal plasma decontamination experiments.

2. **Example case study**
   - **Filename:** `plasma-food-metadata-case-study.json`  
   - **Description:** A practical demonstration of how to apply the metadata schema in a real scenario. This example showcases the essential parameters and their structure, illustrating how to document a non-thermal plasma treatment of black peppercorns.

## How to Use These Files

1. **As a Reference or Template**  
   Use the metadata schema (`plasma_metadata_schema.json`) as a framework to structure and describe your own non-thermal plasma experiments.

2. **Explore the Example**  
   Consult the case study (`plasma_example_case_study.json`) to see how each parameter is utilized in an actual experimental setup, offering guidance on how to provide and format information in the schema.

## Contact
For inquiries or feedback, please reach out to:

- **George Pampoukis**:  
  [georgios.pampoukis@wur.nl](mailto:georgios.pampoukis@wur.nl)  
  [giorgospampoukis@gmail.com](mailto:giorgospampoukis@gmail.com)

Contributions and suggestions for improving this schema are welcome. Feel free to open an issue or submit a pull request.
