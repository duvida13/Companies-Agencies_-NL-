# Methodology

## Goal and scope

Find Dutch rope access contractors, industrial contractors with rope access capability, and agencies supplying technicians. Track training, equipment and client organizations as ecosystem leads without assuming they hire technicians. Include companies without current vacancies and overseas firms with a documented Netherlands operation.

## Phases

1. Establish public register and evidence notes.
2. Discover approximately 100 candidate organizations through varied sources.
3. Combine pages per organization and manually verify classifications.
4. Benchmark optional Jev classification; measure wrongly rejected relevant companies before automatic exclusion.
5. Scale useful search and extraction sources.
6. Incrementally add discoveries and refresh stale evidence.

## Tools

Pilot: existing web search, primary-page reading, structured evidence notes.
Potential later setup: Serper search results; selective Firecrawl extraction; Jev classification if it passes an accuracy test; code for normalization and organization matching; stronger model for ambiguity.
Do not assume paid tools are necessary or available. Record total search/extraction/model costs, not only classifier token charges. Keep credentials out of notes and public repositories.

## Discovery vocabulary

rope access; IRATA; industrieel klimmen; industrieel klimmer; touwtoegang; touwtechnieken; abseiltechnieken; specialistische toegangstechnieken; moeilijk bereikbare locaties.
Combine with offshore, wind, steigerbouw, inspectie, NDO/NDT, onderhoud, lassen, schilderen, isolatie, maritiem, petrochemie and geographic areas. Broad working-at-height terms need context.
Search service pages, projects, careers, PDFs, industry/member directories and historical advertisements. Follow partners and suppliers. Do not limit discovery to .nl domains.

## Verification rules

- Deduplicate URLs early, then group evidence by organization.
- Missing evidence on one page is not evidence of no capability.
- Keep extraction failures and ambiguous results in the queue.
- Use multiple activity labels; a training provider may also undertake projects.
- Distinguish advertised capability, staffing, direct employment and subcontracting.
- Distinguish IRATA technicians from IRATA company membership.
- Historical vacancies reveal leads, not current capability.
- Customer logos do not prove direct hiring; unnamed agency clients stay unnamed.
- Record source URLs, concise supporting excerpts, review date and source date when available.
- Stable IDs survive name changes. Shared domain/address alone does not justify merging.

## Metrics

New verified organizations per batch; duplicate rate; unresolved cases; relevant organizations wrongly rejected; source-specific discoveries; cost per newly verified organization. Few new discoveries do not prove completeness.

## Repository organization

Concise company list: README.md. Authoritative records: data/companies.csv. Detailed records: directory/netherlands.md. Methodology/schema/handoff: context/. Logs, evidence and unresolved queue: research/.

Public research notes include methodology, source evidence and lessons only. Credentials, CVs, private applications, local filesystem paths and private conversations are excluded.
