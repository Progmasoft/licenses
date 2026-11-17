<!-- SPDX-FileCopyrightText: 2026 Progmasoft <support@progmasoft.com> -->
<!-- SPDX-License-Identifier: CC-BY-ND-4.0 -->

# Progmasoft Licenses

The canonical texts of the licenses Progmasoft writes for its own software. Progmasoft's open-source projects use
standard licenses (MIT, EPL-2.0, LGPL-3.0, AGPL-3.0 and others), whose texts are not kept here; the
[Progmasoft Patent Grant](https://github.com/Progmasoft/patent-grants) has a repository of its own.

| License | Text | SPDX identifiers | SHA-256 | State |
| --- | --- | --- | --- | --- |
| Progmasoft Proprietary Source License, version 1.0 (PM-SPL) | [LicenseRef-PM-SPL-1.0.txt](LicenseRef-PM-SPL-1.0.txt) | `LicenseRef-PM-SPL-1.0-only`, `LicenseRef-PM-SPL-1.0-or-later` | `63f2f71254c681a24168c20344862ff08c9e657a6cce7f2331559be422267d6b` | current |

PM-SPL 1.0 is also kept in two marked-up forms, with the same words as the plain text, which is the canonical one:

| Form | File | SHA-256 |
| --- | --- | --- |
| Markdown | [LicenseRef-PM-SPL-1.0.md](LicenseRef-PM-SPL-1.0.md) | `236e58038cc53bc8b4cabcca53599d63fa91f394ab08fabe358ee79e4a4c3fa3` |
| reStructuredText | [LicenseRef-PM-SPL-1.0.rst](LicenseRef-PM-SPL-1.0.rst) | `b5ad63a41b0f799a5d027292f8a5781058ced572d4e7c019ae6f9c1af0017504` |

## The Progmasoft Proprietary Source License

PM-SPL is a proprietary license with public source. It is not an open-source license.

- **What it allows.** Reading and studying the source; building it and running it within your organization for any
  purpose, commercial work included; changing it for your organization's own use; looking for security
  vulnerabilities and reporting them; quoting short excerpts in issues and discussions. The software is free of charge
  (Section 2).
- **What it forbids.** Distributing the software or a modified version, as source or as a build; only Progmasoft
  distributes it. Selling, sublicensing or embedding it in another product, offering it as a service, removing its
  notices (Section 3).
- **Names and advertising.** No use of "Progmasoft", "Agenceland" or the name of any other Progmasoft product to
  present your own version, product or service as official or as Progmasoft's. Advertising in connection with
  Progmasoft or a Progmasoft product must say that it refers to Progmasoft or to a Progmasoft product (Section 4).
- **Forks on GitHub** remain possible as far as GitHub's terms of service allow, under the license, and are not
  distributed outside GitHub (Section 5).
- **Contributions** are welcome and must comply with the license; a contribution is licensed to Progmasoft, relicensing
  included (Section 6).
- **Patents.** The Progmasoft Patent Grant 1.1 applies where the software's PATENTS.md says so, for the uses the license
  allows; a patent claim against the software ends the patent license (Section 8).
- **Termination.** A breach ends the license; a first breach cured within 30 days of notice restores it (Section 9).
- **Law.** The laws of England and Wales; the courts of England and Wales, sitting in London (Section 12).

## Using PM-SPL in a repository

1. Copy the text into `LICENSES/LicenseRef-PM-SPL-1.0-only.txt` (or `-or-later`), unchanged; its SHA-256 is the one
   above. The root `LICENSE.txt` may hold the same text.
2. Mark each of the project's own files with the identifier:
   `SPDX-License-Identifier: LicenseRef-PM-SPL-1.0-only` (or `LicenseRef-PM-SPL-1.0-or-later`, which lets a later
   version be chosen, Section 13).
3. Third-party files keep their own identifiers and notices.

## Changing a license

A change is a new version in a file of its own; a published text never changes. What was published under a version
keeps that version.

## License

The texts may be copied and distributed, unchanged, under [CC BY-ND 4.0](LICENSE.txt). Participation follows the
[Code of Conduct](CODE_OF_CONDUCT.md).
