# final-data-validation.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Final Data Validation
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document provides the final data validation checklist for the MBA Final Project based on the Telex Soluções Auditivas case.

Its purpose is to ensure that all quantitative indicators, operational descriptions, cost estimates, conversion rates, tables, figures and analytical interpretations used in the final manuscript are consistent, accurate, clearly sourced and methodologically defensible.

This document should be completed before creating:

```text id="dkj4a9"
docs/tcc-writing/final-manuscript-with-citations.md
```

and before submitting the manuscript to the academic advisor.

---

# Core Validation Principle

The final TCC must distinguish clearly between:

```text id="b4qg3t"
1. Raw internal data.
2. Calculated indicators.
3. Operational descriptions.
4. Author interpretation.
5. Academic theory.
```

The final manuscript should never present interpretation as raw data, nor present internal company data as academic evidence.

---

# Source Files to Use

Use this checklist together with:

```text id="ywygx8"
telex/case-study-overview.md
telex/kpi-analysis.md
telex/operational-flow.md
telex/before-after-analysis.md
telex/business-rules.md
telex/data-dictionary.md
docs/tcc-writing/final-manuscript-draft.md
docs/tcc-writing/tables-and-figures-list.md
docs/tcc-writing/final-review-checklist.md
docs/tcc-writing/abnt-formatting-checklist.md
```

---

# 1. Data Source Validation

Before final submission, identify the exact source of each data group.

---

## 1.1 Funnel Data

Validate the source of:

```text id="b1l9zq"
Leads generated
Appointments scheduled
Attendance
Sales
```

Checklist:

```text id="cp1bhr"
[ ] Source system identified.
[ ] Extraction date identified.
[ ] Responsible area identified.
[ ] Period covered identified.
[ ] Counting rules identified.
[ ] Data exported or documented.
[ ] Data approved for academic use.
```

Possible source description:

```text id="g0pkaq"
Internal operational records from Telex Soluções Auditivas, consolidated by the author for academic analysis.
```

or, if anonymization is required:

```text id="g2h0vr"
Internal operational records from the company analyzed, consolidated by the author for academic analysis.
```

---

## 1.2 Operational Flow Data

Validate the source of:

```text id="ohgi63"
2024 operational flow
2025 operational flow
Call center responsibilities
CSO responsibilities
Store responsibilities
CRM and automation flow
Business rules
```

Checklist:

```text id="jsnmb5"
[ ] Information source identified.
[ ] Process descriptions confirmed with internal records or responsible team.
[ ] Tool names verified.
[ ] Role names verified.
[ ] Sensitive details removed.
[ ] Company authorization confirmed, if needed.
```

---

## 1.3 Cost Data

Validate the source of:

```text id="lhxo4l"
2024 call center cost
2025 call center cost
CRM cost
Bot or conversational platform cost
Automation tool cost
Variable payment assumptions
Operational cost calculations
```

Checklist:

```text id="f2qwl6"
[ ] Source of salary assumptions confirmed.
[ ] Source of tool costs confirmed.
[ ] Whether benefits are included or excluded is confirmed.
[ ] Whether taxes are included or excluded is confirmed.
[ ] Whether media investment is excluded is clearly stated.
[ ] Whether store costs are excluded is clearly stated.
[ ] Whether indirect overhead is excluded is clearly stated.
[ ] Cost values are authorized for use or anonymized.
```

Critical rule:

```text id="zrdnyk"
Do not call this CAC.
```

Preferred term:

```text id="pjwdff"
estimated operational cost
```

---

# 2. Period Validation

This is one of the most important checks in the study.

The final manuscript compares:

```text id="he59dv"
2024 model
```

with:

```text id="m141uw"
2025 model
```

Before finalizing, validate whether both periods are equivalent.

---

## 2.1 Period Equivalence Checklist

```text id="aop582"
[ ] 2024 period start date confirmed.
[ ] 2024 period end date confirmed.
[ ] 2025 period start date confirmed.
[ ] 2025 period end date confirmed.
[ ] Both periods cover the same number of months.
[ ] Both periods cover equivalent campaign cycles.
[ ] Both periods use the same counting rules.
[ ] Seasonal differences are considered.
```

---

## 2.2 If Periods Are Equivalent

If 2024 and 2025 are equivalent, the manuscript may use total annual or period totals.

Suggested wording:

```text id="gsx1d0"
Os períodos analisados possuem extensão temporal equivalente, permitindo a comparação direta dos indicadores agregados de 2024 e 2025.
```

---

## 2.3 If Periods Are Not Equivalent

If 2024 and 2025 are not equivalent, do not rely only on total values.

Use monthly averages or clearly state the limitation.

Suggested wording:

```text id="vvv89i"
Como os períodos analisados não possuem a mesma extensão temporal, a comparação entre valores absolutos deve ser interpretada com cautela. Sempre que possível, recomenda-se observar médias mensais para reduzir distorções decorrentes da diferença de período.
```

Required action:

```text id="j3rdjh"
[ ] Create monthly average table.
[ ] Update results discussion.
[ ] Update limitations chapter.
[ ] Update abstract if necessary.
[ ] Update conclusion if necessary.
```

---

# 3. Funnel Indicator Validation

Validate the main indicators used throughout the manuscript.

---

## 3.1 Leads Generated

Current value:

```text id="dgbcfg"
2024: 4,560
2025: 24,789
```

Checklist:

```text id="n9mp1a"
[ ] Definition of lead confirmed.
[ ] 2024 and 2025 use the same lead definition.
[ ] Duplicated leads treatment confirmed.
[ ] Bot-abandoned contacts included or excluded consistently.
[ ] Invalid phone numbers included or excluded consistently.
[ ] Organic and paid leads treatment confirmed.
[ ] Repeated contacts treatment confirmed.
```

Suggested definition:

```text id="u55q2f"
Lead generated: contact that entered the commercial journey through the analyzed acquisition channels and was registered in the operational flow.
```

---

## 3.2 Appointments Scheduled

Current value:

```text id="pc3xmm"
2024: 4,552
2025: 24,757
```

Checklist:

```text id="v1szbb"
[ ] Definition of appointment confirmed.
[ ] Appointment counted only after confirmed scheduling.
[ ] Rescheduled appointments treatment confirmed.
[ ] Canceled appointments treatment confirmed.
[ ] Duplicate appointments treatment confirmed.
[ ] Same counting rule used in 2024 and 2025.
```

Suggested definition:

```text id="c8mpxj"
Appointment scheduled: lead with a scheduled hearing check-up, consultation or store service appointment recorded in the operational system.
```

---

## 3.3 Attendance

Current value:

```text id="ucnt2u"
2024: 2,415
2025: 15,785
```

Checklist:

```text id="w3mwl9"
[ ] Definition of attendance confirmed.
[ ] No-show separated from attendance.
[ ] Cancellations separated from attendance.
[ ] Rescheduled appointments treatment confirmed.
[ ] Same attendance rule used in 2024 and 2025.
```

Suggested definition:

```text id="su418o"
Attendance: customer who effectively attended the scheduled store appointment or hearing check-up.
```

---

## 3.4 Sales

Current value:

```text id="qllk43"
2024: 104
2025: 1,288
```

Checklist:

```text id="nwb2mb"
[ ] Definition of sale confirmed.
[ ] Sale attribution rule confirmed.
[ ] Sales linked to original lead source confirmed.
[ ] Same attribution rule used in 2024 and 2025.
[ ] Cancellations, returns or refunds treatment confirmed.
[ ] Sales period aligned with lead period or clearly explained.
```

Suggested definition:

```text id="kyfl46"
Sale: commercial conversion attributed to a lead after the journey of contact, scheduling, attendance and store service.
```

---

# 4. KPI Calculation Validation

Validate all calculated indicators.

---

## 4.1 Absolute Variation

Formula:

```text id="q1ousg"
Absolute variation = 2025 value - 2024 value
```

Checklist:

```text id="uic0qh"
[ ] Leads variation: 24,789 - 4,560 = 20,229
[ ] Appointments variation: 24,757 - 4,552 = 20,205
[ ] Attendance variation: 15,785 - 2,415 = 13,370
[ ] Sales variation: 1,288 - 104 = 1,184
```

Validated values:

| Indicator       |  2024 |   2025 | Absolute Variation |
| --------------- | ----: | -----: | -----------------: |
| Leads Generated | 4,560 | 24,789 |            +20,229 |
| Appointments    | 4,552 | 24,757 |            +20,205 |
| Attendance      | 2,415 | 15,785 |            +13,370 |
| Sales           |   104 |  1,288 |             +1,184 |

---

## 4.2 Relative Variation

Formula:

```text id="bszbwc"
Relative variation = ((2025 value - 2024 value) / 2024 value) × 100
```

Checklist:

```text id="of0hf7"
[ ] Leads: ((24,789 - 4,560) / 4,560) × 100 = 443.6%
[ ] Appointments: ((24,757 - 4,552) / 4,552) × 100 = 443.9%
[ ] Attendance: ((15,785 - 2,415) / 2,415) × 100 = 553.6%
[ ] Sales: ((1,288 - 104) / 104) × 100 = 1,138.5%
```

Validated values:

| Indicator       | Relative Variation |
| --------------- | -----------------: |
| Leads Generated |            +443.6% |
| Appointments    |            +443.9% |
| Attendance      |            +553.6% |
| Sales           |          +1,138.5% |

---

## 4.3 Conversion Rates

Formula:

```text id="nzay5r"
Conversion rate = next funnel stage / previous funnel stage
```

Checklist:

```text id="xic9qz"
[ ] Lead → Appointment 2024: 4,552 / 4,560 = 99.82%
[ ] Lead → Appointment 2025: 24,757 / 24,789 = 99.87%
[ ] Appointment → Attendance 2024: 2,415 / 4,552 = 53.05%
[ ] Appointment → Attendance 2025: 15,785 / 24,757 = 63.76%
[ ] Attendance → Sale 2024: 104 / 2,415 = 4.31%
[ ] Attendance → Sale 2025: 1,288 / 15,785 = 8.16%
[ ] Lead → Sale 2024: 104 / 4,560 = 2.28%
[ ] Lead → Sale 2025: 1,288 / 24,789 = 5.20%
```

Validated values:

| Conversion Metric        |   2024 |   2025 |
| ------------------------ | -----: | -----: |
| Lead → Appointment       | 99.82% | 99.87% |
| Appointment → Attendance | 53.05% | 63.76% |
| Attendance → Sale        |  4.31% |  8.16% |
| Lead → Sale              |  2.28% |  5.20% |

---

## 4.4 Percentage Point Variation

Formula:

```text id="qzbmqr"
Percentage point variation = 2025 rate - 2024 rate
```

Checklist:

```text id="j6pl1h"
[ ] Lead → Appointment: 99.87% - 99.82% = +0.05 p.p.
[ ] Appointment → Attendance: 63.76% - 53.05% = +10.71 p.p.
[ ] Attendance → Sale: 8.16% - 4.31% = +3.85 p.p.
[ ] Lead → Sale: 5.20% - 2.28% = +2.92 p.p.
```

Validated values:

| Conversion Metric        |   Variation |
| ------------------------ | ----------: |
| Lead → Appointment       |  +0.05 p.p. |
| Appointment → Attendance | +10.71 p.p. |
| Attendance → Sale        |  +3.85 p.p. |
| Lead → Sale              |  +2.92 p.p. |

---

# 5. Time Indicator Validation

Current values:

```text id="wakq7n"
2024: time until scheduling up to 48 hours
2025: time until scheduling up to 2 hours
```

Checklist:

```text id="kz4k85"
[ ] Confirm whether this is maximum time, average time or service target.
[ ] Confirm whether 2024 value refers to call center process.
[ ] Confirm whether 2025 value refers to store scheduling process.
[ ] Confirm whether 2025 value includes bot response or only scheduling.
[ ] Confirm whether human response time is measured separately.
[ ] Confirm whether weekend and non-business-hour behavior differs.
```

Critical distinction:

```text id="xwiyqs"
Immediate bot response is not the same as immediate human response.
```

Preferred final wording:

```text id="dpssf0"
O modelo de 2025 passou a oferecer resposta automatizada imediata via bot, enquanto o tempo máximo até agendamento foi reduzido de até 48 horas para até 2 horas, segundo os registros operacionais analisados.
```

Avoid:

```text id="fuxqmb"
O atendimento humano passou a ser imediato.
```

unless human response data proves it.

---

# 6. Operational Cost Validation

Current values:

```text id="mfz2im"
2024 monthly estimated operational cost: R$ 25,052
2025 monthly estimated operational cost: R$ 12,227
2024 annual estimated operational cost: R$ 300,624
2025 annual estimated operational cost: R$ 146,724
```

---

## 6.1 Monthly and Annual Cost Check

Formula:

```text id="raz6hu"
Annual estimated operational cost = monthly estimated operational cost × 12
```

Checklist:

```text id="hwwy25"
[ ] 2024: R$ 25,052 × 12 = R$ 300,624
[ ] 2025: R$ 12,227 × 12 = R$ 146,724
```

---

## 6.2 Cost per Indicator Check

Formula:

```text id="pl3315"
Estimated operational cost per indicator = annual estimated operational cost / annual indicator volume
```

Checklist:

```text id="v5n2ep"
[ ] Cost per lead 2024: R$ 300,624 / 4,560 = R$ 65.93
[ ] Cost per lead 2025: R$ 146,724 / 24,789 = R$ 5.92
[ ] Cost per appointment 2024: R$ 300,624 / 4,552 = R$ 66.04
[ ] Cost per appointment 2025: R$ 146,724 / 24,757 = R$ 5.93
[ ] Cost per attendance 2024: R$ 300,624 / 2,415 = R$ 124.48
[ ] Cost per attendance 2025: R$ 146,724 / 15,785 = R$ 9.29 or R$ 9.30 depending rounding
[ ] Cost per sale 2024: R$ 300,624 / 104 = R$ 2,890.62
[ ] Cost per sale 2025: R$ 146,724 / 1,288 = R$ 113.92
```

Validated values:

| Metric                                     |        2024 |              2025 |
| ------------------------------------------ | ----------: | ----------------: |
| Estimated operational cost per lead        |    R$ 65.93 |           R$ 5.92 |
| Estimated operational cost per appointment |    R$ 66.04 |           R$ 5.93 |
| Estimated operational cost per attendance  |   R$ 124.48 | R$ 9.29 / R$ 9.30 |
| Estimated operational cost per sale        | R$ 2,890.62 |         R$ 113.92 |

---

## 6.3 Cost Limitation Statement

The final manuscript must include this note near any cost table:

```text id="pmzgrr"
Nota: os valores referem-se a custos operacionais estimados relacionados à camada de atendimento, CRM e automação. Eles não representam CAC completo, pois não incluem mídia paga, custos de loja, impostos, benefícios, overhead e custos indiretos.
```

Checklist:

```text id="fr47gg"
[ ] Cost table includes limitation note.
[ ] Methodology includes limitation note.
[ ] Results discussion includes limitation note.
[ ] Limitations chapter includes limitation note.
[ ] Conclusion does not overstate cost reduction.
```

---

# 7. Data Consistency Across Manuscript

Search the full manuscript and confirm that every occurrence of the following numbers is consistent.

---

## 7.1 Funnel Values

```text id="cwc352"
[ ] 4,560 or 4.560 always refers to 2024 leads.
[ ] 24,789 or 24.789 always refers to 2025 leads.
[ ] 4,552 or 4.552 always refers to 2024 appointments.
[ ] 24,757 or 24.757 always refers to 2025 appointments.
[ ] 2,415 or 2.415 always refers to 2024 attendance.
[ ] 15,785 or 15.785 always refers to 2025 attendance.
[ ] 104 always refers to 2024 sales.
[ ] 1,288 or 1.288 always refers to 2025 sales.
```

---

## 7.2 Conversion Values

```text id="ecybg3"
[ ] 99.82% / 99,82% appears only as 2024 Lead → Appointment.
[ ] 99.87% / 99,87% appears only as 2025 Lead → Appointment.
[ ] 53.05% / 53,05% appears only as 2024 Appointment → Attendance.
[ ] 63.76% / 63,76% appears only as 2025 Appointment → Attendance.
[ ] 4.31% / 4,31% appears only as 2024 Attendance → Sale.
[ ] 8.16% / 8,16% appears only as 2025 Attendance → Sale.
[ ] 2.28% / 2,28% appears only as 2024 Lead → Sale.
[ ] 5.20% / 5,20% appears only as 2025 Lead → Sale.
```

---

## 7.3 Percentage Variation Values

```text id="vch8nw"
[ ] +443.6% / +443,6% refers to lead growth.
[ ] +443.9% / +443,9% refers to appointment growth.
[ ] +553.6% / +553,6% refers to attendance growth.
[ ] +1,138.5% / +1.138,5% refers to sales growth.
```

---

# 8. Formatting of Numbers

Choose the final numeric format according to the language and institutional rule.

Since the final TCC is in Portuguese, preferred Brazilian formatting is:

```text id="tvaxba"
4.560
24.789
99,82%
R$ 65,93
```

Avoid mixing Brazilian and English formatting in the final version.

Checklist:

```text id="bk5202"
[ ] Thousands separator is consistent.
[ ] Decimal separator is consistent.
[ ] Percentage formatting is consistent.
[ ] Currency formatting is consistent.
[ ] Tables use the same numeric style as the text.
```

Recommended final style:

```text id="ndkfh1"
Portuguese text: 4.560 | 99,82% | R$ 65,93
English abstract: 4,560 | 99.82% | R$ 65.93, if numbers are included
```

---

# 9. Operational Description Validation

Validate the descriptions of each model.

---

## 9.1 2024 Model

Current description:

```text id="d3vkam"
Digital campaign → Lead form → Call center → Customer contact → Store contact → Manual schedule alignment → Customer confirmation → Appointment → Attendance → Sale or non-sale
```

Checklist:

```text id="v6p7lm"
[ ] Lead form fields confirmed.
[ ] Call center responsibilities confirmed.
[ ] Store contact step confirmed.
[ ] Manual schedule alignment confirmed.
[ ] Customer confirmation process confirmed.
[ ] Appointment rescheduling process confirmed.
[ ] Bottlenecks confirmed.
[ ] Positive aspects confirmed.
```

Key risks to validate:

```text id="gvty7z"
[ ] Call center did not have store schedule access.
[ ] Call center had goals or variable compensation.
[ ] Leads could be retained or delayed.
[ ] Customers sometimes distrusted outsourced/centralized service.
```

Use sensitive details only if authorized.

---

## 9.2 2025 Model

Current description:

```text id="erx4k8"
Digital campaign → Click to WhatsApp → Bot → RD Conversas → RD CRM → Google Sheets → Pluga → Store notification → CSO contact → Appointment → Attendance → Sale or non-sale
```

Checklist:

```text id="s3nkt4"
[ ] WhatsApp entry confirmed.
[ ] Bot function confirmed.
[ ] RD Conversas role confirmed.
[ ] RD CRM role confirmed.
[ ] Google Sheets role confirmed.
[ ] Pluga role confirmed.
[ ] Store notification confirmed.
[ ] CSO ownership confirmed.
[ ] Call center exception role confirmed.
[ ] Scheduling time up to 2h confirmed.
```

---

# 10. Business Rules Validation

Validate whether these rules remain correct.

```text id="tbmmva"
Qualified lead: interacts and shows hearing-related need or interest.
Cold lead: does not respond, cancels or stops interacting.
Maximum acceptable response: 30 minutes.
Priority lead: over 90 years old or urgent hearing aid placement.
Lost lead: no response for more than 3 months.
```

Checklist:

```text id="x1qshw"
[ ] Qualified lead definition confirmed.
[ ] Cold lead definition confirmed.
[ ] Ghost lead definition confirmed.
[ ] Lost lead definition confirmed.
[ ] Maximum response time confirmed.
[ ] Priority rules confirmed.
[ ] These rules are approved for inclusion.
```

---

# 11. Lead Quality Validation

The manuscript states that the redesigned model increased ghost or lower-quality leads.

This point must be treated carefully.

---

## 11.1 Current Evidence Type

Current evidence appears to be:

```text id="emxdmq"
operational observation
```

not:

```text id="wweoe1"
fully quantified dataset
```

Therefore, the final manuscript should say:

```text id="c5kqaz"
Observou-se operacionalmente aumento de leads fantasmas ou de menor qualidade.
```

Avoid saying:

```text id="ltqvsf"
Os dados comprovam aumento de leads fantasmas.
```

unless a quantified dataset is available.

---

## 11.2 Lead Quality Checklist

```text id="pnvyx5"
[ ] Ghost leads are defined.
[ ] Cold leads are defined.
[ ] Low-quality leads are defined.
[ ] Quantified ghost lead data exist or limitation is stated.
[ ] Lead quality limitation appears in limitations chapter.
[ ] Discussion uses cautious language.
```

---

# 12. Data-to-Interpretation Validation

Every major interpretation must be connected to data but phrased cautiously.

---

## 12.1 Acceptable Interpretations

```text id="zvb4tt"
The redesign was associated with higher lead volume.
The redesign was associated with shorter time until scheduling.
The redesigned flow processed more appointments, attendance and sales.
The store ownership model may have contributed to faster scheduling.
CRM and automation may have supported operational scalability.
The increase in low-quality leads appears as an operational trade-off.
```

---

## 12.2 Interpretations to Avoid

```text id="y97wpq"
The redesign caused the increase in sales.
The bot generated more qualified leads.
The CRM proved the effectiveness of the model.
The automation alone explains the growth.
The company reduced CAC.
The model will work for all service companies.
The AI system improved sales.
```

---

# 13. Table Source Validation

Every table must have a source.

Suggested source labels:

---

## 13.1 Tables Based on Internal Data

```text id="uk8zdk"
Fonte: Elaborado pelo autor com base em dados operacionais internos da Telex Soluções Auditivas.
```

Use for:

```text id="d0jlb8"
Funnel indicators
Conversion rates
Cost estimates
Response and scheduling time
```

---

## 13.2 Tables Based on Author Analysis

```text id="busw7j"
Fonte: Elaborado pelo autor.
```

Use for:

```text id="qi6ym5"
Research classification
Hypothesis or proposition evaluation
Managerial recommendations
Limitations and future research
```

---

## 13.3 Tables Based on Internal Operational Information

```text id="w89v58"
Fonte: Elaborado pelo autor com base em informações operacionais internas da Telex Soluções Auditivas.
```

Use for:

```text id="ebyrys"
Operational model comparison
Business rules
Operational flow
```

---

## 13.4 If Anonymization Is Needed

```text id="x4saym"
Fonte: Elaborado pelo autor com base em dados operacionais internos da empresa analisada.
```

---

# 14. Figure Source Validation

Every figure must have a source.

Suggested source labels:

```text id="dm5ax5"
Fonte: Elaborado pelo autor.
```

or:

```text id="lmja2x"
Fonte: Elaborado pelo autor com base em informações operacionais internas da Telex Soluções Auditivas.
```

Checklist:

```text id="yn5vcd"
[ ] Figure 1 source included.
[ ] Figure 2 source included.
[ ] Figure 3 source included.
[ ] Figure 4 source included.
[ ] Figures do not contain confidential data.
[ ] Figures use validated flows.
```

---

# 15. Confidentiality Validation

Before finalizing the data, confirm whether the following can be disclosed.

```text id="xnku5p"
[ ] Company name: Telex Soluções Auditivas.
[ ] Funnel data.
[ ] Sales data.
[ ] Cost estimates.
[ ] Salary or compensation assumptions.
[ ] Tool names: RD Conversas, RD CRM, Google Sheets, Pluga.
[ ] Operational flow.
[ ] Call center structure.
[ ] Store and CSO role.
[ ] Business rules.
[ ] Screenshots.
```

If not authorized, use anonymized language:

```text id="lkw6vw"
empresa analisada
empresa do setor de saúde auditiva
dados operacionais internos
ferramenta de CRM
ferramenta de automação
canal conversacional
equipe centralizada
unidades comerciais
```

---

# 16. Final Data Validation Table

Use this table before creating the cited manuscript.

| Data Group            | Current Status         | Validation Needed                   | Risk Level | Final Decision |
| --------------------- | ---------------------- | ----------------------------------- | ---------- | -------------- |
| Funnel indicators     | Available              | Confirm source and period           | High       | Pending        |
| Conversion rates      | Calculated             | Confirm formulas and rounding       | Medium     | Pending        |
| Scheduling time       | Available              | Confirm definition                  | High       | Pending        |
| Cost estimates        | Available              | Confirm scope and authorization     | High       | Pending        |
| Operational flow 2024 | Available              | Confirm details and confidentiality | Medium     | Pending        |
| Operational flow 2025 | Available              | Confirm details and confidentiality | Medium     | Pending        |
| Lead quality          | Observed qualitatively | Quantify or state limitation        | High       | Pending        |
| Business rules        | Available              | Confirm current definitions         | Medium     | Pending        |
| Tool names            | Available              | Confirm authorization               | Medium     | Pending        |
| Company name          | Available              | Confirm authorization               | High       | Pending        |

---

# 17. Go / No-Go Checklist

The data are ready for the cited manuscript only when:

```text id="u0j10n"
[ ] Periods are validated.
[ ] Funnel data source is validated.
[ ] KPI definitions are validated.
[ ] Conversion formulas are checked.
[ ] Cost scope is validated.
[ ] Cost terminology is corrected.
[ ] Time indicators are defined.
[ ] Lead quality limitation is clear.
[ ] Operational flows are verified.
[ ] Confidentiality is reviewed.
[ ] Table sources are defined.
[ ] Figure sources are defined.
[ ] All numbers are consistent across the manuscript.
```

---

# 18. Output After Validation

After completing this checklist, create:

```text id="nmqia7"
docs/tcc-writing/final-manuscript-with-citations.md
```

This next file should include:

```text id="rsjtkn"
1. Formal citations inserted.
2. Internal notes removed.
3. Data values validated.
4. Tables with sources.
5. Cautious causal language.
6. Final reference placeholder or complete reference list.
```

---

# Final Summary

This document validates the quantitative and operational foundation of the Telex case.

The most critical validation points are:

```text id="f8i4tk"
1. Confirm whether 2024 and 2025 periods are equivalent.
2. Confirm the source and counting rules of funnel data.
3. Confirm that cost values are operational estimates, not CAC.
4. Confirm that immediate bot response is not confused with human response.
5. Confirm whether lead quality is quantified or only observed qualitatively.
6. Confirm authorization to use the Telex name, data, costs, tools and flows.
7. Keep all interpretations cautious and methodologically defensible.
```

Once these points are validated, the project can safely move into the cited manuscript version.

---

**End of Document**

