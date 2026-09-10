# Support Troubleshooting Decision Tree

## Step 1: Is the customer authenticated?

### No

Investigate:

- Credentials
- Password reset
- MFA
- Account status
- Authentication service

### Yes

Continue to Step 2.

## Step 2: Is the user authorised?

### No

Investigate:

- User role
- Permissions
- Access policies

Check for HTTP 403 errors.

### Yes

Continue to Step 3.

## Step 3: Is the application functioning?

### No

Investigate:

- Application errors
- HTTP 500 errors
- Service availability
- Application logs

### Yes

Continue to Step 4.

## Step 4: Is the API responding correctly?

### No

Investigate:

- HTTP status code
- API endpoint
- Authentication
- Rate limits
- API logs

### Yes

Continue to Step 5.

## Step 5: Is the application slow?

Investigate:

- Response time
- API latency
- Browser performance
- Application logs

## Escalation Trigger

Escalate when the issue indicates:

- Widespread service impact
- Backend failure
- Security concern
- Infrastructure failure
- Persistent unresolved defect