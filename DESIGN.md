# First Design Plan

[Home](README.md) · [Research map](DATA_DOMAINS.md) · [Governance](GOVERNANCE.md) · [Participation](CONTRIBUTING.md)

Version 0.1 · 16 October 2026 · Proposal for future independent communities. This release contains documentation only. All capabilities below are proposed, not implemented.

## Turn the question into something everyone can examine

Somewhere, a person is looking at a newly published number and wondering whether it describes the world they live in. They should be able to follow that question beyond a headline. They should be able to reach the original table, see the definitions, compare other observations, and understand what the evidence supports.

This plan invites a community to make that journey possible. Start with a question small enough to investigate and important enough to matter. Build an evidence trail another person can follow. Expose the mistakes in our own methods as readily as the mistakes we find elsewhere. Each reproducible investigation can become a foundation for the next.

## Purpose and first boundary

Develop an open tool that helps people compare complex public evidence, explain discrepancies, identify demonstrable errors or selective presentation, and construct better-supported estimates. The central product should be an inspectable investigation, with a record of how its conclusions were reached.

The long-term scope includes the 84 directions in the research map. An initial community should select one question, one geography, and a short period with suitable documentation. It should demonstrate that its methods are useful before expanding coverage or automating collection. This plan creates no commitment by the initiator to build, maintain, finance, or operate anything.

## The unit of work

Each investigation should state its question, geographic boundary, observation period, target population, metric, unit, denominator, and decision being informed. It should distinguish a descriptive comparison from a causal claim or a model-based estimate. Those require different evidence.

A central future entry point should be **verify a newly released figure**: accept a source link, quoted claim, report, or chart; locate and authenticate the original publication; extract the precise claim and definitions; retrieve comparable and independent evidence; and present the resulting dossier. Publication authenticity, measurement quality, and support for an interpretation are separate questions. An authentic official release can still have limitations; a private estimate can be well supported. The interface should show those distinctions rather than collapse them into a single true/false badge. No such intake or verification feature exists in this seed.

An evidence dossier should contain the following records:

| Record | Minimum content |
| --- | --- |
| Question and claim | Exact statement, scope, alternatives, and what would count against it |
| Source | Publisher, original URL, document/table/page, publication and access dates, reuse conditions |
| Observation | Value, unit, geography, reference period, definition, population, sampling or coverage information, uncertainty where available |
| Version | Original release, revision date, retrieval record, and lawful archived reference or content fingerprint |
| Lineage | Original producer, upstream datasets, quotations, transformations, and dependencies |
| Comparison | Compatibility checks, exclusions, conversion formulas, assumptions, and remaining differences |
| Result | Findings, alternative explanations, limits, sensitivity to assumptions, reviewer comments, and revision history |

A fingerprint can show that a captured file changed. It cannot prove that its contents were accurate. If redistributing a source is not permitted, retain a lawful citation and permitted metadata rather than republishing it.

## A proposed investigation workflow

1. **Specify the question before collecting evidence.** Register scope, candidate metrics, inclusion criteria, comparison rules, and expected failure cases to reduce cherry-picking.
2. **Find candidate sources.** Include methodological notes and revision histories. Record search coverage and known gaps; absence from search results is not evidence of absence.
3. **Extract with verification.** AI may propose fields and citations. Check important figures against the original table or page. Record missing values instead of inventing replacements. Preserve original language alongside translations where interpretation matters.
4. **Check comparability.** Align geography, population, age range, time, units, price basis, seasonal treatment, sampling, and definitions. Mark incompatible series and explain why they cannot be combined.
5. **Map dependencies.** Group sources that share upstream observations. A global aggregator and a national report may contain the same original series. Different model providers may also share training sources or retrieval results.
6. **Apply appropriate checks.** Use accounting identities where definitions permit; examine revisions and within-series consistency; compare genuinely independent measurement methods. Treat satellite, transaction, search, and platform measures as proxies with their own selection and coverage problems.
7. **Test explanations.** Examine denominator changes, publication lags, informal activity, survey redesigns, structural change, and other plausible causes. Run sensitivity analyses and, where possible, test methods on held-out periods or known historical revisions.
8. **Publish and invite challenge.** Provide the dossier, permitted supporting material, reproducible calculations, conflicting evidence, and conditions that would change the conclusion. Allow corrections and preserve a versioned record.

## How to describe a discrepancy

Use specific, reviewable findings: a definition mismatch; a time or geographic mismatch; a coverage or sampling limitation; a revision; a calculation or extraction error; selective presentation supported by identified omissions; an unexplained inconsistency; or insufficient evidence.

Distinguish a source's observed defect from the presumed motive of its author. Describing intentional manipulation requires evidence beyond statistical surprise. Apply the same criteria to official institutions, private companies, researchers, media, advocacy groups, and the project itself. A discrepancy may identify a question without identifying which source is wrong.

Do not automatically average disagreeing figures. Combining estimates requires a stated model, an account of dependence and uncertainty, and sensitivity to assumptions. Do not infer a hidden value solely because several indirect proxies point in one direction. Where evidence cannot identify the quantity, report that limitation.

## AI and system boundaries

AI may assist discovery, extraction, translation, classification, hypothesis generation, and explanation. It must not silently supply missing facts, turn a generated citation into evidence, or declare a source dishonest from a pattern alone. Record model/provider/version where available, the date, prompts or task instructions, tool calls, and human corrections. Respect source terms and avoid sending confidential or personal data to a model provider without an appropriate basis.

A future design could separate source retrieval, extraction, a provenance store, deterministic calculations, review, and presentation. Treat retrieved documents as untrusted input; text inside a source must never authorize tool actions or change investigation rules. Isolate document processing and untrusted code from credentials and privileged operations. No model or infrastructure vendor is selected by this seed. Future communities must decide their own costs, access, hosting, and security arrangements.

## Proposed milestones

| Stage | Deliverable | Acceptance criterion |
| --- | --- | --- |
| 0: form a community | Maintained fork, named custodians, public rules, conflicts and resource disclosures | People know where decisions occur and who can act on them |
| 1: demonstrate the method manually | One evidence dossier, source lineage, comparability table, calculations, and disagreement log | Every key number is traceable; another person can reproduce calculations; limits and counterevidence are visible |
| 2: specify the tool | Data model, source adapter specification, threat model, evaluation cases, and interface proposal | Scope and failure behavior are explicit; extraction accuracy and citation checks have measurable criteria |
| 3: consider a prototype | A separately agreed implementation plan and software license | Participants approve ownership, resources, security, evaluation, and maintenance arrangements before development |
| 4: expand deliberately | Additional domains and cross-domain investigations | Each addition passes the same comparability, lineage, privacy, and reproducibility standards |

These are suggested stages, not deadlines or funding promises. This seed stops before implementation.

## Evaluation before scale

A future community should test against documented errors, legitimate definition differences, revised releases, incompatible proxies, shared-source repetition, and cases with no identifiable answer. Measure extraction and citation errors separately from the correctness of interpretations. Include misleading charts, omitted denominators, OCR mistakes, translated terminology, and stale versions. Compare AI-assisted work with a carefully reviewed manual baseline. Publish failures as well as successes.

For the suggested employment pilot, compare unemployment, labour participation, employment-to-population measures, hours, and wages for the same place and period, subject to availability and compatible definitions. Administrative records or independent surveys can add perspective, but must first be checked for coverage and dependency. A falling unemployment rate alone does not settle the broader question.

## Carry the work forward

The future tool begins with people willing to examine one claim carefully. A checked citation, a sound comparison, a clearly explained limitation: these are the materials from which public understanding grows. Choose a question, bring others into the investigation, and leave a trail strong enough for strangers to test. Let that be the first achievement of your community.

## Methodological references

These references inform the proposal; they do not certify or endorse this project.

- [UN Fundamental Principles of Official Statistics](https://unstats.un.org/fpos): professional methods, transparency, confidentiality, and responsible interpretation.
- [IMF Data Quality Assessment Framework overview](https://www.imf.org/external/np/sta/dsbb/2003/eng/dqaf.htm): a framework for examining statistical practices and data quality.
- [W3C PROV Overview](https://www.w3.org/TR/prov-overview/): representing the provenance of entities, activities, and agents.
- [ILO labour force overview](https://www.ilo.org/resource/labour-force): distinctions among employment, unemployment, and being outside the labour force.
