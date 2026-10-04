# Data rules

`data/companies.csv` is the authoritative register. `README.md` provides a concise company list; `directory/netherlands.md` preserves detailed record-level evidence and limitations. Update all three in the same commit when records change.

## Schema

| Field | Meaning |
|---|---|
| organization_id | Stable ID; never recycle |
| organization_name | Company/brand label; legal identity may need verification |
| nl_location | Verified place or explicit unknown |
| activities | Multiple service/activity labels |
| delivery_staffing_evidence | Evidence of project delivery or personnel supply |
| irata_evidence | Technician qualifications, methodology or membership, kept distinct |
| public_contact_application | Published email or relevant webpage; service contact is not necessarily recruitment |
| evidence_url | Primary supporting source |
| status | Review result and remaining uncertainty |
| checked_date | Source-review date, not source publication date |

Additional sources and concise excerpts belong in research/evidence. Resolve aliases and partnerships before merging. Shared address/domain is not sufficient. Missing fields remain unknown; no invented probabilities or employment claims.

## Every research batch

1. Read the current register, methodology, leads and handoff.
2. Search beyond existing organizations; group evidence across pages.
3. Add or update stable records and retain uncertain leads.
4. Update the concise homepage and detailed directory from the register.
5. Add evidence and query log; record errors and lessons.
6. Update handoff with counts and next steps.
7. Publish and read back the changed files to verify.

Current public fields contain no personal application data. No automated daily task, API pipeline or homepage generator is configured yet.

## Extended fields (extensive research batch)

- `organization_type`: contractor, industrial provider, agency/platform or international provider; hybrid roles remain explicit.
- `nl_connection`: Dutch organizational presence versus NL project versus local delivery uncertainty.
- `evidence_quality`: company page, indexed company page, company-authored social material or authoritative directory.
- `related_organizations`: aliases, partnerships and unresolved identity relationships.

The count represents organizational records, not independent operating teams or certified legal entities. The international section is kept separate from Dutch employers. No confidence percentages are generated without calibrated validation.
