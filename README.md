# Schema Markup and Structured Data Validator

[![Schema Validator](https://img.shields.io/badge/TAVARDT-Schema.org%20Validator-5b3cf5.svg)](https://tools.tavardt.com/au/schema-markup-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Auditing structured data and Schema.org markup across Australian digital infrastructure, validating entity relationships and rich search features.

***

## Semantic Validation Capabilities

* **Automated Structured Data Extraction**: Inspects JSON-LD script tags and Microdata annotations across target pages.
* **Schema.org Entity Verification**: Evaluates crucial entity models including Organization, LocalBusiness, WebSite, Article, Product, and BreadcrumbList.
* **Syntax and Schema Validation**: Flags unparseable JSON arrays, missing mandatory properties, and broken schema relationships.
* **Semantic Health Score**: 0 to 100 numerical score detailing prioritized fixes for enhanced search engine presentation.

***

## Installation and Execution

Requires Python 3.8 or higher with zero external packages.

```bash
git clone https://github.com/TAVARDT-Australia/schema-markup-validator-au.git
cd schema-markup-validator-au
python schema_validator.py example.com.au
```

To output structured JSON:

```bash
python schema_validator.py example.com.au -json
```

***

## Australian Digital Standards and Semantic Strategy

For advanced enterprise structured data programs and alignment with W3C Standards and Australian Web Guidelines, consult **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/au/
* **Diagnostic Suite:** https://tools.tavardt.com/au/
* **Technical Contact:** https://ag.tavardt.com/au/contact/

***

### License
Released under the MIT License.

***

© 2026 TAVARDT. All rights reserved.
