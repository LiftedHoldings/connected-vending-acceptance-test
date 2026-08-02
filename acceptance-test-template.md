# Connected vending go-live acceptance record

**Machine ID:**  
**Location / venue:**  
**Product and slot:**  
**Payment path:**  
**Date / local time zone:**  
**Tester / accountable release owner:**  
**Software / controller / configuration version:**  

## Expected records before testing

For every state below, write the expected customer-screen outcome, payment
outcome, delivery evidence, inventory effect, operator record, fault or alert,
customer-recovery path, and settlement effect before the test runs.

| State | Expected outcome | Actual evidence attached | Result | Owner and deadline for mismatch |
| --- | --- | --- | --- | --- |
| Declined before a vend command |  |  | Pass / fail / N/A |  |
| Approved and dispensed |  |  | Pass / fail / N/A |  |
| Approved but not dispensed |  |  | Pass / fail / N/A |  |
| Timeout or unknown |  |  | Pass / fail / N/A |  |
| Interrupted or duplicate attempt |  |  | Pass / fail / N/A |  |
| Refund, reversal, or recovery |  |  | Pass / fail / N/A |  |
| End-of-day reconciliation |  |  | Pass / fail / N/A |  |

## Evidence packet

- **Customer:** Screen state, support reference, and customer-facing message.
- **Machine:** Machine ID, selection or slot, controller event, and physical
  delivery check where appropriate.
- **Payment:** Attempt identifier, authorization state, reversal or refund
  reference, and timestamps.
- **Inventory and tax:** Expected versus actual quantity, product record,
  price, and tax outcome.
- **Operations:** Order, fault, support, and audit records with ownership.
- **Settlement:** Processor or settlement report and the reconciliation result.

## Release decision

**Release status:** Pass / Conditional / Do not release  
**Open exceptions:**  
**Customer-recovery decision:**  
**Retest trigger after future change:**  
**Release owner signature / date:**  

## Responsible-use note

This template is an operational documentation tool. It does not establish legal
compliance, product authorization, payment approval, tax treatment, privacy
compliance, performance, or legal suitability. Confirm the current requirements
for each deployment with the relevant authority and qualified advisers.
