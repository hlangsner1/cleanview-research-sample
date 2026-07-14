# Cleanview Research Sample: Data Center Project Enrichment

This is a self-directed sample of research work, built to demonstrate the kind of project-level enrichment and multi-source validation described in Cleanview's Senior Research Analyst posting.

**Description:** a single PJM/New Jersey data center record (QTS's proposed second facility in Piscataway, NJ), researched and enriched from public sources — developer/ownership chain, capacity, grid interconnection, a local permitting precedent from the same developer, and financing context on the project's bond structure.

**Findings:**
- Cross-referencing a secondary aggregator record (datacenter.fyi) against corporate news reporting, a company's own sustainability filings, and a local government planning precedent, rather than taking any single source at face value.
- Flagging a genuine coverage gap: this proposed 42.5 MW expansion doesn't yet appear on Cleanview's own public tracker, which currently lists only the existing operational facility at this site.
- Structuring findings as both a queryable data record (`data/qts-piscataway.json`) and a narrative writeup (`research/qts-piscataway-enrichment.md`), since real research work needs to feed both a database and a readable report.

**Further research:** the capacity figure and project status haven't yet been confirmed against a primary source (PSE&G interconnection filings or Piscataway Township planning records) — noted explicitly in both files rather than smoothed over.

## Contents

- [`research/qts-piscataway-enrichment.md`](research/qts-piscataway-enrichment.md) — full narrative writeup with sourcing
- [`data/qts-piscataway.json`](data/qts-piscataway.json) — structured record of the same findings

## Methodology note

Sources used: [interconnection.fyi](https://www.interconnection.fyi) / datacenter.fyi (secondary aggregators), DataCenterDynamics and Hoodline (industry press), Baxtel (corporate/facility profiles), and QTS's own Green Finance Framework Second-Party Opinion (Sustainalytics, 2023). No claim in this sample is drawn from a single source without at least one independent cross-check; places where that wasn't possible are flagged as open verification items rather than presented as settled.
