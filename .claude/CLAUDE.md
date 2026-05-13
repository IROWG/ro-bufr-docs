# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a working documents repository — no code, no build system. It contains `.docx`, `.pptx`, and related files tracking the design and evolution of a new BUFR (Binary Universal Form for the Representation of meteorological data) format for radio occultation (RO) data.

Work is carried out under [IROWG](https://www.irowg.org) (International Radio Occultation Working Group), operating under CGMS/WMO.

## Document Inventory

- `romsaf_bufr_v27.*.docx` — versioned drafts of the main RO BUFR format specification (currently up to v27.9.2)
- `romsaf_bufr_section4*.docx` — separate versioned drafts of Section 4 of the specification (currently up to v1.7)
- `baseline_Stig-romsaf_bufr_proposal.docx` — original baseline proposal
- `eccodes-local-defs.tgz` — ecCodes local definitions archive (BUFR tables/descriptors)
- `github_issue_for_ro_bufr.docx` — draft text for a GitHub issue submission to WMO
- `Notes - BUFR discussion.docx` — meeting/discussion notes
- `20240117_Jennifer-bufr_mtg_v2.pptx`, `20240320_Chris_BUFR_metadata.pptx`, `20240710_Chris_BUFR_PCD_thoughts.docx` — contributor presentations and comments

## Workflow

Documents are maintained here on GitHub (migrated from Google Drive in April 2026). Version history is tracked via git commits. There is no automated build, lint, or test pipeline.
