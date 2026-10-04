# Manual classifier benchmark and acceptance rules

Before spending money on Jev or another classifier, assemble retained source text and manual labels for these cases. This file defines cases, not measured model performance; no model has been tested. Re-fetch source pages into dated local inputs before a trial and retain extraction failures separately. Use the detailed directory and evidence files for source URLs.

| Case | Expected decision | Reason |
|---|---|---|
| Mennens | Retain contractor capability | Equipment supplier also advertises executing team |
| Eurosafe | Retain contractor capability | Training activity does not cancel project execution |
| Hanab | Retain industrial contractor | Own specialist IRATA crew buried in news page |
| Meijerink Technical Services | Retain industrial contractor | Rope access in broader E&I service description |
| Vinçotte / Kiwa | Retain inspection employer; eligibility separate | IRATA mentioned in NDT recruitment; L1 alone insufficient |
| SIRON | Retain technical employer; IRATA desired | L1 experience advantage, not membership or guaranteed job |
| IAS Group / VLR | Retain advertised capability for review | Company-authored social evidence; website failure is not negative evidence |
| HPG / 67 Solutions | Retain service provider with delivery uncertainty | Own employment versus subcontracting not established |
| Mundo / SHS | Retain separate named organizations with relation | Partner delivery must not be labeled separate independent crews |
| EEIS / CIS | Partner relation; do not infer second RA crew | EEIS drone service delivered with CIS access |
| cis-bv.com | Reject as unrelated homonym | Immigration consultancy |
| SGS localized NL rope access page | Unclear Dutch delivery; review | Localization refers to Singapore capability |
| Atlas Createch | Exclude from Dutch universe pending NL proof | Turkish company; not Dutch ATLAS Rope Access |
| Rope Access Team / RAW Concepts | Exclude from Dutch universe pending NL proof | Polish company; reviewed project in Germany |
| Swire | Retain international project provider | NL project does not imply Dutch HQ or live hiring |
| Height Safety Expert / Industrieel Klimmen / SafetyPro | Retain ecosystem, exclude unproven contractor classification | Trainer membership alone is insufficient |
| Historical or filled vacancy | Retain discovery/recruitment evidence with age | Do not label live opportunity |
| Page extraction failure | Review / retry | Missing text is not an irrelevant-company decision |

Required output fields: organizational role (multi-label allowed), own execution evidence, staffing evidence, NL connection type, IRATA evidence type, evidence span, source date if available, uncertainty and review route. No invented confidence probabilities. Compare model output against manual labels, audit false negatives, and retain uncertain cases. A cheap model is only useful if its missed-company rate and total search/extraction cost are acceptable. No automatic discard threshold is authorized by this benchmark alone.
