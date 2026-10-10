# Invoice Paid and Review Request Workflow

## Purpose
Automate post payment communication and review requests for SparkClean Pro.

## Trigger
Invoice Status Paid.

## Action Sequence
1. Add the Invoice Paid contact tag.
2. Update the opportunity to the Paid stage in the Active Jobs pipeline.
3. Send an internal payment notification.
4. Send a thank you email to the customer.
5. Wait three days.
6. Execute the review request action using the configured email review request settings.

## Testing
Tested by recording a manual cash payment against a test invoice. The invoice status changed to Paid, the workflow ran, and the thank you email was received.

## Notes
A valid business review link must be configured before review requests can direct customers to the intended review destination. Online payment gateway integration was not verified by the manual payment test.
