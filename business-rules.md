# business-rules.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Business Rules
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document defines the operational business rules that govern the lead management, customer journey and CRM flow of the Telex Soluções Auditivas case study.

Its purpose is to make the process:

* auditable
* replicable
* measurable
* operationally clear
* academically analyzable
* scalable across stores

This document complements:

* `case-study-overview.md`
* `kpi-analysis.md`
* `operational-flow.md`
* `customer-journey-framework.md`
* `crm-framework.md`
* `lead-management-framework.md`

---

# Strategic Role of Business Rules

Business rules define how the organization makes operational decisions during the customer journey.

They answer questions such as:

* What is a qualified lead?
* When does a lead become cold?
* When should a lead be considered lost?
* Who owns each stage of the journey?
* When should the bot transfer the customer to human support?
* When should the store prioritize a lead?
* What response time is acceptable?
* What actions should be recorded in CRM?

Without explicit business rules, customer journey redesign becomes dependent on individual interpretation.

With clear business rules, the process becomes more consistent, measurable and scalable.

---

# Business Rule Architecture

The Telex business rules are organized into eight categories:

```text
1. Lead Classification Rules
2. Lead Qualification Rules
3. Routing Rules
4. Response Time Rules
5. Contact Attempt Rules
6. Priority Rules
7. Loss and Disqualification Rules
8. CRM Governance Rules
```

Each category defines operational criteria for decision-making.

---

# 1. Lead Classification Rules

Lead classification defines the status of each customer in the journey.

---

## 1.1 New Lead

A lead is classified as **New Lead** when the customer enters the journey through a digital acquisition channel and provides the minimum required data.

Minimum data:

* name
* city of interest
* desired store or nearest store indication

Typical source channels:

* Google Ads
* Meta Ads
* WhatsApp entry point
* campaign landing page
* referral

---

## 1.2 Qualified Lead

A lead is considered **Qualified** when the customer demonstrates at least one of the following characteristics:

* interacts with the company
* reports hearing difficulty
* complains about ear or hearing-related problems
* already uses hearing aids
* indicates possible need for hearing aids
* shows interest in scheduling a hearing check-up
* asks about hearing aid testing
* agrees to continue the conversation with the store

---

## 1.3 Warm Lead

A lead is classified as **Warm** when there is evidence of interest, but the customer has not yet committed to scheduling.

Examples:

* asks questions about the process
* asks about store location
* asks about availability
* responds to the first contact
* shows hesitation but remains engaged

---

## 1.4 Hot Lead

A lead is classified as **Hot** when the customer shows explicit intent to schedule or purchase.

Examples:

* asks for appointment availability
* confirms interest in hearing check-up
* already has an indication for hearing aid use
* urgently needs hearing aid support
* wants to test a hearing aid
* requests fast scheduling

---

## 1.5 Cold Lead

A lead becomes **Cold** when the customer no longer progresses through the journey.

A lead may be considered cold when:

* the customer stops responding
* the customer cancels the appointment
* the customer delays scheduling
* the customer responds inconsistently
* the customer does not confirm availability
* the customer shows interest but does not commit

---

## 1.6 Ghost Lead

A lead is classified as **Ghost Lead** when the customer enters the system but does not respond to any meaningful follow-up interaction.

Typical characteristics:

* provided initial information
* entered through WhatsApp or campaign flow
* was routed to store
* did not answer store contact
* did not confirm interest
* did not progress beyond initial entry

Ghost leads are expected to increase when form friction is reduced.

This is an important trade-off in the 2025 model.

---

## 1.7 Lost Lead

A lead is classified as **Lost** when the customer cannot be reactivated or no longer represents a viable conversion opportunity.

Loss criteria include:

* no response for more than three months
* repeated lack of response
* no feasible store option
* customer refuses displacement to available store
* customer explicitly declines service
* customer cancels and does not reschedule
* customer abandons the process after multiple attempts

---

# 2. Lead Qualification Rules

Lead qualification defines whether a lead should continue in the commercial journey.

---

## 2.1 Minimum Qualification Criteria

A lead should continue in the journey if there is evidence of:

* hearing-related need
* interest in check-up
* geographic feasibility
* willingness to interact
* possible fit with Telex services

---

## 2.2 Hearing Need Indicators

The following signals indicate potential hearing-related need:

* difficulty hearing conversations
* complaint about hearing loss
* previous hearing test
* previous indication for hearing aid use
* current use of hearing aids
* family concern about hearing ability
* request for evaluation
* request for product testing

---

## 2.3 Geographic Feasibility

A lead is geographically feasible when:

* the customer lives near a Telex store
* the customer selects a desired store
* the customer accepts traveling to a nearby store
* the store has capacity to serve the customer

If the customer does not find their city or store, the case should be routed to human support.

---

## 2.4 Qualification Trade-Off

The 2025 model intentionally reduces initial qualification friction.

This means that not all qualification happens before routing.

Instead, qualification is distributed across:

```text
Bot Entry
   ↓
CRM Registration
   ↓
Store Contact
   ↓
CSO Qualification
   ↓
Scheduling Decision
```

This improves lead volume but increases the need for store-level filtering.

---

# 3. Routing Rules

Routing defines where the lead goes after entering the system.

---

## 3.1 Direct Store Routing

A lead should be routed directly to the selected or nearest store when:

* the customer selects a store
* the city is available in the bot flow
* the customer provides sufficient information
* there is no need for exception handling

---

## 3.2 Human Support Routing

A lead should be routed to human support when:

* the customer cannot find the desired city
* the customer cannot find the desired store
* the customer does not understand the bot
* the customer wants to discuss another subject
* the customer wants to make a complaint
* the bot cannot complete the routing
* the customer explicitly asks for human assistance

---

## 3.3 Store Ownership Rule

Once a lead is routed to a store, the store becomes responsible for the next stages of the journey.

Store responsibilities include:

* active contact
* customer problem understanding
* scheduling
* confirmation
* cancellation handling
* rescheduling
* sales treatment
* post-sale follow-up

---

## 3.4 Call Center Role Rule

The call center should not act as the default owner of every lead.

In the redesigned model, the call center acts as a support layer for exceptions, not as the primary scheduling gatekeeper.

The call center should support:

* bot failure cases
* complaints
* customers outside standard routing
* customers who cannot identify a store
* customers requiring additional orientation

---

# 4. Response Time Rules

Speed is a critical variable in the redesigned customer journey.

---

## 4.1 Maximum Acceptable Response Time

The maximum acceptable response time for store-level contact is:

```text
30 minutes
```

This means that after the lead reaches the store, the CSO should attempt contact as quickly as possible and preferably within this time window.

---

## 4.2 Immediate Bot Response

The bot should provide immediate initial response after the customer enters WhatsApp.

This prevents the customer from experiencing silence after clicking an ad.

---

## 4.3 Business Hours Rule

Although the bot can receive leads immediately, active store contact may depend on store business hours.

Therefore, CRM records should distinguish:

* lead entry time
* bot interaction time
* store notification time
* first human contact time
* appointment scheduling time

---

## 4.4 Delay Risk Rule

The longer the time between customer intent and store contact, the higher the probability of:

* lead cooling
* non-response
* distrust
* abandonment
* scheduling loss

Delays must be treated as operational risk.

---

# 5. Contact Attempt Rules

Contact attempt rules define how the store should manage follow-up.

---

## 5.1 First Contact Attempt

The first contact attempt should occur as soon as possible after the lead is routed to the store.

Preferred channel:

* WhatsApp

Alternative channels:

* phone call
* SMS
* email, when available

---

## 5.2 Contact Attempt Logging

Every contact attempt should be recorded in CRM or the operational tracking system.

Minimum record:

* date
* time
* channel
* responsible person
* result of attempt
* next action

---

## 5.3 Suggested Contact Attempt Sequence

A recommended sequence may include:

```text
Attempt 1 — Immediate WhatsApp message
Attempt 2 — Phone call
Attempt 3 — Follow-up WhatsApp message
Attempt 4 — New attempt on the next business day
Attempt 5 — Reclassification as cold lead if no response
```

This sequence may be adjusted according to store capacity and customer profile.

---

## 5.4 Non-Response Rule

If the lead does not respond after repeated attempts, the lead should be classified as cold or ghost depending on the level of prior interaction.

---

# 6. Priority Rules

Priority rules define which leads should receive faster or more careful handling.

---

## 6.1 Age Priority

Customers over 90 years old should receive priority attention.

Rationale:

* potential urgency
* possible vulnerability
* greater need for assisted communication
* higher risk of abandonment if the process is confusing

---

## 6.2 Urgency Priority

Leads should be prioritized when there is urgent need for hearing aid support.

Urgency signals include:

* immediate need for device placement
* replacement of current hearing aid
* strong hearing difficulty
* family concern
* upcoming medical or personal need

---

## 6.3 High-Intent Priority

Hot leads should be prioritized because they are closer to conversion.

High-intent signals include:

* asking for appointment dates
* asking for hearing aid testing
* asking about prices
* confirming availability
* requesting fast service

---

## 6.4 Vulnerability Priority

Priority may also be given to customers who demonstrate:

* difficulty understanding digital channels
* dependence on family support
* communication barriers
* emotional distress related to hearing loss

---

# 7. Loss and Disqualification Rules

Loss and disqualification rules define when the journey should be paused, closed or reclassified.

---

## 7.1 Disqualification Criteria

A lead may be disqualified when:

* there is no hearing-related need
* there is no geographic feasibility
* the customer refuses available store options
* the customer does not want to continue
* the customer entered by mistake
* the customer has an unrelated request

---

## 7.2 Lost Lead Criteria

A lead should be considered lost when:

* the customer does not respond for more than three months
* all reasonable contact attempts have failed
* there is no viable appointment path
* the customer explicitly declines
* the customer cancels and does not reschedule
* the customer remains inactive after reactivation attempts

---

## 7.3 Reactivation Rule

Cold leads may be reactivated through:

* follow-up campaigns
* WhatsApp reminders
* seasonal health campaigns
* hearing check-up invitations
* local store contact

Lost leads should only be reactivated if there is a clear strategic reason and operational capacity.

---

## 7.4 Cancellation Rule

When a customer cancels an appointment, the store should attempt to reschedule before closing the lead.

The cancellation should be recorded with a reason whenever possible.

Possible cancellation reasons:

* schedule conflict
* health issue
* transportation difficulty
* lack of interest
* family decision
* price concern
* lack of trust
* no explanation

---

# 8. CRM Governance Rules

CRM governance ensures that information is recorded consistently.

---

## 8.1 Mandatory CRM Fields

Each lead record should include:

* customer name
* contact information
* city
* selected or assigned store
* source channel
* lead status
* responsible owner
* interaction history
* scheduling status
* final outcome

---

## 8.2 Lead Status Standardization

Recommended status categories:

```text
New
Qualified
Warm
Hot
Scheduled
Confirmed
Attended
Sold
Not Sold
Cold
Ghost
Lost
Disqualified
```

---

## 8.3 Ownership Field

Every lead must have an assigned owner.

Possible owners:

* bot
* call center
* store CSO
* store manager
* marketing team
* support team

No lead should remain without ownership.

---

## 8.4 Timestamp Rule

The system should record key timestamps:

* lead entry time
* bot response time
* CRM registration time
* store notification time
* first contact attempt
* first successful contact
* appointment scheduled time
* appointment date
* sale date, when applicable

These timestamps are essential for measuring operational efficiency.

---

## 8.5 Data Quality Rule

CRM records should be periodically reviewed for:

* duplicate leads
* incomplete records
* outdated statuses
* leads without owner
* leads without outcome
* inconsistent store assignment

---

# 9. Exception Handling Rules

Exception handling defines what happens when the standard flow does not work.

---

## 9.1 Bot Failure

If the customer cannot complete the bot flow, the case should be sent to human support.

---

## 9.2 City Not Found

If the customer cannot find their city, human support should verify:

* nearest Telex store
* possible displacement
* alternative service options
* customer willingness to travel

---

## 9.3 Complaint

Complaints should not follow the standard lead flow.

They should be directed to the appropriate support or customer service channel.

---

## 9.4 Non-Commercial Requests

Customers contacting Telex for non-commercial reasons should be routed outside the sales flow.

Examples:

* support request
* product issue
* administrative request
* complaint
* follow-up on existing service

---

# 10. Operational Monitoring Rules

The business rules must be monitored through KPIs.

Recommended indicators:

* time to first store contact
* time to appointment scheduling
* response rate
* ghost lead rate
* cold lead rate
* lost lead rate
* appointment rate
* attendance rate
* sales conversion rate
* no-show rate
* cancellation rate
* store-level conversion rate

---

# 11. Strategic Interpretation

The redesigned Telex model depends on rule clarity.

The 2025 model increased scale by reducing entry friction and automating initial interaction.

However, reduced friction creates new operational challenges:

* more low-quality leads
* more ghost leads
* greater dependence on store execution
* greater need for CRM discipline

Therefore, business rules become critical to preserve efficiency.

---

# 12. Connection to MROS Frameworks

This document supports the following MROS frameworks:

## Customer Journey Framework

Defines decision rules across the customer journey.

## CRM Framework

Defines how lead records, ownership and status progression should be managed.

## Lead Management Framework

Defines qualification, routing, prioritization and loss criteria.

## Operational Flow

Defines how the rules are executed in practice.

---

# Final Summary

Business rules transform the Telex customer journey from an informal operational process into a structured, measurable and scalable system.

They ensure that each lead has:

* a status
* an owner
* a next action
* a measurable outcome

This makes the case stronger academically and more useful managerially.

---

**End of Document**

