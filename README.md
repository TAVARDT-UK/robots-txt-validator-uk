# Robots.txt and Crawler Directives Validator

[![Robots.txt Validator](https://img.shields.io/badge/TAVARDT-Robots.txt-5b3cf5.svg)](https://tools.tavardt.com/uk/robots-txt-validator/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Technical robots.txt inspection tool preventing catastrophic indexation blocks, auditing bot access rules, and enforcing sitemap declarations.

Engineered and maintained by the search engine infrastructure practice at **TAVARDT**.

***

## Robots.txt Audit Capabilities

* **Critical Disallow Trap Detection**: Automated discovery of accidental `Disallow: /` directives that trigger site-wide de-indexing.
* **Search and AI Bot Governance**: Differentiated access controls for traditional search engines versus AI training scrapers.
* **Sitemap Declaration Auditing**: Verification of syntax, target status, and path accuracy for declared `Sitemap:` directives.
* **Directives Syntax Analysis**: Inspection of `Allow`, `Disallow`, wildcards, and `Crawl-delay` parameters.
* **Crawl Efficiency Benchmark**: Reproducible 0 to 100 scoring with prioritised configuration remediation.

***

## Installation and Execution

Requires Python 3.8 or higher with standard library only.

```bash
git clone https://github.com/TAVARDT-UK/robots-txt-validator-uk.git
cd robots-txt-validator-uk
python robots_validator.py https://example.co.uk
```

To output machine-readable JSON:

```bash
python robots_validator.py https://example.co.uk -json
```

***

## Online Validation Suite

For interactive robots.txt debugging and crawler simulation:

* **Official Robots.txt Validator**
* **TAVARDT Corporate Portal**

***

## Crawl Governance and Technical SEO Advisory

For enterprise crawl budget optimisation, bot management, and alignment with Robots Exclusion Protocol and Search Crawl Standards, contact the specialists at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/uk/
* **Diagnostic Suite:** https://tools.tavardt.com/uk/
* **Technical Contact:** https://ag.tavardt.com/uk/contact/

***

### License
Released under the MIT License. See [LICENSE](LICENSE) for full details.

***

© 2026 TAVARDT. All rights reserved.
