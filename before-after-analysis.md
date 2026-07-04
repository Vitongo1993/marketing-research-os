# before-after-analysis.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Before and After Analysis
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document presents a structured before-and-after analysis of the Telex Soluções Auditivas customer journey redesign.

Its purpose is to compare the 2024 and 2025 operational models across strategic, organizational, technological, commercial and customer experience dimensions.

This document complements:

* `case-study-overview.md`
* `kpi-analysis.md`
* `operational-flow.md`
* `business-rules.md`
* `customer-journey-framework.md`
* `crm-framework.md`
* `lead-management-framework.md`

---

# Analytical Objective

The objective of this analysis is to understand how the redesign of the lead journey affected the performance of the commercial funnel.

The analysis compares two operating models:

## 2024 Model

A centralized model in which the call center acted as the main owner of the lead, responsible for contacting the customer, understanding the problem, mediating scheduling with the store and confirming the appointment.

## 2025 Model

A decentralized and automation-supported model in which the bot handles the initial entry, CRM records the lead, automation distributes the data and the store assumes direct ownership of scheduling and follow-up.

---

# Executive Summary

The Telex redesign changed the customer journey from a call-center-centered model to a store-centered model supported by automation.

The main transformation was not simply the implementation of a chatbot.

The strategic shift was the redesign of operational ownership.

In 2024, the call center controlled the transition between customer intent and store appointment.

In 2025, the customer entered through WhatsApp, interacted with the bot, was registered in CRM and was routed to the store, where the CSO became responsible for scheduling and follow-up.

This shift reduced friction, increased speed, expanded lead volume and improved funnel performance.

---

# 1. Strategic Comparison

## 2024 — Centralized Intermediation

The 2024 model was based on centralized intermediation.

The call center served as the bridge between:

```text
Customer
   ↓
Call Center
   ↓
Store
   ↓
Call Center
   ↓
Customer
```

This model concentrated control, but created delays and operational dependency.

---

## 2025 — Automated Entry and Store Ownership

The 2025 model transferred operational ownership to the store.

The new structure followed this logic:

```text
Customer
   ↓
Bot
   ↓
CRM
   ↓
Automation
   ↓
Store CSO
   ↓
Customer
```

This model reduced the number of intermediaries and made the store responsible for the lead once the routing was completed.

---

# 2. Customer Entry Comparison

## 2024 Entry Model

The customer entered the journey through a more complex form.

The form collected multiple pieces of information before the conversation could advance.

Typical data included:

* name
* phone number
* city
* previous hearing test information
* possible indication for hearing aid use

This model helped qualify leads earlier, but increased friction at the beginning of the journey.

---

## 2025 Entry Model

The customer entered through a simplified WhatsApp flow.

The initial data collected was reduced to:

* name
* city of interest
* desired store

This model reduced friction and increased the probability of entry into the funnel.

---

## Strategic Interpretation

The 2025 model prioritized volume and speed over early qualification.

This decision created a trade-off:

* more leads entered the system
* more low-quality leads also entered the system

The strategic bet was that the increase in total volume and operational speed would compensate for the increase in ghost or low-quality leads.

The results suggest that this trade-off was favorable.

---

# 3. Operational Ownership Comparison

## 2024 Ownership Model

In 2024, the call center owned most of the customer journey before the appointment.

Responsibilities included:

* receiving the lead
* contacting the customer
* understanding the problem
* identifying the preferred store
* contacting the store
* asking for available dates
* returning to the customer
* aligning schedules
* confirming the appointment
* confirming with the store
* rescheduling when necessary

The store participated in the process but did not fully control the lead journey.

---

## 2025 Ownership Model

In 2025, ownership shifted to the store after the bot and CRM routing stage.

The CSO became responsible for:

* active contact with the lead
* understanding the hearing-related complaint
* checking the agenda
* scheduling the appointment
* confirming attendance
* rescheduling
* sales treatment
* post-sale follow-up

The call center became responsible mainly for exception handling.

---

## Strategic Interpretation

The 2025 model aligned ownership with the actual service delivery point.

This was important because the store had direct knowledge of:

* local agenda
* audiologist availability
* customer context
* store capacity
* service feasibility

This reduced the mismatch between centralized scheduling and local execution.

---

# 4. Technology Comparison

## 2024 Technology Stack

The 2024 model used:

* RD CRM
* Bot Conversas
* call center operations
* manual communication with stores

The system supported lead registration, but the operational flow still depended heavily on human intermediation.

---

## 2025 Technology Stack

The 2025 model used:

* RD Conversas
* RD CRM
* Google Sheets
* Pluga integrations
* Google Ads
* Meta Ads

The system was structured as an operational flow:

```text
RD Conversas
   ↓
RD CRM
   ↓
Google Sheets
   ↓
Pluga
   ↓
Email to Store
   ↓
CSO Action
```

---

## Strategic Interpretation

In 2024, technology supported the process.

In 2025, technology became part of the process architecture.

The CRM and automation layers no longer acted only as information storage or communication support.

They became mechanisms for moving the lead through the journey.

---

# 5. Funnel Performance Comparison

## Main Funnel Indicators

| Indicator              |  2024 |   2025 | Interpretation                        |
| ---------------------- | ----: | -----: | ------------------------------------- |
| Leads Generated        | 4,560 | 24,789 | Strong increase in entry volume       |
| Appointments Scheduled | 4,552 | 24,757 | Strong increase in scheduling volume  |
| Attendance             | 2,415 | 15,785 | Strong increase in attended check-ups |
| Sales                  |   104 |  1,288 | Strong increase in commercial output  |

---

# 6. Conversion Rate Comparison

| Conversion Metric        |   2024 |   2025 | Strategic Reading                          |
| ------------------------ | -----: | -----: | ------------------------------------------ |
| Lead → Appointment       | 99.82% | 99.87% | Stable and very high scheduling conversion |
| Appointment → Attendance | 53.05% | 63.76% | Improved attendance commitment             |
| Attendance → Sale        |  4.31% |  8.16% | Improved sales efficiency after attendance |
| Lead → Sale              |  2.28% |  5.20% | Improved full-funnel efficiency            |

---

# 7. Interpretation of Funnel Changes

## Lead Generation

The increase in leads suggests that reducing initial friction expanded the top of the funnel.

The shift from a form-heavy model to a WhatsApp-based entry helped more customers start the journey.

---

## Appointment Scheduling

The lead-to-appointment rate was already very high in 2024 and remained high in 2025.

The key difference was scale.

The new model processed a much larger number of leads without proportional expansion of the call center structure.

---

## Attendance

The appointment-to-attendance rate improved significantly.

This suggests that faster scheduling, direct store contact and clearer ownership may have increased customer commitment.

---

## Sales

The increase in attendance-to-sale conversion suggests that the redesigned model improved not only operational movement, but also the quality or timing of customer interaction at the store level.

This interpretation must be made carefully because sales may also have been affected by external factors such as campaign quality, media investment, pricing, promotions, training and store-level commercial performance.

---

# 8. Response Time Comparison

## 2024

Initial response occurred in approximately 20 minutes, from Monday to Friday, between 8h and 20h.

There was no weekend service.

---

## 2025

The bot provided immediate initial response.

Human store contact occurred during business hours after routing.

---

## Strategic Interpretation

The 2025 model reduced the silence between customer action and company response.

This is strategically relevant because the moment immediately after the click is a high-intent moment.

If the customer does not receive a quick response, the lead may cool down, abandon the journey or seek alternatives.

---

# 9. Scheduling Time Comparison

| Indicator             |      2024 |     2025 |
| --------------------- | --------: | -------: |
| Time Until Scheduling | Up to 48h | Up to 2h |

---

# 10. Interpretation of Scheduling Time Reduction

The reduction from up to 48 hours to up to 2 hours represents one of the strongest operational improvements in the case.

The improvement occurred because:

* the store became responsible for the agenda
* the call center stopped mediating every scheduling interaction
* automation accelerated lead distribution
* CSO teams could contact customers directly

This change reduced the distance between intent and confirmed action.

---

# 11. Cost Structure Comparison

## 2024 Cost Structure

The 2024 model included:

* 1 supervisor
* 6 operators
* variable compensation per appointment
* variable compensation per sale
* RD CRM
* Bot Conversas

This model had higher people dependency and incentive-based variable cost.

---

## 2025 Cost Structure

The 2025 model included:

* 3 operators
* RD CRM
* RD Conversas
* Pluga integrations

The structure reduced the number of operators and increased reliance on automation.

---

# 12. Estimated Operational Efficiency

| Metric                             |        2024 |       2025 | Interpretation                       |
| ---------------------------------- | ----------: | ---------: | ------------------------------------ |
| Estimated Monthly Operational Cost |   R$ 25,052 |  R$ 12,227 | Lower direct operational cost        |
| Estimated Annual Operational Cost  |  R$ 300,624 | R$ 146,724 | Lower annual structure cost          |
| Estimated Cost per Lead            |    R$ 65.93 |    R$ 5.92 | Higher operational efficiency        |
| Estimated Cost per Sale            | R$ 2,890.62 |  R$ 113.92 | Stronger output per operational cost |

---

# 13. Cost Interpretation Caution

The operational cost comparison does not represent full customer acquisition cost.

It does not include:

* media investment
* employee benefits
* taxes
* indirect overhead
* management cost
* store-level costs
* training costs
* creative production costs

Therefore, the cost comparison should be interpreted as operational efficiency of the call center, CRM and automation layer, not as complete CAC.

---

# 14. Customer Experience Comparison

## 2024 Customer Experience

Strengths:

* human contact from the beginning
* early problem understanding
* more personalized initial qualification
* better early filtering

Weaknesses:

* slower scheduling
* more intermediation
* possible distrust in call center
* repeated confirmations
* possible cancellations and rescheduling friction

---

## 2025 Customer Experience

Strengths:

* immediate initial response
* faster routing
* direct store contact
* faster scheduling
* clearer store ownership

Weaknesses:

* bot may reduce perception of human care
* use of two WhatsApp accounts may create confusion
* more low-quality leads enter the process
* some leads may not respond after store routing

---

# 15. Organizational Comparison

## 2024 Organization Logic

The organization worked through central control.

The call center concentrated the journey.

This increased control but created bottlenecks.

---

## 2025 Organization Logic

The organization worked through distributed ownership.

The store became responsible for the customer relationship after routing.

This increased speed but required stronger local execution discipline.

---

# 16. Risk Comparison

| Risk                       | 2024 Model  | 2025 Model |
| -------------------------- | ----------- | ---------- |
| Lead delay                 | High        | Lower      |
| Customer distrust          | Medium/High | Medium     |
| Lead quality loss          | Lower       | Higher     |
| Bot abandonment            | None        | Possible   |
| Store execution dependency | Lower       | Higher     |
| Call center overload       | High        | Lower      |
| Scheduling bottleneck      | High        | Lower      |
| Multi-channel confusion    | Lower       | Higher     |

---

# 17. Strategic Trade-Offs

The redesign did not eliminate all problems.

It changed the nature of the problems.

## 2024 Main Problem

Too much control concentrated in the call center.

## 2025 Main Problem

Higher scale requiring stronger store discipline and CRM governance.

---

# 18. Main Before-and-After Findings

## Finding 1

The 2025 model generated significantly more leads than the 2024 model.

## Finding 2

The 2025 model improved attendance rate, indicating better movement from scheduled appointment to actual store visit.

## Finding 3

The 2025 model improved sales conversion after attendance.

## Finding 4

The 2025 model reduced scheduling time substantially.

## Finding 5

The 2025 model reduced direct operational cost while increasing output.

## Finding 6

The 2025 model created a new challenge: managing higher lead volume and more ghost leads.

---

# 19. Managerial Implications

The Telex case suggests that customer journey optimization should not focus only on marketing acquisition.

Managerial attention should also be directed to:

* routing logic
* ownership clarity
* CRM integration
* response time
* local team execution
* automation governance
* lead status discipline

The main lesson is that acquisition only creates value when the organization can process demand efficiently.

---

# 20. Academic Implications

The case contributes to applied marketing research by connecting:

* customer journey theory
* CRM operationalization
* lead management
* AI-assisted customer interaction
* sales funnel efficiency
* service marketing

It demonstrates how process redesign can influence funnel performance in a service-based B2C organization.

---

# 21. Core Research Interpretation

The evidence suggests that reducing friction in the initial customer journey and transferring lead ownership to the point of service delivery improved funnel performance.

However, this should be treated as an evidence-supported interpretation, not as definitive causal proof.

The case is a strong before-and-after analysis, but it does not have a randomized control group.

---

# 22. Future Research Opportunities

Future analysis should investigate:

* store-level performance variation
* lead quality by source
* ghost lead rate
* response time by store
* conversion by CSO
* media investment by period
* customer satisfaction
* no-show reasons
* qualitative feedback from customers and teams
* statistical significance of funnel changes

---

# Final Summary

The before-and-after analysis shows that the 2025 redesign changed the Telex customer journey from a centralized, manual and call-center-dependent model into a faster, more scalable and store-owned operating system.

The transformation improved lead volume, attendance, sales and operational efficiency.

The main strategic insight is that the customer journey is not only a communication path.

It is an operating architecture that connects marketing, CRM, automation, sales and service delivery.

---

**End of Document**

