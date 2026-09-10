# TICKET-001: Customer Unable to Log In

## Ticket Information

Ticket ID: TICKET-001  
Category: Authentication  
Priority: P2 - High  
Status: Resolved  
Customer: Alex Morgan  
Product: CloudDesk SaaS

## Customer Issue

The customer reports that they are unable to log into their CloudDesk account.

They confirmed that they are using their normal email address and password.

## Initial Investigation

### Step 1: Verify Account

Account exists and is active.

### Step 2: Credential Check

Customer confirmed that the credentials were recently working.

### Step 3: Browser Testing

Customer reproduced the issue in their normal browser.

The issue was not reproduced in a private browsing session.

### Step 4: Browser Investigation

Existing browser session data was suspected to be causing the authentication failure.

Customer cleared cookies and cache and restarted the browser.

## Resolution

The customer successfully logged into CloudDesk after clearing browser session data.

## Root Cause

Stale browser session data interfered with the authentication process.

## Troubleshooting Performed

- Verified account status
- Confirmed affected user
- Tested browser behaviour
- Tested private browsing
- Cleared browser cache and cookies
- Retested authentication

## Customer Impact

One customer was temporarily unable to access the SaaS platform.

## Escalation

No escalation required.

## Lessons Learned

Browser session and cache issues should be considered when authentication problems occur for an individual user but the authentication service remains operational.