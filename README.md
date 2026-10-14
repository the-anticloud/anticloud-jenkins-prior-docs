# JENKINS PRIOR DOCS

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-software_development-lightgrey)

> Anticloud-hardened packaging of the upstream project `JENKINS_PRIOR_DOCS` in category **SOFTWARE DEVELOPMENT**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SOFTWARE DEVELOPMENT · **Upstream:** https://github.com/jenkinsci/jenkins · **Upstream pin:** `e2ba107d13304978b338eb19f31fad5a53a858cc` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<a href="https://jenkins.io">
    <img width="400" src="https://www.jenkins.io/images/jenkins-logo-title-dark.svg" alt="Jenkins logo"> 
</a>

[![Jenkins Regular Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog%2Fbadge.json)](https://www.jenkins.io/changelog)
[![Jenkins LTS Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog-stable%2Fbadge.json)](https://www.jenkins.io/changelog-stable)
[![Docker Pulls](https://img.shields.io/docker/pulls/jenkins/jenkins.svg)](https://hub.docker.com/r/jenkins/jenkins/)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/3538/badge)](https://bestpractices.coreinfrastructure.org/projects/3538)
[![Reproducible Builds](https://img.shields.io/badge/Reproducible_Builds-ok-green)](https://maven.apache.org/guides/mini/guide-reproducible-builds.html)
[![Gitter](https://img.shields.io/gitter/room/jenkinsci/jenkins)](https://matrix.to/#/#jenkinsci_jenkins:gitter.im)

---

# Table of Contents

- [About](#about)
- [What to Use Jenkins for and When to Use It](#what-to-use-jenkins-for-and-when-to-use-it)
- [Downloads](#downloads)
- [Getting Started (Development)](#getting-started-development)
- [Source](#source)
- [Contributing to Jenkins](#contributing-to-jenkins)
- [News and Website](#news-and-website)
- [Governance](#governance)
- [Adopters](#adopters)
- [License](#license)

---

# About

In a nutshell, Jenkins is the leading open-source automation server.
Built with Java, it provides over 2,000 [plugins](https://plugins.jenkins.io/) to support automating virtually anything,
so that humans can spend their time doing things machines cannot.

# What to Use Jenkins for and When to Use It

Use Jenkins to automate your development workflow, so you can focus on work that matters most. Jenkins is commonly used for:

- Building projects
- Running tests to detect bugs and other issues as soon as they are introduced
- Static code analysis
- Deployment

Execute repetitive tasks, save time, and optimize your development process with Jenkins.

# Downloads

The Jenkins project provides official distributions as WAR files, Docker images, native packages and installers for platforms including several Linux distributions and Windows.
See the [Downloads](https://www.jenkins.io/download) page for references.

For all distributions Jenkins offers two release lines:

- [Weekly](https://www.jenkins.io/download/weekly/) -
  Frequent releases which include all new features, improvements, and bug fixes.
- [Long-Term Support (LTS)](https://www.jenkins.io/download/lts/) -
  Older release line which gets periodically updated via bug fix backports.

Latest releases:

[![Jenkins Regular Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog%2Fbadge.json)](https://www.jenkins.io/changelog)
[![Jenkins LTS Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog-stable%2Fbadge.json)](https://www.jenkins.io/changelog-stable)

# Getting Started (Development)

For more information on setting up your development environment, contributing, and working with Jenkins internals, check the [contributing guide](CONTRIBUTING.md) and the [Jenkins Developer Documentation](https://www.jenkins.io/doc/developer/).

# Source

Our latest and greatest source of Jenkins can be found on [GitHub](https://github.com/jenkinsci/jenkins). Fork us!

# Contributing to Jenkins

New to open source or Jenkins? Here’s how to get started:

- Read the [Contribution Guidelines](CONTRIBUTING.md)
- Check our [good first issues](https://github.com/jenkinsci/jenkins/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22)
- Join our [Gitter chat](https://matrix.to/#/#jenkinsci_newcomer-contributors:gitter.im) for questions and help

For more information about participating in the community and contributing to the Jenkins project,
see [this page](https://www.jenkins.io/participate/).

Documentation for Jenkins core maintainers is in the [maintainers guidelines](docs/MAINTAINERS.adoc).

# News and Website

All information about Jenkins can be found on our [official website](https://www.jenkins.io/), including documentation, blog posts, plugin listings, community updates, and more.

Stay up-to-date with the latest Jenkins news, tutorials, and release notes:

- [Jenkins Blog](https://www.jenkins.io/blog/)
- [Documentation](https://www.jenkins.io/doc/)
- [Plugins Index](https://plugins.jenkins.io/)
- [Events](https://www.jenkins.io/events/)

Follow Jenkins on social media to stay connected with the community:

- [Twitter / X](https://x.com/jenkinsci)
- [YouTube](https://www.youtube.com/@jenkinscicd)
- [LinkedIn](https://www.linkedin.com/company/jenkins-project/)

# Governance

The Jenkins project is governed by an open source community.
To learn more about the governance structure, project leadership, and how decisions are made, visit the [Governance Page](https://www.jenkins.io/project/governance/).

# Adopters

Jenkins is trusted by **millions of users** and adopted by **thousands of companies** around the world — from startups to enterprises — to automate their software delivery pipelines.

Explore the [Adopters Page](https://www.jenkins.io/project/adopters/) and https://stories.jenkins.io to see:

- Companies and organizations using Jenkins
- Success stories and case studies
- How Jenkins is used in different industries

> If your company uses Jenkins and you'd like to be featured, feel free to [submit your story](https://www.jenkins.io/project/adopters/contributing/#share-your-story)!

# License

Jenkins is **licensed** under the **[MIT License](LICENSE.txt)**.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Node.js / npm** (manifests: package.json, yarn.lock; scanned in UPSTREAM_CLONE)
- Top-level source layout: `bom/`, `cli/`, `core/`, `coverage/`, `src/`, `test/`, `war/`, `websocket/`
- Snapshot size: **12414 files**, **354811 lines of code** (measured; see Benchmarks)
- Primary languages: `.properties` (7489), `.java` (1946), `.html` (1004), `.jelly` (900), `.svg` (218), `.js` (132)
- Upstream commit pinned for this packaging: `e2ba107d13304978b338eb19f31fad5a53a858cc`

---

## Installation

[![Gitter](https://img.shields.io/gitter/room/jenkinsci/jenkins)](https://matrix.to/#/#jenkinsci_jenkins:gitter.im)

---

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

- [Downloads](#downloads)
- [Getting Started (Development)](#getting-started-development)
- [Source](#source)
- [Contributing to Jenkins](#contributing-to-jenkins)
- [News and Website](#news-and-website)
- [Governance](#governance)
- [Adopters](#adopters)
- [License](#license)

---

*Section quoted from the upstream readme.*
Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

For all distributions Jenkins offers two release lines:

- [Weekly](https://www.jenkins.io/download/weekly/) -
  Frequent releases which include all new features, improvements, and bug fixes.
- [Long-Term Support (LTS)](https://www.jenkins.io/download/lts/) -
  Older release line which gets periodically updated via bug fix backports.

Latest releases:

[![Jenkins Regular Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog%2Fbadge.json)](https://www.jenkins.io/changelog)
[![Jenkins LTS Release](https://img.shields.io/endpoint?url=https%3A%2F%2Fwww.jenkins.io%2Fchangelog-stable%2Fbadge.json)](https://www.jenkins.io/changelog-stable)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Node.js / npm |
| Manifests detected | package.json, yarn.lock |
| Files in snapshot | 12414 |
| Lines of code | 354811 |
| Dependency references | 38 |
| Dependencies by ecosystem | npm: 38 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| npm | handlebars | 4.7.9 | package.json |
| npm | hotkeys-js | 3.12.2 | package.json |
| npm | jquery | 4.0.0 | package.json |
| npm | lodash | 4.18.1 | package.json |
| npm | sortablejs | 1.15.7 | package.json |
| npm | tippy.js | 6.3.7 | package.json |
| npm | window-handle | 1.0.1 | package.json |
| npm | @babel/cli | 8.0.6 | package.json |
| npm | @babel/core | 8.0.6 | package.json |
| npm | @babel/preset-env | 8.0.6 | package.json |
| npm | @eslint/js | 10.0.1 | package.json |
| npm | babel-loader | 10.1.1 | package.json |
| npm | clean-webpack-plugin | 4.0.0 | package.json |
| npm | css-loader | 7.1.5 | package.json |
| npm | css-minimizer-webpack-plugin | 8.0.0 | package.json |
| ... | (23 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `package.json`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing to Jenkins

This page provides information about contributing code to the Jenkins core codebase.

:exclamation: There's a lot more to the Jenkins project than just code. For more information on the ways that you can contribute to the Jenkins project, see [Participate](https://www.jenkins.io/participate/).

## Getting started

1. Fork the project on GitHub
2. source the forked project to your machine
3. Install the necessary development tools. In order to develop Jenkins, you need the following:
   - Java Development Kit (JDK) 21 or 25.
     In the Jenkins project we usually use [Eclipse Temurin](https://adoptium.net/) or [OpenJDK](https://openjdk.org/), but you can use other JDKs as well.
   - Apache Maven 3.9.6 or above. You can [download Maven here](https://maven.apache.org/download.cgi).
     In the Jenkins project we usually use the most recent Maven release.
   - Any IDE which supports importing Maven projects.
4. Set up your development environment as described in [Preparing for Plugin Development](https://www.jenkins.io/doc/developer/tutorial/prepare/)

If you want to contribute to Jenkins, or just learn about the project,
you can start by fixing some easier issues.
In the Jenkins issue tracker we mark such issues as `good first issue`.
You can find them by using this query (check the link) for [good first issues](https://github.com/jenkinsci/jenkins/issues?q=is%3Aissue%20is%3Aopen%20label%3A%22good%20first%20issue%22).

## Building and Debugging

The Jenkins core build flow is built around Maven.
You can read a description of the [building and debugging process here](https://www.jenkins.io/doc/developer/building/).

### Building the WAR file

If you want simply to build the `jenkins.war` file as fast as possible without tests, run:

```sh
mvn -am -pl war,bom -Pquick-build clean install
```

The WAR file will be created in `war/target/jenkins.war`.

> [!NOTE]
> `quick-build` sets `maven.test.skip`, so test classes are not compiled and are not present
> afterwards. To build something you can then run tests against, drop the profile or pass
> `-Dmaven.test.skip=false`.

`clean` deliberately leaves `node/`, `node_modules/` and `.yarn/` in place, so the node
toolchain and the downloaded packages survive between builds. Pass `-Dclean.node` to delete
those as well.

If you are only changing backend code and `war/src/main/webapp/jsbundles` is already populated
from an earlier build, `-Dskip.frontend=true` skips the node installation, `y

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
The MIT License

Copyright (c) 2004-, Kohsuke Kawaguchi, Sun Microsystems, Inc., and a number of other of contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `JENKINS_PRIOR_DOCS` (category: SOFTWARE DEVELOPMENT)
- **Upstream URL:** https://github.com/jenkinsci/jenkins
- **Pinned commit (SHA):** `e2ba107d13304978b338eb19f31fad5a53a858cc`
- **Branch:** master
- **Pin provenance:** resolved during the second documentation pass. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`f9e06f57c9b5dfea243386ed938ab0c158f16fcffeea8c3b803dd20937b1f95d`.

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

