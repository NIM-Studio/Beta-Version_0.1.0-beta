# NIM Studio open-source transition — review package

This package contains proposed changes for the public NIM Studio documentation repository. No GitHub files were changed, and no application source code is included.

## Intended release model

- Public documentation and original repository materials: proposed Apache License 2.0.
- NIM Studio 0.1.0-beta evaluation executables: separate current beta licence, reproduced in `BETA_EXECUTABLE_LICENSE.md`.
- Application source code: planned public open-source release in January 2027, subject to release-rights confirmation and testing.
- Roadmap timing: beta foundation April–July 2026; internal evaluation September 2026–January 2027 (overlapping with release preparation); public source-code release targeted separately for January 2027.

## Files to review

- `README.md`: minimal messaging updates, roadmap image, licensing scope, and contribution link.
- `LICENSE`: standard Apache License 2.0 text, proposed for published repository materials.
- `BETA_EXECUTABLE_LICENSE.md`: the existing evaluation-binary licence, preserved separately.
- `BETA_POLICY.md`: clarifies that executable restrictions do not apply to Apache-licensed documentation.
- `RIGHTS.md` and `NOTICE`: public attribution, scope, trademarks, and third-party rights.
- `CITATION.cff`: corrected public-release status and roadmap.
- `CONTRIBUTING.md`, `AUTHORS.md`, and `.github/ISSUE_TEMPLATE/`: contributor and collaboration routes.
- `docs/source/`: installation, quickstart, licensing, citation, and contribution pages.
- `assets/NIM_OpenSource_Roadmap.svg`: scalable illustration for the README.

## Before applying to GitHub

1. Confirm ownership and authority to open-license the affected materials, especially in light of any institutional claims.
2. Decide whether Apache 2.0 is the final choice. This package treats it as a **proposal**.
3. Review whether NIM Studio logos and third-party images need file-specific rights notices.
4. Check distributed beta packages and any in-app licence acceptance text against the newly separated beta executable terms.
5. Keep the January 2027 software source release clearly identified as planned until the code is actually published.

## Reference ideas from CliMB

- Licence badge and distinct licensing information.
- Contributor guide and community issue reporting.
- Clear data-privacy warnings.
- Demonstration visuals and documentation entry points.

CliMB's own `CONTRIBUTING.md` and README were reviewed as structural references; their text and implementation have not been copied into NIM Studio's new contribution documents.
