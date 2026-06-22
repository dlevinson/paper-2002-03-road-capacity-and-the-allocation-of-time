# Road Capacity and the Allocation of Time

## Contribution

This paper reframes induced demand by asking how added highway capacity changes people's allocation of time rather than only vehicle travel. Comparing national travel surveys, it finds stable total travel time but meaningful shifts among work, commuting, shopping, home, and other activities, with distinct responses for workers and nonworkers.

This package stages the paper-specific code and small derived workbook outputs located for:

Levinson, David M., and Seshasai Kanchi. (2002). Road Capacity and the Allocation of Time. Journal of Transportation and Statistics, 5(1), 19-33.

## Package Status

Status: `UPLOADED`

The paper states that the analysis used the 1990/91 and 1995/96 Nationwide Personal Transportation Surveys and Federal Highway Administration Highway Statistics data. Those source datasets are public and are not duplicated here. The local archive did contain paper-specific Stata scripts and small workbook outputs, so the earlier `NOTHING-TO-DO` classification was stale.

## Contents

- `paper/`: local reference PDF and paper citation note.
- `code/original/stata/`: 52 original Stata `.do` files from `/Users/dlev2617/Documents/Data/~Nexus_Data/RoadCapacityInducedDemand/paper`.
- `data/derived_workbooks/original/`: 11 small original Excel workbook outputs from the same paper-specific source folder.
- `data/derived_workbooks/modernized/`: `.xlsx` conversions of those workbooks.
- `metadata/`: file manifest, workbook sheet inventory, code summary, and source selection review.
- `documentation/`: validation and package-boundary notes.

## Source Data Boundary

The package does not include bulk NPTS, FHWA Highway Statistics, TTI, or derivative Stata `.dta` files. Those files are either public source data or intermediate derivatives. The code retains the original legacy paths and names so future users can see how the analysis was originally organized; modernizing paths would be a separate reproducibility cleanup.

## Excluded Material

The source folder also contains drafts, Word documents, presentations, logs, resumes, prior versions, and broad intermediate analysis folders. These were excluded because the archive target is paper, data, code, and documentation only.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-21 06:40:20 AEST

- Pipeline: `UPLOADED`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- The repository license boundary is recorded in `LICENSE.md`.
<!-- package-hardening-status:end -->

## License

See `LICENSE.md`. Author-created code is MIT licensed; author-created derived
workbooks and documentation are CC BY 4.0. Papers and public source data
retain their original terms.
