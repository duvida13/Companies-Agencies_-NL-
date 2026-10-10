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

## Reusable research instructions — all eight methods

Use this section as instructions in another chat or AI model. Research organizations that perform, organize or supply personnel for rope access work in the Netherlands. Read the existing register first, then search for new organizations and strengthen uncertain records. Search for capability even when no vacancy is advertised. Report facts and limitations without assigning subjective job-fit scores.

### 1. Dutch and English keywords, synonyms and spelling variants

Search rope access, rope acces, IRATA, industrieel klimmen, industrieel klimmer, industriële abseiltechnieken, abseiltechniek, touwtoegang, touwtechnieken, specialistische toegangstechnieken and moeilijk bereikbare locaties. Combine these with bedrijf, diensten, werkzaamheden, personeel, projects and technicians. Search Dutch and English pages, including non-.nl domains. Generic working-at-height wording alone needs evidence of rope techniques.

### 2. Adjacent sectors and companies whose main business is something else

Explore lifting and rigging; wire-rope reeving; crane and derrick maintenance; scaffolding and insulation; NDO/NDT and structural inspection; industrial maintenance; welding, blasting, coatings and conservation; wind turbine and blade repair; offshore, maritime and petrochemicals; telecom masts and antennas; glass, facade, silo and tank cleaning; glazing and roof maintenance; fire protection; rescue and confined spaces; green facades and gardening. Equipment suppliers, trainers and customers may lead to contractors, but do not assume they execute rope work. Add other sectors when projects reveal them.

### 3. Geographic searches across the Netherlands

Vary the province, town, port and industrial area rather than repeating only Rotterdam or Amsterdam. Cover Groningen, Friesland, Drenthe, Overijssel, Flevoland, Gelderland, Utrecht, Noord-Holland, Zuid-Holland, Zeeland, Noord-Brabant and Limburg. Include industrial clusters such as Eemshaven, Delfzijl, Den Helder, IJmuiden, Rotterdam/Pernis/Botlek/Maasvlakte, Dordrecht, Vlissingen/Terneuzen and Chemelot/Geleen. A city service-area page is not evidence of an office. Separate headquarters, branches, project locations and nationwide coverage.

### 4. Deeper company pages and documents

Inspect service pages, project descriptions, case studies, careers, contact pages, brochures, certificates and PDFs. A homepage omission does not exclude a company. Look for concrete descriptions of technicians doing work, access methods, completed projects and application routes. Separate the underlying project/document date from the search engine's crawl date. An old certificate or PDF does not prove current certification. If a page redirects, inspect the successor site.

### 5. Partners, subcontractors, suppliers, subsidiaries and rebrands

Follow named execution partners, subcontractors, suppliers and related companies from projects and service pages. Determine which organization supplies the crew, advertises the contract and recruits personnel. Record distinct partner-supported providers with an explicit relationship; do not infer an independent crew. Trace acquisitions, subsidiaries, trading names, alternate domains and former names before counting additions. Customer logos alone are not proof of rope capability or hiring. Shared address/domain alone does not justify merging distinct businesses.

### 6. IRATA and industry directories

Check the Netherlands IRATA member list and relevant operator details, plus maritime, wind, port, industrial and specialist-cleaning directories. Record category, membership number and status when independently verified, including probationary status. Training-only members are not automatically contractors. Certification of individual technicians is different from company membership. Nonmembers may still perform rope access and remain in scope. Use general business directories/KvK as identity clues rather than conclusive operational evidence.

### 7. Recruitment and company-authored social material

Search employer careers pages, current and historical job advertisements, open applications, freelance routes, and company-authored LinkedIn or other public project posts. Rope access may appear inside an NDT, maintenance, gardening, welding or wind role. Trace third-party adverts back to the named employer when possible. Keep an agency client unnamed when the advert does not identify it. Historical vacancies reveal leads; they do not prove a current vacancy. Company posts can support execution even when website extraction fails. Personal profiles alone are weak leads. Record L1/L2/L3, trade qualifications and other certificates only when stated; do not infer L1 eligibility from any mention of IRATA.

### 8. Combine evidence per organization and preserve uncertainty

Group all relevant pages before deciding. Separately establish identity, Netherlands connection, rope capability, own crew versus partner execution, staffing, direct employment, training, certification and hiring. Use more than one activity label where appropriate. Record unknowns, conflicting information, inaccessible pages and indexed-only evidence. Never treat failed extraction or absence on one page as proof of no capability. Keep weak leads in a follow-up queue. Confirm names/aliases against the register before adding a stable ID.

## Research workflow and deliverables

1. Read existing records and unresolved leads; retain stable IDs and resolve aliases.
2. Build a search matrix across methods 1–7. Log exact query strings while running them. Note which routes produced discoveries and which returned only duplicates or irrelevant results.
3. Apply method 8 to every candidate. Prefer primary service/project/employer evidence and authoritative member directories. Corroborate directory clues; label indexed-only or historical evidence.
4. For each admitted organization record name, website, Dutch location/connection, activities, delivery/staffing evidence, IRATA evidence, contact/application route, status/limits, source URLs, checked date, source quality and related organizations.
5. Record only company-published business contacts; label HR/recruitment separately from operations, owners, sales and general inboxes. Never guess email addresses. Confirm street addresses from an appropriate source; add a clickable map for each known address and preserve office/correspondence distinctions.
6. Keep confirmed capability separate from current hiring, and Dutch presence separate from Dutch rope crew evidence. Preserve uncertainty within supported records; candidates lacking sufficient identity or capability evidence remain uncounted.
7. Update the concise directory, CSV, contact records, detailed evidence and unresolved queue consistently. Report actual additions and duplicates, rather than working toward an arbitrary target count.
8. Describe scope and remaining gaps. Repeated duplicates or few discoveries do not demonstrate an exhaustive market census.

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
