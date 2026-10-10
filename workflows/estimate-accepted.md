# Estimate Accepted Workflow

## Purpose
Update the CRM when a customer accepts an estimate.

## Trigger
Estimate Status Accepted.

## Action Sequence
1. Remove the contact from the estimate follow up workflow.
2. Find the contact's most recent open opportunity in the New Leads pipeline.
3. Update the opportunity stage to Won.
4. Update the opportunity status to Won, where configured.
5. Add the Won contact tag.
6. Send an internal notification if an opportunity cannot be found, where configured.

## Testing
Tested by accepting a test estimate. The opportunity moved to Won, the Won tag was applied, and the contact was removed from the estimate follow up workflow.
