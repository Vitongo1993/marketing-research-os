# operational-flow.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Operational Flow
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document describes the operational flow of the Telex Soluções Auditivas customer journey before and after the 2025 redesign.

Its purpose is to document, in operational detail, how leads moved through the organization, which teams were responsible for each stage, where friction occurred and how the new model changed the relationship between marketing, call center, CRM, stores and customers.

This document complements:

* `case-study-overview.md`
* `kpi-analysis.md`
* `customer-journey-framework.md`
* `crm-framework.md`
* `lead-management-framework.md`

---

# Strategic Role of This Document

While `case-study-overview.md` explains the case at a strategic level and `kpi-analysis.md` analyzes the numbers, this document explains the real operational process.

It answers the following questions:

* How did the customer enter the journey?
* Who received the lead?
* Who was responsible for follow-up?
* Where did delays happen?
* Where were leads lost?
* How did the new process reduce friction?
* How did automation change the operating model?

---

# High-Level Operational Comparison

## 2024 Model

```text
Paid Ads
   ↓
Lead Form
   ↓
Call Center
   ↓
Customer Contact
   ↓
Store Contact
   ↓
Manual Schedule Alignment
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

## 2025 Model

```text
Paid Ads
   ↓
Click-to-WhatsApp
   ↓
Bot Interaction
   ↓
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
CSO Contact
   ↓
Appointment Scheduling
   ↓
Confirmation
   ↓
Hearing Check-Up
```

---

# 2024 Operational Flow

## Stage 1 — Lead Generation

The customer was impacted by digital campaigns and filled out a lead form.

The form collected multiple pieces of information, such as:

* name
* phone number
* city
* whether the customer had already taken a hearing test
* whether the customer had already been advised to use hearing aids

---

## Stage 2 — Call Center Reception

After the form submission, the lead was sent to the centralized call center.

The call center became the first human contact point in the journey.

---

## Stage 3 — Initial Human Contact

The call center contacted the customer and attempted to:

* understand the problem
* identify hearing-related complaints
* confirm interest
* ask which store the customer preferred
* verify whether the customer was willing to schedule a hearing check-up

---

## Stage 4 — Store Intermediation

After speaking with the customer, the call center contacted the desired store.

The goal was to verify:

* available appointment days
* audiologist availability
* possible times
* store schedule conditions

Because the call center did not have direct access to the store agenda, the process required manual intermediation.

---

## Stage 5 — Schedule Matching

The call center then returned to the customer with possible dates.

If the dates were not compatible, the call center had to return to the store and restart the alignment process.

This created a repetitive cycle:

```text
Customer availability
   ↓
Call center
   ↓
Store availability
   ↓
Call center
   ↓
Customer confirmation
```

---

## Stage 6 — Appointment Confirmation

Near the appointment date, the call center contacted:

* the customer, to confirm attendance
* the store, to confirm schedule
* the store again, when necessary, to confirm the audiologist would be available

This increased operational workload and created multiple points of failure.

---

## Stage 7 — Rescheduling

If the appointment could not happen, which occurred frequently, the call center had to restart the process.

The rescheduling flow required:

* contacting the customer
* contacting the store
* checking availability again
* proposing new dates
* confirming with both parties

---

# 2024 Operational Bottlenecks

## 1. Excessive Intermediation

The call center acted as an intermediary between the customer and the store.

This increased the number of touchpoints and slowed the scheduling process.

---

## 2. Lack of Agenda Visibility

The call center did not have real-time access to store schedules.

This made the scheduling process dependent on manual confirmation.

---

## 3. Lead Retention by Call Center

Because call center operators had financial incentives linked to appointments and sales, some leads could be retained for longer than ideal.

This created the risk of leads cooling down before reaching the store.

---

## 4. Customer Distrust

Some customers became suspicious because the first contact did not come directly from the store where the appointment would happen.

In a health-related service, this trust gap could negatively affect conversion.

---

## 5. Operational Overload

The call center concentrated too many responsibilities:

* first contact
* qualification
* scheduling
* confirmation
* rescheduling
* customer-store mediation

This created a central bottleneck in the journey.

---

# 2024 Operational Strengths

The previous model also had strengths that should be acknowledged.

## 1. Human Contact From the Beginning

Customers received human interaction early in the journey.

This allowed emotional support, clarification and trust building.

---

## 2. Early Problem Understanding

Operators could understand the customer's complaint before sending the lead forward.

---

## 3. Early Lead Filtering

The call center could separate:

* qualified leads
* low-quality leads
* uncertain leads
* leads with no real intent

This reduced the number of poor-quality leads sent to stores.

---

# 2025 Operational Flow

The 2025 model redesigned the process around three principles:

1. reduce initial friction
2. automate the entry layer
3. transfer lead ownership to the store

---

# 2025 Flow — Path 1: Direct Store Routing

## Stage 1 — Ad Impact

The customer sees a digital campaign on platforms such as:

* Google Ads
* Meta Ads

---

## Stage 2 — Click-to-WhatsApp

Instead of filling out a long form, the customer clicks the ad and starts a WhatsApp interaction.

---

## Stage 3 — Bot Interaction

The bot receives the lead immediately and asks for essential information:

* name
* city of interest
* desired store

The objective is to reduce friction and initiate the journey quickly.

---

## Stage 4 — CRM Registration

The lead data is sent to RD CRM.

The CRM becomes the central registration layer of the lead.

---

## Stage 5 — Store Spreadsheet

The lead information is sent to the corresponding store spreadsheet.

This creates visibility for the local unit.

---

## Stage 6 — Automated Email Notification

Through Pluga automation, an email is sent to the store with the customer information.

The email functions as an operational trigger for store action.

---

## Stage 7 — CSO Active Contact

The CSO of the selected or nearest store contacts the lead.

The CSO is responsible for:

* understanding the customer problem
* checking available times
* scheduling the hearing check-up
* confirming the appointment
* handling cancellations
* rescheduling if necessary

---

## Stage 8 — Hearing Check-Up

The customer attends the store and completes the hearing check-up.

---

## Stage 9 — Product Testing

If indicated, the customer tests the hearing aid.

---

## Stage 10 — Purchase or Non-Purchase

The customer may decide to purchase or not purchase.

If the customer purchases, the journey continues into post-sale follow-up.

---

## Stage 11 — Post-Sale Follow-Up

After purchase, the customer enters a follow-up period focused on:

* adaptation
* usage improvement
* support
* relationship continuity

---

# 2025 Flow — Path 2: Human Support After Bot Difficulty

Some customers do not complete the bot flow successfully.

This may happen when:

* the customer does not find the desired city
* the customer does not understand the bot
* the customer wants another subject
* the customer wants to make a complaint
* the customer needs human help

---

## Stage 1 — Bot Failure or Exception

The customer enters the WhatsApp flow but does not complete the routing process.

---

## Stage 2 — Call Center Human Support

The call center receives the exception case.

The role of the call center is now supportive, not central.

---

## Stage 3 — Location Mapping

The operator identifies:

* where the customer lives
* whether there is a nearby store
* whether displacement to another city or store is possible

---

## Stage 4 — Decision Point

If there is no feasible store option, the interaction may be closed.

If there is a feasible store option, the customer is routed to the store.

---

## Stage 5 — Store Ownership

Once routed, the store assumes responsibility for:

* contact
* scheduling
* confirmation
* hearing check-up process

---

# 2025 Technology Stack

The redesigned flow uses the following tools:

## Acquisition Platforms

* Google Ads
* Meta Ads

## Conversational Layer

* RD Conversas

## CRM Layer

* RD CRM

## Operational Distribution Layer

* Google Sheets

## Automation Layer

* Pluga

## Store Action Layer

* email notification
* CSO active contact

---

# 2025 Operational Logic

The new flow works through the following operational sequence:

```text
Customer enters WhatsApp
   ↓
Bot collects minimal data
   ↓
RD Conversas structures the interaction
   ↓
RD CRM stores the lead
   ↓
Lead is sent to store spreadsheet
   ↓
Pluga triggers email notification
   ↓
Store CSO contacts the customer
   ↓
Store schedules the appointment
```

---

# Role Redesign

## Call Center — 2024

Primary role:

* central lead receiver
* first contact
* scheduler
* intermediary
* confirmation agent
* rescheduling agent

---

## Call Center — 2025

Primary role:

* support for exception cases
* bot failure assistance
* complaint handling
* non-standard customer requests
* city/store mapping support

---

## CSO — 2024

Secondary or dependent role.

The store waited for the call center to intermediate the process.

---

## CSO — 2025

Primary owner of the lead after routing.

Responsibilities:

* active customer contact
* problem understanding
* scheduling
* confirmation
* sales treatment
* post-sale relationship
* cancellation and rescheduling

---

## Store Manager

The store manager remains responsible for:

* store performance
* process supervision
* team management
* results monitoring
* operational quality

---

## Marketing

Marketing is responsible for:

* paid media campaigns
* acquisition strategy
* lead generation
* campaign performance monitoring
* message and creative optimization

---

## Technology / Automation

The technology and automation layer is responsible for:

* CRM integrations
* WhatsApp automation
* data flow stability
* Pluga workflows
* data distribution to stores

---

# Before vs After — Role Comparison

| Function               | 2024 Model             | 2025 Model          |
| ---------------------- | ---------------------- | ------------------- |
| First response         | Call center            | Bot                 |
| Lead ownership         | Call center            | Store CSO           |
| Scheduling             | Call center-mediated   | Store-managed       |
| Store agenda access    | Indirect               | Direct by store     |
| Call center role       | Central operator       | Exception support   |
| CRM role               | Registration / support | Operational routing |
| Automation role        | Limited                | Core process layer  |
| Customer-store contact | Delayed                | Faster and direct   |

---

# Main Operational Improvements

## 1. Reduced Scheduling Time

The time until scheduling was reduced from up to 48 hours to up to 2 hours.

---

## 2. Reduced Intermediation

The customer no longer depends on the call center to access the store.

---

## 3. Clearer Ownership

The store becomes the owner of the lead after routing.

---

## 4. Faster Initial Response

The bot provides immediate entry response.

---

## 5. Greater Scalability

The process can handle more leads without requiring the same call center structure.

---

# New Operational Risks

## 1. Bot Rejection

Some customers may prefer human service and abandon the journey when they identify the bot.

---

## 2. Multi-WhatsApp Confusion

The customer may begin in one WhatsApp account and later receive contact from another store account.

This may create confusion or distrust.

---

## 3. Store Follow-Up Variability

The model depends on the quality and speed of each store's CSO team.

---

## 4. Increased Ghost Leads

Reducing form friction increases volume, but also increases low-quality or non-responsive leads.

---

# Operational Control Points

To maintain performance, the operation should monitor:

* time from lead entry to store contact
* time from store contact to scheduling
* number of contact attempts
* non-response rate
* ghost lead rate
* appointment cancellation rate
* no-show rate
* store-level conversion rate
* response time by CSO
* lead distribution by city and store

---

# Operational Decision Points

The following decisions are critical in the 2025 model:

## 1. When should a lead leave the bot and go to human support?

## 2. How many contact attempts should the store make?

## 3. When should a lead be considered cold?

## 4. When should a lead be considered lost?

## 5. How should urgent leads be prioritized?

## 6. How should high-age customers be treated?

## 7. How should leads outside store coverage areas be handled?

---

# Business Rules Embedded in the Flow

## Qualified Lead

A qualified lead is a person who:

* interacts with the company
* reports hearing difficulty
* already uses hearing aids
* indicates possible need for hearing aids
* shows willingness to schedule a check-up

---

## Cold Lead

A lead becomes cold when:

* there is no response
* the customer cancels
* the customer stops interacting
* the customer does not progress

---

## Lost Lead

A lead is considered lost when:

* there is no response for more than three months
* there is no viable store option
* the customer abandons the process
* the customer does not accept available scheduling possibilities

---

## Maximum Acceptable Response Time

The maximum acceptable response time is:

```text
30 minutes
```

---

## Priority Leads

Priority should be given to:

* customers over 90 years old
* urgent hearing aid cases
* customers with immediate need for hearing support

---

# Strategic Interpretation

The 2025 operational redesign did not simply add a chatbot.

It changed the operating architecture of the customer journey.

The main transformation was the shift from:

```text
Centralized intermediation
```

to:

```text
Automated entry + store-level ownership
```

This reduced friction, accelerated scheduling and aligned operational responsibility with the actual point of service delivery.

---

# Connection to MROS Frameworks

This operational flow applies three MROS frameworks:

## Customer Journey Framework

Used to identify friction and redesign the transition between intent and conversion.

## CRM Framework

Used to structure the movement of lead data and operational ownership.

## Lead Management Framework

Used to define capture, routing, qualification and lead progression.

---

# Final Summary

The redesigned operational flow created a more scalable, faster and more store-centered customer journey.

The new model improved the connection between digital acquisition and physical service delivery by:

* simplifying lead entry
* reducing manual intermediation
* automating data distribution
* assigning lead ownership to stores
* repositioning call center as support
* accelerating appointment scheduling

This operational redesign is one of the central pillars of the Telex case study within the Marketing Research OS.

---

**End of Document**

