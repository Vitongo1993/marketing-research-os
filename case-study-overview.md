# case-study-overview.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Case Study Overview
> Version: 2.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document presents the **Telex Soluções Auditivas Case Study**, the first real-world application of the **Marketing Research OS (MROS)**.

The case analyzes a customer journey, CRM and lead management redesign implemented in a live business environment, focusing on how the reduction of friction, decentralization of operational ownership and automation of the initial customer interaction impacted lead generation, appointment scheduling, attendance and sales performance.

This document is designed to support:

* MBA Final Project development
* Applied marketing research
* CRM and customer journey analysis
* AI-assisted process optimization
* Academic case study documentation

---

# Case Context

## Company

**Telex Soluções Auditivas**

Sector: Hearing care / audiology solutions
Business focus: Hearing check-ups, hearing aid testing, customer acquisition, relationship management and hearing aid sales.

---

## Business Context

Telex operates through a hybrid customer acquisition and service model involving:

* paid media campaigns
* WhatsApp-based inbound interactions
* centralized call center operations
* physical stores
* CSO teams at store level
* hearing check-up scheduling
* hearing aid testing
* post-sale adaptation and relationship follow-up

The business depends heavily on the successful transition between digital lead acquisition and physical store attendance.

Because hearing care is a service with emotional, functional and financial dimensions, the customer journey requires trust, speed, clarity and personalized support.

---

# Initial Problem Statement

The original customer acquisition and conversion process presented structural inefficiencies between lead generation and appointment scheduling.

The main issue was not only the volume of leads generated, but the operational friction that occurred after the lead entered the system.

The original process created unnecessary intermediations, delays and ownership ambiguity between marketing, call center and stores.

---

# Initial Operational Model — 2024

In the 2024 model, the customer journey followed a centralized structure.

```text
Paid Ads
   ↓
Lead Form
   ↓
Call Center
   ↓
Store Contact
   ↓
Scheduling Intermediation
   ↓
Customer Confirmation
   ↓
Store Confirmation
   ↓
Appointment
   ↓
Possible Rescheduling
```

---

# Main Problems Identified in 2024

## 1. Excessive Form Friction

The original lead capture process required multiple pieces of information before the customer could move forward.

The form included questions such as:

* name
* phone number
* city
* previous hearing test
* indication for hearing aid use

Although these questions could improve lead qualification, they also increased friction at the first point of contact.

In customer acquisition systems, excessive data collection can reduce conversion probability because it increases cognitive effort and delays the beginning of the conversation.

---

## 2. Centralized Call Center Bottleneck

The call center was responsible for:

* receiving the lead
* contacting the customer
* understanding the problem
* asking for preferred store
* contacting the store
* requesting available appointment dates
* returning to the customer
* checking agenda compatibility
* scheduling the appointment
* confirming with the customer
* confirming with the store
* checking whether the audiologist would be available
* rescheduling when necessary

This structure created a long operational chain between customer intention and actual appointment confirmation.

---

## 3. Lack of Real-Time Store Schedule Access

The call center did not have direct access to store schedules.

As a result, the scheduling process depended on manual back-and-forth communication between:

```text
Customer ↔ Call Center ↔ Store ↔ Call Center ↔ Customer
```

This structure increased the time required to schedule appointments and created multiple opportunities for abandonment.

---

## 4. Incentive Misalignment

The call center had financial incentives linked to appointments and sales.

In 2024, operators received variable compensation for:

* scheduled appointments
* sales generated from their appointments

This incentive structure created a behavioral distortion.

Instead of immediately forwarding uncertain or warm leads to the stores, operators could hold leads in the call center to preserve the possibility of future commission.

This created an operational conflict between short-term individual incentives and the broader organizational objective of reducing lead loss.

---

## 5. Customer Trust Friction

Some customers perceived the call center as a third-party or outsourced layer.

This generated distrust because the customer had not yet interacted directly with the store where the hearing check-up would take place.

For a service related to health, age, hearing difficulty and personal vulnerability, trust is a critical conversion factor.

---

# 2024 Operational Advantages

Although the original model created friction, it also had advantages.

## Strengths of the 2024 Model

* human interaction from the beginning
* initial understanding of the customer problem
* early filtering of qualified and unqualified leads
* ability to separate high-intent leads from low-quality leads
* more conversational qualification

These advantages are important because they explain why the previous model should not be interpreted only as inefficient.

It had strong qualitative components, but poor scalability and high operational dependency.

---

# 2025 Redesign Strategy

The redesign implemented in 2025 was based on a fundamental strategic decision:

> Remove unnecessary friction from the beginning of the journey and transfer scheduling ownership to the store responsible for the actual service.

The intervention was not only a technological change.

It involved:

* customer journey simplification
* CRM restructuring
* lead management redesign
* call center role redefinition
* store-level ownership
* automation through chatbot and integrations

---

# New Operational Model — 2025

```text
Paid Ads
   ↓
Click-to-WhatsApp
   ↓
Bot Interaction
   ↓
Name + City + Store Preference
   ↓
CRM Registration
   ↓
Store Spreadsheet
   ↓
Automated Email to Store
   ↓
CSO Active Contact
   ↓
Problem Understanding
   ↓
Appointment Scheduling
   ↓
Confirmation
   ↓
Hearing Check-Up
   ↓
Product Testing
   ↓
Sale or Non-Sale
   ↓
Post-Sale Follow-Up
```

---

# 2025 Process Flow

The 2025 journey has two main paths.

---

## Path 1 — Direct Store Routing

```text
Ad Campaign View
   ↓
Conversion Click
   ↓
WhatsApp Entry
   ↓
Bot Flow
   ↓
Store or City Selection
   ↓
Nearest / Desired Store Routing
   ↓
CSO Contact
   ↓
Customer Problem Understanding
   ↓
Hearing Check-Up Scheduling
   ↓
Check-Up Attendance
   ↓
Hearing Aid Testing
   ↓
Purchase or Non-Purchase
   ↓
Post-Purchase Follow-Up
```

---

## Path 2 — Human Support After Bot Difficulty

```text
Ad Campaign View
   ↓
Conversion Click
   ↓
WhatsApp Entry
   ↓
Bot Flow
   ↓
Customer Does Not Find Desired Store
   ↓
Human Call Center Support
   ↓
Location Mapping
   ↓
Feasibility of Customer Displacement
   ↓
If Not Feasible: End of Interaction
   ↓
If Feasible: Store Routing
   ↓
CSO Contact
   ↓
Appointment Scheduling
   ↓
Hearing Check-Up
   ↓
Product Testing
   ↓
Purchase or Non-Purchase
   ↓
Post-Purchase Follow-Up
```

---

# Key Intervention Components

## 1. Lead Capture Simplification

The original form was replaced by a simplified entry structure.

Required initial information:

* name
* city of interest
* desired store

This reduced the effort required from the customer and accelerated the beginning of the conversation.

---

## 2. Chatbot as Initial Interface

The chatbot became responsible for the first layer of interaction.

Its role was to:

* receive the lead immediately
* collect minimum required data
* identify desired city or store
* initiate routing
* reduce dependency on human availability

This allowed the business to provide immediate response even outside regular call center working hours.

---

## 3. CRM and Automation Integration

The redesigned process used an integrated stack involving:

* RD Conversas
* RD CRM
* Google Sheets
* Pluga integrations
* Google Ads
* Meta Ads

The operational flow can be summarized as:

```text
RD Conversas
   ↓
RD CRM
   ↓
Google Sheets
   ↓
Pluga Automation
   ↓
Email Notification to Store
   ↓
CSO Active Contact
```

---

## 4. Store-Level Ownership

The CSO at the store became responsible for:

* contacting the lead
* understanding the customer need
* checking the store agenda
* scheduling the appointment
* confirming attendance
* handling cancellations
* rescheduling when necessary
* supporting sales interactions
* conducting post-sale follow-up

This change improved ownership clarity and reduced operational ambiguity.

---

## 5. Call Center Reconfiguration

The call center was no longer the primary scheduling gatekeeper.

Its role changed to support specific situations, such as:

* customers unable to complete the bot flow
* customers who could not find their city
* customers requesting other subjects
* customers making complaints
* cases requiring human assistance

This repositioned the call center as a support layer rather than the central operating hub.

---

# Organizational Structure — Before and After

## 2024 — Call Center-Centered Model

### Call Center Responsibilities

* receive lead
* contact customer
* understand issue
* identify desired store
* contact store
* request available dates
* return to customer
* match availability
* schedule appointment
* confirm with store and customer
* manage rescheduling

### Operational Burden

* delayed scheduling
* operational bottleneck
* commission-driven lead retention
* customer distrust
* excessive intermediation

### Operational Advantage

* human contact from the beginning
* initial problem understanding
* early lead filtering
* separation between qualified and low-quality leads

---

## 2025 — Store-Centered Model

### Bot Responsibilities

* receive lead
* request name, city and desired store
* send lead to CRM
* initiate routing flow

### CRM and Automation Responsibilities

* register lead
* send data to store spreadsheet
* trigger email notification to store
* structure operational visibility

### Store CSO Responsibilities

* contact lead
* understand customer problem
* schedule appointment
* confirm attendance
* reschedule if needed
* handle sales interaction
* manage post-sale follow-up

### Call Center Responsibilities

* support bot failure cases
* assist customers who cannot find their city
* handle non-standard requests
* manage complaints
* provide human backup

---

# Business Rules

## Qualified Lead Definition

A lead is considered qualified when the person:

* interacts with the company
* reports or suggests a hearing-related problem
* already uses hearing aids
* indicates the need for hearing aids
* shows intent to schedule a hearing check-up

---

## Cold Lead Definition

A lead becomes cold when:

* the customer does not respond
* the customer cancels the appointment
* the customer stops interacting
* the customer does not progress through the journey

---

## Lost Lead Definition

A lead is considered lost when:

* the customer does not respond for more than three months
* the customer cannot attend any available store
* the customer abandons interaction after repeated attempts
* the customer shows no viable path to appointment

---

## Maximum Acceptable Response Time

The maximum acceptable response time is:

```text
30 minutes
```

This rule reflects the strategic importance of speed in lead conversion.

---

## Priority Leads

Priority should be given to:

* customers over 90 years old
* urgent hearing aid cases
* customers with explicit need for immediate hearing support

---

# Quantitative Results

## Funnel Comparison — 2024 vs 2025

| Indicator              |  2024 |   2025 | Absolute Change | Relative Change |
| ---------------------- | ----: | -----: | --------------: | --------------: |
| Leads Generated        | 4,560 | 24,789 |         +20,229 |         +443.6% |
| Appointments Scheduled | 4,552 | 24,757 |         +20,205 |         +443.9% |
| Attendance             | 2,415 | 15,785 |         +13,370 |         +553.6% |
| Sales                  |   104 |  1,288 |          +1,184 |       +1,138.5% |

---

# Conversion Rate Analysis

| Conversion Metric        |  2024 |  2025 |     Change |
| ------------------------ | ----: | ----: | ---------: |
| Lead → Appointment       | 99.8% | 99.9% |  +0.1 p.p. |
| Appointment → Attendance | 53.1% | 63.8% | +10.7 p.p. |
| Attendance → Sale        |  4.3% |  8.2% |  +3.9 p.p. |
| Lead → Sale              |  2.3% |  5.2% |  +2.9 p.p. |

---

# Strategic Interpretation of Results

The most relevant improvement did not occur only in lead volume.

The redesigned system improved downstream efficiency.

The strongest evidence is visible in three areas:

## 1. Attendance Rate Improvement

The appointment-to-attendance rate increased from approximately 53.1% to 63.8%.

This suggests that direct store ownership, faster scheduling and clearer communication may have improved customer commitment.

---

## 2. Sales Conversion Improvement

The attendance-to-sale rate increased from approximately 4.3% to 8.2%.

This indicates that the new model may have improved the quality of the interaction between customer and store, although this result should be interpreted with caution because other commercial factors may also have influenced sales.

---

## 3. Lead-to-Sale Efficiency

The lead-to-sale conversion rate increased from approximately 2.3% to 5.2%.

This indicates that the system became more efficient not only at generating volume, but at transforming demand into revenue outcomes.

---

# Response Time and Scheduling Time

## Response Time

| Indicator        | 2024                                           | 2025                                |
| ---------------- | ---------------------------------------------- | ----------------------------------- |
| Initial Response | Around 20 minutes, Monday to Friday, 8h to 20h | Immediate bot response              |
| Weekend Coverage | No weekend service                             | Bot available immediately           |
| Human Follow-Up  | Call center dependent                          | Store contact during business hours |

---

## Time to Appointment Scheduling

| Indicator                     |      2024 |     2025 |
| ----------------------------- | --------: | -------: |
| Average Time Until Scheduling | Up to 48h | Up to 2h |

The reduction from up to 48 hours to up to 2 hours represents a major operational improvement.

This change is strategically relevant because long scheduling delays may reduce purchase intent, increase uncertainty and increase the probability of lead abandonment.

---

# Operational Cost Analysis

## 2024 Cost Structure

### People

* 1 supervisor: R$ 7,000 fixed salary + benefits
* 6 operators: R$ 1,800 fixed salary + benefits
* bonus per appointment: R$ 10
* bonus per sale: R$ 70

### Systems

* RD CRM: R$ 1,900/month
* Bot Conversas: R$ 952/month

---

## 2025 Cost Structure

### People

* 3 operators: R$ 2,800 fixed salary + benefits

### Systems

* RD CRM: R$ 400/month
* RD Conversas: R$ 3,352/month
* Pluga Integrations: R$ 900/year

---

## Estimated Operational Cost Comparison

> Note: This estimate excludes benefits, media investment, management overhead and other indirect costs.

### 2024 Estimated Monthly Operational Cost

```text
Supervisor salary: R$ 7,000
Operators salary: 6 × R$ 1,800 = R$ 10,800
RD CRM: R$ 1,900
Bot Conversas: R$ 952
Estimated monthly fixed cost: R$ 20,652
```

Estimated variable compensation:

```text
Appointments: 4,552 × R$ 10 = R$ 45,520/year
Sales: 104 × R$ 70 = R$ 7,280/year
Total variable compensation: R$ 52,800/year
Estimated monthly variable compensation: R$ 4,400
```

Estimated total monthly cost:

```text
R$ 20,652 + R$ 4,400 = R$ 25,052/month
```

---

### 2025 Estimated Monthly Operational Cost

```text
Operators salary: 3 × R$ 2,800 = R$ 8,400
RD CRM: R$ 400
RD Conversas: R$ 3,352
Pluga: R$ 900/year = R$ 75/month
Estimated monthly cost: R$ 12,227/month
```

---

## Estimated Operational Efficiency

| Metric                         |        2024 |       2025 |
| ------------------------------ | ----------: | ---------: |
| Estimated Monthly Cost         |   R$ 25,052 |  R$ 12,227 |
| Estimated Annual Cost          |  R$ 300,624 | R$ 146,724 |
| Estimated Cost per Lead        |    R$ 65.93 |    R$ 5.92 |
| Estimated Cost per Appointment |    R$ 66.04 |    R$ 5.93 |
| Estimated Cost per Attendance  |   R$ 124.48 |    R$ 9.29 |
| Estimated Cost per Sale        | R$ 2,890.62 |  R$ 113.92 |

---

# Strategic Cost Interpretation

The redesign improved both scale and operational efficiency.

The model generated significantly more leads and sales while reducing the estimated direct operational cost of the call center/CRM/automation layer.

This does not represent the full CAC, because paid media investment and other acquisition costs are not included.

However, it strongly indicates that the operational layer became more efficient.

---

# Main Strategic Findings

## 1. Simpler Entry Increased Scale

Reducing the number of required fields lowered friction and increased lead entry volume.

The system accepted a higher number of low-quality leads, but the increased volume and improved operational flow compensated for this effect.

---

## 2. Faster Response Improved Journey Continuity

Immediate bot response reduced waiting time and helped preserve customer intent.

Even when human follow-up still depended on business hours, the customer no longer experienced silence after clicking the ad.

---

## 3. Store Ownership Improved Conversion Logic

By assigning responsibility directly to the store, the process became more aligned with real service availability.

The store controlled:

* agenda
* confirmation
* rescheduling
* customer relationship
* sales treatment

This reduced the inefficiency of centralized intermediation.

---

## 4. Call Center Repositioning Reduced Bottlenecks

The call center became a support layer instead of a mandatory conversion gate.

This reduced overload and allowed human service to focus on exceptions, complaints and bot failure cases.

---

## 5. CRM Became Operational, Not Merely Informational

The redesigned system used CRM and automation to trigger action.

Instead of only storing leads, the system connected data to operational movement:

```text
Lead Entry → CRM → Store Sheet → Email Alert → CSO Action
```

This is a key difference between a passive CRM and an operational CRM.

---

# New Model: Strengths and Weaknesses

## Strengths

* faster initial response
* higher lead volume
* lower form friction
* direct store ownership
* faster scheduling
* improved attendance volume
* improved sales volume
* reduced call center dependency
* lower estimated operational cost
* better scalability

---

## Weaknesses

* beginning of interaction is automated, not human
* some customers may abandon when they realize they are speaking to a bot
* interaction may occur across two WhatsApp accounts
* higher volume of low-quality leads
* more ghost leads
* some leads do not respond after being sent to stores
* store execution quality becomes more critical

---

# Critical Risks

## 1. Bot Abandonment Risk

Some customers may prefer human interaction and abandon the flow when the first contact is automated.

---

## 2. Multi-Channel Confusion Risk

If the customer starts in one WhatsApp account and later receives contact from a store account, confusion may occur.

This can affect trust and response probability.

---

## 3. Store Execution Risk

The redesigned system depends on the ability of stores to contact leads quickly and consistently.

If store-level follow-up is weak, the model may lose efficiency.

---

## 4. Lead Quality Risk

Reducing form friction increases volume but may reduce average lead quality.

This requires stronger lead classification and follow-up rules.

---

# Academic Relevance

This case is relevant for academic research because it connects multiple theoretical fields:

* customer journey optimization
* CRM restructuring
* lead management
* friction reduction
* AI-assisted service flows
* marketing automation
* sales funnel performance
* service marketing
* behavioral decision-making

The case demonstrates how changes in process design can affect marketing and sales outcomes.

---

# Possible Research Questions

## Main Research Question

How does reducing friction in the initial customer journey and decentralizing lead ownership affect lead conversion performance in a service-based B2C organization?

---

## Alternative Research Questions

1. How does chatbot-based initial service influence lead volume and appointment scheduling efficiency?

2. What is the impact of transferring lead ownership from a centralized call center to local stores?

3. How does CRM automation affect the relationship between marketing acquisition and sales conversion?

4. What are the trade-offs between lead volume and lead quality when lead capture friction is reduced?

---

# Possible Hypotheses

## H1

Reducing friction in the lead capture process increases lead generation volume.

---

## H2

Decentralizing lead ownership to store-level teams reduces scheduling time.

---

## H3

Faster response time increases appointment scheduling efficiency.

---

## H4

Store-level ownership improves attendance and sales conversion rates.

---

## H5

Reducing form complexity increases the volume of low-quality or ghost leads, but may still improve total conversion outcomes.

---

# Methodological Positioning

This case is best positioned as:

* applied research
* single case study
* mixed-methods approach
* documentary research
* before-and-after analysis

The case combines:

* quantitative indicators
* operational process analysis
* organizational role redesign
* CRM and automation documentation
* qualitative interpretation of operational effects

---

# Limitations

This case has limitations that must be explicitly acknowledged.

## 1. No Randomized Control Group

The intervention was not tested through a randomized experiment.

Therefore, causal claims must be made cautiously.

---

## 2. Possible External Influences

Sales growth may have been influenced by factors such as:

* media investment changes
* campaign quality
* seasonality
* store performance
* commercial training
* pricing or promotional conditions

---

## 3. Benefits Not Included in Cost Estimate

The operational cost comparison does not include employee benefits, taxes or indirect overhead.

---

## 4. CAC Not Fully Calculated

Paid media investment is not included.

Therefore, the cost analysis should not be interpreted as full CAC.

---

## 5. Lead Quality Trade-Off

The increase in lead volume came with an increase in low-quality and ghost leads.

This requires further analysis.

---

# Recommended Future Analyses

To strengthen the case academically, future documentation should include:

* monthly funnel data
* campaign investment by period
* media channel breakdown
* store-level conversion rates
* response time by store
* ghost lead rate
* lead quality classification
* sales by origin
* statistical significance testing
* qualitative interviews with CSO and call center team

---

# MROS Framework Integration

This case directly applies three MROS frameworks:

## Customer Journey Framework

Used to identify friction between intent and conversion.

## CRM Framework

Used to redesign ownership and operational flow.

## Lead Management Framework

Used to restructure capture, routing and qualification.

Together, these frameworks explain the strategic logic of the intervention.

---

# Case Summary

The Telex case demonstrates that customer journey redesign is not limited to communication or advertising.

It requires alignment between:

* marketing acquisition
* CRM architecture
* lead routing
* operational ownership
* sales execution
* post-sale relationship

The 2025 redesign improved speed, scale and operational efficiency by reducing unnecessary friction and transferring lead ownership to the store level.

The result was a more scalable, responsive and conversion-oriented customer journey.

---

**End of Document**

