# A metadata schema to standardize non-thermal plasma decontamination parameters in food-related applications

> **Repository:** `plasma-food-metadata-schema`  
> *Forked from [`plasma-mds/plasma-metadata-schema`](https://github.com/plasma-mds/plasma-metadata-schema) to extend Plasma-MDS for food-related decontamination applications.*

## About this repository
This repository accompanies the manuscript **“A metadata schema to standardize non-thermal plasma decontamination parameters in food-related applications.”** It now contains *three* JSON files that implement a metadata schema designed to promote FAIR (findable, accessible, interoperable, and reusable) data principles in non-thermal plasma decontamination experiments in food-related applications.

The metadata schema is based on [Plasma-MDS](https://doi.org/10.1038/s41597-020-00771-0) and was developed using [Adamant](https://doi.org/10.12688/f1000research.110875.2), a JSON schema-based metadata editor for research data management workflows. By providing a structured way to describe the relevant parameters, the repository aims to support reproducibility, comparability, and broader data integration across studies.

> **All three JSON files are also presented in tabular form in the manuscript.**

## Files Overview

1. **Full metadata schema**
   - **Filename:** `plasma-food-metadata-schema.json`  
   - **Description:** A single, integrated JSON schema that includes all relevant parameter categories (e.g., plasma source, plasma medium, plasma target, and plasma diagnostics) for describing non-thermal plasma decontamination experiments in food-related applications.

2. **DBD-specific metadata schema**  
   - **Filename:** `plasma-food-metadata-schema-dbd.json`  
   - **Description:** The same schema structure as above, but trimmed to the elements that are only applicable to dielectric-barrier-discharge (DBD) plasma devices and their associated diagnostics. Functionally, this file is identical to `plasma-food-metadata-schema.json` *plus* a handful of DBD-specific elements—demonstrating the flexibility of using the main schema as a foundation for **any** non-thermal plasma setup and extending it with additional parameters when needed.

3. **Example case study**
   - **Filename:** `plasma-food-metadata-case-study.json`  
   - **Description:** A practical demonstration of how to apply the metadata schema in a real scenario. This example showcases the essential parameters and their structure, illustrating how to document a non-thermal plasma treatment of black peppercorns contaminated with *Salmonella*.

## How to use these files
  
1. **As a reference or template**  
   - Load **either** `plasma-food-metadata-schema.json` **or** `plasma-food-metadata-schema-dbd.json` in [Adamant](https://plasma-mds.github.io/adamant) (or any JSON-Schema-aware editor).  
   - After the schema loads, Adamant renders a form-based interface; populate the fields with your experimental data to create a standards-compliant metadata file for your experiment.

2. **Consult the case study**  
   - With the DBD schema loaded, click the **“Upload”** button in Adamant and load `plasma-food-metadata-case-study.json`.  
   - The form will populate automatically, allowing you to visualise how the example was created and to use it as a blueprint for your own documentation.

## Contact
For inquiries or feedback, please reach out to:

- **George Pampoukis**:  
  [georgios.pampoukis@wur.nl](mailto:georgios.pampoukis@wur.nl)  
  [giorgospampoukis@gmail.com](mailto:giorgospampoukis@gmail.com)

Contributions and suggestions for improving this schema are welcome. Feel free to open an issue or submit a pull request.
