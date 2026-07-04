# data-dictionary.md

> **Marketing Research OS (MROS)**
> Telex Soluções Auditivas — Data Dictionary
> Version: 1.0
> Status: Active
> Last Updated: July 2026

---

# Purpose

This document defines the main metrics, variables, statuses and operational fields used in the Telex Soluções Auditivas case study.

Its purpose is to standardize terminology across the research and ensure that all indicators used in the TCC are clear, consistent and auditable.

This document supports:

* `case-study-overview.md`
* `kpi-analysis.md`
* `operational-flow.md`
* `business-rules.md`
* `before-after-analysis.md`
* `research-questions-and-hypotheses.md`
* `methodological-positioning.md`

---

# Why a Data Dictionary Is Necessary

A data dictionary is necessary because the same term may have different meanings across marketing, sales, CRM, call center and store operations.

For example, the term "lead" may refer to:

* a person who clicked an ad
* a person who entered WhatsApp
* a person registered in CRM
* a person routed to a store
* a person who responded to the CSO
* a person who scheduled a hearing check-up

Without clear definitions, funnel analysis may become inconsistent.

This document defines how each term should be understood within the Telex case.

---

# Core Funnel Metrics

## 1. Lead Generated

## Definition

A **Lead Generated** is a customer or potential customer who entered the Telex commercial journey through a digital acquisition channel and provided enough information to be registered or routed in the system.

## Operational Criteria

A lead is counted when at least one of the following occurs:

* the customer completes the lead entry form
* the customer starts the WhatsApp flow
* the customer provides minimum identification data
* the customer is registered in CRM
* the customer is routed to a store or support flow

## Minimum Expected Data

* name
* contact information
* city
* desired store or location indication

## Notes

In the 2025 model, lead generation may include more low-quality or ghost leads because entry friction was reduced.

---

## 2. Appointment Scheduled

## Definition

An **Appointment Scheduled** is a lead for whom a hearing check-up, consultation or store visit has been scheduled.

## Operational Criteria

A lead is counted as scheduled when:

* a date and time are defined
* the customer agrees to attend
* the store or CSO registers the appointment
* the appointment is associated with a store

## Required Fields

* customer name
* store
* appointment date
* appointment time
* responsible CSO
* scheduling status

## Notes

Appointment scheduled does not mean the customer attended.

---

## 3. Attendance

## Definition

**Attendance** refers to the customer actually appearing at the scheduled appointment.

## Operational Criteria

A lead is counted as attendance when:

* the customer arrives at the store
* the customer completes or initiates the hearing check-up process
* the store confirms presence

## Required Fields

* appointment date
* attendance status
* store
* responsible CSO or professional
* outcome of the visit

## Notes

Attendance is different from appointment confirmation.

A customer may confirm an appointment and still not attend.

---

## 4. Sale

## Definition

A **Sale** occurs when the customer purchases a hearing aid, product, service or related solution after progressing through the commercial journey.

## Operational Criteria

A sale is counted when:

* the purchase is confirmed
* the transaction is registered
* the sale is attributed to the lead or appointment
* the store records the commercial outcome

## Required Fields

* customer name or ID
* sale date
* store
* product or service sold
* transaction value, when available
* responsible seller or CSO
* lead source, when available

## Notes

For full commercial analysis, sales should ideally be linked to the original lead source.

---

# Funnel Conversion Metrics

## 5. Lead-to-Appointment Rate

## Definition

The percentage of generated leads that became scheduled appointments.

## Formula

```text id="t5ignh"
Lead-to-Appointment Rate = Appointments Scheduled / Leads Generated
```

## Interpretation

This metric indicates how efficiently the operation transforms initial interest into scheduled store visits.

## Caution

A very high lead-to-appointment rate should be checked for data consistency, because it may indicate that the definition of "lead generated" is close to the definition of "appointment opportunity" in the operational database.

---

## 6. Appointment-to-Attendance Rate

## Definition

The percentage of scheduled appointments that resulted in actual attendance.

## Formula

```text id="qwr5sp"
Appointment-to-Attendance Rate = Attendance / Appointments Scheduled
```

## Interpretation

This metric indicates how effectively the operation converts scheduled appointments into real store visits.

## Caution

This metric may be affected by:

* confirmation quality
* reminder process
* customer trust
* weather
* transportation
* store location
* appointment availability
* customer health condition

---

## 7. Attendance-to-Sale Rate

## Definition

The percentage of customers who attended an appointment and made a purchase.

## Formula

```text id="jc3ttw"
Attendance-to-Sale Rate = Sales / Attendance
```

## Interpretation

This metric evaluates commercial efficiency after the customer reaches the store.

## Caution

This metric may be influenced by:

* sales training
* price
* product availability
* customer profile
* promotion
* payment conditions
* audiologist recommendation
* perceived value

---

## 8. Lead-to-Sale Rate

## Definition

The percentage of generated leads that became sales.

## Formula

```text id="5hj6fc"
Lead-to-Sale Rate = Sales / Leads Generated
```

## Interpretation

This is a full-funnel efficiency indicator.

It shows how many initial leads became final sales.

## Caution

This metric should not be interpreted alone.

It should be analyzed together with lead quality, media investment, store performance and operational cost.

---

# Time Metrics

## 9. Response Time

## Definition

**Response Time** is the time between lead entry and the first company response.

## In 2024

Response time refers mainly to the first human contact attempt made by the call center.

## In 2025

Response time must be separated into two categories:

```text id="uet4md"
Automated Response Time
Human Response Time
```

---

## 10. Automated Response Time

## Definition

The time between customer entry into WhatsApp and the first bot response.

## Interpretation

This metric measures the speed of automated reception.

## Notes

Automated response does not mean the customer received human service.

---

## 11. Human Response Time

## Definition

The time between lead routing and the first human contact attempt by the store, CSO or call center.

## Interpretation

This metric measures the speed of actual human follow-up.

## Recommended Formula

```text id="slcmxm"
Human Response Time = First Human Contact Attempt Time - Store Notification Time
```

---

## 12. Time Until Scheduling

## Definition

The time between lead entry and confirmed appointment scheduling.

## Formula

```text id="x0w9lc"
Time Until Scheduling = Appointment Scheduled Time - Lead Entry Time
```

## Interpretation

This metric measures how quickly the organization transforms interest into a concrete appointment.

## Caution

This metric should distinguish between:

* time until first contact
* time until customer response
* time until appointment agreement
* time until CRM scheduling record

---

# Lead Status Definitions

## 13. New Lead

## Definition

A customer who has entered the commercial journey but has not yet been qualified, contacted or scheduled.

## Typical Status

```text id="xvrvm4"
New
```

---

## 14. Qualified Lead

## Definition

A lead that demonstrates hearing-related need, interest or fit with Telex services.

## Qualification Signals

* reports hearing difficulty
* already uses hearing aids
* has previous indication for hearing aids
* wants a hearing check-up
* asks about hearing aid testing
* responds to contact
* agrees to continue the journey

---

## 15. Warm Lead

## Definition

A lead with interest but without immediate scheduling commitment.

## Examples

* asks questions
* responds but does not confirm
* wants more information
* shows hesitation
* needs family input

---

## 16. Hot Lead

## Definition

A lead with high purchase or scheduling intent.

## Examples

* asks for appointment availability
* wants urgent hearing aid support
* requests fast service
* asks about product testing
* confirms interest in visiting the store

---

## 17. Cold Lead

## Definition

A lead that showed some interest but stopped progressing.

## Criteria

* stopped responding
* postponed scheduling
* cancelled appointment
* did not confirm availability
* delayed decision
* showed weak engagement

---

## 18. Ghost Lead

## Definition

A lead that entered the system but did not respond to meaningful follow-up attempts.

## Criteria

* entered through WhatsApp or form
* provided minimal data
* was routed or registered
* did not respond to store contact
* did not confirm need or interest

## Notes

Ghost leads are expected to increase when the entry process becomes easier.

---

## 19. Lost Lead

## Definition

A lead that no longer represents a viable conversion opportunity.

## Criteria

* no response for more than three months
* no viable store option
* explicit refusal
* repeated failed contact attempts
* cancellation without rescheduling
* abandonment of process

---

## 20. Disqualified Lead

## Definition

A lead that should not continue in the commercial journey due to lack of fit.

## Disqualification Reasons

* no hearing-related need
* wrong contact
* duplicate entry
* outside service area
* unrelated request
* no interest
* no geographic feasibility

---

# Appointment Status Definitions

## 21. Scheduled

## Definition

The appointment has been booked with a defined date, time and store.

---

## 22. Confirmed

## Definition

The customer confirmed that they intend to attend the appointment.

## Notes

Confirmed does not mean attended.

---

## 23. Attended

## Definition

The customer appeared at the store for the appointment.

---

## 24. No-Show

## Definition

The customer scheduled an appointment but did not attend.

## Recommended Tracking

No-show should be tracked separately from cancellation.

---

## 25. Cancelled

## Definition

The appointment was cancelled before the scheduled time.

## Recommended Cancellation Reasons

* schedule conflict
* transportation difficulty
* health issue
* family decision
* price concern
* lack of interest
* no explanation
* store rescheduling need

---

## 26. Rescheduled

## Definition

The original appointment was cancelled or changed and a new date/time was defined.

---

# Ownership Fields

## 27. Lead Owner

## Definition

The person, team or system responsible for the next action with the lead.

## Possible Owners

* bot
* call center
* store CSO
* store manager
* marketing team
* customer support
* automation workflow

## Rule

No lead should remain without an owner.

---

## 28. Store Assigned

## Definition

The store responsible for handling the lead.

## Criteria

The store may be assigned based on:

* customer selection
* city
* geographic proximity
* availability
* routing logic
* manual adjustment by support team

---

## 29. Responsible CSO

## Definition

The store-level professional responsible for contacting, scheduling and following up with the customer.

---

# Source and Channel Fields

## 30. Lead Source

## Definition

The channel or platform from which the lead originated.

## Possible Values

```text id="4yhsp6"
Google Ads
Meta Ads
WhatsApp
Landing Page
Organic
Referral
Direct Contact
Other
```

---

## 31. Campaign

## Definition

The marketing campaign associated with the lead.

## Examples

* hearing check-up campaign
* promotional campaign
* local store campaign
* seasonal campaign
* awareness campaign

---

## 32. Medium

## Definition

The marketing medium used to generate the lead.

## Possible Values

```text id="24eolv"
Paid Search
Paid Social
Organic Social
WhatsApp
Referral
Direct
Email
Other
```

---

# Operational Cost Metrics

## 33. Estimated Operational Cost

## Definition

The estimated cost of the operational layer responsible for handling leads.

## Included Costs

May include:

* call center salaries
* supervisor salary
* CRM tools
* chatbot tools
* automation tools
* variable compensation linked to appointments or sales

## Excluded Costs

Should exclude, unless explicitly available:

* paid media investment
* taxes
* benefits
* store costs
* management overhead
* creative production
* indirect company costs

---

## 34. Cost per Lead

## Formula

```text id="j8x9qu"
Cost per Lead = Estimated Operational Cost / Leads Generated
```

## Notes

This should be called operational cost per lead, not CAC.

---

## 35. Cost per Appointment

## Formula

```text id="m151ra"
Cost per Appointment = Estimated Operational Cost / Appointments Scheduled
```

---

## 36. Cost per Attendance

## Formula

```text id="mu2ac3"
Cost per Attendance = Estimated Operational Cost / Attendance
```

---

## 37. Cost per Sale

## Formula

```text id="u8y3dl"
Cost per Sale = Estimated Operational Cost / Sales
```

## Caution

This is not full customer acquisition cost.

It only represents the estimated operational cost per sale.

---

# Customer Journey Variables

## 38. Entry Friction

## Definition

The amount of effort required from the customer to start the journey.

## Examples of Friction

* many form fields
* delayed response
* unclear next step
* multiple contacts
* repeated information requests
* need to wait for call center
* lack of store availability information

---

## 39. Customer Effort

## Definition

The level of effort required from the customer to progress from interest to appointment.

## Possible Indicators

* number of interactions
* number of repeated contacts
* time waiting
* number of handoffs
* need to repeat information
* difficulty scheduling

---

## 40. Touchpoint

## Definition

Any interaction between the customer and Telex.

## Examples

* ad impression
* ad click
* WhatsApp message
* bot response
* call center contact
* store contact
* appointment confirmation
* hearing check-up
* post-sale follow-up

---

## 41. Handoff

## Definition

A transfer of responsibility from one actor or system to another.

## Examples

* bot to CRM
* CRM to store
* call center to store
* store to audiologist
* CSO to post-sale support

## Notes

Handoffs are important because they often create friction or loss risk.

---

# Technology Fields

## 42. RD Conversas

## Definition

The conversational platform used to manage the WhatsApp bot and initial interaction flow.

---

## 43. RD CRM

## Definition

The CRM platform used to register and manage lead information.

---

## 44. Google Sheets

## Definition

The operational spreadsheet layer used to distribute or organize store-level lead information.

---

## 45. Pluga

## Definition

The automation tool used to connect systems and trigger operational workflows, such as sending lead information to stores.

---

## 46. Email Notification

## Definition

The automated message sent to a store to notify the team about a new lead.

---

# Recommended CRM Fields

The CRM or operational database should ideally include the following fields.

---

## Identification Fields

```text id="y079bi"
lead_id
customer_name
phone_number
email
city
state
selected_store
assigned_store
```

---

## Source Fields

```text id="2b8dor"
lead_source
campaign_name
medium
platform
ad_id
creative_id
```

---

## Status Fields

```text id="cga443"
lead_status
appointment_status
sales_status
qualification_status
loss_reason
disqualification_reason
```

---

## Ownership Fields

```text id="6sf3b5"
lead_owner
responsible_cso
store_manager
last_updated_by
```

---

## Time Fields

```text id="hry5yd"
lead_entry_time
bot_response_time
crm_registration_time
store_notification_time
first_contact_attempt_time
first_successful_contact_time
appointment_scheduled_time
appointment_date
attendance_time
sale_date
```

---

## Interaction Fields

```text id="dg3j99"
number_of_contact_attempts
last_contact_channel
last_contact_result
customer_response_status
next_action
next_action_date
```

---

## Commercial Fields

```text id="pdu175"
sale_value
product_sold
payment_method
discount_applied
salesperson
```

---

# Recommended Standard Status List

For consistency, the following status list is recommended:

```text id="zombzj"
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
Cancelled
Rescheduled
No-Show
```

---

# Metrics Available in the Current Case

The current Telex case includes the following available metrics:

```text id="fp91gb"
Leads Generated
Appointments Scheduled
Attendance
Sales
Initial Response Time
Time Until Scheduling
Estimated Operational Cost
Call Center Structure
CRM and Automation Stack
```

---

# Metrics That Should Be Added in Future Versions

To strengthen future analysis, the following metrics should be collected:

```text id="q4bngv"
Media Investment
Cost per Lead by Channel
Lead Source Breakdown
Ghost Lead Rate
Cold Lead Rate
Lost Lead Rate
No-Show Rate
Cancellation Rate
Store-Level Conversion
CSO-Level Conversion
Response Time by Store
Contact Attempts per Lead
Revenue per Lead
Average Ticket
Customer Satisfaction
NPS
Complaint Rate
Reason for Non-Purchase
```

---

# Data Quality Rules

## 1. Every Lead Must Have a Status

No lead should remain without classification.

---

## 2. Every Lead Must Have an Owner

Every lead must be assigned to a system, person or team responsible for the next action.

---

## 3. Every Appointment Must Have an Outcome

Possible outcomes:

* attended
* no-show
* cancelled
* rescheduled

---

## 4. Every Lost Lead Should Have a Reason

Possible reasons:

* no response
* no store availability
* customer refused
* customer cancelled
* invalid contact
* no geographic feasibility
* unrelated request

---

## 5. Timestamps Must Be Recorded

Without timestamps, it is not possible to measure speed, delay or operational friction.

---

# Data Interpretation Rules

## Rule 1 — Do Not Treat Operational Cost as CAC

Operational cost per lead or sale should not be presented as full CAC unless paid media and all related costs are included.

---

## Rule 2 — Separate Bot Response from Human Response

Immediate bot response should not be confused with human service.

Both should be measured separately.

---

## Rule 3 — Separate Scheduled from Attended

An appointment only becomes attendance when the customer appears at the store.

---

## Rule 4 — Separate Cancellation from No-Show

A cancellation occurs before the appointment.

A no-show occurs when the customer does not attend without completing the appointment.

---

## Rule 5 — Avoid Causal Overstatement

Before-and-after data suggests association, not definitive causality.

---

# Final Summary

This data dictionary standardizes the main metrics, statuses and variables used in the Telex Soluções Auditivas case study.

It ensures that the analysis remains consistent across documents and supports a stronger academic discussion.

The most important principle is that each lead should have:

* a clear status
* a clear owner
* a recorded next action
* a measurable outcome

This makes the case more auditable, replicable and useful for both academic and managerial analysis.

---

**End of Document**

