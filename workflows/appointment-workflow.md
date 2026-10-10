# Appointment Workflow

## Purpose
Automate appointment confirmations, reminders, and CRM updates for SparkClean Pro.

## Trigger
Appointment Status Confirmed for the Free Consultation calendar.

## Action Sequence
1. Find the contact's most recent open opportunity.
2. Update the opportunity stage to Appointment Booked.
3. Add the Appointment Booked contact tag.
4. Remove the Needs Follow Up tag.
5. Remove the contact from the New Lead Nurture workflow.
6. Send an appointment confirmation email.
7. Send an appointment confirmation SMS.
8. Wait until one day before the appointment.
9. Send an appointment reminder email.
10. Wait until one hour before the appointment.
11. Send an appointment reminder SMS.

## Testing
Tested by booking a consultation through the booking page. The confirmation email was received, and the opportunity moved to the Appointment Booked stage.

## Notes
SMS delivery depends on the messaging number and account configuration.
