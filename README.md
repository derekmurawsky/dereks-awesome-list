<!-- lint ignore no-dead-urls awesome-git-repo-age -->
<!-- markdownlint-disable-file MD033 MD041 -->
<div align="center">

<!-- title -->

# Derek's Awesome List <!-- omit in toc -->
<!--lint disable double-link -->
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/derekmurawsky/dereks-awesome-list/actions/workflows/lint.yaml/badge.svg)](https://github.com/derekmurawsky/dereks-awesome-list/actions/workflows/lint.yaml) [![CC-BY-SA](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-5-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->
<!--lint enable double-link -->
<!-- subtitle -->

An awesome list of things I like and have found useful

</div>

<!-- omit in toc -->
## Contents
<!--lint disable double-link -->
- [Awesome Lists](#awesome-lists)
- [Containers](#containers)
- [Development Tools](#development-tools)
- [Documentation](#documentation)
- [Open Source Best Practices](#open-source-best-practices)
- [Software Supply Chain Security](#software-supply-chain-security)
- [Contributors ✨](#contributors-)
<!--lint enable double-link -->
## Awesome Lists

There are many great awesome lists. These are a few of them.
<!--lint ignore double-link -->
- [Awesome](https://github.com/sindresorhus/awesome) - The original awesome list.
- [Awesome Docker](https://github.com/veggiemonk/awesome-docker) - A curated list of Docker resources and projects.
- [Awesome Selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - An awesome list dedicated to self-hostable applications.
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - A curated list of amazingly awesome open source sysadmin resources.
- [Awesome VSCode](https://github.com/viatsko/awesome-vscode) - A curated list of delightful Visual Studio Code packages and resources.
- [The Book of Secret Knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) - A collection of inspiring lists, manuals, cheatsheets, blogs, hacks, one-liners, cli/web tools, and more.

## Containers

- [Docker](https://www.docker.com/) - The Docker container runtime & developer ecosystem.
- [Hadolint](https://github.com/hadolint/hadolint) - A smarter Dockerfile linter that helps you build [best practice](https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices) Docker images.
- [Microsoft Container Tagging Recommendations](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-image-tag-version) - Recommendations on container tags from Microsoft.
- [OCI Container Annotations](https://github.com/opencontainers/image-spec/blob/main/annotations.md) - A list of container annotations (labels) recommended by the [Open Container Initiative](https://opencontainers.org/).
- [Skopeo](https://github.com/containers/skopeo) - Skopeo is a command line utility that performs various operations on container images and image repositories.
- [tini](https://github.com/krallin/tini) - Tini is the simplest init you could think of. All Tini does is spawn a single child (Tini is meant to be run in a container), and wait for it to exit all the while reaping zombies and performing signal forwarding.
- [Trivy](https://github.com/aquasecurity/trivy) - Scanner for vulnerabilities in container images, file systems, and Git repositories, as well as for configuration issues.

## Development Tools

- [Direnv](https://github.com/direnv/direnv) - Direnv is an extension for your shell. It augments existing shells with a new feature that can load and unload environment variables depending on the current directory.
- [NocoDB](https://github.com/nocodb/nocodb) - Turns any MySQL, PostgreSQL, SQL Server, SQLite & MariaDB into a smart-spreadsheet.
- [PostGraphile](https://www.graphile.org/postgraphile/) - Instantly spin-up a GraphQL API server by pointing PostGraphile at your existing PostgreSQL database.
- [PostgREST](https://github.com/PostgREST/postgrest) - PostgREST serves a fully RESTful API from any existing PostgreSQL database.
- [pre-commit](https://pre-commit.com/) - A framework for managing and maintaining multi-language pre-commit hooks.
- [Visual Studio Code](https://code.visualstudio.com/) - Code editing. Redefined. Free. Built on open source. Runs everywhere.

## Documentation

- [Hugo](https://gohugo.io/) - The world's fastest framework for building websites.
- [MarkdownLint](https://github.com/DavidAnson/markdownlint) - A Node.js style checker and lint tool for Markdown/CommonMark files.
- [MarkdownLint-cli2](https://github.com/DavidAnson/markdownlint-cli2) - A fast, flexible, configuration-based command-line interface for linting Markdown/CommonMark files with the markdownlint library.
- [MKDocs](https://www.mkdocs.org/) - MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation.
- [MKDocs Material](https://squidfunk.github.io/mkdocs-material/) - Create a branded static site from a set of Markdown files to host the documentation of your Open Source or commercial project. Set up in 5 minutes.

## Open Source Best Practices

- [All Contributors](https://allcontributors.org/) - Recognize All Contributors, Including those that don't push code.
- [Balanced Employee IP Agreement (BEIPA)](https://github.com/github/balanced-employee-ip-agreement) - BEIPA takes a balanced approach to assigning control of intellectual property (IP) created by an employee. The company gets exclusive control of IP created in the scope of an employee's job. The employee maintains exclusive control of IP created outside of their job and not related to the company's business.
- [Contributor Covenant](https://www.contributor-covenant.org) - A Code of Conduct for Open Source Communities.
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) - A specification for adding human and machine readable meaning to commit messages.
- [Open Source Security Foundation](https://openssf.org/) - Group dedicated to securing the open source ecosystem.

## Software Supply Chain Security

- [DSSE](https://github.com/secure-systems-lab/dsse) - Simple, foolproof standard for signing arbitrary data.
- [GitLeaks](https://github.com/zricethezav/gitleaks) - Gitleaks is a SAST tool for detecting and preventing hardcoded secrets like passwords, api keys, and tokens in git repos.
- [Grype](https://github.com/anchore/grype) - A vulnerability scanner for container images and filesystems. Works with Syft, the powerful SBOM (software bill of materials) tool for container images and filesystems.
- [in-toto](https://in-toto.io/) - A framework to secure the integrity of software supply chains. in-toto is designed to ensure the integrity of a software product from initiation to end-user installation. It does so by making it transparent to the user what steps were performed, by whom and in what order.
- [in-toto Attestations](https://github.com/in-toto/attestation) - This repository defines the in-toto attestation format, which represents authenticated metadata about a set of software artifacts.
- [OWASP ZAP](https://www.zaproxy.org/) - The world's most widely used web app scanner.
- [SLSA](https://slsa.dev/) - Supply chain Levels for Software Artifacts, or SLSA (salsa). It's a security framework, a check-list of standards and controls to prevent tampering, improve integrity, and secure packages and infrastructure in your projects, businesses or enterprises.
- [Syft](https://github.com/anchore/syft) - A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems. Exceptional for vulnerability detection when used with a scanner tool like Grype.
- [TUF](https://theupdateframework.io/) - A framework for securing software update systems. The Update Framework (TUF) helps developers maintain the security of software update systems, providing protection even against attackers that compromise the repository or signing keys.
- [Witness](https://github.com/testifysec/witness) - Witness is a pluggable framework for supply chain security. Witness prevents tampering of build materials and verifies the integrity of the build process from source to target.

## Contributors ✨

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://www.theendofthetunnel.org"><img src="https://avatars.githubusercontent.com/u/3741839?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Derek Murawsky</b></sub></a><br /><a href="#content-derekmurawsky" title="Content">🖋</a> <a href="#design-derekmurawsky" title="Design">🎨</a></td>
    <td align="center"><a href="https://jthegedus.medium.com/"><img src="https://avatars.githubusercontent.com/u/20798510?v=4?s=100" width="100px;" alt=""/><br /><sub><b>James Hegedus</b></sub></a><br /><a href="#tool-jthegedus" title="Tools">🔧</a> <a href="#tutorial-jthegedus" title="Tutorials">✅</a> <a href="#example-jthegedus" title="Examples">💡</a></td>
    <td align="center"><a href="https://sindresorhus.com/apps"><img src="https://avatars.githubusercontent.com/u/170270?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Sindre Sorhus</b></sub></a><br /><a href="#ideas-sindresorhus" title="Ideas, Planning, & Feedback">🤔</a> <a href="#example-sindresorhus" title="Examples">💡</a></td>
    <td align="center"><a href="https://allcontributors.org"><img src="https://avatars.githubusercontent.com/u/46410174?v=4?s=100" width="100px;" alt=""/><br /><sub><b>All Contributors</b></sub></a><br /><a href="#ideas-all-contributors" title="Ideas, Planning, & Feedback">🤔</a> <a href="#tool-all-contributors" title="Tools">🔧</a></td>
    <td align="center"><a href="http://alexlapinski.name"><img src="https://avatars.githubusercontent.com/u/37541?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alex Lapinski</b></sub></a><br /><a href="#ideas-alexlapinski" title="Ideas, Planning, & Feedback">🤔</a> <a href="#tool-alexlapinski" title="Tools">🔧</a> <a href="#mentoring-alexlapinski" title="Mentoring">🧑‍🏫</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. [Contributions of any kind welcome, just follow the guidelines](contributing.md)!
