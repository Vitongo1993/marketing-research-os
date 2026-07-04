# revision-plan.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — TCC Revision Plan
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document defines the revision plan for transforming the current TCC drafts into a final academic version.

Its purpose is to organize what still needs to be reviewed, validated, rewritten, standardized and formatted before the final submission of the MBA Final Project.

This document should be used as a working checklist before assembling the final TCC.

---

# Current Project Status

The project is already structurally advanced.

The main research architecture, case documentation, theoretical mapping, references and chapter drafts have already been created.

The current stage is no longer about building the project from zero.

The current stage is about:

```text id="p4z6kd"
Refining
Validating
Connecting
Citing
Formatting
Finalizing
```

---

# Estimated Completion Status

| Area                             | Current Status |
| -------------------------------- | -------------: |
| MROS project structure           |            90% |
| Analytical frameworks            |            85% |
| Telex case documentation         |            85% |
| Reference mapping                |            75% |
| TCC chapter drafts               |            70% |
| Formal citations inside the text |            30% |
| Final unified document           |            20% |
| Final ABNT formatting            |            10% |

Overall estimate:

```text id="l8qp7m"
Project structure: approximately 75% complete
Final TCC readiness: approximately 60% complete
```

---

# Documents Already Created

## 1. Project Foundation

```text id="bf9a9w"
README.md
PROJECT_PRINCIPLES.md
PROJECT_CHARTER.md
ROADMAP.md
CONTRIBUTING.md
RESEARCH_FOUNDATIONS.md
RESEARCH_WORKFLOW.md
ADR-0001-Adopt-Knowledge-Framework-Architecture.md
```

---

## 2. Frameworks

```text id="xwpoui"
customer-journey-framework.md
crm-framework.md
lead-management-framework.md
```

---

## 3. Telex Case Documents

```text id="rotapv"
case-study-overview.md
kpi-analysis.md
operational-flow.md
business-rules.md
before-after-analysis.md
research-questions-and-hypotheses.md
methodological-positioning.md
data-dictionary.md
tcc-outline.md
```

---

## 4. Literature and References

```text id="78t7da"
literature-review-map.md
references/README.md
references/authors.md
references/books.md
references/articles.md
references/reports.md
references/abnt-references.md
references/citation-notes.md
```

---

## 5. TCC Chapter Drafts

```text id="ttz14u"
docs/tcc-writing/introduction-draft.md
docs/tcc-writing/methodology-draft.md
docs/tcc-writing/theoretical-framework-draft.md
docs/tcc-writing/case-context-draft.md
docs/tcc-writing/results-discussion-draft.md
docs/tcc-writing/conclusion-draft.md
```

---

# Revision Philosophy

The revision process should follow four principles:

```text id="8gzw4p"
1. Academic rigor
2. Conceptual consistency
3. Data consistency
4. Clear connection between theory and case
```

The final TCC should not read like a collection of separate documents.

It should read as one coherent academic work.

---

# Critical Revision Priorities

The following items are considered critical before final submission.

---

## 1. Avoid Strong Causal Language

Because the research is a before-and-after case study without a control group, the text must avoid definitive causal claims.

## Replace Strong Causality

Avoid:

```text id="doxwlf"
The redesign caused the increase in sales.
```

Prefer:

```text id="a8q3s9"
The data suggest that the redesign was associated with an increase in sales.
```

Avoid:

```text id="rqn6ml"
The chatbot improved conversion.
```

Prefer:

```text id="y0gc7b"
The chatbot-based entry coincided with faster response time and may have contributed to improved funnel performance when combined with CRM routing and store-level ownership.
```

Avoid:

```text id="c5op6c"
Store ownership caused higher attendance.
```

Prefer:

```text id="v3mjyh"
The increase in attendance rate may be associated with faster scheduling, clearer ownership and more direct store contact.
```

---

## 2. Standardize Cost Terminology

The project must consistently distinguish:

```text id="fy74iu"
Estimated operational cost
```

from:

```text id="lib5tq"
Customer Acquisition Cost — CAC
```

The current analysis does not calculate full CAC because it does not include:

* paid media investment
* store-level costs
* taxes
* benefits
* management overhead
* creative production
* indirect company costs

Use the correct wording:

```text id="ps5p8g"
estimated operational cost per lead
estimated operational cost per appointment
estimated operational cost per attendance
estimated operational cost per sale
```

Do not use:

```text id="q8k0i7"
CAC
cost of acquisition
full acquisition cost
```

unless the missing data is added later.

---

## 3. Standardize Key Terms

The following terms must be consistent across all chapters:

| Preferred Term           | Avoid Inconsistency With                                                      |
| ------------------------ | ----------------------------------------------------------------------------- |
| lead                     | prospect, contato, oportunidade, when used interchangeably without definition |
| agendamento              | consulta marcada, atendimento marcado, if not standardized                    |
| comparecimento           | presença, atendimento realizado, if not defined                               |
| venda                    | conversão final, compra, sale, if not standardized                            |
| lead fantasma            | ghost lead, non-responsive lead, if not defined                               |
| lead frio                | cold lead                                                                     |
| lead perdido             | lost lead                                                                     |
| ownership                | responsabilidade, dono do lead, if not consistently explained                 |
| CSO                      | loja, vendedor, atendente, if role is unclear                                 |
| tempo até agendamento    | scheduling time                                                               |
| tempo de resposta humana | human response time                                                           |
| resposta automatizada    | automated response                                                            |

The `data-dictionary.md` should be used as the source of truth.

---

## 4. Separate Automated Response from Human Response

The TCC must clearly distinguish:

```text id="czvlnj"
Bot response
```

from:

```text id="orhszz"
Human store contact
```

The 2025 model provides immediate bot response, but this does not necessarily mean immediate human service.

This distinction is important for academic rigor.

---

## 5. Validate All Numbers Across Chapters

The following numbers must remain consistent in every chapter:

| Indicator              |    2024 |   2025 |
| ---------------------- | ------: | -----: |
| Leads Generated        |   4.560 | 24.789 |
| Appointments Scheduled |   4.552 | 24.757 |
| Attendance             |   2.415 | 15.785 |
| Sales                  |     104 |  1.288 |
| Time Until Scheduling  | Até 48h | Até 2h |

Conversion rates:

| Metric                   |   2024 |   2025 |
| ------------------------ | -----: | -----: |
| Lead → Appointment       | 99,82% | 99,87% |
| Appointment → Attendance | 53,05% | 63,76% |
| Attendance → Sale        |  4,31% |  8,16% |
| Lead → Sale              |  2,28% |  5,20% |

Estimated operational cost:

| Metric                   |        2024 |       2025 |
| ------------------------ | ----------: | ---------: |
| Monthly operational cost |   R$ 25.052 |  R$ 12.227 |
| Annual operational cost  |  R$ 300.624 | R$ 146.724 |
| Estimated cost per lead  |    R$ 65,93 |    R$ 5,92 |
| Estimated cost per sale  | R$ 2.890,62 |  R$ 113,92 |

---

# Chapter-by-Chapter Revision Plan

---

# 1. Introduction Draft

File:

```text id="rwz20m"
docs/tcc-writing/introduction-draft.md
```

## Revision Goals

The introduction should clearly present:

* research context
* business problem
* relevance of customer journey
* Telex case context
* research question
* general objective
* specific objectives
* justification
* study delimitation
* structure of the work

## Required Revisions

* Add formal citations to support digital transformation, customer journey, CRM and services context.
* Reduce possible repetition between context and justification.
* Confirm final research title.
* Ensure problem statement matches the methodology and results chapters.
* Keep causal language cautious.
* Confirm whether the text will mention exact KPI results in the introduction or reserve them for the results chapter.

## Suggested Citations

* Lemon and Verhoef
* Kotler, Keller and Chernev
* Chaffey and Ellis-Chadwick
* Payne and Frow
* Zeithaml, Bitner and Gremler
* WHO or hearing health report, if used for sector context

## Status

```text id="dqb7xw"
Good draft — needs citations and refinement.
```

---

# 2. Theoretical Framework Draft

File:

```text id="ctxsmw"
docs/tcc-writing/theoretical-framework-draft.md
```

## Revision Goals

The theoretical framework should support the full interpretation of the Telex case.

It should explain:

* customer journey
* friction
* customer experience
* service quality
* CRM
* lead management
* funnel metrics
* automation
* AI and hybrid service
* service marketing

## Required Revisions

* Insert formal citations throughout the chapter.
* Reduce generic explanations where they do not directly support the Telex case.
* Strengthen the connection between theory and the research problem.
* Avoid making the chapter too broad.
* Ensure every concept appears later in the results/discussion.
* Add a final synthesis connecting theory to the conceptual model.

## Suggested Citation Blocks

Customer Journey:

```text id="21hri3"
Lemon and Verhoef, 2016
Rawson, Duncan and Jones, 2013
Edelman and Singer, 2015
```

CRM:

```text id="6wjjwu"
Payne and Frow, 2005
Buttle and Maklan, 2019
```

Lead Management and Automation:

```text id="p8uo9k"
Järvinen and Taiminen, 2016
Farris et al., 2016
```

AI and Service:

```text id="rervsj"
Davenport et al., 2020
Huang and Rust, 2018
```

Service Marketing:

```text id="tmnx71"
Parasuraman, Zeithaml and Berry, 1985/1988
Grönroos, 1984/2007
Zeithaml, Bitner and Gremler, 2018
```

## Status

```text id="s76acf"
Strong draft — needs formal academic citation insertion.
```

---

# 3. Methodology Draft

File:

```text id="typf7l"
docs/tcc-writing/methodology-draft.md
```

## Revision Goals

The methodology must make the study academically defensible.

It should clearly explain:

* research classification
* case study strategy
* documentary research
* mixed-method approach
* before-and-after comparison
* unit of analysis
* data sources
* indicators analyzed
* limitations
* ethical aspects

## Required Revisions

* Add methodology citations.
* Confirm exact period covered by 2024 and 2025 data.
* Confirm whether 2025 data represents full year, partial year or projected period.
* Confirm source and extraction method of the operational data.
* Clarify whether data were exported from CRM, spreadsheet or internal report.
* Strengthen validity and reliability section.
* Clarify ethical handling of company/customer data.
* Mention that data are aggregated and anonymized.

## Suggested Citations

```text id="clx9w3"
Yin, 2018
Creswell and Creswell, 2018
Gil, 2019
Lakatos and Marconi, 2017
Bardin, only if formal content analysis is used
```

## Status

```text id="8qmp4m"
Good draft — needs data source validation and methodology citations.
```

---

# 4. Case Context Draft

File:

```text id="xdphkz"
docs/tcc-writing/case-context-draft.md
```

## Revision Goals

This chapter should describe the Telex case clearly without turning into the results chapter.

It should explain:

* organization context
* sector context
* 2024 model
* call center role
* bottlenecks
* 2025 redesign
* bot, CRM and automation flow
* store ownership
* business rules
* key operational changes

## Required Revisions

* Avoid repeating too much KPI interpretation from the results chapter.
* Keep numbers only as contextual preview or move them to the results chapter.
* Confirm exact tool names:

  * RD Conversas
  * RD CRM
  * Google Sheets
  * Pluga
* Confirm whether the word "CSO" needs explanation for academic readers.
* Add a short paragraph explaining why hearing care is a service-sensitive context.
* Remove confidential operational details if necessary.

## Suggested Citations

* Zeithaml, Bitner and Gremler
* Grönroos
* Lovelock and Wirtz
* WHO hearing report, if used
* Chaffey and Ellis-Chadwick, for digital acquisition context

## Status

```text id="hkso2m"
Strong operational chapter — needs confidentiality review and citation insertion.
```

---

# 5. Results and Discussion Draft

File:

```text id="mnl9si"
docs/tcc-writing/results-discussion-draft.md
```

## Revision Goals

This chapter must connect data, theory and interpretation.

It should answer the research question directly.

## Required Revisions

* Add citations where theory is used to interpret results.
* Ensure every KPI matches `kpi-analysis.md`.
* Keep causal language cautious.
* Strengthen the distinction between:

  * volume increase
  * conversion improvement
  * operational efficiency
  * lead quality trade-off
* Clarify that cost analysis is operational, not full CAC.
* Consider adding a table summarizing hypothesis support.
* Consider moving managerial implications to a separate chapter or section.

## Suggested Additional Table

```text id="6b99i6"
Hypothesis | Evidence | Status | Caution
H1 | Lead growth | Partially supported | Media investment not controlled
H2 | Immediate bot response | Descriptively supported | Not equal to human response
H3 | Scheduling time reduction | Descriptively supported | Store-level variation unknown
H4 | Attendance rate increase | Partially supported | Other factors may influence
H5 | Sales conversion increase | Partially supported | Sales influenced by several factors
H6 | More ghost leads | Qualitatively supported | Needs detailed dataset
H7 | More scale with fewer operators | Partially supported | Cost estimate incomplete
```

## Suggested Citations

* Lemon and Verhoef
* Rawson, Duncan and Jones
* Payne and Frow
* Järvinen and Taiminen
* Farris et al.
* Huang and Rust
* Parasuraman, Zeithaml and Berry
* Yin and Creswell for methodological caution

## Status

```text id="6ogfgu"
Very strong draft — needs citations, hypothesis table and final data validation.
```

---

# 6. Conclusion Draft

File:

```text id="b40jai"
docs/tcc-writing/conclusion-draft.md
```

## Revision Goals

The conclusion should answer the research question, summarize findings and present contributions without adding new data.

## Required Revisions

* Remove any new information not previously discussed.
* Ensure the conclusion directly answers the research question.
* Keep causal language cautious.
* Strengthen distinction between contribution and limitation.
* Confirm that the conclusion does not repeat entire results chapter.
* Add final managerial and academic contribution in a concise way.

## Status

```text id="4mydb7"
Good draft — should be revised after all other chapters are finalized.
```

---

# Cross-Document Revision Checklist

Use this checklist across all chapters.

---

## Conceptual Consistency

Check whether the following concepts are used consistently:

```text id="0lb5zd"
Customer journey
Friction
Customer experience
CRM
Lead management
Automation
AI
Service marketing
Sales funnel
Ownership
Operational efficiency
```

---

## Data Consistency

Check whether the same numbers appear identically in every chapter:

```text id="dhhyy4"
4.560 leads in 2024
24.789 leads in 2025
4.552 appointments in 2024
24.757 appointments in 2025
2.415 attendances in 2024
15.785 attendances in 2025
104 sales in 2024
1.288 sales in 2025
48h to 2h scheduling time
```

---

## Methodological Consistency

Check whether the study is always described as:

```text id="dht6nb"
Applied research
Descriptive and exploratory research
Single case study
Documentary research
Mixed-method approach
Before-and-after analysis
```

Avoid describing it as:

```text id="e6n730"
Experiment
Causal study
Statistical proof
Longitudinal causal analysis
Randomized test
```

---

## Language Consistency

Preferred expressions:

```text id="id39no"
the data suggest
the results indicate
the redesign was associated with
the evidence points to
the case suggests
may have contributed
```

Avoid:

```text id="yqwaxz"
proved
caused
guaranteed
directly generated
fully explained
definitively demonstrated
```

---

# Citation Revision Plan

Formal citations must be inserted in four stages.

---

## Stage 1 — Theoretical Framework

This is the highest priority.

Every key concept should have at least one formal citation.

---

## Stage 2 — Methodology

Insert methodology citations to justify the research design.

---

## Stage 3 — Results and Discussion

Use citations to connect findings to theory.

Do not over-cite KPI tables.

---

## Stage 4 — Introduction

Use citations to support context and relevance.

---

# Reference Validation Plan

The `references/abnt-references.md` file must be reviewed before final submission.

---

## Items to Verify

```text id="oer98a"
1. Exact title of each book
2. Exact edition used
3. Year of publication
4. Publisher
5. City of publication, when required
6. Article volume and issue
7. Article page range
8. DOI, when required
9. URL and access date for online sources
10. UFRJ/MBA formatting requirements
```

---

# Final Assembly Plan

After revision, the TCC should be assembled in the following order:

```text id="0ous1y"
1. Cover
2. Title page
3. Abstract
4. Keywords
5. Summary
6. Introduction
7. Theoretical Framework
8. Methodology
9. Case Context
10. Before-and-After Analysis
11. Results and Discussion
12. Managerial Implications
13. Limitations and Future Research
14. Conclusion
15. References
16. Appendices
```

---

# Recommended Next Documents

After this revision plan, the next recommended files are:

```text id="vxz2r1"
docs/tcc-writing/final-tcc-assembly-plan.md
docs/tcc-writing/citation-insertion-plan.md
docs/tcc-writing/abnt-formatting-checklist.md
docs/tcc-writing/managerial-implications-draft.md
docs/tcc-writing/limitations-future-research-draft.md
```

---

# Final Summary

The project is already highly structured and has enough material to become a complete TCC.

The remaining work is concentrated in:

```text id="sy2h8d"
1. Revising chapter drafts
2. Inserting formal citations
3. Validating references
4. Checking data consistency
5. Unifying the document
6. Applying ABNT formatting
7. Reviewing with the academic advisor
```

The most critical next task is not creating new theory, but transforming the existing material into a cohesive, cited and academically polished final document.

---

**End of Document**

