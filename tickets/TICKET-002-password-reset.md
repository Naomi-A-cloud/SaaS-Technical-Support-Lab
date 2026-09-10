# TICKET-002: Password Reset Failure

## Ticket Information

Ticket ID: TICKET-002  
Category: Account Access  
Priority: P3 - Medium  
Status: Resolved  
Customer: Jordan Lee  
Product: CloudDesk SaaS

## Customer Issue

The customer reports that the password reset email is not arriving.

## Investigation

- Confirmed the customer account exists.
- Confirmed the email address on the account.
- Asked the customer to check spam and junk folders.
- Confirmed the customer was using the correct password reset page.
- Reviewed authentication logs for reset activity.

## Findings

The password reset request was successfully generated, but the customer did not initially receive the email.

## Resolution

The customer checked the spam folder and located the password reset email.

The password was successfully reset.

## Root Cause

The reset email was filtered into the customer's spam folder.

## Escalation

No escalation required.

## Customer Impact

Customer temporarily could not access the account.

## Final Status

Resolved.