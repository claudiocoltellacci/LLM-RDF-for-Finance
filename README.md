# LLM-RDF-for-Finance

## Overview

**LLM-RDF-for-Finance** is a project that leverages a finance-focused Knowledge Graph, represented in RDF (Turtle) format, and integrates with Large Language Models (LLMs) to enable advanced querying and reasoning in the financial domain.

## Repository Contents

- [`ultimate_financial_ontology.ttl`](ultimate_financial_ontology.ttl):  
  The main Knowledge Graph of the project, containing both the schema and financial data, encoded in Turtle format.
- [`Financial Analysis_Print.pdf`](Financial%20Analysis_Print.pdf):  
  Project documentation. This PDF details the sources, methodology, and reasoning that shaped the Knowledge Graph and project direction.
- **SPARQL Query Template**:  
  The repository includes a template for SPARQL queries, allowing for straightforward interrogation of the Knowledge Graph.

## Features

- **Finance Knowledge Graph**:  
  A comprehensive graph of financial concepts, relationships, and real-world data, designed for semantic querying and advanced analytics.
- **LLM Integration**:  
  Integration with Mistral LLMs (Research license required, API access needed) for natural language querying, enrichment, or reasoning over the graph.
- **Transparent Documentation**:  
  All sources and design choices are explained in the included PDF documentation.
- **Built with VocBench**:  
  The Knowledge Graph was created and managed using [VocBench](https://vocbench.uniroma2.it/), an advanced web-based platform for collaborative development of semantic resources.

## Getting Started

### Prerequisites

- [VocBench](https://vocbench.uniroma2.it/) or any RDF-compatible triple store/viewer to load and explore the Knowledge Graph.
- A PDF reader for the documentation.
- Access to Mistral LLMs (with a Research license and API key) if you wish to use the LLM integration.

### Usage

1. **Opening the Knowledge Graph**:  
   Load `ultimate_financial_ontology.ttl` in VocBench or your preferred RDF tool.
2. **Consulting Documentation**:  
   Refer to `Financial Analysis_Print.pdf` for in-depth explanation of the graph’s structure, sources, and the rationale behind it.
3. **Querying the Graph**:  
   Use the included SPARQL query template to interact with the Knowledge Graph.
4. **LLM Integration**:  
   To enable natural language interaction or advanced reasoning, set up your Mistral API credentials as per the integration scripts (see project files for details). Ensure you have a valid Mistral Research license.

## Contribution

Contributions are welcome! Please open issues or submit pull requests for improvements, bug reports, or new features.

## License

*# Licensing

## Code (scripts, integration):

MIT License

Copyright (c) 2025 Claudio Coltellacci

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

## Knowledge Graph and Documentation (`ultimate_financial_ontology.ttl`, `Financial Analysis_Print.pdf`):

Licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

You are free to:

- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
*

## Contact

GitHub: [claudiocoltellacci](https://github.com/claudiocoltellacci)

---

*This README reflects the current state and aims of the project. For further technical details, consult the included documentation PDF.*
