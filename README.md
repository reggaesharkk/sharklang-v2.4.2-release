<p align="center"><a href="https://github.com/reggaesharkk/Reggae-shark-universe-"><img src="https://raw.githubusercontent.com/reggaesharkk/Reggae-shark-universe-/main/assets/universe_bar.svg" alt="Reggae Shark Universe — public research map" width="100%" /></a></p>

<p align="center"><a href="https://github.com/reggaesharkk/Reggae-shark-universe-">Public research map</a> &nbsp;·&nbsp; <a href="https://github.com/reggaesharkk?tab=repositories">All public repositories</a> &nbsp;·&nbsp; <a href="https://orcid.org/0009-0002-1170-4487">ORCID</a></p>

> I keep each project’s evidence, scope, and open questions alongside the work.

---

# SharkLang Governed AI — v2.4.2 Security Review Release

[![Release validation](https://github.com/reggaesharkk/sharklang-v2.4.2-release/actions/workflows/release-validation.yml/badge.svg)](https://github.com/reggaesharkk/sharklang-v2.4.2-release/actions/workflows/release-validation.yml)

**Author:** Prince Upadhyay · [ORCID 0009-0002-1170-4487](https://orcid.org/0009-0002-1170-4487)  
**Repository:** <https://github.com/reggaesharkk/sharklang-v2.4.2-release>  
**Research portfolio:** <https://github.com/reggaesharkk/Reggae-shark-universe->  
**Release date:** 1 November 2026 · **Version:** 2.4.2

I built SharkLang as a small policy language and runtime for examining an approval-gated AI request flow. I included the compiler/runtime, tests, a signed example package and Lean certificate, verification logs, review inputs, and an optional live-provider demo.

## Release archive

Download [`SHARKLANG_GOVERNED_AI_REVIEW_RELEASE_20261101_FINAL.zip`](./SHARKLANG_GOVERNED_AI_REVIEW_RELEASE_20261101_FINAL.zip).

**SHA-256:** `d347cb51591d7e1ee5e65a5903fe862663081574f027cdb9db86cf80a1a0027d`

The archive contains its own SHA-256 manifest and Windows and Ubuntu run logs. The logs record 70 tests on each platform: 69 passed with one POSIX-only skip on Windows ARM64, and 70 passed on Ubuntu aarch64. The release README documents the commands and environments.

## Scope and evidence boundary

I include the tests, signed example, Lean certificate and local Witness as evidence of the included implementation under the recorded checks. They do not establish production security, an independently operated approval service, or assurance for every environment. The demo's purchase amount and spending cap are simulated policy inputs; it does not process payments. Provider calls are real network requests only when I explicitly run the demo with `--live`.

I use the same evidence labels and claim boundaries across my [Reggae Shark Universe portfolio](https://github.com/reggaesharkk/Reggae-shark-universe-).

## Rights and licensing

I publish this release under a custom **SharkLang Evaluation License 1.0**, not MIT or Apache. I allow inspection, citation, downloading, and private use or modification for non-commercial evaluation, research, testing, or security review. Production or real-world deployment, commercial use, product or service integration, and redistribution require my separate written permission or a paid license. Read [`EVALUATION_LICENSE.txt`](./EVALUATION_LICENSE.txt) and [`RIGHTS_RESERVED.txt`](./RIGHTS_RESERVED.txt) before use.

Third-party works and dependencies retain their own terms. This page and the archive do not claim rights over material outside the copyright holder's ownership.

## Continuous integration

I added provider-free GitHub Actions checks for repository checksums, ZIP integrity, both archive manifests, and the bundled release validation on Ubuntu x86_64 with Python 3.12 and 3.14. The workflow does not call AI providers or use API keys.

## Citation

The v2.4.2 release is archived on Zenodo: [10.5281/zenodo.23841845](https://doi.org/10.5281/zenodo.23841845) ([record page](https://zenodo.org/records/23841845)).

**Contact:** [starxshark@gmail.com](mailto:starxshark@gmail.com)
