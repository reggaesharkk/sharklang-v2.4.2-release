# SharkLang Governed AI — v2.4.2 Security Review Release

**Author:** Prince Upadhyay · [ORCID 0009-0002-1170-4487](https://orcid.org/0009-0002-1170-4487)  
**Repository:** <https://github.com/reggaesharkk/sharklang-v2.4.2-release>  
**Research portfolio:** <https://github.com/reggaesharkk/Reggae-shark-universe->  
**Release date:** 31 October 2026 · **Version:** 2.4.2

SharkLang is a small policy language and runtime used here to demonstrate a governed AI request flow. The release archive includes the compiler/runtime, tests, a signed example package and Lean certificate, verification logs, review inputs, and an optional live-provider demo.

## Release archive

Download [`SHARKLANG_GOVERNED_AI_REVIEW_RELEASE_20261031_FINAL.zip`](./SHARKLANG_GOVERNED_AI_REVIEW_RELEASE_20261031_FINAL.zip).

**SHA-256:** `ec09756f685e3ae905f9533bf6c6eed29425bbcfba30ce9ea15091728eed12f1`

The archive contains its own SHA-256 manifest and Windows and Ubuntu run logs. The logs record 70 tests on each platform: 69 passed with one POSIX-only skip on Windows ARM64, and 70 passed on Ubuntu aarch64. The release README documents the commands and environments.

## Scope and evidence boundary

The tests, signed example, Lean certificate, and local Witness demonstrate the behavior of the included implementation under the recorded checks. They do not establish production security, an independently operated approval service, or assurance for every environment. The AI demo's purchase amount and spending cap are simulated policy inputs; it does not process payments. Provider calls in the demo are real network requests when explicitly run with `--live`.

The evidence labels and limits follow the claim-boundary practice used across the [Reggae Shark Universe portfolio](https://github.com/reggaesharkk/Reggae-shark-universe-).

## Rights and licensing

This release uses a custom **SharkLang Evaluation License 1.0**, not MIT or Apache. The license allows people to inspect, cite, download, and privately run or modify copies for non-commercial evaluation, research, testing, or security review. Production or real-world deployment, commercial use, integration into a product or service, and redistribution require separate written permission or a paid license from the copyright holder. Read [`EVALUATION_LICENSE.txt`](./EVALUATION_LICENSE.txt) and [`RIGHTS_RESERVED.txt`](./RIGHTS_RESERVED.txt) before use.

Third-party works and dependencies retain their own terms. This page and the archive do not claim rights over material outside the copyright holder's ownership.

## Citation

A Zenodo record is being prepared for this release. Its DOI and record link will be added here after publication.

**Contact:** [starxshark@gmail.com](mailto:starxshark@gmail.com)
