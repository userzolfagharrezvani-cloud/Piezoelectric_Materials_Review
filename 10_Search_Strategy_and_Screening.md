# 10 — Literature Search Strategy and Screening Protocol

## Purpose
This protocol turns the current starter bibliography into a reproducible literature map for review papers on piezoelectric materials published from 1 January 2020 through 31 December 2026. Because 2026 is not complete until year-end, any search conducted earlier must be labelled as an interim search with its exact date.

## Research questions
1. Which piezoelectric material families and device architectures have been reviewed in 2020–2026?
2. What application areas dominate the literature (harvesting, sensing, flexible electronics, catalysis, biomedical, actuators/ultrasound)?
3. Which metrics and test conditions are reported consistently enough for comparison?
4. What unresolved methodological and translation barriers are identified across reviews?

## Databases
Recommended coverage: Consensus, Web of Science Core Collection, Scopus, IEEE Xplore (electronics/actuators), PubMed (biomedical), and publisher platforms for citation verification. Record which databases were actually searched; do not state that a database was searched unless it was.

## Search strings
Run each string separately and adapt syntax to the database.

### Broad review search
`(piezoelectric OR piezo-elect* OR piezoelectricity) AND (review OR overview OR roadmap OR "systematic review")`

### Energy harvesting
`(piezoelectric) AND ("energy harvesting" OR harvester) AND (review OR overview) `

### Sensors and flexible electronics
`(piezoelectric) AND (flexible OR wearable OR sensor OR "electronic skin") AND (review OR overview)`

### Environmental catalysis
`(piezocatalysis OR piezocatalytic OR "piezo-photocatalysis" OR "piezo-assisted catalysis") AND (review OR remediation OR environment)`

### Biomedical
`(piezoelectric) AND (biomedical OR biomaterial OR tissue OR implant OR bioelectronics) AND (review OR overview)`

### Actuators and ultrasound
`(piezoelectric) AND (actuator OR ultrasonic OR transducer OR MEMS OR NEMS) AND (review OR overview)`

### Lead-free materials
`(piezoelectric) AND ("lead-free" OR "lead free" OR KNN OR "barium titanate") AND (review OR overview)`

## Inclusion criteria
- Publication date falls within 2020–2026 (record online-first and issue years separately where relevant).
- Review, systematic review, review of reviews, or clearly labelled feature/review article with a substantial synthesis.
- Piezoelectric materials or piezoelectric coupling is a central topic, not merely a passing mention.
- Full bibliographic identity can be verified from a publisher page or DOI record.

## Exclusion criteria
- Original research articles unless separately collected as representative primary studies.
- Papers with unverifiable bibliographic details.
- Conference abstracts without sufficient review content.
- Duplicate versions of the same article (retain the definitive record).
- Papers that only mention piezoelectricity incidentally.

## Screening workflow
1. Export all search results with title, authors, year, journal, DOI, abstract, and source database.
2. Deduplicate by DOI, then normalized title.
3. Screen title/abstract against the criteria.
4. Retrieve the full text or publisher record for potentially eligible reviews.
5. Confirm article type, date, scope, and DOI.
6. Assign one primary application category and optional secondary categories.
7. Record exclusion reasons for full-text exclusions.
8. Update the bibliography and report the last search date.

## Data extraction fields
`record_id, title, authors, year_online, year_issue, journal, DOI, article_type, database, search_date, material_families, application_category, review_scope, key_conclusions, stated_limitations, full_text_checked, inclusion_decision, exclusion_reason`

## Reporting
For a systematic review, report the exact databases and platform interfaces, search date, full query for each database, result counts, duplicate count, screening counts, full-text exclusions and reasons, and the final included set. A PRISMA-style flow diagram is appropriate where the review design qualifies.

## Current status
The repository's review list is a **starter bibliography**, not the output of a completed systematic screening exercise. Counts should not be invented. Populate this protocol with actual search dates and result counts only after searches have been run and documented.
