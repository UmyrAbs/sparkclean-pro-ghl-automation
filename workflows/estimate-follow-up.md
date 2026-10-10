# Estimate Follow Up Workflow

## Purpose
Automate estimate follow ups and help SparkClean Pro track outstanding estimates.

## Trigger
Estimate Status Sent.

## Action Sequence
1. Add the Estimate Sent contact tag.
2. Find the contact's most recent open opportunity.
3. Move the opportunity to the Estimate Sent stage.
4. Send an internal notification.
5. Check whether the estimate has been accepted.
6. Wait two days before sending the estimate reminder email.
7. Wait three additional days before sending the reminder SMS.
8. Check the estimate status again before completing the follow up sequence.

## Testing
Tested by creating and sending an estimate. The estimate email was received, the Estimate Sent tag was applied, and the opportunity moved to the Estimate Sent stage.

## Related Workflow
The separate Estimate Accepted workflow handles estimate acceptance and updates the opportunity to Won.
