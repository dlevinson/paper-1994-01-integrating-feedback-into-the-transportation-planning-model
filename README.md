# Integrating Feedback Into The Transportation Planning Model

## Contribution

This paper restructures the conventional transportation planning model so that travel demand, route assignment, and traffic-signal control respond consistently to one another. Its six-stage feedback algorithm produces convergent travel times and shows, in a Baltimore–Washington application, that feedback materially changes long-range forecasts compared with a one-way sequential model.

## Bibliographic Information

- Row ID: `paper-1994-01`
- Year: 1994
- Authors: David M. Levinson and Ajay Kumar
- Venue: Transportation Research Record 1413:70-77
- Citation: Levinson, D. M., and Kumar, A. (1994). Integrating feedback into transportation planning model: structure and application. Transportation Research Record, 1413, 70-77.

## Package Status

This package is ready for public GitHub upload after routine repository license selection. It contains no raw household, person-level, survey microdata, or sensitive spatial traces. The reusable Travel/2 code context is not duplicated here; it is referenced through the shared source bundle listed in `documentation/SHARED_SOURCE_POINTERS.md`.

## Paper-First Validation

The paper was read directly from `paper/1413-008.pdf`. It uses the TRAVEL/2 model for the Baltimore-Washington region, with Montgomery County as the main application area. The paper describes 1990 and 2010 tests using Round IV Metropolitan Washington Council of Governments forecasts, Round III Baltimore Regional Council of Governments forecasts, MCPD mode-choice inputs, automobile and transit networks, turning-lane definitions, and signalized-intersection control.

The package contains the paper reference PDF, paper-specific derived table/figure data from the local TRR-FEEDBACK folder, and pointers to the shared Travel/2 macro/source/tool trees. The generic Travel/2 source trees were removed from this per-paper folder after byte-level duplicate checks against `_shared_sources/mncppc-travel2-source`.

## Package Contents

- `paper/`: local audit reference copy of the published paper.
- `data/derived_tables/original_legacy/`: original legacy Lotus 1-2-3 and Word 5 table files from the paper project folder.
- `data/derived_tables/modernized/`: LibreOffice conversions to `.xlsx`, `.txt`, and `.csv` for easier inspection.
- `documentation/SHARED_SOURCE_POINTERS.md`: canonical shared Travel/2 source locations and deduplication evidence.
- `PAPER_FIRST_VALIDATION.md`: paper-to-assets validation note.
- `PACKAGE_MANIFEST.csv`: current package file manifest.

## Exclusions

Manuscript drafts, cover letters, cuts, and presentation-only files from the TRR-FEEDBACK folder were not copied. Generic Travel/2 source trees are not duplicated in this package because they are shared by multiple early papers.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:23:47 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
