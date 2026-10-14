# PYTHON API CLIENT

![license](https://img.shields.io/badge/license-license-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-online_retail-lightgrey)

> Anticloud-hardened packaging of the upstream project `PYTHON_API_CLIENT` in category **ONLINE RETAIL**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** ONLINE RETAIL · **Upstream:** https://github.com/googleapis/google-api-python-client · **Upstream pin:** `da51708ed59e8e3d602b4a3c7389a66905f57677` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# Google API Client

[![PyPI version](https://badge.fury.io/py/google-api-python-client.svg)](https://badge.fury.io/py/google-api-python-client)

This is the [Google API Python client library](https://cloud.google.com/apis/docs/client-libraries-explained#google_api_client_libraries)
for Google's discovery based APIs. To get started, please see the
[docs folder](https://github.com/googleapis/google-api-python-client/blob/main/docs/README.md).

This library is considered complete and is in maintenance mode. This means
that we will address critical bugs and security issues but will not add any
new features.

This library is officially supported by Google.  However, the maintainers of
this project recommend using [Cloud Client Libraries for Python](https://github.com/googleapis/google-cloud-python),
where possible, for new code development. For more information, please visit
[Client Libraries Explained](https://cloud.google.com/apis/docs/client-libraries-explained).

## Version 2.0 Release
The 2.0 release of `google-api-python-client` includes a substantial reliability 
improvement, compared with 1.x, as discovery documents are now cached in the library 
rather than fetched dynamically. It is highly recommended to upgrade from v1.x to v2.x.

Only python 3.10 and newer is supported. If you are not able to upgrade python, then
please continue to use version 1.x as we will continue supporting python 2.7+ in
[v1](https://github.com/googleapis/google-api-python-client/tree/v1).

Discovery documents will no longer be retrieved dynamically when
you call `discovery.build()`. The discovery documents will instead be retrieved
from the client library directly. New versions of this library are released weekly.
As a result of caching the discovery documents, the size of this package is at least 
50 MB larger compared to the previous version. 

Please see the [Migration Guide](https://github.com/googleapis/google-api-python-client/blob/main/UPGRADING.md)
for more information.

## Documentation

See the [docs folder](https://github.com/googleapis/google-api-python-client/blob/main/docs/README.md) for more detailed instructions and additional documentation.

## Other Google API libraries

The maintainers of this project recommend using
[Cloud Client Libraries for Python](https://github.com/googleapis/google-cloud-python),
where possible, for new code development due to the following reasons:

With [Cloud Client Libraries for Python](https://github.com/googleapis/google-cloud-python):
- There is a separate client library for each API, so you can choose
which client libraries to download. Whereas, `google-api-python-client` is a
single client library for all APIs. As a result, the total package size for
`google-api-python-client` exceeds 50MB.
- There are stricter controls for breaking changes to the underlying APIs
as each client library is focused on a specific API.
- There are more features in these Cloud Client Libraries as each library is
focused on a specific API, and in some cases, the libraries are owned by team
who specialized in that API.
- Developers will benefit from intellisense.

For more information, please visit
[Client Libraries Explained](https://cloud.google.com/apis/docs/client-libraries-explained).

Although there are many benefits to moving to
[Cloud Client Libraries for Python](https://github.com/googleapis/google-cloud-python),
the maintainers want to emphasize that `google-api-python-client` will continue
to be supported.

For Google Ads API, we recommend using [Google Ads API Client Library for Python](https://github.com/googleads/google-ads-python/).

For Google Firebase Admin API, we recommend using [Firebase Admin Python SDK](https://github.com/firebase/firebase-admin-python).

## Installation

Install this library in a [virtualenv](https://virtualenv.pypa.io/en/latest/) using pip. virtualenv is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With virtualenv, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

### Mac/Linux

```bash
pip3 install virtualenv
virtualenv <your-env>
source <your-env>/bin/activate
<your-env>/bin/pip install google-api-python-client
```

### Windows

```batch
pip install virtualenv
virtualenv <your-env>
<your-env>\Scripts\activate
<your-env>\Scripts\pip.exe install google-api-python-client
```

## Supported Python Versions

Python 3.10, 3.11, 3.12, 3.13, and 3.14 are fully supported and tested. This library may work on later versions of 3, but we do not currently run tests against those versions.

## Unsupported Python Versions

Python < 3.10

## Third Party Libraries and Dependencies

The following libraries will be installed when you install the client library:
* [httplib2](https://github.com/httplib2/httplib2)
* [uritemplate](https://github.com/sigmavirus24/uritemplate)

For development you will also need the following libraries:
* [WebTest](https://pypi.org/project/WebTest/)
* [pyopenssl](https://pypi.python.org/pypi/pyOpenSSL)

## Contributing

Please see our [Contribution Guide](https://github.com/googleapis/google-api-python-client/blob/main/CONTRIBUTING.rst).
In particular, we love pull requests - but please make sure to sign
the contributor license agreement.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: setup.py; scanned in UPSTREAM_CLONE)
- Top-level source layout: `apiclient/`, `googleapiclient/`, `samples/`, `scripts/`, `testing/`, `tests/`, `tools/`
- Snapshot size: **9193 files**, **20608 lines of code** (measured; see Benchmarks)
- Primary languages: `.html` (8308), `.json` (640), `.py` (87), `.gif` (45), `.md` (30), `(none)` (28)
- Upstream commit pinned for this packaging: `da51708ed59e8e3d602b4a3c7389a66905f57677`

---

## Installation

from the client library directly. New versions of this library are released weekly.
As a result of caching the discovery documents, the size of this package is at least 
50 MB larger compared to the previous version. 

Please see the [Migration Guide](https://github.com/googleapis/google-api-python-client/blob/main/UPGRADING.md)
for more information.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

[v1](https://github.com/googleapis/google-api-python-client/tree/v1).

Discovery documents will no longer be retrieved dynamically when
you call `discovery.build()`. The discovery documents will instead be retrieved
from the client library directly. New versions of this library are released weekly.
As a result of caching the discovery documents, the size of this package is at least 
50 MB larger compared to the previous version. 

Please see the [Migration Guide](https://github.com/googleapis/google-api-python-client/blob/main/UPGRADING.md)
for more information.

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

[![PyPI version](https://badge.fury.io/py/google-api-python-client.svg)](https://badge.fury.io/py/google-api-python-client)

This is the [Google API Python client library](https://cloud.google.com/apis/docs/client-libraries-explained#google_api_client_libraries)
for Google's discovery based APIs. To get started, please see the
[docs folder](https://github.com/googleapis/google-api-python-client/blob/main/docs/README.md).

This library is considered complete and is in maintenance mode. This means
that we will address critical bugs and security issues but will not add any
new features.

This library is officially supported by Google.  However, the maintainers of
this project recommend using [Cloud Client Libraries for Python](https://github.com/googleapis/google-cloud-python),
where possible, for new code development. For more information, please visit
[Client Libraries Explained](https://cloud.google.com/apis/docs/client-libraries-explained).

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | setup.py |
| Files in snapshot | 9193 |
| Lines of code | 20608 |
| Dependency references | 5 |
| Dependencies by ecosystem | pypi: 5 |
| Upstream license | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | httplib2 | >=0.19.0,<1.0.0 | setup.py |
| pypi | google-auth | >=1.32.0,<3.0.0,!=2.24.0,!=2.25.0 | setup.py |
| pypi | google-auth-httplib2 | >=0.2.0, <1.0.0 | setup.py |
| pypi | google-api-core | >= 1.31.5, <3.0.0,!=2.0.*,!=2.1.*,!=2.2.*,!=2.3.0 | setup.py |
| pypi | uritemplate | >=3.0.1,<5 | setup.py |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

dependencies and versions, and indirectly permissions.

With virtualenv, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

*Section quoted from the upstream readme.*
Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.rst`:*

.. Generated by synthtool. DO NOT EDIT!
############
Contributing
############

#. **Please sign one of the contributor license agreements below.**
#. Fork the project, develop and test your code changes, add docs.
#. Make sure that your commit messages clearly describe the changes.
#. Send a pull request. (Please Read: `Faster Pull Request Reviews`_)

.. _Faster Pull Request Reviews: https://github.com/kubernetes/community/blob/master/contributors/guide/pull-requests.md#best-practices-for-faster-reviews

.. contents:: Here are some guidelines for hacking on the Google Cloud Client libraries.

***************
Adding Features
***************

In order to add a feature:

- The feature must be documented in both the API and narrative
  documentation.

- The feature must work fully on the following CPython versions:
  3.10, 3.11, 3.12, 3.13, and 3.14 on both UNIX and Windows.

- The feature must not add unnecessary dependencies (where
  "unnecessary" is of course subjective, but new dependencies should
  be discussed).

****************************
Using a Development Checkout
****************************

You'll have to create a development environment using a Git checkout:

- While logged into your GitHub account, navigate to the
  ``google-api-python-client`` `project`_ on GitHub.

- Fork and source the ``google-api-python-client`` project to your GitHub account by
  clicking the "Fork" button.

- source your fork of ``google-api-python-client`` from your GitHub account to your local
  computer, substituting your account username and specifying the destination
  as ``hack-on-google-api-python-client``.  E.g.::

   $ cd ${HOME}
   $ git source git@github.com:USERNAME/google-api-python-client.git hack-on-google-api-python-client
   $ cd hack-on-google-api-python-client
   # Configure remotes such that you can pull changes from the googleapis/google-api-python-client
   # project into your local project.
   $ git remote add upstream git@github.com:googleapis/google-api-python-client.git
   # fetch and merge changes from upstream into main
   $ git fetch upstream
   $ git merge upstream/main

Now your local project is set up such that you will push changes to your GitHub
project, from which you can submit a pull request.

To work on the codebase and run the tests, we recommend using ``nox``,
but you can also use a ``virtualenv`` of your own creation.

.. _repo: https://github.com/googleapis/google-api-python-client

Using ``nox``
=============

We use `nox <https://n

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: Apache-2.0** (evidence: `LICENSE` in the upstream snapshot).

License file excerpt:

```text
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original Apache-2.0 terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `Apache-2.0` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `PYTHON_API_CLIENT` (category: ONLINE RETAIL)
- **Upstream URL:** https://github.com/googleapis/google-api-python-client
- **Pinned commit (SHA):** `da51708ed59e8e3d602b4a3c7389a66905f57677`
- **Branch:** main
- **Pin provenance:** GitHub API commits/main. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`a34c5568c09b5813a359ab1abef0e254e5556d2f5f3afdb85fe40d314faa5692`.

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

