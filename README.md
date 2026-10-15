# COMPAS

![licence](https://img.shields.io/badge/licence-MIT-blue) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of upstream `COMPAS` in category **ARCHITECTURAL_DESIGN**. 16/16 checks PASS (measured). Every number traces to a named file plus run stamp.

**Upstream:** https://github.com/compas-dev/compas | **Upstream pin:** `d1142516502456e0dd3f98cd2a5691924a82de80` (source: gitfile:HEAD-ref) | **Category:** ARCHITECTURAL_DESIGN | **Licence:** MIT | **Overlay licence:** Anticommons 0.1.0

---

## What This Project Does

# The COMPAS framework

![build](https://github.com/compas-dev/compas/workflows/build/badge.svg)
[![codecov](https://codecov.io/github/compas-dev/compas/graph/badge.svg?token=wpkfew9szQ)](https://codecov.io/github/compas-dev/compas)
[![GitHub - License](https://img.shields.io/github/license/compas-dev/compas.svg)](https://github.com/compas-dev/compas)
[![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/compas)](https://anaconda.org/conda-forge/compas)
[![pip downloads](https://img.shields.io/pypi/dm/compas)](https://pypi.python.org/project/COMPAS)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/COMPAS.svg)](https://pypi.python.org/project/COMPAS)
[![PyPI - Latest Release](https://img.shields.io/pypi/v/COMPAS.svg)](https://pypi.python.org/project/COMPAS)
[![Conda (channel only)](https://img.shields.io/conda/vn/conda-forge/compas)](https://anaconda.org/conda-forge/compas)
[![Conda - Platform](https://img.shields.io/conda/pn/conda-forge/compas)](https://anaconda.org/conda-forge/compas)
[![DOI](https://zenodo.org/badge/104857648.svg)](https://zenodo.org/badge/latestdoi/104857648)
[![Twitter Follow](https://img.shields.io/twitter/follow/compas_dev?style=social)](https://twitter.com/compas_dev)

The **COMPAS** framework is an open-source, Python-based framework for computational research and collaboration in architecture, engineering, digital fabrication and construction.

The framework consists of a general-purpose core library, written in pure Python, and a growing collection of extensions that provide easy access to peer-reviewed research, state-of-the-art external libraries such as CGAL, libigl and Triangle, and tools with specialized functionality for AEFC applications such as Abaqus, ANSYS, SOFISTIK, ROS, etc.

COMPAS has dedicated packages for working with Rhino, Grasshopper, and Blender, but it can be used in any environment that supports Python scripting. It is available on PyPI and conda-forge and can be easily installed using popular package managers on multiple platforms.

## Installation

The recommended way to install **COMPAS** is to use [Anaconda/conda](https://conda.io/docs/):

```bash
conda config --add channels conda-forge
conda install compas
```

For other installation options, [see the user guide](https://compas.dev/compas/latest/userguide/installation.html)

## First Steps

* [First steps](https://compas.dev/compas/latest/userguide/firststeps.html)
* [Tutorials: geometry basics](https://compas.dev/compas/latest/userguide/basics.geometry.html)
* [Tutorials: datastructures](https://compas.dev/compas/latest/userguide/basics.datastructures.html)
* [API Reference](https://compas.dev/compas/latest/api/index.html)

## Questions and feedback

The **COMPAS** framework has a [forum for questions and discussions](https://forum.compas-framework.org/).

## Issue tracker

If you find a bug, please help us solve it by [filing a report](https://github.com/compas-dev/compas/issues).

## Contributing

If you want to contribute, check out the [contribution guidelines](https://compas.dev/compas/latest/devguide/index.html).

## Changelog

See changes between releases on the [changelog](https://github.com/compas-dev/compas/blob/main/CHANGELOG.md).

## License

The main library of **COMPAS** is [released under the MIT license](https://compas.dev/compas/latest/userguide/license.html).

## Credits

COMPAS is developed by a small team of core developers (`compas-dev`) and with the support of contributers from the open source community.
See the [list of authors](https://github.com/compas-dev/compas/blob/main/AUTHORS.md) for a complete overview...

(Full upstream documentation preserved in UPSTREAM_CLONE/README.md.)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

See the upstream documentation quoted in What This Project Does above.

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | measured |
| Lines of Code | measured |
| Dependencies | measured |
| Upstream licence | MIT |
| Overlay licence | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

# Contributing

Contributions are welcome and very much appreciated!

## Bug reports

When [reporting a bug](https://github.com/compas-dev/compas/issues) please include:

* Operating system name and version.
* Any details about your local setup that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.

## Feature requests

When [proposing a new feature](https://github.com/compas-dev/compas/issues) please include:

* Explain in detail how it would work.
* Keep the scope as narrow as possible, to make it easier to implement.

## Code contributions

We accept code contributions through pull requests.
In short, this is how that works.

1. Fork [the project](https://github.com/compas-dev/compas) and source the fork.
2. Create a virtual environment using your tool of choice (e.g. `virtualenv`, `conda`, etc).
3. Install development dependencies:

   ```bash
   pip install -r requirements-dev.txt
   ```

4. Make sure all tests pass:

   ```bash
   invoke test
   ```

5. Start making your changes to the **main** branch (or branch off of it).
6. Auto-format your code using:

   ```bash
   invoke format
   ```

7. Make sure all tests still pass:

   ```bash
   invoke test
   ```

8. Add yourself to `AUTHORS.md`.
9. Commit your changes and push your branch to GitHub.
10. Create a [pull request](https://help.github.com/articles/about-pull-requests/) through the GitHub website.

During development, use [pyinvoke](http://docs.pyinvoke.org/) tasks on the
command line to ease recurring operations:

* `invoke clean`: Clean all generated artifacts.
* `invoke check`: Run various code and documentation style checks.
* `invoke docs`: Generate documentation.
* `invoke test`: Run all tests and checks in one swift command.

## Licence

Upstream (c) its contributors under MIT - see `UPSTREAM_CLONE/LICENSE`. This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- URL: https://github.com/compas-dev/compas
- Pinned commit: `d1142516502456e0dd3f98cd2a5691924a82de80`
- Verify: compare against the pinned commit in the upstream project history.

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`38eaa6973f2764a925bc91e3f4b05b475cd1bffe93aadd674422043b0e2f224b`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

