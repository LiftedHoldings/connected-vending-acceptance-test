# Connected Vending Go-Live Acceptance Test

A printable, vendor-specific worksheet for documenting the customer, payment,
delivery, inventory, fault, refund, and settlement handoffs that an operator
should reconcile before opening a configured connected-vending deployment.

The maintained web version is available at
[AgeVend's Connected Vending Go-Live Acceptance Test](https://agevend.com/connected-vending-go-live-test.html).

The public, plain-HTML companion for this open worksheet is available at
https://liftedholdings.github.io/connected-vending-acceptance-test/.

## Purpose

Unattended retail is a chain of handoffs. A reader approval does not, by
itself, establish delivery, inventory movement, customer recovery, or
settlement. This template creates one review record for a specific machine,
location, product setup, and payment path.

It covers seven observable states:

1. Declined before a vend command
2. Approved and dispensed
3. Approved but not dispensed
4. Timeout or unknown
5. Interrupted or duplicate customer attempt
6. Refund, reversal, or customer recovery
7. End-of-day reconciliation

## Use

1. Start from [`acceptance-test-template.md`](acceptance-test-template.md).
2. Record the exact configuration and expected records before testing.
3. Attach the actual customer, machine, payment, inventory, support, and
   settlement evidence.
4. Leave a mismatch open until an accountable owner explains the customer and
   financial outcome.
5. Retest the successful path and affected exception after material changes.

## Scope and limits

This is a practical operational worksheet, not legal, tax, payment, privacy,
or regulatory advice. It is not a universal technical standard, a performance
benchmark, or multi-platform validation. Product rules, venue conditions,
equipment, controller, payment, network, tax, and local regulatory
requirements can differ materially by deployment and can change over time.

Operators should use applicable agreements and qualified advisers for the
actual route. For age-restricted tobacco or nicotine products in the United
States, federal rules restrict vending-machine sales to facilities where
individuals under 21 are not present or permitted to enter; state and local
restrictions may be stricter. See the current FDA retail guidance before
planning a deployment.

## Versioning

This repository contains a text-friendly version of the worksheet. The hosted
AgeVend version is the maintained customer-facing resource; use its date and
scope statements when citing the tool.

## License

The template is released under the [MIT License](LICENSE). Attribution is
appreciated but not required by the license. Do not imply AgeVend endorsement
of a modified version.
