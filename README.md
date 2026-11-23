# Remote Schools Resources

A structured, searchable catalog of learning materials for Uganda, with download links kept at their original sources. It is designed for learners and for the Remote Schools app.

## Current catalog

- 54 PDF links from [Fresh Teacher's exams repository](https://github.com/Fresh-Teacher/exams).
- 4 official NCDC document links.
- Catalog formats: JSON for apps and CSV for spreadsheets.

**This repository currently stores metadata and links, not copies of the PDFs.** Learners download from the publisher or source repository.

## Use from the app

JSON catalog: [catalog/resources.json](catalog/resources.json)
Raw JSON URL: https://raw.githubusercontent.com/trebronwayne/remote-schools-resources/main/catalog/resources.json
CSV export: [catalog/resources.csv](catalog/resources.csv)

Each record includes a stable ID, title, level, subject, resource type, year or period, source and download URLs, rights status, redistribution status, and last-checked date. Validate against [catalog/resource.schema.json](catalog/resource.schema.json).

## Rights and attribution

- The NCDC PSHPE book and 2025 Biology and Geography syllabi state **all rights reserved** and require prior permission for reproduction. They remain link-only.
- The NCDC teacher-support PDF is link-only because reuse permission was not confirmed.
- The Fresh Teacher exams repository has no declared license or LICENSE file. Its PDFs are linked at their source; this catalog does not authorize copying or rehosting them.
- Never assume a PDF inherits the license of a website or application. See [docs/rights-and-sources.md](docs/rights-and-sources.md).

## Add resources

Add individual records to catalog/resources.json and regenerate the CSV. Only place PDF bytes in this repository after confirming permission to redistribute them and recording the evidence. Use a source link when rights are unclear.

## Source freshness

Repository-hosted Fresh Teacher links are pinned to the source commit recorded in each entry. last_checked records when the source link and metadata were checked.
