<!--
KISS Open License Version 1.0 (KOL-v1)

SPDX-FileCopyrightText: 2026 I-plusplus Inc.
SPDX-License-Identifier: LicenseRef-KOL-v1

Copyright remains with its respective holders; original copyright and attribution notices must be preserved.
Contributors may add copyright notices for their own original modifications.
Distributed modifications must be identified as required by Section 4(c) of KOL-v1.

Use, modification, distribution, and incorporation into commercial or proprietary software are permitted
without license fees or source disclosure, subject to all terms of the complete KOL-v1 license.

Contributors grant the patent permissions stated in KOL-v1. Outputs are not covered merely because a
KOL-licensed tool produced them; embedded licensed material remains subject to applicable license terms.

THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OR LIABILITY TO THE EXTENT PERMITTED BY APPLICABLE LAW.

This header is a summary, not a separate license or an amendment to KOL-v1.
All terms and conditions of KOL-v1 apply. See the accompanying LICENSE file for the complete license text.
-->

# PETER

Portable Execution & Translation Environment: planned portability, translation and ABI compatibility.

## Current status

No implementation is included in this repository bootstrap. No buildable
component, runtime feature, ABI compatibility or release readiness is claimed.
The bootstrap does not import any PoC implementation into `main`.

See [Project-KISS](https://github.com/i-pp/Project-KISS) for project principles.

## Minimum CI

CI validates the tracked administrative files, JSON policy and relative document
links. It retrieves the versioned license-checker artifact, verifies its pinned
SHA-256 before execution and checks every tracked file against the declared
license policy. Both checks must succeed for `Minimum CI` to succeed, including
pull requests and merge groups. Missing evidence or a failed download fails CI.

These checks cover this bootstrap only. They do not establish functional test
coverage, legal ownership, license compatibility or production acceptance.
Future implementation requires its own tests and acceptance criteria.

## License

The current project-owned administrative files, including CI and JSON policy,
are covered by [KOL v1](LICENSE). See [NOTICE](NOTICE) for attribution and scope.
Third-party material must retain its own terms and is not automatically
relicensed by this repository's root license.
